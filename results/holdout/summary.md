# 2026 holdout of the locked rule (confirmation entry, 2R, net R)

Sessions 2026-01-02 - 2026-10-02; good side touches with book features: 3911 real, 3323 shifted (of 3911 real in the event study).

| set | real | shifted |
|---|---|---|
| all good side | n=2762 29% **+0.00**±0.05 | n=2330 27% **-0.05**±0.05 |
| confluence >= 3 | n=1525 30% **+0.07**±0.07 | n=1103 27% **-0.05**±0.08 |
| locked rule | n=907 33% **+0.11**±0.09 | n=634 29% **-0.03**±0.11 |

Verdict: **strong pass** (real +0.115 ± 0.091, shifted -0.033).

Locked rule, real, per month:

| month | n | mean R | sum R |
|---|---|---|---|
| 2026-01 | 91 | -0.08 | -6.9 |
| 2026-02 | 85 | +0.03 | +2.5 |
| 2026-03 | 120 | +0.11 | +12.9 |
| 2026-04 | 88 | +0.16 | +14.4 |
| 2026-05 | 85 | +0.30 | +25.2 |
| 2026-06 | 120 | +0.16 | +18.6 |
| 2026-07 | 152 | +0.13 | +20.2 |
| 2026-08 | 73 | -0.13 | -9.8 |
| 2026-09 | 79 | +0.22 | +17.3 |
| 2026-10 | 14 | +0.69 | +9.7 |

## Descriptive checks after the verdict (not part of the locked criteria)

- One trade per distinct touch (same session, minute and side; confluent zones give the same touch several times):
  real 862 trades +0.107 ± 0.106 R with a session-clustered 95% interval, shifted 609 trades -0.037 ± 0.125.
  Same counting on the development years: 2024 real +0.019 ± 0.103 (shifted -0.105), 2025 real +0.104 ± 0.091
  (shifted -0.021).
- 151 sessions with a trade, ~6 trades per session (max 21); trades can overlap in time, a one position at a time
  simulation is still to be done. First trade of the session only: n=151, -0.01 R.
- Outcomes: 301 target (2R), 523 stop, 83 time exit. Total +103.9 R, max drawdown 24.0 R, median risk 9.7 points.
- Long 489 trades +0.01 R, short 418 trades +0.24 R.
