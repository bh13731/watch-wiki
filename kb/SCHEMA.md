# kb/ — Bolt's digest knowledge base (schema)

Pattern: Karpathy's "LLM Wiki". This directory is a persistent, compounding wiki
maintained ENTIRELY by LLM agents (cron digest runs + weekly maintenance).
Barney reads it; agents write it. Raw sources (the web) are never stored here —
only compiled knowledge.

Purpose: digests used to be stateless — every run rediscovered the world from
scratch, so they repeated old items and posted stale news. This KB is the memory
between runs.

## Layout

```
kb/
  SCHEMA.md          # this file — conventions + workflows
  index.md           # catalog: every page, one line each. Update on ingest.
  log.md             # append-only chronological log of ingests/lints
  <domain>/          # ai | news | culture | arts | restaurants | sport | racing | watches | cars
    _ledger.md       # dedup ledger — one line per item ever reported
    <topic>.md       # topic/entity pages, created on demand
```

## Ledger format (`_ledger.md`)

One line per reported item, newest LAST (append-only):

```
YYYY-MM-DD | kebab-slug | one-line summary | source-domain
```

- Slug is the stable ID. Reuse the same slug for follow-ups, suffixed:
  `gpt-5-6-sol-preview`, then `gpt-5-6-sol-ga` for the GA follow-up.
- Ledgers are the FAST path: `tail -n 150 kb/<domain>/_ledger.md` before composing.

## Topic pages (`<topic>.md`)

For entities that recur (labs, venues, teams, franchises). Format:

```
# <Name>
_Last updated: YYYY-MM-DD_

One-paragraph current-state summary (keep current, rewrite freely).

## Timeline
- YYYY-MM-DD — fact (source-domain)
```

- Newest timeline entries at TOP.
- When new info contradicts old, keep both and mark the old line `[superseded]`.
- Cross-link related pages with relative markdown links.

## Workflows

### Ingest (every digest cron run that actually sends)
1. BEFORE composing: read your domain ledger tail (~150 lines) + any relevant
   topic pages. Never re-report a ledger item unless there is a genuinely new
   development — then report only the delta, marked as an update.
2. AFTER composing the outgoing digest: append ledger lines for every item
   reported; update/create topic pages for significant entities; add the new
   pages to index.md; append one log.md line.
3. If replying NO_REPLY: write nothing.

### Query (any agent answering questions)
Read index.md first, drill into pages. Answers worth keeping can be filed back
as new pages (add to index.md + log.md).

### Lint (weekly maintenance cron)
- Ledgers: entries older than 90 days → ensure anything durable lives on a topic
  page, then delete the old ledger lines (ledger stays a rolling ~90-day window).
- Topic pages: collapse timeline entries older than 6 months into a short
  "## History" summary paragraph; flag contradictions; mark superseded claims.
- Orphans: pages missing from index.md → add them. Index entries for deleted
  pages → remove.
- log.md over 300 lines → truncate oldest half, leave a `[truncated YYYY-MM-DD]` marker.
- Append `## [YYYY-MM-DD] lint | <summary>` to log.md.

## log.md entry format

```
## [YYYY-MM-DD] ingest | <domain> | <n> items | <headline slug>
## [YYYY-MM-DD] lint | <what changed>
```

Parseable via `grep "^## \[" kb/log.md | tail -5`.

## Hard rules
- Append, don't clobber: use `>>` / targeted edits, never rewrite a ledger wholesale (except lint pruning).
- Dates are facts: never guess publish dates. If a story's original date can't
  be established, treat it as suspect-stale and check before reporting as new.
- This KB is Barney-private. Never quote it to third parties or group chats.
