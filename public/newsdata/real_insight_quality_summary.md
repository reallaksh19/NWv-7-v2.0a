# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.5`
- Base report share: `0.058823529411764705`
- Multi-angle parents: `3`
- Weak parents: `3`
- Story count: `611`
- Source groups: `9`
- Content hash: `a4c0960e9a6c7951`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | World leaders offers solidarity and aid as country reels from quakes | 2 | official_response, fact_update | NO | 0.62551 |
| 2 | Ryanair says it will reluctantly not charge parents to sit next to children | 2 | base_report, investigative_detail | NO | 0.6112599999999999 |
| 3 | On the Taratala warehouse collapse in Kolkata | 2 | fact_update, regional_followup | NO | 0.5845100000000001 |
| 4 | PM Modi | 2 | official_response | NO | 0.6945633864516649 |
| 5 | Rupee ends a tad higher as oil slide, foreign inflows lift sentiment | 2 | market_reaction | NO | 0.6272599999999999 |
| 6 | Amazon CEO meets PM Modi; announces plans to invest additional $13 billion in India on cloud, AI | 2 | fact_update | NO | 0.6034766666666667 |
| 7 | IAEA chief says Iran inspections will go ahead, working on modalities | 2 | official_response | NO | 0.60076 |
| 8 | HDFC Mutual Fund buys additional 10 lakh shares of Global Health for Rs 130 crore | 1 | fact_update | YES | 0.7226911614783158 |
| 9 | Housing sales rise 19% in Apr-Jun across 9 cities despite global uncertainties | 1 | fact_update | YES | 0.7226911614783158 |
| 10 | Madhusudan Kela-backed fund buys stake in IPO-bound Steamhouse India for Rs 40 crore | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `4`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.5`
- Base report share: `0.059`
- Multi-angle parents: `3`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.3`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.6`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.059` / `<= 0.55`
- Multi-angle parent count: `3` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.3` / `<= 0.5`
