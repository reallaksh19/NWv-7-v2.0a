# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.7`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.9`
- Base report share: `0.2727272727272727`
- Multi-angle parents: `7`
- Weak parents: `0`
- Story count: `498`
- Source groups: `11`
- Content hash: `02077eb3f019fe89`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Powerful earthquake hits Afghanistan, sending tremors across Pakistan, Delhi | 3 | regional_followup, official_response | NO | 0.6692477209716007 |
| 2 | Govt. to launch affordable digital health management system for small clinics across India | 2 | base_report, fact_update | NO | 0.6934967197849984 |
| 3 | Indian firm, CEO among entities sanctioned by U.S. for ‘fuelling’ civil war in Sudan | 2 | base_report, official_response | NO | 0.6814967197849984 |
| 4 | Trump likely to visit India in 2027: Rubio | 3 | base_report, official_response | NO | 0.6130795435138721 |
| 5 | India Sends Relief Material To Quake-Hit Venezuela Under 'Operation Amistad' - The Quint | 2 | base_report, official_response | NO | 0.6669967197849983 |
| 6 | Trump warns Iran ‘will no longer exist’ if U.S. decides to escalate | 2 | official_response, fact_update | NO | 0.61951 |
| 7 | Swiss glaciers shrink as climate crisis fuels extreme heat across Europe | 2 | base_report, expert_analysis | NO | 0.6285800531183316 |
| 8 | US conducts strikes on Iran after attack on cargo ship | 2 | official_response | NO | 0.6632467197849983 |
| 9 | U.S. allows limited access to Anthropic’s Mythos AI model | 2 | official_response | NO | 0.6232300531183317 |
| 10 | Trump Taps Former Trooper Lance Schroyer To Lead Immigration Agency | 2 | investigative_detail | NO | 0.5820099999999999 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.7`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.9`
- Base report share: `0.273`
- Multi-angle parents: `7`
- Top parent angles: `2`
- Top parent children: `3`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.7` / `>= 1.4`
- Average evolution role count: `1.9` / `>= 1.6`
- Base report share: `0.273` / `<= 0.55`
- Multi-angle parent count: `7` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
