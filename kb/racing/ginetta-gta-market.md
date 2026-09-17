# Ginetta GT Academy (GTA) market
_Last updated: 2026-09-14_

Tracker for cars eligible for the BRSCC Ginetta GT Academy. Under the **2026 regs the only eligible car is the Ginetta G56 GTA** (3.7 or 3.5 Ford V6, ~270bhp, Quaife QBE69G sequential, 1325kg min) — the G55 GTA is not eligible (invitation class at organisers' discretion, no points), so tier 2 is effectively closed. Baseline (2026-09-14): **4 live G56 GTA for sale in the UK, all on racecarsdirect**, priced £37k (private RHD, no hours stated) to £50k+VAT (2025-spec 3.5, engine in warranty). Nothing on PistonHeads / Collecting Cars / Racemarket / eBay UK. Used band ≈ £37k–£60k inc VAT; new car last publicly listed at £75k+VAT (2022 price list); 2026 championship registration £16,500+VAT incl. all rounds. Fed by the daily `ginetta-gta-watch` cron (06:20 London); dedup lines in `_ledger.md` with slug prefix `ginetta-gta-`. Detail catalog: `ginetta-gta-watch/listings.md`.

## Regs (eligible-car clause)
- **2026 BRSCC Ginetta GT Academy regs — PUBLISHED 21 Apr 2026** (Clean + Marked-Up copies):
  - https://brscc.co.uk/wp-content/uploads/2026/04/2026-Ginetta-GT-Academy-Championship-Sporting-Technical-Commercial-Regulations-PUBLISHED-21APR2026-Clean-Copy.pdf
  - https://brscc.co.uk/wp-content/uploads/2026/04/2026-Ginetta-GT-Academy-Championship-Sporting-Technical-Commercial-Regulations-PUBLISHED-21APR2026-Marked-Up.pdf
  - **5.2.1**: "The Ginetta GT Academy is a 'one make' race series for Competitors participating in Ginetta G56 GTA race car as specified herein."
  - **5.10.2**: Ford 3.7 V6 **or** 3.5 V6, Ginetta-sealed, 40mm inlet restrictor (5.10.3). Ginetta.com now quotes the G56 GTA as 3.5 ltr / 270bhp / 1230kg dry.
  - **5.12.1**: Quaife QBE69G 6-speed sequential mandated (2025 onward). **5.20.1**: min weight 1325kg.
  - **5.1**: non-compliant car may be accepted into an invitation class only — no points/awards. ⇒ **G55 GTA not eligible.**
  - Classes (1.3.2 j/k): GT Academy + Rookie (<6 circuit races started). Chairman's Cup for 45+.
  - **2026 changes** (marked-up vs 2025) a used car must have to be compliant: Motec ECU + PDM + keypad + C125 display logger (5.14.13); MSUK-sealed ECU (5.10.5); driver net mandatory (5.4.1); paddle-shift compressor tunnel-mounted (5.12.7); rear oil-cooler temp sensors (5.15.4); no cockpit Anderson/boost connector (5.14.15); Pirelli 245/40ZR18 Trofeo RS control tyre, 28/season (5.18); Sunoco control fuel; TSL RaceLink GPS/signalling receiver (2.10.3).
  - **Fees (1.4.5)**: registration £16,500+VAT payable to SRO Motorsport, inclusive of all round entries (2025 was £15,000+VAT). Prizes: 1st = free 2027 entry + £15k parts credit.
- 2025 regs (superseded): https://brscc.co.uk/wp-content/uploads/2025/04/2025-Ginetta-GT-Academy-Championship-Sporting-Technical-Commercial-Regulations-PUBLISHED-01APR2025.pdf — same G56-GTA-only clause.
- Next regs check: look for 2027 PDF from ~Jan–Apr 2027.

## Season costs (Ginetta)
- 2022 Ginetta price list (last public one found; https://www.ginetta.com/uploads/downloads/2022-GT-Academy-Price-List.pdf): car £75,000+VAT; Rookie run package (storage at Blyton, transport, tech support, coaching, fuel, season tyres, hospitality) £29,000+VAT; entry fees then £6,000. No 2026 price list published online — ask Ginetta / Want2Race directly.
- 2026: registration £16,500+VAT incl. entries (regs). Run-package cost with a team: ask (Want2Race works team, Performance One, Vortice etc.).

## What's for sale (baseline 2026-09-14)
| # | Car | Price | Hours | Seller | Listed | Verdict |
|---|-----|-------|-------|--------|--------|---------|
| 1 | 2025-spec 3.5 G56 GTA | £50,000+VAT | engine in warranty, g'box 12h, diff 0h | trade, Preston | 28/10/2025 | closest to current spec; 11 months unsold → negotiate |
| 2 | G56 GTA RHD | £37,000 | not stated | private, Lincs | 31/08/2026 | cheapest RHD; no data — get hours/spec first |
| 3 | 2024 G56 GTA LHD | £39,995+VAT (was £49,500+VAT) | 108h total, g'box 62h | 7TSIX Ltd, Dewsbury | 15/05/2026 | high hours, LHD, body damage — rebuild money |
| 4 | G56 GTA 3.7 "current spec" | £POA+VAT | not stated | trade, South Kirkby | 03/11/2025 | zero detail, low priority |

Comps (not eligible): G55 Supercup £32k+VAT and £35k; GTP8 £75k / £85k+VAT / £84,999; G56 GT4 EVO £145k+VAT. US: 2024 G56 GTA (48h) sold $57k on BaT Oct 2025.

## Standing observations
- The entire UK used-GTA market lives on racecarsdirect.com; nothing surfaced elsewhere at baseline. racecarsdirect blocks direct fetch (Cloudflare) — search-result pages and adverts are readable via the r.jina.ai reader proxy.
- Supply is thin (4 cars) and slow-moving: two of the four have been listed 10–11 months. Expect leverage on price.
- Sellers rarely state hours or spec year; every viewing should start with Ginetta logbook, engine/gearbox hours vs 60h warranty, and the 2026 electronics/driver-net/compressor items.
- LHD G56 GTAs exist (US/SRO programme cars) — eligible but a resale liability in the UK.

## Timeline
- 2026-09-14 — Baseline run: 2026 regs located (G56 GTA only; £16,500+VAT reg fee), 4 live G56 GTA + 6 comps catalogued, seen.json seeded (racecarsdirect.com, brscc.co.uk, ginetta.com)
- 2026-09-14 — Watch created on Barney's ask; baseline run pending (bolt)
