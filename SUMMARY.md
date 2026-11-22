# PAXGUSD ORB - live forward-test summary
Last updated: 2026-11-22 23:52:11 UTC
**Walk-forward validated on PAXGUSD's own 7+ month history (70/30 train/test split): trend-following breakout entry with a chandelier trailing stop, no fixed target, no time/trade-count cap. Delta Exchange's estimated round-trip fee is deducted from every trade at close (not a toggle) - train +30.3% CAGR, test +29.0% CAGR, both net of fees. Paper trading only, no real money involved. Checked on a schedule (see workflow) - notification lag applies.**
## Early-warning indicator accuracy
- Alerts fired: 2
- Resolved so far: 2 (followed by real breakout: 1, not followed: 1)
- Follow-through rate: 50.0%

## Trades (paper)
- Total: 19  |  Wins: 9  |  Losses: 10
- Win rate: 47.4%
- Total R: 14.90  |  Avg R/trade: 0.784
- Trades WITH a prior alert: 1, win rate 0.0%
- Trades WITHOUT a prior alert: 18, win rate 50.0%

## Simulated account balances (1% risk per trade, compounding)
| Starting balance | Current balance | Return | Max drawdown | Trades | Win rate |
|---|---|---|---|---|---|
| $100 | $111.66 | +11.66% | -4.34% | 19 | 47.4% |
| $1,000 | $1,116.62 | +11.66% | -4.34% | 19 | 47.4% |
| $10,000 | $11,166.15 | +11.66% | -4.34% | 19 | 47.4% |
