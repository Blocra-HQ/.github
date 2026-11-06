# Stellar Traction Report

**Contract CDL74R…IGWA**

| Field | Value |
| --- | --- |
| Subject | `CDL74RF5BLYR2YBLCCI7F5FB6TPSCLKEJUBSD2RSVWZ4YHF3VMFAIGWA` |
| Kind | Soroban contract |
| Network | Stellar mainnet |
| Period | 2026-10-31 – 2026-11-06 (UTC, 7 days) |
| Generated | 2026-11-06 11:42 UTC |
| Source | BlocRA, from Stellar ledgers it collected |

> **⚠ Partial data: BlocRA holds 3 hours of the 7-day period (66.7% of ledgers in that span), collected since 2026-11-06. All figures cover only the collected time, and there is no previous period to compare with.**

## Scorecard

| Metric | Value | Δ vs previous period |
| --- | --- | --- |
| Active accounts | 4,618 | — |
| New accounts | 4,618 (insufficient history) | — |
| Contract calls | 134,946 | — |
| Failure rate | 1.5% | — |
| Volume (asset units) | — (not applicable) | — |
| Contract calls per account | 29.2 | — |

## Key findings

- 1.5% of calls failed, in line with the 0.9% median of comparable contracts.
- Ranked #1 of 144 contracts by active accounts in this period (top 1%).
- Partial data: BlocRA holds 3.0 hours of the 7-day period (66.7% of ledgers in that span). Figures cover only the collected time.

## Activity

| Day (UTC) | Active accounts | Contract calls | Failed |
| --- | --- | --- | --- |
| 2026-11-06 | 4,618 | 134,946 | 2,024 |

## Retention & user quality

| Measure | Value |
| --- | --- |
| Returning accounts (active in previous period too) | — (needs a previous period) |
| Top-10 accounts' share of activity | 0.3% |
| Bot-like accounts (≥ 1,000 calls on one day) | 0 |
| Bot-like share of activity | 0% |

Top accounts:

| Account | Contract calls | Share | Bot-like |
| --- | --- | --- | --- |
| [GCBMJ4…SR3H](https://stellar.expert/explorer/public/account/GCBMJ4JTFA26LGRKRM5CFDRXN645RJEKEH5DLGF5XOR6ZCRBCCNTSR3H) | 46 | <0.1% | no |
| [GBO4MS…2RNK](https://stellar.expert/explorer/public/account/GBO4MS2WZLZMIL3P2NNICILVMTOAC6GVUIQK36L4I4OA5IJC435M2RNK) | 46 | <0.1% | no |
| [GB6HK3…WCK5](https://stellar.expert/explorer/public/account/GB6HK3R546TKZMHPVGQQYAF57NB66EXMHY4MRBNP3KFA4QZN4GYAWCK5) | 46 | <0.1% | no |
| [GDZUVK…2KF6](https://stellar.expert/explorer/public/account/GDZUVKR4XSAXRVWMELZ2FCO5KVVR5QM5A2SUBZ7XDO2FFCIDOBEY2KF6) | 45 | <0.1% | no |
| [GDYTC7…4EKR](https://stellar.expert/explorer/public/account/GDYTC7F7J4BHU2ZUGRY76BXRWXB3R5XOWZWSDK7YXTNQT3HXYQ7N4EKR) | 45 | <0.1% | no |

## Contract functions

| Function | Calls | Failed | Failure rate |
| --- | --- | --- | --- |
| `plant` | 75,347 | 101 | 0.1% |
| `work` | 59,413 | 1,917 | 3.2% |
| `harvest` | 186 | 6 | 3.2% |

## Ecosystem position

| Measure | Value |
| --- | --- |
| Rank by active accounts | #1 of 144 contracts |
| Percentile | 100 |
| Median failure rate of peer contracts | 0.9% |

## Coverage & methodology

| Measure | Value |
| --- | --- |
| Ledger range | 65,333,687 – 65,335,854 |
| Ledgers collected | 1,447 |
| Expected ledgers in period | 109,964 |
| Completeness | 66.7% |
| Time covered | 3 hours of 7 days |
| Collection started | 2026-11-06 |

- Source: every Stellar ledger read from Horizon by BlocRA's collector and stored with its transactions and operations.
- Days are UTC calendar days; the latest day may be partial.
- A call is one invoke_host_function operation targeting the contract; the account is the operation's source. Failed calls (from failed transactions) are included in calls and counted in failed.
- Automated (bot-like) accounts made at least 1000 calls on a single day.
- New accounts were first seen during the period in all data BlocRA has collected; with less history than the period, they are marked unreliable.
- Ecosystem rank compares active accounts with every contract (or asset) active in the same period; the failure-rate median uses peers with at least 10 active accounts.

## Verification

This file is verifiable: its sha256 hash can be recorded in BlocRA's report registry on Stellar. Upload this exact file at BlocRA → Verify Report (/verify-report) to check that it was published and has not been modified.
