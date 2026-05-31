# EGX Pro Matrix Family

**Status:** Beta  
**Category:** Scalping / Matrix / EGX Dashboard  
**Platform:** TradingView Pine Script v6

## Purpose

The EGX Pro Matrix family contains lightweight dashboard-style indicators for EGX scalping workflows. The family focuses on pivot balance levels, higher-timeframe confirmation, position sizing, and simple price-matrix levels.

## Scripts

| Script | Purpose |
|---|---|
| `EGX-Pro-Matrix-MTF-Filter_v1.0.pine` | Pivot signals filtered by a higher-timeframe EMA trend. |
| `EGX-Pro-Matrix-Risk-Manager_v1.0.pine` | Adds capital/risk-based position sizing to the matrix concept. |

## Cleanup Notes

The old PR #4 versions used `barmerge.lookahead_on` in `request.security()`. These cleaned versions use `barmerge.lookahead_off` to avoid future-looking bias.

## Caution

These scripts are signal and dashboard helpers, not standalone trading systems. Validate signals with price action, trend, liquidity, and support/resistance context.
