# Porsche GT3 RS Manthey market
_Last updated: 2026-09-16_

Tracker for Porsche 911 GT3 RS cars with the Manthey Racing kit: 992 GT3 RS + Manthey Kit (tier 1) > 991.2 GT3 RS MR (tier 2) > Manthey-ready / kit-on-order (tier 3). Non-Manthey RS are comps only; GT2 RS MR and 991.1 MR cars get a one-line mention. Fed by the daily `gt3rs-manthey-watch` cron (06:10 London); dedup lines in `_ledger.md` with slug prefix `gt3rs-`; full catalogue in `gt3rs-manthey-watch/listings.md`. Migrated into kb/ on 2026-09-15 after 11 runs (baseline 2026-09-05).

**State 2026-09-15:** Zero UK 992 GT3 RS with Manthey kit on sale — confirmed by the first full PistonHeads + AutoTrader keyword sweep (via jina proxy) on 2026-09-15. Tier 1 supply is EU-only: three elferspot cars (2025 PTS Lava Orange full €102k kit, warranty to 08/2027, best spec anywhere; 2024 ex-Werkswagen; 2023 Ice Grey 27,800 km, Porsche France-fitted kit) — all LHD, prices unreadable. Tier 2 is the live UK action: VVS UK's 2018 991.2 GT3 RS Manthey (Lizard Green, 16,750 mi, £189,990) RELISTED 15 Sep after a week off market — partial kit only (mag wheels + Surface Transform discs; no dampers/aero evidenced), JCR exhaust, 4 owners; a fallen-through sale is negotiating leverage. A second UK 991.2 (2019, C00 German-supplied, full MR pack from new, 15,680 mi, RH12 trade seller via Classic Driver) has been indexed since ~13 Jul but price/dealer are unverified. EU tier-2 comps: 2020 black Weissach + €67k documented kit €249,990 VAT-deductible (best-documented anywhere), Stimpfig PTS Ultraviolet Weissach MR POA (6 months unsold), Wagenwerk Lizard Green €284,850 (over-ask). RPM Technik's reference 991.2 MR is sold. New out-of-scope FYI: 2016 991.1 GT3 RS "full Manthey Kit" £144,990 (Durham, 7 months unsold).

## Price bands (asking, 2026-09-15)
- 992 GT3 RS + Manthey: no UK asks. Kit alone ≈ £99,999 + fitting (Porsche Tequipment) / €100–102k EU. Std 992 GT3 RS UK comps £247,500–£330,000 (bulk £265–300k); VVS 2024 1,300 mi £289,990.
- 991.2 GT3 RS MR: UK £189,990 (partial kit, 16,750 mi) — effectively a £5–10k premium over std 991.2 RS comps (£179,995–£184,950). EU full-kit cars €249,990 (VAT-deductible, 32,300 km) → €284,850 (43,000 km). Historic: PH Spotted a Lizard Green ST-disc car at £220k in Feb 2024 (kit £64.8k) → ~£30k softer today.
- 991.1 GT3 RS + Manthey (out of scope): £144,990 = cheapest UK Manthey-kitted RS.
- GT2 RS MR (out of scope): UK £599,950 (PH 20772150, 6,900 mi).

## Standing observations
- Since 2026-09-15 the `r.jina.ai` proxy renders PistonHeads keyword search (`/buy/search?keywords=manthey&model=gt3-rs`) and AutoTrader keyword search (`car-search?make=Porsche&model=911&keywords=manthey`) — first reliable UK classifieds sweep; run both every day (AT is slow, 30–60s).
- Still blocked: Collecting Cars, Porsche Finder, Classic Driver, Car & Classic, classic.com, theparking (Cloudflare). elferspot detail pages fetch but prices often don't render; elferspot search page returns nothing crawlable.
- "Manthey" in an ad ≠ full kit: VVS's car itemises wheels + brakes only. Demand the conversion invoice (RPM Technik / Porsche Centre / Manthey) — full kit is ~£40–65k on a 991.2, ~£100k on a 992.
- C00 = German-market supply → almost certainly LHD; check before getting excited about "UK-located" cars.
- UK fitters for tier-3 leads: RPM Technik (Tring, first approved full-MR installer), JZM Porsche (Kings Langley, kit supply/fit), Porsche Centres (Tequipment kit from £99,999).
- Historic comp: a 992 GT3 RS Manthey Pack sold at Flat6 Sale Lyon 26 Apr 2026 (est. $464–522k) — not live.
- Tier 1 clears instantly in the EU: a 2024 992 RS PTS British Racing Green, 28 km, Manthey Racing Kit (P One Cars, Barcelona, elferspot 6247384) was already marked Sold within ~16h of being indexed on 2026-09-16 (price never shown). Expect UK Tier 1 cars, if any appear, to go the same way — daily cadence matters.

## Timeline
- 2026-09-16 — No live updates. PH+AT keyword sweeps unchanged (7 results each, all known/out of scope). New Tier 1 sighting elferspot 6247384 (2024 992 RS PTS BRG, 28 km, Manthey Kit, Spain) already SOLD on first index → logged, not reported (elferspot.com)
- 2026-09-15 — Migrated into kb/cars (ledger seeded with 12 seen entries; topic page created) (bolt)
- 2026-09-15 — First full PH+AT keyword sweep via jina: zero UK 992 RS Manthey. VVS 991.2 MR £189,990 RELISTED (PH 20896649 live again, AT 202609085843355 posted 8 Sep). Out-of-scope: 2016 991.1 RS full Manthey Kit £144,990 Durham (pistonheads.com, autotrader.co.uk)
- 2026-09-08 — NEW tier 2: 2019 991.2 GT3 RS Manthey full MR pack from new, C00, 15,680 mi, RH12 trade seller (price unverified, Cloudflare); Stimpfig 2019 991.2 RS MR PTS Ultraviolet Weissach POA (classicdriver.com, elferspot.com)
- 2026-09-07 — VVS 991.2 MR DELISTED (UK in-scope stock = zero); NEW EU tier 2: 2020 991.2 RS Weissach + €67k documented Manthey kit, 32,300 km, €249,990 VAT-deductible (elferspot 6212559) (elferspot.com)
- 2026-09-05 — Baseline: UK tier 1 none; UK tier 2 VVS 991.2 £189,990 (partial kit); EU tier 1 ×3 elferspot (prices unreadable); Wagenwerk 991.2 MR €284,850; RPM Technik 991.2 MR SOLD; GT2 RS MR £599,950 noted (pistonheads.com, elferspot.com, wagenwerk.at)
