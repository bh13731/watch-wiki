# Ferrari 296 coupé market (Speciale / GTB Assetto Fiorano)
_Last updated: 2026-09-16_

Tracker for UK-market Ferrari 296 coupés in Barney's scope: 296 Speciale (tier 1) > 296 GTB with Extended Assetto Fiorano pack (tier 2) > special/limited-edition GTBs (tier 3). GTS/Speciale A spiders and non-AF GTBs are out of scope (comps only). Fed by the daily `ferrari-296-coupe-watch` cron (06:05 London); dedup lines in `_ledger.md` with slug prefix `f296-`; full catalogue in `ferrari-296-watch/listings.md`. Migrated into kb/ on 2026-09-15 after 11 runs (baseline 2026-09-05).

**State 2026-09-16:** Six UK Speciales live, all at independent traders on AutoTrader, all delivery-mileage 26-reg cars: Asean Corporation £449,950 VAT-Q (≈£375k ex-VAT — the value pick if VAT is recoverable), Marcus Freeman £459,000, Ventura £479,000 (spec undisclosed), Amari £488,995 (Verde Nürburgring, best spec, only non-red), Nuvola £519,990 (spec undisclosed), Virginia Water private £550,000 (over-ask). Both franchised cars came and went inside a week — H.R. Owen Mayfair £559k (Verde Assenzio, 1,702 mi) delisted after ~48h, Stratstone Colchester Ferrari Approved £499,830 delisted after 4 days — so main-dealer Speciales clear fast while trader flips sit. Vertar's yellow launch-spec car sold at £499,990. Tier 2: only two live AF coupés — Morgan Cars NI 2025 Extended AF £239,995 VAT-Q (360 mi, TDF Blue, best spec) and the cheapest AF, Driven Landjets 2022 Extended AF £194,995 (cut from £199,995 on 16 Sep after two days; 8,667 mi, Nero, independent trader — quick cut hints at negotiating room; get build sheet + warranty status). Ferrari Approved GB holds 0 Speciales and 9 non-AF GTBs (2022s from £195k), so the used-AF premium has effectively collapsed to zero at the bottom of the market. Top555 (£212,950) and Romans (POA) AF cars both sold during the watch. No tier-3 UK cars found.

## Price bands (asking, 2026-09-15)
- 296 Speciale (RRP ~£359,900 before options): UK asks £449,950–£550,000, i.e. £90–190k over list. Cleared: Vertar Giallo launch spec £499,990 (sold), H.R. Owen Verde Assenzio £559k (gone <48h), Stratstone Rosso Imola £499,830 (gone 4 days). Franchised/Approved premium ≈ £10–50k over the trader pack.
- 296 GTB Extended AF used: £194,995 (2022, 8,667 mi; was £199,995) → £212,950 (2023, 2,235 mi, sold) → £239,995 (2025, 360 mi, VAT-Q). Carbon wheels + full spec pushed a 2023 to £234,950 (Hamilton Grays, sold). Higher-mileage 2022s cleared at ~£210k (Saxon, sold).
- Non-AF 2022–23 GTB comps: £189,999–£209,995 (main dealers £195–229k) — AF premium on a used car is currently only ~£5–15k.
- Tier 3 comp: 2024 GTB AF "Hungaroring Edition" 1 of 5 sold RM Sotheby's Monaco Apr 2026 (not UK).

## Standing observations
- AutoTrader: search/SEO pages degrade to 4 IDs some days; `/car-details/<id>` always fetches. Best route since 2026-09-15 is `r.jina.ai` proxy of the AT car-search URL (make=Ferrari&model=296 GTB&sort=datedesc) → ~21 IDs.
- preowned.ferrari.com (Ferrari Approved) fetchable since 2026-09-14 via NEXT_DATA JSON; GB search pattern `/en-GB/r/europe/used-ferrari/great-britain/<model-slug>/rfcm`. Primary main-dealer source.
- PistonHeads: www.pistonheads.com serves NEXT_DATA for `/buy/used-cars/ferrari/296-gtb` and `/296-speciale` (detail pages reCAPTCHA'd); www-cdn host intermittently blocked.
- Blocked: Collecting Cars (403 on everything — a "2024 296 GTB AF Coming Soon" lot has been unverifiable since 9 Sep), Dick Lovett, autouncle, theparking. Tom Hartley/THJ/Graypaul/Amari/Furlonger/Hexagon stock URLs 404 or JS-only; H.R. Owen/GVE/Macari pages render but show no 296 content.
- Speciale sellers are overwhelmingly independent "sports & 4x4" traders flipping allocations; always ask first-reg date, VAT status, build sheet. Brave snippets are frequently stale (e.g. old prices, gone cars) — verify on the detail page before reporting.

## Timeline
- 2026-09-16 — PRICE CUT: Driven Landjets 2022 GTB Extended AF £199,995 → £194,995 (−£5k); Speciales ×6 unchanged; Ferrari Approved GB 0 Speciale / 9 GTB none AF; Maranello Sales 2023 GTB £189,000 / 10,754 mi new non-AF main-dealer comp (autotrader.co.uk, preowned.ferrari.com)
- 2026-09-15 — Migrated into kb/cars (ledger seeded with 18 seen entries; topic page created) (bolt)
- 2026-09-15 — NEW cheapest AF: Driven Landjets 2022 GTB Extended AF £199,995 / 8,667 mi (AT 202609146032738); Stratstone Colchester Speciale £499,830 DELISTED after 4 days (autotrader.co.uk, preowned.ferrari.com)
- 2026-09-14 — NEW: Stratstone Colchester Ferrari Approved 2026 Speciale £499,830 / 85 mi, Rosso Imola, harnesses + door numbers (preowned.ferrari.com)
- 2026-09-10 — Top555 2023 AF £212,950 and Romans 2022 AF (POA) both marked SOLD; Morgan Cars NI the only live UK AF coupé (top555.co.uk, romansinternational.com)
- 2026-09-09 — H.R. Owen Mayfair £559k Speciale DELISTED ~48h after listing; Vertar Giallo Speciale Reserved → SOLD at £499,990 (autotrader.co.uk, vertar.com)
- 2026-09-08 — NEW: Ferrari Mayfair (H.R. Owen) 2026 Speciale £559,000 / 1,702 mi Verde Assenzio #25 livery; PRICE CUT Asean Speciale £465,000 → £449,950 (autotrader.co.uk)
- 2026-09-06 — NEW: Nuvola London Speciale £519,990; Morgan Cars NI 2025 GTB Extended AF £239,995 / 360 mi; £479k Speciale resolved to Ventura Collection MK (autotrader.co.uk)
- 2026-09-05 — Baseline: 6 Speciales (4 live AT £459k–£550k, Vertar reserved £499,990, one unlocated £479k) + 7 AF (Top555 £212,950 live; Saxon/Hamilton Grays/European Prestige sold comps) (autotrader.co.uk, top555.co.uk)
