# PAXGUSD ORB - live forward-test summary
Last updated: 2026-10-30 16:15:48 UTC
**Walk-forward validated on PAXGUSD's own 7+ month history (70/30 train/test split): trend-following breakout entry with a chandelier trailing stop, no fixed target, no time/trade-count cap. Delta Exchange's estimated round-trip fee is deducted from every trade at close (not a toggle) - train +30.3% CAGR, test +29.0% CAGR, both net of fees. Paper trading only, no real money involved. Checked on a schedule (see workflow) - notification lag applies.**
## Early-warning indicator accuracy
- Alerts fired: 2
- Resolved so far: 2 (followed by real breakout: 1, not followed: 1)
- Follow-through rate: 50.0%

## Trades (paper)
- Total: 9  |  Wins: 4  |  Losses: 5
- Win rate: 44.4%
- Total R: 5.70  |  Avg R/trade: 0.633
- Trades WITH a prior alert: 1, win rate 0.0%
- Trades WITHOUT a prior alert: 8, win rate 50.0%

## Simulated account balances (1% risk per trade, compounding)
| Starting balance | Current balance | Return | Max drawdown | Trades | Win rate |
|---|---|---|---|---|---|
| $100 | $103.26 | +3.26% | -4.34% | 9 | 44.4% |
| $1,000 | $1,032.64 | +3.26% | -4.34% | 9 | 44.4% |
| $10,000 | $10,326.38 | +3.26% | -4.34% | 9 | 44.4% |
