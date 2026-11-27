# PAXGUSD ORB - live forward-test summary
Last updated: 2026-11-27 08:11:38 UTC
**Walk-forward validated on PAXGUSD's own 7+ month history (70/30 train/test split): trend-following breakout entry with a chandelier trailing stop, no fixed target, no time/trade-count cap. Delta Exchange's estimated round-trip fee is deducted from every trade at close (not a toggle) - train +30.3% CAGR, test +29.0% CAGR, both net of fees. Paper trading only, no real money involved. Checked on a schedule (see workflow) - notification lag applies.**
## Early-warning indicator accuracy
- Alerts fired: 4
- Resolved so far: 4 (followed by real breakout: 2, not followed: 2)
- Follow-through rate: 50.0%

## Trades (paper)
- Total: 22  |  Wins: 9  |  Losses: 13
- Win rate: 40.9%
- Total R: 11.90  |  Avg R/trade: 0.541
- Trades WITH a prior alert: 2, win rate 0.0%
- Trades WITHOUT a prior alert: 20, win rate 45.0%

## Simulated account balances (1% risk per trade, compounding)
| Starting balance | Current balance | Return | Max drawdown | Trades | Win rate |
|---|---|---|---|---|---|
| $100 | $108.01 | +8.01% | -4.34% | 22 | 40.9% |
| $1,000 | $1,080.07 | +8.01% | -4.34% | 22 | 40.9% |
| $10,000 | $10,800.72 | +8.01% | -4.34% | 22 | 40.9% |
