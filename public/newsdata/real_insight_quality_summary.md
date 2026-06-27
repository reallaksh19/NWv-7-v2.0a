# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.7`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.9`
- Base report share: `0.2727272727272727`
- Multi-angle parents: `7`
- Weak parents: `0`
- Story count: `556`
- Source groups: `10`
- Content hash: `274ca8757b98f9a8`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Swiss glaciers shrink as climate crisis fuels extreme heat across Europe | 2 | base_report, expert_analysis | NO | 0.6725800531183317 |
| 2 | What's a 'doublet' earthquake? Science behind Venezuela’s strongest quake in over a century | 2 | official_response, base_report | NO | 0.6814967197849984 |
| 3 | US approves limited rollout of Anthropic's Mythos 5 AI model | 2 | base_report, official_response | NO | 0.6605800531183317 |
| 4 | Small aircraft crashes into Beijing's tallest skyscraper | 2 | base_report, official_response | NO | 0.6723967197849983 |
| 5 | US conducts strikes on Iran after attack on cargo ship | 3 | base_report, official_response | NO | 0.5730606512950195 |
| 6 | Israel and Lebanon sign framework agreement after US-brokered talks | 2 | base_report, official_response | NO | 0.5952599999999999 |
| 7 | Trump adviser-turned-critic John Bolton pleads guilty to mishandling classified documents | 2 | regional_followup, official_response | NO | 0.5952599999999999 |
| 8 | Venezuela health minister says around 235 people dead, 4,300 injured in catastrophic earthquakes | 3 | fact_update | NO | 0.6679143876382674 |
| 9 | US weekly jobless claims drop more than expected | 2 | market_reaction | NO | 0.6814967197849984 |
| 10 | UN agency pauses evacuation of ships through Strait of Hormuz after attack on vessel | 2 | official_response | NO | 0.6792467197849983 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.7`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.9`
- Base report share: `0.273`
- Multi-angle parents: `7`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.7` / `>= 1.4`
- Average evolution role count: `1.9` / `>= 1.6`
- Base report share: `0.273` / `<= 0.55`
- Multi-angle parent count: `7` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
