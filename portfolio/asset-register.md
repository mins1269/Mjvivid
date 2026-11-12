# Jean Capital — Asset Register

As at 12 Nov 2026 (KST). Compiled from `portfolio/assets/*.md` (Market Desk, firm setup).
All assets are **fictional**; tenants are fictional. Asset-level figures are `[ASSUMED]` and
anchored to the real comparables listed in each asset file's Sources section.
Derived metrics are deliberately blank: **Analyst to compute**.

| Code | Asset | Location | Sector | Tenure / vehicle | Size | Units / tenants | Occupancy (facts) | Acquired | Price (excl. costs) | Passing rent | NOI | NIY | WAULT |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [UK-01](assets/UK-01.md) | Larchwood Trade Park | Manor Royal, Crawley RH10, West Sussex | Multi-let industrial | Freehold | 47,050 sq ft GIA `[ASSUMED]` | 8 units `[ASSUMED]` | 7 let / 1 vacant (U4); U2 rent-free to 31 Jan 2027; U3 in arrears `[ASSUMED]` | 14 Aug 2025 `[ASSUMED]` | £8,450,000 `[ASSUMED: anchored to Comps C5–C10 in UK-01]` | Analyst to compute | Analyst to compute | Analyst to compute | Analyst to compute |
| [UK-02](assets/UK-02.md) | Corvel Yard | Ancoats, Manchester M4 | Build-to-Rent | Freehold | 180 flats, 115,920 sq ft resi NIA + 2,750 sq ft commercial `[ASSUMED]` | 180 flats + 2 commercial units (café, gym) `[ASSUMED]` | 172 / 180 flats occupied; both commercial let; 4 tenancies in arrears `[ASSUMED]` | 20 Mar 2025 `[ASSUMED]` | £39,500,000 `[ASSUMED: anchored to Comps C5–C6 in UK-02]` | Analyst to compute | Analyst to compute | Analyst to compute | n/a (periodic) — Analyst to define metric |
| [KR-01](assets/KR-01.md) | Seolleung Meridian Tower, 15F–16F (strata) | Yeoksam-dong, Gangnam-gu, Seoul (GBD) | Grade A office | Strata (구분소유) via private REF | 1,400 평 / 4,628.1 m² 임대면적; 728 평 / 2,406.6 m² 전용 `[ASSUMED]` | 4 tenants `[ASSUMED]` | Fully let; Yeonsu rent-free ends 30 Nov 2026 `[ASSUMED]` | 15 Dec 2025 `[ASSUMED]` | KRW 58.8bn (KRW 42.0m/평) `[ASSUMED: anchored to Sources 4, 6 in KR-01]` | Analyst to compute | Analyst to compute | Analyst to compute | Analyst to compute |
| [KR-02](assets/KR-02.md) | Hobeop Gaon Logistics Centre | Hobeop-myeon, Icheon, Gyeonggi | Logistics (ambient + cold) | Non-listed REIT (위탁관리) | 20,000 평 / 66,115.7 m² GFA; ambient 14,000 평, cold 6,000 평 `[ASSUMED]` | 3 tenants + vacant cold floor `[ASSUMED]` | Ambient fully let; cold 3,500 평 let / 2,500 평 vacant since completion `[ASSUMED]` | 28 Jun 2024 `[ASSUMED]` | KRW 124.0bn (KRW 6.2m/평 GFA) `[ASSUMED: anchored to Source 6 in KR-02]` | Analyst to compute | Analyst to compute | Analyst to compute | Analyst to compute |

Portfolio totals (GAV, rent, GBP/KRW translation, sector/country split): **Analyst to compute.**

## Source-verification status
The Market Desk could not open source pages directly from this environment (network
blocked); all comparable figures were taken from search-engine extracts of the linked
pages. Each asset file's **Data gaps** section lists what is unverified. Open each link
before relying on a figure in a model or IC paper.

## Files
- `assets/UK-01.md`, `assets/UK-02.md`, `assets/KR-01.md`, `assets/KR-02.md` — rent roll, lease terms, 24-month events, comps, sources, data gaps
- `lease-events-calendar.md` — consolidated 24-month calendar
- `mandate.md` — return targets blank, awaiting Owner
