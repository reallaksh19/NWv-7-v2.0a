# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `B`
- Parents: `10`
- Average angles: `2.1`
- Average temporal tiers: `1.7`
- Average evolution roles: `2.1`
- Base report share: `0.2608695652173913`
- Multi-angle parents: `10`
- Weak parents: `0`
- Story count: `568`
- Source groups: `9`
- Content hash: `899413e3f3c2adcd`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Iran Guards say targeted U.S. sites in response to strikes: state TV | 3 | base_report, market_reaction, official_response | NO | 0.6812477209716007 |
| 2 | Powerful earthquake hits Afghanistan, sending tremors across Pakistan, Delhi | 3 | regional_followup, official_response | NO | 0.6212939846283527 |
| 3 | Japan PM to visit India next week | 2 | fact_update, official_response | NO | 0.7012467197849983 |
| 4 | What's a 'doublet' earthquake? Science behind Venezuela’s strongest quake in over a century | 2 | official_response, base_report | NO | 0.6814967197849984 |
| 5 | India Sends Relief Material To Quake-Hit Venezuela Under 'Operation Amistad' - The Quint | 3 | official_response, base_report | NO | 0.6196239879583165 |
| 6 | Sebi rejects Anil Ambani's Reliance Infra settlement application | 2 | official_response, investigative_detail | NO | 0.6583266666666667 |
| 7 | Govt. to launch affordable digital health management system for small clinics across India | 2 | base_report, fact_update | NO | 0.64151 |
| 8 | Swiss glaciers shrink as climate crisis fuels extreme heat across Europe | 2 | base_report, expert_analysis | NO | 0.6285800531183316 |
| 9 | Israel and Lebanon sign framework agreement after US-brokered talks | 2 | base_report, official_response | NO | 0.5952599999999999 |
| 10 | Trump adviser-turned-critic John Bolton pleads guilty to mishandling classified documents | 2 | regional_followup, official_response | NO | 0.5952599999999999 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `B`
- Score: `76`
- Parents: `10`
- Average angles: `2.1`
- Average temporal tiers: `1.7`
- Average evolution roles: `2.1`
- Base report share: `0.261`
- Multi-angle parents: `10`
- Top parent angles: `3`
- Top parent children: `3`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `B` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `2.1` / `>= 1.4`
- Average evolution role count: `2.1` / `>= 1.6`
- Base report share: `0.261` / `<= 0.55`
- Multi-angle parent count: `10` / `>= 1`
- Top parent angle count: `3` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
