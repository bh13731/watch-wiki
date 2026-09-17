# kb/racing — bundle (2026-09-17 07:51 UTC)


---

<!-- kb/racing/arrive-and-drive-market.md -->

# UK/Euro arrive-and-drive race seat market
_Last updated: 2026-09-17_

Barney (Caterham Academy 2026) wants ongoing visibility of race seats /
arrive-and-drive RACE opportunities, stack-ranked by budget. Primary marketplace
is racecarsdirect.com "Drives Available"; series sites (EnduroKa, Fun Cup, C1
Racing Club, Britcar) list team-run seats directly. Most premium listings are
£/€POA — real prices usually only surface on enquiry, so band estimates matter.

## Budget bands (per seat per race unless noted)
- 💚 <£2k: EnduroKa (~£1,000–1,500/round), C1 Cup (~£1,000–1,800), Go Racing A&D (£1,495 for 2027), MX-5 club racing
- 💛 £2–5k: Fun Cup (from £3,500+VAT; seat hire ~£3,650), Caterham A&D rounds, Radical A&D seats (£2,800+VAT)
- 🧡 £5–15k: Britcar GT/Ginetta G56, Porsche Cayman Sprint Challenge UK, NLS rounds (typ. €8–15k), Praga Equipe
- ❤️ £15k+: GT4/GT3 seats, 992 Cup 24H Series, 24h Barcelona / 12h Spa, LMP3 (Le Mans Cup ~€200k+/season), N24

## Standing observations
- EnduroKa + C1 = best £/seat-time in UK motorsport; obvious post-Academy value play.
- Fun Cup = best multi-hour stint length per £ (incl. 25h Spa-format events).
- racecarsdirect Drives Available churns slowly; many adverts are evergreen (team capacity ads, not one-offs) — e.g. MX-5 ad id 80197 live since ~2023.
- Sub-£2k priced listings get snapped up; POA GT stuff lingers.
- racecarsdirect.com sits behind a Cloudflare challenge (direct fetch + headless browser both blocked from 2026-09-12); a reader proxy (r.jina.ai) gets the listing page through.
- Since 2026-09-15 every reported seat/test day is also catalogued in `race-seat-watch/listings.md` (tiers = the four budget bands below; RACE seats first, test days tagged) and rendered on the watch-wiki site; the cron flips Status to gone when an advert drops off Drives Available.
- theracehub.com/seats is a second live marketplace (team-run seats, Europe-heavy, budget shown as bands not prices, no per-item URLs — link the listing page + team name). First indexed 2026-09-12; ~78 active listings, mostly GT4/F4/LMP3 full seasons.

## Timeline
- 2026-09-17 — New: Zenith Racing Series 12h at Daytona (30–31 Oct), LS3-swapped Ginetta in ZR2/GT4 class, Cambern Performance Engineering — 2 seats at £9,500 each incl. insurance, coaching, hospitality (rcd 166298). First US listing and first priced 🧡-band race seat on the marketplace; everything else in the band is POA. Rest of Drives Available unchanged (20 known adverts + karting). Web searches (EnduroKa 2027, Fun Cup UK seats, Radical/Cayman/Ginetta Nov seats) — nothing new. (racecarsdirect.com)
- 2026-09-15 — Catalog seeded: 31 entries from the ledger (27 live, 4 gone). Drives Available re-checked via jina: 20 of 24 ledgered RCD adverts still listed; dropped off since 2 Sep = GP seats 157533, NLS3 Cayman test 162682, Ligier LMP3 test 163867, Radical SR3 test 163624 (all POA test/experience items — priced race seats all still live). Radical World Finals Barcelona seat (160722) expires this week (event 16–19 Sep). (racecarsdirect.com)
- 2026-09-12 — New: Brno 9H (18 Oct) seat from 147 Endurance / Clubsport Endurance, £1,650 per driver in a 4-way share with 50% damage cover included — cheapest priced race seat seen so far on the marketplace (rcd 166155). theracehub.com indexed for the first time: ART Racing (BE) posted a 24H Series GT3 R season (€100k+) and a GT3 R test day (<€25k) on 08/09; older UK-relevant Vortice Motorsport Britcar G56 GTA seat + G56 test day (£10-25k band) also captured. (racecarsdirect.com, theracehub.com)
- 2026-09-06 — New: F4 CEZ / German F4 seat from Chabrmotorsport (Czech), Tatuus T-421 — full season, individual race weekends or test days, £POA. First single-seater listing since watch began; off-profile geographically but a rare pro-run formula test option. (racecarsdirect.com)
- 2026-09-02 — Go Racing (rcd 163057) relisted as "Go Racing 2027": price cut £1,900 → £1,495 — now cheapest priced A&D on the marketplace. Rest of Drives Available churn is test days only (LMP3 Portimão, NLS3 Cayman, Radical). (racecarsdirect.com)
- 2026-08-22 — Watch created. Baseline: 18 racecarsdirect listings + EnduroKa/Fun Cup/C1 series A&D captured in _ledger.md. Cron `race-seat-watch` daily 08:00 London, NEW-only after day one. (racecarsdirect.com)


---

<!-- kb/racing/cayman-gt4rs-clubsport-market.md -->

# Porsche 718 Cayman GT4 RS Clubsport market
_Last updated: 2026-09-17_

Tracker for 718 Cayman GT4 RS Clubsport race cars for sale (2022-on, ~500PS 4.0, tier 1), with 718 GT4 Clubsport (2019–21) as tier 2 and 981 GT4 Clubsport as comps. Fed by the daily `cayman-gt4rs-cs-watch` cron; dedup lines in `_ledger.md` with slug prefix `gt4rs-cs-`. Catalog: `cayman-gt4rs-cs-watch/listings.md`.

**State of the market (2026-09-17):** Quiet day — full three-query racecarsdirect sweep (527 advert IDs) shows all 35 tracked adverts still live with no price movement; one new tier-1 arrival, a Bulgarian team car in Sofia (Mirafiori Team, #9 DBM) at €155k with zero disclosed data. Supply now ~25 GT4 RS CS in Europe; the market remains stuck — nothing has sold since the watch began on 14 Sep.

**Previous read (2026-09-16):** ~24 GT4 RS Clubsports openly for sale in Europe (incl. two brand-new MY2025/26 at €225k net), **two in the UK** (Graves Motorsport, Essex, 2024 POA; Team Parker Racing, Leicester, 2022 POA since Dec 2024), one in Japan, one in the US. The 16 Sep run found the racecarsdirect search is paginated and fuzzy — a further 10 cars surfaced under `gt4rs` / `cayman gt4` queries. Clean-2024 clearing band still **€145–155k+VAT**, now with a new floor: **Rempp Racing's PSC France 2025 champion car at €139k** (10,058km, hours not stated, 2-week-old advert). Black Falcon is selling its two 2024 NLS/N24 cars (€169k undamaged / €164k with a strut-tower repair). PG Motorsport (NL) is the only seller quoting real hours (47.25h all-round, safety dates listed) but at €179k it sits in the over-ask band with the rest of the Benelux/Scandi/Spanish stock. Pro-team cars with fresh drivetrains (RAZOON AT, engine+box 4,850km since rebuild, €150k) are the sweet spot for a racer; the €205k "never *big* crash" 3,000km private car and the €165k four-line Schütz advert are what to avoid.

**Previous read (2026-09-15, first full racecarsdirect pass):** ~14 GT4 RS Clubsports openly for sale in Europe, one in the UK, one in Japan, one in the US. Supply is deeper than the baseline suggested but heavily skewed to 2023/24 one- or two-season Porsche Sprint Challenge cars from FR/SE/NL/ES/CZ/LV teams. The clearing price for a clean 2024 with 7–10k km is **€145–155k+VAT** (two French cars: 9,800km/51hrs at €145k, 8,900km never-crashed at €153k). Everything asking €170–190k (Autovitesse, Andersson, PCR Sport, GP Elite) has sat 8–16 months with thousands of views — the market has rejected that band. Below €145k you are buying a problem: 15,000km engine (Riga), 160-hr car (Madrid), maintenance-list car in Japan, or the €79,990 Nürburgring wreck. New list remains ~€224.7k net (elferspot DE) with a brand-new car also in Ireland at POA. **UK supply: one car** — Graves Motorsport (Essex), 2024 ex-PSC GB, 7,500km, POA since Oct 2025. Tier 2: a fully refreshed 2019 718 GT4 CS Manthey at €125k+VAT (NL) is the only 718 GT4 CS with a price; 981 comps €85–100k. Macro: Porsche announced the 911 Challenge (Aug 2026, $275k) as the GT4 RS CS replacement at the entry level — expect used GT4 RS CS values to soften through 2027 as PSC grids transition.

## Price bands (2026-09-16)
- **Tier 1 new (MY2025/26):** €224.7k net (elferspot DE) / €225k+VAT (Schütz DE); Ireland dealer POA; US $289.9k (Isringhausen)
- **Tier 1 unknown-data new arrivals:** €155k (Mirafiori Team, Sofia BG, 166288 — no year/km/hours, added 16 Sep)
- **Tier 1 used, clean 2024 (6–10k km):** €139k (Rempp FR, 10k km, champion, VAT?) → €145k+VAT (51 hrs, FR) → €145k+VAT (GPA FR 8,900km = prob. CG car) → €150k (RAZOON AT, drivetrain 4,850km since rebuild) → €153k+VAT (CG FR) → €165k+VAT (Sorg, repaired hit) → €165k+VAT (Schütz, no data) → €168k (NKtech CZ) → €169k+VAT (Black Falcon car 1, 6,214km)
- **Tier 1 over-ask band (not selling):** €164k+VAT (Black Falcon car 2, strut-tower repair) → €170k (MY23 Autovitesse FR) → €179k+VAT (PG NL, 47h, best docs) → €179k (Andersson SE) → €185k (PCR ES) → €190k (GP Elite NL) → €205k+VAT (private FR, 3,000km, "never big crash") → €210k+VAT (Bacaracing FR)
- **Tier 1 tired/project/unknown:** "£110k+VAT" (gt4rent, W&S vice-champion, zero data) / €130k+VAT (160 hrs, ES) / €130k+VAT (13,000km JP) / €145k+VAT (15,000km engine, LV) / €79,990+VAT (crash, LT)
- **UK:** Graves Motorsport 2024 £POA+VAT; Team Parker 2022 £POA+VAT (Dec 2024 listing)
- **Spare engines:** $25,000 (5,500mi, US) / €29,900 (20,000km, being dismantled) / €7,000 (broken, 7,800km) — brackets a used 4.0 unit at core €7k → runner €25–30k
- **Tier 2 (718 GT4 CS 2019–21):** €125k+VAT (2019 Manthey, rebuilt engine + new box, NL); €89.9k ex-VAT (YM Motors FR, 19,500km, generation unconfirmed)
- **Tier 3 (981 GT4 CS):** €85,000 (2016 MR, 28k km, PT — live) → €84,981+VAT (2016 Trackday, 25k km, ES) → €99,900 (2016, 3,500km)
- **US comps:** $195k (2024 IMSA MPC car, CSM); BaT $241k (27-mile 2025, Aug 2026), $211k (2024, Sep 2025)

## Standing observations
- **RCD search is paginated (6 pages) and fuzzy.** Adverts titled "GT4RS", "GT4 CS RS", "Cayman GT4 718 CS" don't surface under "gt4 rs clubsport". Run `gt4+rs+clubsport`, `gt4rs` and `cayman+gt4` every time and diff the advert-ID set. Also check "Related Adverts" at the bottom of each advert page — that's how Schütz's two cars surfaced.
- **Same car, two sellers:** GPA Réalmont (161884, €145k) and CG Motorsport (159061, €153k) describe the identical 8,900km car. French PSC cars get cross-listed by owner and team — dedupe on km + spares before counting supply.
- **Hours vs km, updated:** PG Motorsport's car gives the only hard datapoint — 6,784km = 47.25h on a PSC Benelux car (~7 h per 1,000km). Use that to convert other sellers' km.
- **Strut-tower repairs at €5k discount** (Black Falcon car 2) show how little sellers discount structural work. Price structural repairs at €25k+ off, not €5k.
- **racecarsdirect.com access:** Cloudflare blocks web_fetch/curl/browser, but `r.jina.ai/<url>` renders search grids and advert pages fully (price, description, Added date, Views, seller). Use `&sold=False` and check the advert is still in the live grid before reporting.
- **Hours vs km:** most Euro sellers quote km not hours; ~7,000–10,000km ≈ 45–60 race hours on a PSC car. Ask for engine + gearbox hours and Porsche Motorsport service log explicitly.
- **"Never crashed" needs reading past the headline** — Sorg's ad admits a repaired right-rear hit in the body text. Assume every ex-team car has had contact until invoices say otherwise.
- **UK supply is one car on the open market**; UK cars move via teams (Team Parker, Redline, Valluga, Toro Verde, Century, Graves) off-market. Worth calling teams directly if Barney gets serious.
- **French one-season PSC cars** carry the best spares/electronics packages and the most realistic pricing; Scandinavian/Benelux/Spanish sellers anchor €30–40k higher and don't sell.
- **Stale adverts persist on RCD for 12+ months** (PCR Sport since May 2025, PDC since Oct 2024) — "Added" date + Views is the best staleness signal.
- Porsche 911 Challenge (announced Aug 2026) replaces the GT4 RS CS at the bottom of the Porsche Motorsport ladder — watch for teams dumping GT4 RS CS stock over winter 2026/27.

## Timeline
- 2026-09-17 — Run 4: 1 update sent. New tier-1: Mirafiori Team (Sofia, BG) GT4 RS CS #9 DBM, €155,000, added 16 Sep, no year/km/hours/history in advert — photos confirm genuine RS CS, Racelogic, no visible damage (166288). All 35 tracked live adverts still live, zero price changes. Brave/PistonHeads/racemarket added nothing. (racecarsdirect.com)
- 2026-09-16 — Run 3: RCD search found to be paginated/fuzzy; 3 queries surfaced 10 further tier-1 cars → 10 updates sent. New floor: Rempp Racing PSC France 2025 champion 2024 car €139k (165987). Black Falcon selling both 2024 NLS/N24 cars (165661: €169k clean / €164k strut-tower repair). PG Motorsport NL 47.25h fully documented €179k (160175). Real RAZOON advert located (161985, €150k, drivetrain 4,850km since rebuild) — baseline had mis-attributed it to NKtech 156414. GPA €145k (161884) = probable CG Motorsport car relist. Schütz DE: new MY25 €225k (160633) + used 8,000km €165k no data (160634). gt4rent "£110+VAT" W&S vice-champion, zero data (165614). Private FR 3,000km €205k "never big crash" (165511). Team Parker Racing 2022 UK £POA (151556) — second UK car. Status fixes: 981 MR 161380 live; Bacaracing = RCD 159312. Engine comps €7k broken / €29.9k 20,000km. (racecarsdirect.com)
- 2026-09-15 — Run 2: racecarsdirect fully readable via jina proxy; 14 updates sent — 12 new (10 T1 incl. the only UK car, Graves Motorsport Essex £POA; best value 2024 51hrs €145k+VAT FR; 1 T2 2019 Manthey €125k; 1 T3 981 Trackday €84,981) + 2 material updates (156414 relisted €168k by NKtech Prague; 164538 verified as Sorg Rennsport with repaired hit). 4 baseline items delisted (154804 new factory-wrap, 160880 SE Competition, 132005 PSC GT4 CS, 981 MR €85k). Price band reset to €145–155k for clean 2024s. (racecarsdirect.com)
- 2026-09-14 — BASELINE run: 9 items reported (6 T1 / 2 T2 / 1 T3); racecarsdirect Cloudflare-blocked, snippet-only; racemarket + elferspot verified live (racecarsdirect.com, racemarket.net, elferspot.com)
- 2026-09-14 — Watch created on Barney's ask (bolt)


---

<!-- kb/racing/ginetta-gta-market.md -->

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


---

<!-- kb/racing/radical-race-seats.md -->

# Radical race seats
_Last updated: 2026-08-23_

Radical opportunities in the racing ledger are a recurring arrive-and-drive / race-support cluster rather than a single confirmed seat. Current durable state: Racecarsdirect had Radical World Finals Barcelona drive availability, 2026 Radical SR3 XXR hire with A&D seats quoted at £2,800+VAT, and Radical UK/Euro championship race support for owner-drivers quoted at £1,900. Treat exact prices and availability as enquiry-dependent because the source listings can be evergreen.

## Timeline
- 2026-08-22 — Radical World Finals Barcelona drive available, price POA (racecarsdirect.com)
- 2026-08-22 — 2026 Radical SR3 XXR hire listing included arrive-and-drive seats at £2,800+VAT (racecarsdirect.com)
- 2026-08-22 — Radical UK/Euro championship race support for owner-drivers listed at £1,900 (racecarsdirect.com)


---

<!-- kb/racing/radical-sr3-market.md -->

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


---

<!-- kb/racing/seven-uk-2026-championship.md -->

# 2026 Dutch Barn Vodka / MOTUL Caterham Seven Championship UK — Standings Tracker

**State as of:** Sun 23 Aug 2026, after Round 15 (Donington GP weekend complete).
**Season:** 21 rounds / 7 events. 15 rounds run. Remaining: Snetterton 300 (R16–18, 12–13 Sep) and Brands Hatch GP (R19–21, 10–11 Oct).

## Current-state summary

Donington Sunday was a **Matt Armstrong** day. **Aaron Head** swept the weekend (3 wins from 3), but Armstrong shadowed him home P2–P2 (+ Pro Am FL in R14, and only 0.867s off Head in R15) for a 47-point Sunday, while **O'Flanagan** collapsed — P6 in R14, then P16 in R15, +1:18 adrift and ~40s behind the car ahead (trouble of some kind; the sheet shows no penalty) — and **Senior** managed only P7 / P6 (+Pro Am FL, fastest lap overall in R15). **Nuttall** DNF'd R14 (3 laps) but bounced back P4 in R15; **Lower** took P3 in R14 then DNF'd R15 on lap 11 of 12; **Justin Armstrong** recovered from P13 in R14 to a podium (P3) in R15. Armstrong now leads on gross (342) *and* post-drops (297), +9 over O'Flanagan and +18 over Senior with 6 rounds left. Critically, Armstrong's drop slate (7/17/21) is already spent, so every point he scores sticks, while O'Flanagan's R15 disaster (9 pts) burned one of his drop slots.

## Standings after Round 15 (15 of 21 rounds run)

| Pos (gross) | Driver | Gross pts | Post-drops (worst 3 removed, if applied today) | Notes |
|---|---|---|---|---|
| 1 | Matt Armstrong | 342 | **297** | 5 wins; P2+FL / P2 at Donington Sun; drops (7,17,21) already banked — everything scores from here |
| 2 | Taylor O'Flanagan | 334 | 288 | 4 wins; R15 P16 (+1:18) is now a drop (9,18,19 dropped) — one bad-round buffer gone |
| 3 | Harry Senior | 324 | 279 | 3 wins (all pre-June); P7 R14, P6+FL R15 (fastest overall); winless in 11 rounds; drops 8,18,19 |
| 4 | Justin Armstrong | 272 | ~240 | P3 in R15; drops ≈ 7,12,~13 (estimate) |
| 5 | Charlie Lower | 264 | ~249 | P3 R14, DNF R15 (lap 11); two zero-scores now dropped (estimate) |
| 6 | Steve Nuttall | 257 | ~232 | DNF R14 (first non-score), P4 R15 (estimate) |
| 7 | Nick Highton | 222 | — | P10 / P10 |
| 8 | Craig Storey | 222 | — | P12 + Am FL (fastest overall R14) / P7 — leading Am |

Further back: Monty Hinde 210, Darren McCormack 198. Donington-only starters: **Aaron Head 76** (3 wins + R13 FL), **Harry Cook 58**, Stephen Lyall 38, Tom Eden 38 (Am; P8 R14, P5 + Am FL R15), Louis Darling 28. (Post-drops for P4–P6 are estimates — exact 2nd/3rd-worst round scores not itemised in this file; top-3 drop sets are exact.)

### Points system (2026 Championship Regulations, Reg 1.6.1/1.6.2)

- **Race points** (registrations ≤32 scale, which applies — ~28 drivers seen in 2026): 25-23-22-21-20-19-18-17-16-15-14-13-12-11-10-9-8-7-6-5-4-3-2, all other classified finishers 1. (Scales of 30… and 35… exist for 33–40 / 41+ registrations.)
- **Fastest lap:** +1 per race. TSL result sheets list a fastest lap per class (Pro Am and Am); this tracker credits both (per-class), per established Caterham convention. If only the overall FL scores, Justin Armstrong's total falls by up to 4 and a handful of Am drivers by 1–2.
- **SuperPole:** top-10 shootout after qualifying; **3-2-1 bonus points** for the top three (BARC championship page confirms "additional points on offer for the top three placing cars"; 3/2/1 per series' established format — the exact figure is not printed in the 2026 regs PDF).
- **Drops (Reg 1.6.2):** season total = all 21 rounds **less three**, applied at season end. Dropped scores include any FL point from the dropped rounds; technical-DQ rounds cannot be dropped. The "post-drops" column above is a projection (worst 3 of the 13 rounds held; SuperPole bonuses kept outside the drop, as they attach to events, not race classifications — treatment in the official table unverified).

Sources: [2026 regs PDF (BARC)](https://www.barc.net/wp-content/uploads/2026/04/2026-Caterham-Seven-Championship-UK-Regulations-Published.pdf) · [BARC championship page (SuperPole note)](https://www.barc.net/championship/caterham-seven-championship-uk/)

## Season timeline (verified results)

| Event | Rounds | Winners (overall) | Source |
|---|---|---|---|
| Croft, 2–3 May (Speedfest North) | 1–3 | Senior / Senior / O'Flanagan. SP: Senior | [TSL 261821](https://www.tsl-timing.com/event/261821) rc1/rc2/rc3cuk PDFs |
| Spa-Francorchamps, 29–31 May (combined grid w/ 310R, class CSCUK) | 4–6 | Senior / O'Flanagan / O'Flanagan. SP(quali): Lower | [SER results](https://ser2026.racspa.be/resultats) 31005_ClassificationByClass_Race1/2/3 |
| Oulton Park, 18 Jul (Caterham Island) | 7–9 | M. Armstrong / O'Flanagan / M. Armstrong. SP: M. Armstrong | [TSL 262927](https://www.tsl-timing.com/event/262927) |
| Knockhill, 8–9 Aug (BTCC support) | 10–12 | M. Armstrong ×3. SP: M. Armstrong | [TSL 263203](https://www.tsl-timing.com/event/263203) |
| Donington GP, 22–23 Aug (BTCC support) | 13–15 | **R13: Aaron Head** (Lower 2nd, Lyall 3rd, M.Armstrong 4th, Cook 5th, Senior 6th, O'Flanagan 7th; J.Armstrong 18th after lap-7 stop; FL A. Head). SP: O'Flanagan. **R14 (11 laps): Aaron Head** (M.Armstrong 2nd + Pro Am FL, Lower 3rd, Cook 4th, Darling 5th, O'Flanagan 6th, Senior 7th, Eden 8th, Lyall 9th, Highton 10th; Storey 12th + Am FL (fastest overall); J.Armstrong 13th; DNF: Nuttall/D.Head/Evans lap 3, NC Curtis). **R15 (12 laps): Aaron Head** (M.Armstrong 2nd +0.867, J.Armstrong 3rd, Nuttall 4th, Eden 5th + Am FL, Senior 6th + Pro Am FL (fastest overall, 1:36.445), Storey 7th, Cook 8th; O'Flanagan 16th +1:18; DNF: Lower lap 11, Lyall lap 4, Evans lap 0) | [TSL 263403](https://www.tsl-timing.com/event/263403) rc2/rc3cuk PDFs |
| Snetterton 300, 12–13 Sep | 16–18 | — | |
| Brands Hatch GP, 10–11 Oct | 19–21 | — | |

Note: Cadwell Park (11–12 Apr) and Donington National "Seven Heaven" (20 Jun) hosted other Caterham series (Roadsport/270R/310R/Academy), **not** Seven UK — the Seven UK calendar is the 7 events above (Reg 1.5).

## Title maths (6 rounds left: Snetterton R16–18, Brands GP R19–21)

Max remaining haul ≈ 6 races × 26 (win+FL) + SuperPole 3 at Snetterton + 3 at Brands ≈ **162**. Post-drops: **Armstrong 297, O'Flanagan 288 (−9), Senior 279 (−18)**. All three now have their drop slots effectively filled with low scores, so from here the championship is close to a straight points race — but Armstrong's drops (7/17/21) are the cheapest, and his floor is the highest: he hasn't finished worse than P4 since Spa. Practical read for **Senior**: he must out-score Armstrong by ~18 over 6 races (≈3 pts/race) having not beaten him on the road since Croft in May; two more anonymous P6–P7s this weekend means the yesterday-frame "win → ~40%" branch is dead and his title shot is on life support (~5%). His realistic fight is now P2 vs O'Flanagan (9 pts back, and O'Flanagan's form just cracked — R15's 9-pointer was his first finish outside the top 7 all year). **O'Flanagan → Armstrong** (−9) stays live but needs an Armstrong bad weekend that hasn't happened in three months. Wildcard: if Aaron Head enters Snetterton/Brands he keeps removing 25s from the table, which freezes gaps and helps the leader.

## Caveats / unverified

- **Spa guest drivers:** Swann, Sampson, Dickens, Finlayson appear only at Spa; if any were non-scoring guests, registered drivers below them move up 1–2 positions (e.g., M. Armstrong's Spa R1 P18→~P16, +2; several +1s). Totals could shift by low single digits. Not verified.
- **Spa lapped finishers** (listed P18–P22, some many laps down) treated as classified per the official sheets.
- **SuperPole at Spa** assumed awarded on the single CSCUK qualifying classification (Lower/Senior/O'Flanagan).
- **FL per-class vs overall** ambiguity (see points system above).
- **Aaron Head, Cook, Lyall** treated as scoring registrations (listed as normal Pro Am entries, not guests, on the TSL sheet).
- No official BARC/Caterham points table was found published online to cross-check these computed totals.

## Data trail

- Raw classification PDFs parsed from TSL (`/file/?f=BARC|TOCA/2026/<event><session>cuk.pdf`) and racspa.be (`docs/31005_ClassificationByClass_*.PDF`).
- Regs PDF cached at `kb/racing/seven26regs.pdf`.
- Knockhill narrative cross-check: [BARC report](https://www.barc.net/toca-support-championships-deliver-blockbuster-action-at-knockhill/) — confirms Armstrong treble and that O'Flanagan arrived as points leader (matches computed gross standings: after R9 (pre-Knockhill) O'Fl 216, M.Armstrong 195, Senior 195; after R12 O'Fl 285, M.A. 273, Senior 267 (incl. SP bonuses).


---

<!-- kb/racing/_ledger.md -->

# racing ledger — race-seat-watch + car-watch dedup (slug prefixes: rcd-, radical-sr3-, ginetta-gta-, gt4rs-cs-)

Format: `YYYY-MM-DD | slug | one-line summary | source-domain`

2026-08-22 | rcd-153178-nls-n24-drives | Nürburgring NLS + 24h drives available, €POA | racecarsdirect.com
2026-08-22 | rcd-144830-philippines-endurance | Endurance race Philippines 2026-11-21, €1,200 | racecarsdirect.com
2026-08-22 | rcd-160722-radical-world-finals | Radical World Finals Barcelona drive, £POA | racecarsdirect.com
2026-08-22 | rcd-161486-legends-le-mans | Legends of Le Mans drive available, £POA | racecarsdirect.com
2026-08-22 | rcd-80197-brscc-mx5-aad | BRSCC MX-5 Championship arrive-and-drive package, £POA | racecarsdirect.com
2026-08-22 | rcd-164096-barcelona-24h-gt4 | 24h Barcelona GT4 seat, €POA+VAT | racecarsdirect.com
2026-08-22 | rcd-165251-992-cup-24h-series | Porsche 992 GT3 Cup 24H Series Europe/Middle East, £POA | racecarsdirect.com
2026-08-22 | rcd-165150-992-barcelona-spa | 992 endurance drives 24h Barcelona / 12h Spa, €POA | racecarsdirect.com
2026-08-22 | rcd-129901-radical-sr3xxr-hire | 2026 Radical SR3 XXR for hire, £POA (A&D seats £2,800+VAT) | racecarsdirect.com
2026-08-22 | rcd-160724-radical-race-support | Radical UK/Euro champs race support for owner-drivers, £1,900 | racecarsdirect.com
2026-08-22 | rcd-164853-leon-supercopa | SEAT Leon Supercopa Iberian series drive, €POA | racecarsdirect.com
2026-08-22 | rcd-164291-lmp3-le-mans-cup | LMP3 Le Mans Cup 2027 seats (Ligier JS P325), €POA+VAT | racecarsdirect.com
2026-08-22 | rcd-164288-gt4-euro-amg | GT4 European Series Mercedes-AMG driver seat, £POA | racecarsdirect.com
2026-08-22 | rcd-150679-cayman-sprint-challenge | Porsche Cayman Sprint Challenge UK subsidised seat, £POA+VAT | racecarsdirect.com
2026-08-22 | rcd-152180-mx5-mk1-aad | Mazda MX-5 Mk1 racing/trackday arrive-and-drive, £POA | racecarsdirect.com
2026-08-22 | rcd-125547-praga-equipe | Praga prototype drive in Equipe series, £POA | racecarsdirect.com
2026-08-22 | rcd-163057-go-racing-aad | Go Racing no-hassle arrive & drive race seats, £1,900 | racecarsdirect.com
2026-08-22 | rcd-157533-grand-prix-seats | 2026 Grand Prix driving seats available, £POA | racecarsdirect.com
2026-08-22 | enduroka-aad-2026 | EnduroKa series-approved arrive-and-drive, ~£1,000-1,500/seat/round | enduroka.co.uk
2026-08-22 | funcup-aad-2026 | Fun Cup A&D from £3,500+VAT/driver, seat hire from £3,650, season from £23,510+VAT | funcup.co.uk
2026-08-22 | c1-cup-aad-2026 | C1 Cup arrive-and-drive via teams, ~£1,000-1,800/seat/round | tomofcars.com
2026-08-23 | seven-uk-r14-r15-donington | R14+R15 results ingested from TSL 263403 rc2/rc3cuk PDFs; standings recomputed (Armstrong 342/297, O'Flanagan 334/288, Senior 324/279) | tsl-timing.com
2026-09-02 | rcd-163057-go-racing-2027-price-drop | UPDATE: Go Racing A&D relisted for 2027, price cut £1,900 → £1,495 | racecarsdirect.com
2026-09-02 | rcd-165949-lmp3-test-portimao | LMP3 driver test Portimão 29-30 Sept, €POA+VAT (test days now in scope per Barney) | racecarsdirect.com
2026-09-02 | rcd-162682-nls3-cayman-test | NLS3 test day Nürburgring, Cayman GT4 CS 718, £POA+VAT | racecarsdirect.com
2026-09-02 | rcd-163867-ligier-lmp3-test | Test a Ligier LMP3 V8 Le Mans prototype, £POA | racecarsdirect.com
2026-09-02 | rcd-163624-radical-sr3-test | Radical SR3 XXR test/track day experience, £POA | racecarsdirect.com
2026-09-06 | rcd-161271-f4-cez-german-seat | F4 CEZ / German F4 seat (Tatuus T-421, Chabrmotorsport CZ) — full season, single race weekends or test days, £POA, added 05/09 | racecarsdirect.com
2026-09-12 | rcd-166155-brno-9h-147-endurance | Brno 9H race 18 Oct, 147 Endurance 2000cc Superproduction, £1,650 per driver (4-way share, 50% damage cover incl.), added 09/09 | racecarsdirect.com
2026-09-12 | racehub-art-gt3r-24h-series-season | ART Racing (BE) 24H Series full-season seat, Porsche 992 GT3 R, €100k+, FIA Bronze+, listed 08/09 | theracehub.com
2026-09-12 | racehub-art-gt3r-test-day | ART Racing Porsche 992 GT3 R test day, under €25k, Belgium/Germany, listed 08/09 | theracehub.com
2026-09-12 | racehub-vortice-britcar-g56-gta | Vortice Motorsport Britcar Endurance Ginetta G56 GTA seat, £10-25k band, National licence, UK/Europe (older listing, first index of theracehub) | theracehub.com
2026-09-12 | racehub-vortice-g56-test-day | Vortice Motorsport Ginetta G56 UK test day, £10-25k band, incl. fees/fuel/tyres/staff/data (older listing, first index of theracehub) | theracehub.com
2026-09-14 | radical-sr3-xxr-2026-highspec-84995 | BASELINE T1: 2026 SR3 XXR high-spec latest gen, £84,995+VAT, listed 23.08.2026 (snippet, page unverified) | racecarsdirect.com
2026-09-14 | radical-sr3-xxr-feb2025-never-raced-poa | BASELINE T1: SR3 XXR 1500 built Feb 2025 never raced, £POA, featured 23.08.2026 | racecarsdirect.com
2026-09-14 | radical-sr3-xxr-0hr-rpe-71995 | BASELINE T1?: SR3 with 0-hour RPE motor, £71,995, updated 25.07.2026, model year unconfirmed | racecarsdirect.com
2026-09-14 | radical-sr3-rcd-150175-xxr-2023-gen5 | BASELINE T1: 2023 SR3 XXR Gen5 1500 LS, 10h run/6h load, new splitter/skirts/billet clutch, price n/a | racecarsdirect.com
2026-09-14 | radical-sr3-rcd-158830-xxr-2025 | BASELINE T1: 2025 SR3 XXR, latest 1500 RPE, Intrax triple, cast uprights, price n/a | racecarsdirect.com
2026-09-14 | radical-sr3-rcd-162055-xxr-dubai-122500 | BASELINE T1: SR3 XXR 1500 full race spec, 1 meeting, Dubai, £122,500 — over-ask | racecarsdirect.com
2026-09-14 | radical-sr3-rcd-164487-xxr-1340-white | BASELINE T1: SR3 XXR 1340 Brilliant White carbon centre seat Quaife LSD, 14.06.2026, price n/a | racecarsdirect.com
2026-09-14 | radical-sr3-xx-2022-world-finals-52995 | BASELINE T2: 2022 SR3 XX World Finals winner, £52,995+VAT (was £72k+VAT Jul 2024 → £65k+VAT), updated 01.07.2026 | racecarsdirect.com
2026-09-14 | radical-sr3-rsx-rlm-rebuild-42000 | BASELINE T3: SR3 RSX full engine/gearbox/GDU rebuild by RLM Racing, low hours, £42,000, 28.05.2026 | racecarsdirect.com
2026-09-14 | gt4rs-cs-rcd-2024-never-crashed-165k | BASELINE: 2024 GT4 RS Clubsport "Original Low Mileage / Never Crashed", €165,000+VAT, listed 16.06.2026 (search-index only, unverified) | racecarsdirect.com
2026-09-14 | gt4rs-cs-rcd-156414-razoon-adac | BASELINE: RAZOON ex-ADAC GT4 Germany GT4 RS CS, €150,000, listed 16.02.2026 (unverified) | racecarsdirect.com
2026-09-14 | gt4rs-cs-rcd-2024-nurburgring-crash | BASELINE: 2024 GT4 RS CS 9,500km accident-damaged Nürburgring, €79,990+VAT, listed 11.08.2026 (project car, unverified) | racecarsdirect.com
2026-09-14 | gt4rs-cs-racemarket-6672-bacaracing | BASELINE: 2024 GT4 RS CS Bacaracing FR, ex-PSC France 2024, 5,000km, big spares/AIM/radio, €210,000 ex-VAT (over-ask, live) | racemarket.net
2026-09-14 | gt4rs-cs-elferspot-5886269-new-2026 | BASELINE: NEW 2026 GT4 RS CS German dealer, €224,700 net (€271,900 gross), spares pkg €6,990 extra (live) | elferspot.com
2026-09-14 | gt4rs-cs-rcd-154804-new-factory-wrap | BASELINE one-liner: GT4 RS CS NEW, factory wrap, POA (unverified) | racecarsdirect.com
2026-09-14 | gt4rs-cs-rcd-160880-gt4cs-comp-sweden | BASELINE tier2: 718 GT4 CS Competition 7,250km ex-Porsche Sweden PSC Scandinavia, POA (unverified) | racecarsdirect.com
2026-09-14 | gt4rs-cs-racemarket-6168-ym-manthey | BASELINE tier2: Cayman GT4 CS Manthey, 19,500km, €89,900 ex-VAT, YM Motors FR, generation unconfirmed (live) | racemarket.net
2026-09-14 | gt4rs-cs-rcd-981-gt4-mr-85k | BASELINE tier3 comp: 981 GT4 MR €85,000, listed 19.01.2026 (unverified) | racecarsdirect.com
2026-09-14 | ginetta-gta-regs-2026 | 2026 BRSCC GT Academy regs (pub 21 Apr 2026): G56 GTA only (5.2.1), 3.7 or 3.5 V6 (5.10.2), G55 GTA not eligible; reg fee £16,500+VAT incl all rounds; 2026 adds Motec C125/PDM, sealed ECU, driver net, Pirelli Trofeo RS 18" | brscc.co.uk
2026-09-14 | ginetta-gta-rcd-159270-2025-spec-preston | Tier 1: 2025-spec 3.5 G56 GTA, £50,000+VAT, engine in warranty, gearbox 12h, diff 0h, trade Preston, listed Oct 2025 (11 months unsold) | racecarsdirect.com
2026-09-14 | ginetta-gta-rcd-165948-rhd-37k | Tier 1: G56 GTA RHD £37,000, private Lincs, listed 31/08/2026, dry-stored/2 track days, hours+spec not stated | racecarsdirect.com
2026-09-14 | ginetta-gta-rcd-163858-2024-lhd | Tier 1: 2024 G56 GTA LHD £39,995+VAT (cut from £49,500+VAT), 108h total, gearbox 62h, 3 wheel sets, minor body damage, 7TSIX Ltd Dewsbury | racecarsdirect.com
2026-09-14 | ginetta-gta-rcd-159438-poa-south-kirkby | Tier 1: G56 GTA 3.7 "upgraded to current spec" £POA+VAT, trade South Kirkby, listed Nov 2025, no hours | racecarsdirect.com
2026-09-14 | ginetta-gta-comps-baseline | Tier 3 comps: G55 Supercup £32k+VAT / £35k; GTP8 £75k, £85k+VAT, £84,999; G56 GT4 EVO £145k+VAT; BaT US 2024 GTA sold $57k Oct 2025 | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-165920-xxr-2023-white-novat-71995 | T1 NEW: 2023 SR3 XXR Brilliant White, 1500 just refreshed by RPE factory, £71,995 no VAT, Performance Time Stratford, added 28.08.2026 | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-166114-xx-2020-1301-47000 | T2 NEW: 2020 SR3 XX #1301, RLM 1500 Gen4 16h load since rebuild, fresh GDU, Life F88 paddleshift, £47,000, RJ Motorsport Cambs, added 07.09.2026 | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-165991-xx-2021-romania-50000 | T2 comp NEW: SR3 XX 2021/22 1500, Romania, 1 season then stored, hours unstated, €50,000+VAT, added 02.09.2026 | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-165548-rsx-forge-40000 | T3 NEW: SR3 RSX very low hours RLM 1500, refreshed GDU, Intrax, £40,000, Forge Precision Derbyshire, added 06.08.2026 | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-162701-xxr-2023-01595-dubai-99000 | T1 comp (catalogued, not headlined): 2023 XXR #01595 G5 1500 16h, LHD, ex Gulf Radical Cup, £99k excl shipping, Dream Racing Dubai, 19.03.2026 | racecarsdirect.com
2026-09-15 | radical-sr3-xxr-0hr-rpe-71995 | STATUS: RCD 165312 2023 XXR Rosso Red 0h RPE £71,995 now DEPOSIT TAKEN (7 weeks on market) | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-150175-xxr-2023-gen5 | STATUS: SOLD (North Motorsport 2023 XXR Gen5 10h/6h) | racecarsdirect.com
2026-09-15 | radical-sr3-xxr-2026-highspec-84995 | VERIFIED: RCD 165836 = Performance Time 2026 XXR Stealth Black, 17h under load, carbon splitter/diffuser, AP brakes, £84,995+VAT, cost new £135.5k | racecarsdirect.com
2026-09-15 | radical-sr3-rcd-158830-xxr-2025 | PRICE: Valour Racing 2025 XXR = £81,000+VAT, listed 09.10.2025, 5975 views — stale | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-159263-graves-pscgb-uk | 2024 GT4 RS CS Graves Motorsport Essex, ex-PSC GB, 7,500km, £POA+VAT — only UK car (live, verified) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-164811-france-51hrs | 2024 GT4 RS CS Val d'Isère FR, 9,800km, engine 51hrs, accident-free, €145,000+VAT — best value (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-159061-cg-motorsport | 2024 GT4 RS CS CG Motorsport FR, 8,900km, never crashed, PCF 2024 winner, €153,000+VAT (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-165138-riga-baltic | GT4 RS CS Riga LV, engine 15,000km / box 4,000km, VBOX, FIA 2027, €145,000+VAT — tired engine flag (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-156414-razoon-adac | UPDATE: advert 156414 now NKtech Prague MY2024 7,200km one season no damage, €168,000 (+€18k vs baseline €150k snippet) (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-2024-never-crashed-165k | UPDATE: verified as Sorg Rennsport advert 164538, 6,625km, 1 season; small print admits right-rear hit repaired — contradicts "never crashed" (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-159030-autovitesse-my23 | MY23 GT4 RS CS Autovitesse FR, chassis 10,791km / engine 4,670km / box 2,028km, FFSA GT4→GT4 Euro→PSC FR, €170,000+VAT (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-160380-andersson-sweden | MY24 GT4 RS CS Andersson SE, 7,200km PSC Scandinavia, service due, €179,000+VAT — over-ask (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-155170-pcr-barcelona-my23 | MY23 GT4 RS CS PCR Sport Barcelona, 7,844km, 16 months unsold, €185,000+VAT — over-ask (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-161649-gp-elite-my23 | MY23 GT4 RS CS GP Elite NL, 9,532km ex-PSC Benelux, €190,000+VAT — over-ask (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-160114-rgb-madrid-160hrs | GT4 RS CS RGB Racing Madrid, 160hrs, box 20hrs, "€130+VAT" (≈€130k) — tired (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-163383-japan-destino | 2024 GT4 RS CS Yokohama JP, 13,000km Japan Cup, new PDK, needs maintenance, €130,000+VAT + shipping (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-160135-faulkner-ireland-new | Brand-new GT4 RS CS + 2024 3k km, Damien Faulkner IE, €POA+VAT (live, one-liner) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-154820-pdc-2019-manthey | tier2: 2019 718 GT4 CS Manthey kit, Porsche Drivers Club NL, 25,000km, rebuilt engine + new box 1,000km, fuel cell 2029, €125,000+VAT (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-165095-julia-981-trackday | tier3: 2016 981 GT4 CS Trackday, Julia Automobile Barcelona, 25,290km, Andorra-reg, €84,981+VAT (live) | racecarsdirect.com
2026-09-15 | gt4rs-cs-rcd-166008-spare-engine | parts: spare GT4 RS CS engine 5,500mi, $25,000 USA (live, one-liner) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-165987-rempp-psc-france-champ | 2024 GT4 RS CS Rempp Racing FR, 10,058km, PSC France 2025 champion + 3 wins 2026, FFSA passport, €139,000 — cheapest running T1, hours not stated (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-165661-black-falcon-pair | 2x MY2024 GT4 RS CS Black Falcon DE ex-NLS/N24 2025: car1 6,214km original drivetrain no damage €169,000+VAT; car2 14,920km new engine/box + strut-tower repair €164,000+VAT (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-160175-pg-motorsport-4725h | 2024 GT4 RS CS PG Motorsport NL, 6,784km, 47.25h all, PSC Benelux 2024 champion, fuel cell 2028, 3 rim sets, €179,000+VAT — best documented, over-ask (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-161985-razoon-austria | GT4 RS CS RAZOON AT ex-ADAC GT4 Germany, engine+box 4,850km since rebuild, DMSB+SRO passports, €150,000 — the real RAZOON advert (baseline mis-attributed to 156414) (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-161884-gpa-realmont | 2024 GT4 RS CS GPA Réalmont FR, 8,900km, never crashed, 2 wheel sets, FFSA exhaust, €145,000+VAT — same spec as CG Motorsport 159061 (€153k), likely same car (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-160634-schuetz-ready-to-race | GT4 RS CS Schütz Motorsport DE, 8,000km, VBOX HD2, no year/hours/crash info, €165,000+VAT (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-160633-schuetz-new-my25 | NEW MY2025 GT4 RS CS 0km Schütz Motorsport DE, €225,000+VAT (live, one-liner) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-165614-gt4rent-ws-vicechamp | GT4 RS CS gt4rent.com Nürburgring, W&S-run GT4 European Series vice-champion, "£110+VAT", no year/km/hours, rental fleet (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-165511-shunker-3000km | Cayman GT4 RS race car private FR, 3,000km, "never big crash", wheels extra, €205,000+VAT — over-ask (live) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-151556-team-parker-uk | 2022 GT4 RS CS Team Parker Racing Leicester UK, British GT 2022/23 + PSC GB 2024, £POA+VAT since Dec 2024 — UK car #2 (live, one-liner) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-164382-engine-20000km | parts: GT4 RS engine 20,000km €29,900 + broken 7,800km engine 163528 €7,000 (live, one-liner) | racecarsdirect.com
2026-09-16 | gt4rs-cs-rcd-981-gt4-mr-85k | STATUS: 981 GT4 MR €85,000 (advert 161380, Estoril PT) is LIVE — 15 Sep "delisted" was a search-scope miss; seen.json URL fixed (not re-reported) | racecarsdirect.com
2026-09-16 | gt4rs-cs-racemarket-6672-bacaracing | STATUS: Bacaracing €210,000+VAT also live as RCD advert 159312 (added 29.10.2025) — same car, not re-reported | racecarsdirect.com
2026-09-17 | gt4rs-cs-rcd-166288-mirafiori-sofia | GT4 RS CS Mirafiori Team Sofia BG (DBM #9, Markov/Balev), €155,000 VAT? — no year/km/hours disclosed, BMW/drift seller, added 16.09.2026 (live) | racecarsdirect.com
2026-09-17 | rcd-166298-daytona-12h-v8-ginetta | Zenith Racing Series 12h Daytona 30-31 Oct, LS3 V8 Ginetta ZR2 class, Cambern Performance Engineering, 2 seats £9,500 each incl insurance/coaching/hospitality, added 16/09 | racecarsdirect.com
