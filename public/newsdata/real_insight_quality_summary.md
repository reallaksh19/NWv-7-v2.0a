# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `B`
- Parents: `10`
- Average angles: `2.1`
- Average temporal tiers: `1.7`
- Average evolution roles: `2.1`
- Base report share: `0.3181818181818182`
- Multi-angle parents: `10`
- Weak parents: `0`
- Story count: `605`
- Source groups: `11`
- Content hash: `849c90e1738f4e52`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Bangladesh protests India 'questioning' PM's adviser at Delhi airport - Reuters | 3 | official_response, investigative_detail, reaction_public | NO | 0.6418462101805388 |
| 2 | Hormuz Strait, Nuclear Program, Lebanon: Key Terms Of US-Iran Peace Deal | 2 | official_response, base_report | NO | 0.728163386451665 |
| 3 | Oil prices slide after US-Iran deal announced | 2 | base_report, official_response | NO | 0.728163386451665 |
| 4 | Elon Musk says SpaceX could bring $1 trillion in revenue by 2030 | 2 | fact_update, official_response | NO | 0.6934967197849984 |
| 5 | After criticism, NCERT to restore original 'Dancing Girl' image in school textbook | 2 | fact_update, reaction_public | NO | 0.6874967197849983 |
| 6 | Trump says deal to end war with Iran already signed and details to be released 'pretty soon' | 2 | base_report, official_response | NO | 0.6601766666666666 |
| 7 | Indian envoy meets 20 rescued crew members of MT Jalveer | 2 | base_report, official_response | NO | 0.6714967197849984 |
| 8 | Smriti Mandhana only Indian among TIME magazine's 100 most influential sportspersons | 3 | base_report, fact_update | NO | 0.5696702516150686 |
| 9 | Stanford students boo Sundar Pichai, walk out during Google CEO's commencement speech | 2 | official_response, base_report | NO | 0.6132300531183317 |
| 10 | G7 Summit Day 1 LIVE: G7 leaders open summit talks on Ukraine and West Asia as Zelenskyy joins in France | 2 | base_report, fact_update | NO | 0.5852732802150018 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `B`
- Score: `76`
- Parents: `10`
- Average angles: `2.1`
- Average temporal tiers: `1.7`
- Average evolution roles: `2.1`
- Base report share: `0.318`
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
- Base report share: `0.318` / `<= 0.55`
- Multi-angle parent count: `10` / `>= 1`
- Top parent angle count: `3` / `>= 2`
- Top parent child depth: `3` / `>= 2`
- Weak parent ratio: `0` / `<= 0.5`
