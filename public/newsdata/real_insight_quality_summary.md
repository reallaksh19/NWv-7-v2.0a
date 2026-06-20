# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.8`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.2857142857142857`
- Multi-angle parents: `8`
- Weak parents: `0`
- Story count: `562`
- Source groups: `10`
- Content hash: `6033fb7a60f8fde7`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Reliance unveils India's biggest IPO plan as Jio Platforms files DRHP | 2 | fact_update, market_reaction | NO | 0.68321 |
| 2 | RTC buses available for 73,000 NEET students | 2 | fact_update, base_report | NO | 0.6747467197849983 |
| 3 | BEST employees go on indefinite strike; public bus services hit in Mumbai | 2 | reaction_public, regional_followup | NO | 0.6732467197849983 |
| 4 | Cycles distributed on Rahul Gandhi’s birthday in Sangareddy | 2 | official_response, base_report | NO | 0.6709967197849983 |
| 5 | Kerala Revised Budget 2026-27 LIVE: V.D. Satheesan's Budget pledges 'New Kerala' with inclusive growth, sustainable development | 2 | correction, official_response | NO | 0.6604967197849982 |
| 6 | Supreme Court dismisses plea seeking CBI probe into alleged TVK horse-trading | 2 | investigative_detail, official_response | NO | 0.6513967197849984 |
| 7 | Iran-US peace deal under threat? Israel launches strikes at Lebanon despite ceasefire, killing 5 | 2 | official_response, fact_update | NO | 0.6212600000000001 |
| 8 | Modi ‘tough cookie’, ‘great leader’ who has been in power for over 12 years, says Trump | 2 | base_report, official_response | NO | 0.59101 |
| 9 | Who is Andy Burnham? The 'King of the North' who could replace Keir Starmer as UK PM | 3 | base_report | NO | 0.6627477209716007 |
| 10 | Monsoon tracker LIVE / Heavy rain expected in 10 districts of Tamil Nadu | 2 | regional_followup | NO | 0.6324100000000001 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `76`
- Parents: `10`
- Average angles: `1.8`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.7`
- Base report share: `0.286`
- Multi-angle parents: `8`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.8` / `>= 1.4`
- Average evolution role count: `1.7` / `>= 1.6`
- Base report share: `0.286` / `<= 0.55`
- Multi-angle parent count: `8` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
