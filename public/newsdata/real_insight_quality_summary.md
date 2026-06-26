# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.8`
- Base report share: `0.13636363636363635`
- Multi-angle parents: `5`
- Weak parents: `0`
- Story count: `568`
- Source groups: `9`
- Content hash: `1fdf5617a52a8a50`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | What's a 'doublet' earthquake? Science behind Venezuela’s strongest quake in over a century | 2 | official_response, base_report | NO | 0.6814967197849984 |
| 2 | Japan PM to visit India next week | 2 | fact_update, official_response | NO | 0.6452600000000001 |
| 3 | Israel and Lebanon sign framework agreement after US-brokered talks | 2 | base_report, official_response | NO | 0.5752600000000001 |
| 4 | Small aircraft crashes into Beijing's tallest skyscraper | 2 | base_report, official_response | NO | 0.5724232802150018 |
| 5 | Trump adviser-turned-critic John Bolton pleads guilty to mishandling classified documents | 2 | regional_followup, official_response | NO | 0.5392732802150018 |
| 6 | Venezuela health minister says around 235 people dead, 4,300 injured in catastrophic earthquakes | 3 | fact_update | NO | 0.6479573212916498 |
| 7 | US weekly jobless claims drop more than expected | 2 | market_reaction | NO | 0.6814967197849984 |
| 8 | UN agency pauses evacuation of ships through Strait of Hormuz after attack on vessel | 2 | official_response | NO | 0.6792467197849983 |
| 9 | Death toll in Kolkata warehouse collapse rises to 15 | 3 | fact_update | NO | 0.6535487346782661 |
| 10 | India says 'very close' to trade deal with US - Reuters | 2 | official_response | NO | 0.5678433333333333 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.5`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.8`
- Base report share: `0.136`
- Multi-angle parents: `5`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.5` / `>= 1.4`
- Average evolution role count: `1.8` / `>= 1.6`
- Base report share: `0.136` / `<= 0.55`
- Multi-angle parent count: `5` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
