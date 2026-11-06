# Stellar Traction Report

**USDC (issuer GA5Z…KZVN)**

| Field | Value |
| --- | --- |
| Subject | `USDC:GA5ZSEJYB37JRC5AVCIA5MOP4RHTM335X2KGX3IHOJAPP5RE34K4KZVN` |
| Kind | Asset |
| Network | Stellar mainnet |
| Period | 2026-10-31 – 2026-11-06 (UTC, 7 days) |
| Generated | 2026-11-06 11:42 UTC |
| Source | BlocRA, from Stellar ledgers it collected |

> **⚠ Partial data: BlocRA holds 3 hours of the 7-day period (66.7% of ledgers in that span), collected since 2026-11-06. All figures cover only the collected time, and there is no previous period to compare with.**

## Scorecard

| Metric | Value | Δ vs previous period |
| --- | --- | --- |
| Active accounts | 1,631 | — |
| New accounts | 1,631 (insufficient history) | — |
| Payments | 15,291 | — |
| Failure rate | 64.3% | — |
| Volume (asset units) | 31,039,125.66 | — |
| Payments per account | 9.4 | — |

## Key findings

- Activity is concentrated: the top 10 of 1631 accounts made 64.1% of payments.
- 4 accounts made ≥1000 payments on a single day (automated); together 45.2% of all payments.
- 69.7% of payments were sent to the sender's own account (arbitrage loops); they are excluded from volume.
- 64.3% of payments failed, well above the 1.7% median of comparable assets.
- Ranked #2 of 633 assets by active accounts in this period (top 1%).
- Partial data: BlocRA holds 3.0 hours of the 7-day period (66.7% of ledgers in that span). Figures cover only the collected time.

## Activity

| Day (UTC) | Active accounts | Payments | Failed | Volume |
| --- | --- | --- | --- | --- |
| 2026-11-06 | 1,631 | 15,291 | 9,825 | 31,039,125.66 |

## Retention & user quality

| Measure | Value |
| --- | --- |
| Returning accounts (active in previous period too) | — (needs a previous period) |
| Top-10 accounts' share of activity | 64.1% |
| Bot-like accounts (≥ 1,000 payments on one day) | 4 |
| Bot-like share of activity | 45.2% |
| Self-payments (to own account, excluded from volume) | 69.7% (10,651) |

Top accounts:

| Account | Payments | Share | Bot-like |
| --- | --- | --- | --- |
| [GC2IXX…2X7M](https://stellar.expert/explorer/public/account/GC2IXXCFV5LN7YF732GZ353J22F3G2BZWUM4U4BCSF2WYGTW4QIX2X7M) | 2,260 | 14.8% | yes |
| [GAUA7X…PNJU](https://stellar.expert/explorer/public/account/GAUA7XL5K54CC2DDGP77FJ2YBHRJLT36CPZDXWPM6MP7MANOGG77PNJU) | 1,765 | 11.5% | yes |
| [GBXQUJ…HMTP](https://stellar.expert/explorer/public/account/GBXQUJBEDX5TYLJ6D5BGJZFLYF5GZVGXLWA2ZORS5OIA7H6B5O3MHMTP) | 1,703 | 11.1% | yes |
| [GAOYFQ…PNLT](https://stellar.expert/explorer/public/account/GAOYFQYMNHR3A4Q44I6BYQSD6IJ7RSKWPJQLGJQSJ7TF2HO7A4SHPNLT) | 1,191 | 7.8% | yes |
| [GBEJMH…N4CW](https://stellar.expert/explorer/public/account/GBEJMHIMASJBIGGV5UKACNIZTQN3ZCILKZBH6W5PFI5TPCFPT5ASN4CW) | 640 | 4.2% | no |

## Asset snapshot

| Measure | Value |
| --- | --- |
| Holders (accounts with a trustline) | 2,528,503 |
| Supply in accounts | 210,000,588.18 |
| Supply in contracts | 114,401,741.19 |
| Supply in liquidity pools | 2,484,700.27 |
| Contracts holding the asset | 48,298 |
| Liquidity pools | 955 |
| Stellar Asset Contract | [`CCW67TSZV3SSS2HXMBQ5JFGCKJNXKZM7UQUWUZPUTHXSTZLEO7SJMI75`](https://stellar.expert/explorer/public/contract/CCW67TSZV3SSS2HXMBQ5JFGCKJNXKZM7UQUWUZPUTHXSTZLEO7SJMI75) |
| stellar.toml | <https://circle.com/.well-known/stellar.toml> |

Snapshot from Horizon at 2026-11-06 11:42 UTC.

## Ecosystem position

| Measure | Value |
| --- | --- |
| Rank by active accounts | #2 of 633 assets |
| Percentile | 99.8 |
| Median failure rate of peer assets | 1.7% |

## Coverage & methodology

| Measure | Value |
| --- | --- |
| Ledger range | 65,333,687 – 65,335,853 |
| Ledgers collected | 1,446 |
| Expected ledgers in period | 109,964 |
| Completeness | 66.7% |
| Time covered | 3 hours of 7 days |
| Collection started | 2026-11-06 |

- Source: every Stellar ledger read from Horizon by BlocRA's collector and stored with its transactions and operations.
- Days are UTC calendar days; the latest day may be partial.
- Activity is payments and path payments of the asset; the account is the sender. Volume sums amounts of successful payments to other accounts, in the asset's units; payments to oneself (arbitrage loops) are counted as self-payments and left out of volume.
- Automated (bot-like) accounts made at least 1000 payments on a single day.
- New accounts were first seen during the period in all data BlocRA has collected; with less history than the period, they are marked unreliable.
- Ecosystem rank compares active accounts with every contract (or asset) active in the same period; the failure-rate median uses peers with at least 10 active accounts.

## Verification

This file is verifiable: its sha256 hash can be recorded in BlocRA's report registry on Stellar. Upload this exact file at BlocRA → Verify Report (/verify-report) to check that it was published and has not been modified.
