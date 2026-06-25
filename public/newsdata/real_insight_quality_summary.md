# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.15789473684210525`
- Multi-angle parents: `4`
- Weak parents: `1`
- Story count: `661`
- Source groups: `9`
- Content hash: `4a8b2a324409fd27`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | StartupTN CEO Sivarajah Ramanathan resigns | 2 | base_report, investigative_detail | NO | 0.6756467197849984 |
| 2 | Pakistani man held French woman, children captive for 12 years; child's escape leads to rescue | 2 | investigative_detail, base_report | NO | 0.6741467197849984 |
| 3 | World leaders offers solidarity and aid as country reels from quakes | 2 | official_response, fact_update | NO | 0.62551 |
| 4 | Ryanair says it will reluctantly not charge parents to sit next to children | 2 | base_report, investigative_detail | NO | 0.6112599999999999 |
| 5 | PM Modi | 2 | official_response | NO | 0.6945633864516649 |
| 6 | Rupee cushioned by central bank hand even as dollar strength dents Asia FX | 2 | market_reaction | NO | 0.6642467197849984 |
| 7 | Rupee ends a tad higher as oil slide, foreign inflows lift sentiment | 2 | market_reaction | NO | 0.6272599999999999 |
| 8 | Amazon CEO meets PM Modi; announces plans to invest additional $13 billion in India on cloud, AI | 2 | fact_update | NO | 0.6034766666666667 |
| 9 | IAEA chief says Iran inspections will go ahead, working on modalities | 2 | official_response | NO | 0.60076 |
| 10 | HDFC Mutual Fund buys additional 10 lakh shares of Global Health for Rs 130 crore | 1 | fact_update | YES | 0.7226911614783158 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.158`
- Multi-angle parents: `4`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.4` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.158` / `<= 0.55`
- Multi-angle parent count: `4` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.1` / `<= 0.5`
