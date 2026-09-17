# Radical SR3 market (for-sale cars)
_Last updated: 2026-09-15_

Tracker for Radical SR3 race cars for sale, latest spec first: SR3 XXR (2023-on, tier 1) > SR3 XX (2019–22) > SR3 RSX (2013–18). Fed by the daily `radical-sr3-watch` cron; dedup lines live in `_ledger.md` with slug prefix `radical-sr3-`; full catalog in `radical-sr3-watch/listings.md`.

**Current state (2026-09-15):** Supply still concentrated on racecarsdirect.com, now fully readable via the jina proxy. UK XXR stock = Performance Time (Stratford) x2 — 2026 Stealth Black 17h £84,995+VAT (RCD 165836, the strongest T1) and 2023 Brilliant White with just-refreshed RPE engine £71,995 no VAT (RCD 165920, the sharpest ask) — plus a private Feb-2025 24h car at £POA (RCD 165833) and Valour Racing's 2025 at £81,000+VAT (RCD 158830, 11 months unsold). Performance Time's red 2023 XXR (0h RPE, AP brakes, £71,995) went to DEPOSIT in ~7 weeks and North Motorsport's 2023 Gen5 car is SOLD — fresh-engine 2023 XXRs at ~£72k no VAT clear quickly. Dubai cars (RCD 162701 £99k, 162055 €95k, 162053 €98k, 163125 €94k) are £20–30k over UK money before shipping. XX: new best-value car is RJ Motorsport's 2020 #1301 at £47,000 (RLM 1500 16h since rebuild, fresh GDU, RCD 166114); a Romanian 2021/22 XX at €50k+VAT (RCD 165991) and the long-stale 2022 World Finals winner at £52,995+VAT (RCD 147598) complete the tier. RSX: Forge Precision car £40,000 (RCD 165548) and RLM-rebuilt car £42,000 (RCD 162789). PistonHeads and Collecting Cars: nothing in scope.

## Price bands (asking, 2026-09-15)
- XXR used UK: £72k no-VAT (2023, fresh RPE engine) → £81k+VAT (2025, no hours given) → £85k+VAT (2026, 17h). New XXR: €135k+VAT (EU dealer), £133–135k inc VAT (Performance Time quoted cost-new), US $149–159k. Dubai used XXR €94–99k / £99k = over-ask.
- XX: £47k (2020, 16h since rebuild) → €50k+VAT (2021/22 RO) → £53k+VAT (2022 WF winner, stale) → €64k (2022 LHD zero-hours EU). US used XX $72–82k.
- RSX: £40–42k UK (RLM engines, refreshed GDUs); €35–39.5k EU LHD. Older SR3 RS/SL comps €30–35k.
- Clearing evidence: 2023 XXR + 0h RPE + AP brakes at £71,995 no VAT → deposit in ~7 weeks (Jul–Sep 2026).

## Standing observations
- racecarsdirect.com is Cloudflare-walled to direct fetch/curl/browser, but `https://r.jina.ai/<RCD url>` renders search grids (price, date, title, advert URL) and advert pages (description, seller, Added, Views, SOLD banner). Use it every run.
- Performance Time Ltd (Stratford-upon-Avon, Chris Preen) is the main UK XXR trader: same template ads, quotes cost-new, "engine refreshed by RPE factory". RJ Motorsport, Valour Racing, North Motorsport, Forge Precision are prep shops selling customer cars.
- Dates on RCD are "last updated" and move on relist/price-cut; treat as freshness, not first-listed.
- Hire/arrive-and-drive XXR adverts (RJ Motorsport, 360 Competition, DW Racing, RCD 163624) are common noise — out of scope here.

## Timeline
- 2026-09-15 — 4 new (2023 XXR fresh-engine £71,995 no VAT; 2020 XX £47k; RO XX €50k+VAT; RSX £40k) + status changes (red 0h XXR deposit taken, North Motorsport XXR sold, 2026 XXR verified 17h, Valour 2025 = £81k+VAT). RCD readable via jina. (racecarsdirect.com)
- 2026-09-14 — Baseline run: 9 cars catalogued (7 XXR, 1 XX, 1 RSX); lead = 2026 XXR £84,995+VAT (racecarsdirect.com)
- 2026-09-14 — Watch created on Barney's ask; baseline run pending (bolt)
