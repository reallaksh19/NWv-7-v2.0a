# Real Insight Snapshot Quality

- Status: **PASS**
- Reason: -
- Grade: `D`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.6`
- Base report share: `0.3333333333333333`
- Multi-angle parents: `4`
- Weak parents: `2`
- Story count: `587`
- Source groups: `10`
- Content hash: `ec446dd6f7a0118e`

## Top parents

| # | Headline | Children | Angles | Weak | Score |
|---:|---|---:|---|---|---:|
| 1 | Price of commercial LPG, 5-kg FTL and domestic ATF reduced as conflict pressures ease | 2 | base_report, fact_update | NO | 0.6874967197849983 |
| 2 | Three held for bid to bribe TVK MLA to vote against Speaker in no-confidence motion | 2 | base_report, investigative_detail | NO | 0.6814967197849984 |
| 3 | ATF price cut by ₹5/litre to ₹110 on softer global oil prices | 2 | fact_update, official_response | NO | 0.6714967197849984 |
| 4 | Seven killed as boulder collapses at stone quarry on outskirts of Bengaluru, death toll likely to rise | 2 | regional_followup, fact_update | NO | 0.60551 |
| 5 | TVS extends lead as India’s electric two-wheeler registrations surge 74% in June | 2 | market_reaction | NO | 0.7535467197849983 |
| 6 | Rupee bounce fizzles as RBI intervention thins, arbitrage flows pick up | 2 | market_reaction | NO | 0.6602600000000001 |
| 7 | 'Don't want to look like America': 5 reasons why Europe is against ACs despite melting summers | 2 | base_report | NO | 0.6098300531183317 |
| 8 | Sri Lanka upgraded to upper-middle income economy by World Bank | 2 | base_report | NO | 0.5875232802150018 |
| 9 | Tamilnad Mercantile Bank shares surge 5% after strong Q1FY27 business update | 1 | market_reaction | YES | 0.7226911614783158 |
| 10 | Infosys, TCS and other IT stocks jump up to 5% on dip buying. Is the worst over? | 1 | market_reaction | YES | 0.7226911614783158 |

## Warnings

- Real snapshot still produces low Insight grade.

## Real Snapshot Ratchet Gate

- Status: **FAIL**
- Gate version: `real-insight-snapshot-ratchet-v1`
- Grade: `D`
- Score: `52`
- Parents: `10`
- Average angles: `1.4`
- Average temporal tiers: `1.6`
- Average evolution roles: `1.6`
- Base report share: `0.333`
- Multi-angle parents: `4`
- Top parent angles: `2`
- Top parent children: `2`

### Failed gates

- **Real snapshot grade floor** — actual `D`, required `A/B/C`. Fix: Do not accept D/F real snapshot output. Improve child selection, parent rerank, or data intake.
- **Average temporal tier count** — actual `1.6`, required `>= 1.8`. Fix: C+E output should cover multiple event-time tiers, not only source buckets.

### Passed gates

- Parent cluster count: `10` / `>= 3`
- Average visible angle count: `1.4` / `>= 1.4`
- Average evolution role count: `1.6` / `>= 1.6`
- Base report share: `0.333` / `<= 0.55`
- Multi-angle parent count: `4` / `>= 1`
- Top parent angle count: `2` / `>= 2`
- Top parent child depth: `2` / `>= 2`
- Weak parent ratio: `0.2` / `<= 0.5`
