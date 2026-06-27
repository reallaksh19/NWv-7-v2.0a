# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `B`
- Parents: `10`
- Average angles: `2`
- Average temporal tiers: `1.7`
- Average evolution roles: `2.1`
- Base report share: `0.391304347826087`
- Multi-angle parents: `9`
- Weak parents: `0`
- Story count: `569`
- Source groups: `10`
- Content hash: `2e9303e9743e5df2`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Iran Guards say targeted U.S. sites in response to strikes: state TV | 3 | base_report, market_reaction, official_response | NO | 0.6812477209716007 |
| 2 | Powerful earthquake hits Afghanistan, sending tremors across Pakistan, Delhi | 3 | regional_followup, official_response | NO | 0.6212939846283527 |
| 3 | India Sends Relief Material To Quake-Hit Venezuela Under 'Operation Amistad' - The Quint | 3 | official_response, base_report | NO | 0.6196239879583165 |
| 4 | Govt. to launch affordable digital health management system for small clinics across India | 2 | base_report, fact_update | NO | 0.64151 |
| 5 | Indian firm, CEO among entities sanctioned by U.S. for ‘fuelling’ civil war in Sudan | 2 | base_report, official_response | NO | 0.62551 |
| 6 | Swiss glaciers shrink as climate crisis fuels extreme heat across Europe | 2 | base_report, expert_analysis | NO | 0.6285800531183316 |
| 7 | Israel and Lebanon sign framework agreement after US-brokered talks | 2 | base_report, official_response | NO | 0.5952599999999999 |
| 8 | Trump adviser-turned-critic John Bolton pleads guilty to mishandling classified documents | 2 | regional_followup, official_response | NO | 0.5952599999999999 |
| 9 | Trump likely to visit India in 2027: Rubio | 2 | base_report, official_response | NO | 0.5223566135483351 |
| 10 | Fragments fall after an aircraft hits Beijing’s tallest building. | 2 | base_report | NO | 0.6803967197849983 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `B`
- Score: `76`
- Parents: `10`
- Average angles: `2`
- Average temporal tiers: `1.7`
- Average evolution roles: `2.1`
- Base report share: `0.391`
- Multi-angle parents: `9`
- Top parent angles: `3`
- Top parent children: `3`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `B` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `2` / `>= 1.4`
- Average evolution role count: `2.1` / `>= 1.6`
- Base report share: `0.391` / `<= 0.55`
- Multi-angle parent count: `9` / `>= 1`
- Top parent angle count: `3` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
