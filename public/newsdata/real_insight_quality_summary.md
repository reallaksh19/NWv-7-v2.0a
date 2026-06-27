# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.8`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.8`
- Base report share: `0.23809523809523808`
- Multi-angle parents: `7`
- Weak parents: `0`
- Story count: `540`
- Source groups: `9`
- Content hash: `c6cd871ccf3230ab`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Iran Guards say targeted U.S. sites in response to strikes: state TV | 3 | base_report, market_reaction, official_response | NO | 0.6132939846283528 |
| 2 | Swiss glaciers shrink as climate crisis fuels extreme heat across Europe | 2 | base_report, expert_analysis | NO | 0.6725800531183317 |
| 3 | What's a 'doublet' earthquake? Science behind Venezuela’s strongest quake in over a century | 2 | official_response, base_report | NO | 0.6814967197849984 |
| 4 | Sebi rejects Anil Ambani's Reliance Infra settlement application | 2 | official_response, investigative_detail | NO | 0.6583266666666667 |
| 5 | Israel and Lebanon sign framework agreement after US-brokered talks | 2 | base_report, official_response | NO | 0.5952599999999999 |
| 6 | Trump adviser-turned-critic John Bolton pleads guilty to mishandling classified documents | 2 | regional_followup, official_response | NO | 0.5952599999999999 |
| 7 | India says it discussed pathways to interim trade deal with US - Reuters | 2 | base_report, official_response | NO | 0.5623433333333332 |
| 8 | UN agency pauses evacuation of ships through Strait of Hormuz after attack on vessel | 2 | official_response | NO | 0.6792467197849983 |
| 9 | Venezuela health minister says around 235 people dead, 4,300 injured in catastrophic earthquakes | 2 | fact_update | NO | 0.6684967197849983 |
| 10 | Death toll in Kolkata warehouse collapse rises to 15 | 2 | fact_update | NO | 0.6604967197849982 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.8`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.8`
- Base report share: `0.238`
- Multi-angle parents: `7`
- Top parent angles: `3`
- Top parent children: `3`

### Failed gates

- **Average temporal tier count** — actual `1.6`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.8` / `>= 1.4`
- Average evolution role count: `1.8` / `>= 1.6`
- Base report share: `0.238` / `<= 0.55`
- Multi-angle parent count: `7` / `>= 1`
- Top parent angle count: `3` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
