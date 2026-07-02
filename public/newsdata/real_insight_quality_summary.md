# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.5`
- Base report share: `0.35294117647058826`
- Multi-angle parents: `3`
- Weak parents: `3`
- Story count: `598`
- Source groups: `11`
- Content hash: `28acce0d0bf910b6`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Price of commercial LPG, 5-kg FTL and domestic ATF reduced as conflict pressures ease | 2 | base_report, fact_update | NO | 0.6874967197849983 |
| 2 | Three held for bid to bribe TVK MLA to vote against Speaker in no-confidence motion | 2 | base_report, investigative_detail | NO | 0.6814967197849984 |
| 3 | ATF price cut by ₹5/litre to ₹110 on softer global oil prices | 2 | fact_update, official_response | NO | 0.6714967197849984 |
| 4 | TVS extends lead as India’s electric two-wheeler registrations surge 74% in June | 2 | market_reaction | NO | 0.7535467197849983 |
| 5 | Rupee bounce fizzles as RBI intervention thins, arbitrage flows pick up | 2 | market_reaction | NO | 0.6602600000000001 |
| 6 | 'Don't want to look like America': 5 reasons why Europe is against ACs despite melting summers | 2 | base_report | NO | 0.6098300531183317 |
| 7 | Sri Lanka upgraded to upper-middle income economy by World Bank | 2 | base_report | NO | 0.5875232802150018 |
| 8 | Tamilnad Mercantile Bank shares surge 5% after strong Q1FY27 business update | 1 | market_reaction | YES | 0.7226911614783158 |
| 9 | Infosys, TCS and other IT stocks jump up to 5% on dip buying. Is the worst over? | 1 | market_reaction | YES | 0.7226911614783158 |
| 10 | Shutterstock shares crash 29% after Getty Images calls off $3.7 billion merger | 1 | fact_update | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `4`
- Parents: `10`
- Average angles: `1.3`
- Average temporal tiers: `1.5`
- Average evolution roles: `1.5`
- Base report share: `0.353`
- Multi-angle parents: `3`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average visible angle count** — actual `1.3`, required `>= 1.4`. Fix: Angle-diverse child selection is not strong enough on real data.
- **Average temporal tier count** — actual `1.5`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.
- **Average evolution role count** — actual `1.5`, required `>= 1.6`. Fix: C+E output should include distinct event evolution roles.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Base report share: `0.353` / `<= 0.55`
- Multi-angle parent count: `3` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.3` / `<= 0.5`
