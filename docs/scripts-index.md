# Scripts Index

This index lists the Pine Script assets currently organized in this repository.

## Active / Beta Indicators

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Trend Engine v1.0 | Trend | Beta | `indicators/trend/smart-egx-trend-engine/Smart-EGX-Trend-Engine_v1.0.pine` |
| AboSamra Pro v1.1 | Trend / Momentum / Manual S&R | Active Beta | `indicators/trend/AboSamra-Pro/AboSamra-Pro_v1.1.pine` |
| Smart Correction Signals Pro v1.0 | Momentum / Correction | Beta | `indicators/momentum/smart-correction-signals-pro/Smart-Correction-Signals-Pro_v1.0.pine` |
| Smart EGX Liquidity S/R Dashboard v0.9 | Smart Money / Structure / Liquidity | Active Beta | `indicators/smart-money/smart-egx-liquidity-sr-dashboard/Smart-EGX-Liquidity-SR-Dashboard_v0.9.pine` |

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

## Needs Cleanup / Triage

| Script | Current Location | Issue | Suggested Action |
|---|---|---|---|
| Smart Market Behavior Pro – v6 Ultimate Clean | Repository root | No `.pine` extension and likely incomplete variable declarations | Move to `archive/broken-or-test/` or replace with complete working version |
| MM Trap Pro Compact | `indicators/mm-trap-pro/mm-trap-pro.pine` | Compact unversioned path, minimal inputs, no README, overlaps with planned MM Trap Pro migration | Consolidate with full MM Trap Pro from old PR #3 or archive compact version |

## Status Definitions

- **Beta / Active Beta:** usable for chart review and further testing, but still subject to refinement.
- **Experimental:** research/prototype logic that should be visually validated before relying on it.
- **Long Only:** strategy behavior designed around long entries and exits, suitable for EGX-style retail backtesting assumptions.
- **Legacy Reference:** preserved for study and historical reference, not the preferred production script.

## Notes

The old large migration PRs are being split into smaller cleaned PRs to keep the repository maintainable and avoid merging diverged branches.
