# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `C`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.5`
- Base report share: `0.21052631578947367`
- Multi-angle parents: `3`
- Weak parents: `1`
- Story count: `585`
- Source groups: `10`
- Content hash: `dc9d3383ff828f51`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Price of commercial LPG, 5-kg FTL and domestic ATF reduced as conflict pressures ease | 2 | base_report, fact_update | NO | 0.6874967197849983 |
| 2 | Three held for bid to bribe TVK MLA to vote against Speaker in no-confidence motion | 2 | base_report, investigative_detail | NO | 0.60551 |
| 3 | ATF price cut by ₹5/litre to ₹110 on softer global oil prices | 2 | fact_update, official_response | NO | 0.59551 |
| 4 | TVS extends lead as India’s electric two-wheeler registrations surge 74% in June | 2 | market_reaction | NO | 0.7255600000000002 |
| 5 | Starmer's defence investment plan leaves £5 billion funding gap for Burnham | 2 | fact_update | NO | 0.680563386451665 |
| 6 | Godrej Properties acquires 47-acre land parcel in South Chennai, eyes ₹500 crore revenue | 2 | fact_update | NO | 0.6875300531183317 |
| 7 | ICEYE chooses India for sovereign SAR mission; picks Agnikul Cosmos as launch partner | 2 | regional_followup | NO | 0.6823967197849983 |
| 8 | U.S. Supreme Court upholds State laws banning transgender girls, women from school athletic teams | 2 | official_response | NO | 0.6522467197849984 |
| 9 | 'Don't want to look like America': 5 reasons why Europe is against ACs despite melting summers | 2 | base_report | NO | 0.6098300531183317 |
| 10 | Shutterstock shares crash 29% after Getty Images calls off $3.7 billion merger | 1 | fact_update | YES | 0.7226911614783158 |

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `C`
- Score: `28`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.7`
- Average evolution roles: `1.5`
- Base report share: `0.211`
- Multi-angle parents: `3`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Average visible angle count** — actual `1.3`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.7`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.

### Passed gates

- Real snapshot grade floor: `C` / `A/B/C`
- Parent cluster count: `10` / `>= 3`
- Base report share: `0.211` / `<= 0.55`
- Multi-angle parent count: `3` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.1` / `<= 0.5`
