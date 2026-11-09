# PAXGUSD ORB - live forward-test summary
Last updated: 2026-11-09 02:05:47 UTC
**Walk-forward validated on PAXGUSD's own 7+ month history (70/30 train/test split): trend-following breakout entry with a chandelier trailing stop, no fixed target, no time/trade-count cap. Delta Exchange's estimated round-trip fee is deducted from every trade at close (not a toggle) - train +30.3% CAGR, test +29.0% CAGR, both net of fees. Paper trading only, no real money involved. Checked on a schedule (see workflow) - notification lag applies.**
## Early-warning indicator accuracy
- Alerts fired: 2
- Resolved so far: 2 (followed by real breakout: 1, not followed: 1)
- Follow-through rate: 50.0%

## Trades (paper)
- Total: 14  |  Wins: 6  |  Losses: 8
- Win rate: 42.9%
- Total R: 8.31  |  Avg R/trade: 0.594
- Trades WITH a prior alert: 1, win rate 0.0%
- Trades WITHOUT a prior alert: 13, win rate 46.2%

## Simulated account balances (1% risk per trade, compounding)
| Starting balance | Current balance | Return | Max drawdown | Trades | Win rate |
|---|---|---|---|---|---|
| $100 | $105.24 | +5.24% | -4.34% | 14 | 42.9% |
| $1,000 | $1,052.44 | +5.24% | -4.34% | 14 | 42.9% |
| $10,000 | $10,524.35 | +5.24% | -4.34% | 14 | 42.9% |
