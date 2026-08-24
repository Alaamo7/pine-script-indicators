# Case Study: Integrated Swing Strategy

## Test context

| Field | Value |
|---|---|
| Platform | TradingView Strategy Tester |
| Symbol | EGX:RMDA |
| Timeframe | 4 hours |
| Test date | 2026-08-21 |
| Direction | Long-only research setup |

## Recorded result

| Metric | Result |
|---|---:|
| Total P&L | -7,189.45 EGP (-0.72%) |
| Maximum drawdown | 24,027.10 EGP (2.39%) |
| Profitable trades | 38.52% (47 of 122) |
| Profit factor | 0.884 |

## Interpretation

This configuration did not demonstrate an edge in the sampled market. A profit factor below 1.0 and a low win rate make the unmodified setup unsuitable for practical use. Publishing the negative result prevents compile success from being confused with trading performance and provides a concrete baseline for improvement.

## Lessons and next steps

1. Review regime filters so entries are reduced during sideways markets.
2. Inspect exit timing and the balance between average win and average loss.
3. Add realistic costs before any optimization.
4. Validate changes out of sample and across multiple EGX symbols.
5. Reject parameter combinations that improve one period but degrade broadly.

This case study is a transparent research record, not financial advice.
