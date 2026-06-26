# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.5`
- Base report share: `0.09523809523809523`
- Multi-angle parents: `2`
- Weak parents: `1`
- Story count: `623`
- Source groups: `9`
- Content hash: `8b103b1aafbf63ff`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | What's a 'doublet' earthquake? Science behind Venezuela’s strongest quake in over a century | 2 | official_response, base_report | NO | 0.7254967197849984 |
| 2 | Small aircraft crashes into Beijing's tallest skyscraper | 2 | base_report, official_response | NO | 0.5724232802150018 |
| 3 | Venezuela health minister says around 235 people dead, 4,300 injured in catastrophic earthquakes | 3 | fact_update | NO | 0.6479573212916498 |
| 4 | US weekly jobless claims drop more than expected | 2 | market_reaction | NO | 0.6814967197849984 |
| 5 | UN agency pauses evacuation of ships through Strait of Hormuz after attack on vessel | 2 | official_response | NO | 0.6792467197849983 |
| 6 | Death toll in Kolkata warehouse collapse rises to 15 | 3 | fact_update | NO | 0.6535487346782661 |
| 7 | Amazon CEO meets PM Modi; announces plans to invest additional $13 billion in India on cloud, AI | 2 | fact_update | NO | 0.6034766666666667 |
| 8 | India says 'very close' to trade deal with US - Reuters | 2 | official_response | NO | 0.5678433333333333 |
| 9 | U.S. Supreme Court’s ruling to end protections for Haitian, Syrian immigrants could have broader impact | 2 | official_response | NO | 0.5282732802150019 |
| 10 | Silver Consumer Electricals concludes Rs 150 cr pre-IPO secondary share sale | 1 | market_reaction | YES | 0.7226911614783158 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `28`
- Parents: `10`
- Average angles: `1.2`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.5`
- Base report share: `0.095`
- Multi-angle parents: `2`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average visible angle count** — actual `1.2`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Base report share: `0.095` / `<= 0.55`
- Multi-angle parent count: `2` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.1` / `<= 0.5`
