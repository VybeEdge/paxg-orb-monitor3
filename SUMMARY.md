# PAXGUSD ORB - live forward-test summary
Last updated: 2026-11-25 23:48:40 UTC
**Walk-forward validated on PAXGUSD's own 7+ month history (70/30 train/test split): trend-following breakout entry with a chandelier trailing stop, no fixed target, no time/trade-count cap. Delta Exchange's estimated round-trip fee is deducted from every trade at close (not a toggle) - train +30.3% CAGR, test +29.0% CAGR, both net of fees. Paper trading only, no real money involved. Checked on a schedule (see workflow) - notification lag applies.**
## Early-warning indicator accuracy
- Alerts fired: 4
- Resolved so far: 4 (followed by real breakout: 2, not followed: 2)
- Follow-through rate: 50.0%

## Trades (paper)
- Total: 21  |  Wins: 9  |  Losses: 12
- Win rate: 42.9%
- Total R: 12.90  |  Avg R/trade: 0.614
- Trades WITH a prior alert: 1, win rate 0.0%
- Trades WITHOUT a prior alert: 20, win rate 45.0%

## Simulated account balances (1% risk per trade, compounding)
| Starting balance | Current balance | Return | Max drawdown | Trades | Win rate |
|---|---|---|---|---|---|
| $100 | $109.18 | +9.18% | -4.34% | 21 | 42.9% |
| $1,000 | $1,091.78 | +9.18% | -4.34% | 21 | 42.9% |
| $10,000 | $10,917.79 | +9.18% | -4.34% | 21 | 42.9% |
