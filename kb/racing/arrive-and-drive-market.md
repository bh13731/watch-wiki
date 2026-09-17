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
