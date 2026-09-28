# PAXGUSD ORB - live forward-test summary
Last updated: 2026-09-26 15:05:03 UTC
**Walk-forward validated on PAXGUSD's own 7+ month history (70/30 train/test split): trend-following breakout entry with a chandelier trailing stop, no fixed target, no time/trade-count cap. Delta Exchange's estimated round-trip fee is deducted from every trade at close (not a toggle) - train +30.3% CAGR, test +29.0% CAGR, both net of fees. Paper trading only, no real money involved. Checked on a schedule (see workflow) - notification lag applies.**
## Early-warning indicator accuracy
- Alerts fired: 48
- Resolved so far: 48 (followed by real breakout: 22, not followed: 26)
- Follow-through rate: 45.8%

## Trades (paper)
- Total: 68  |  Wins: 29  |  Losses: 39
- Win rate: 42.6%
- Total R: 25.74  |  Avg R/trade: 0.378
- Trades WITH a prior alert: 20, win rate 45.0%
- Trades WITHOUT a prior alert: 48, win rate 41.7%

## Simulated account balances (1% risk per trade, compounding)
| Starting balance | Current balance | Return | Max drawdown | Trades | Win rate |
|---|---|---|---|---|---|
| $100 | $118.72 | +18.72% | -7.78% | 68 | 42.6% |
| $1,000 | $1,187.17 | +18.72% | -7.78% | 68 | 42.6% |
| $10,000 | $11,871.68 | +18.72% | -7.78% | 68 | 42.6% |
