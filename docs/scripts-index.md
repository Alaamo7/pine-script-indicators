# Scripts Index

This index lists the Pine Script assets currently organized in this repository after the cleaned Batch 4 migration work.

## Active / Beta Indicators

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Trend Engine v1.0 | Trend | Beta | `indicators/trend/smart-egx-trend-engine/Smart-EGX-Trend-Engine_v1.0.pine` |
| Smart Correction Signals Pro v1.0 | Momentum / Correction | Beta | `indicators/momentum/smart-correction-signals-pro/Smart-Correction-Signals-Pro_v1.0.pine` |

## Experimental Indicators

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Smart Money Core v1.0 | Smart Money / Market Structure | Experimental | `indicators/experimental/smart-egx-smart-money-core/Smart-EGX-Smart-Money-Core_v1.0.pine` |
| Expert EGX Analyst Pro v5.0 | Multi-Module EGX Indicator | Experimental | `indicators/experimental/expert-egx-analyst-pro/Expert-EGX-Analyst-Pro_v5.0.pine` |

## Backtest Strategies

| Script | Category | Status | Path |
|---|---|---|---|
| Scalping EMA+RSI Strategy v1.0 | Scalping / Backtest | Long Only | `strategies/backtest/scalping-ema-rsi-strategy/Scalping-EMA-RSI-Strategy_v1.0.pine` |

## Legacy Archive

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Institutional Suite v5.0 | Archive / Legacy | Legacy Reference | `archive/legacy/smart-egx-institutional-suite/Smart-EGX-Institutional-Suite_v5.0_Legacy-Full-Reference.pine` |

## Status Definitions

- **Beta:** usable for chart review and further testing, but still subject to refinement.
- **Experimental:** research/prototype logic that should be visually validated before relying on it.
- **Long Only:** strategy behavior designed around long entries and exits, suitable for EGX-style retail backtesting assumptions.
- **Legacy Reference:** preserved for study and historical reference, not the preferred production script.

## Notes

The old Batch 4 PR was intentionally split into smaller cleaned PRs to keep the repository maintainable and avoid merging a large diverged branch.
