# Scripts Index

This index lists the Pine Script assets currently organized in this repository.

## Active / Beta Indicators

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Trend Engine v1.0 | Trend | Beta | `indicators/trend/smart-egx-trend-engine/Smart-EGX-Trend-Engine_v1.0.pine` |
| AboSamra Pro v1.1 | Trend / Momentum / Manual S&R | Active Beta | `indicators/trend/AboSamra-Pro/AboSamra-Pro_v1.1.pine` |
| Smart Correction Signals Pro v1.0 | Momentum / Correction | Beta | `indicators/momentum/smart-correction-signals-pro/Smart-Correction-Signals-Pro_v1.0.pine` |
| Smart EGX Liquidity S/R Dashboard v0.9 | Smart Money / Structure / Liquidity | Active Beta | `indicators/smart-money/smart-egx-liquidity-sr-dashboard/Smart-EGX-Liquidity-SR-Dashboard_v0.9.pine` |
| MM Trap Pro v1.0 | Smart Money / Trap Detection | Active Beta | `indicators/smart-money/mm-trap-pro/MM-Trap-Pro_v1.0.pine` |
| EGX Smart Balance Matrix Pro v1.0 | Smart Money / Balance Matrix | Active Beta | `indicators/smart-money/egx-smart-balance-matrix-pro/EGX-Smart-Balance-Matrix-Pro_v1.0.pine` |

## Experimental Indicators

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Smart Money Core v1.0 | Smart Money / Market Structure | Experimental | `indicators/experimental/smart-egx-smart-money-core/Smart-EGX-Smart-Money-Core_v1.0.pine` |
| Expert EGX Analyst Pro v5.0 | Multi-Module EGX Indicator | Experimental | `indicators/experimental/expert-egx-analyst-pro/Expert-EGX-Analyst-Pro_v5.0.pine` |

## Backtest Strategies

| Script | Category | Status | Path |
|---|---|---|---|
| Scalping EMA+RSI Strategy v1.0 | Scalping / Backtest | Long Only | `strategies/backtest/scalping-ema-rsi-strategy/Scalping-EMA-RSI-Strategy_v1.0.pine` |
| Reverse SMA+RSI Strategy v1.0 | Reverse Scalping / Backtest | Long Only | `strategies/backtest/reverse-sma-rsi-strategy/Reverse-SMA-RSI-Strategy_v1.0.pine` |

## Legacy / Archive

| Script | Category | Status | Path |
|---|---|---|---|
| Smart EGX Institutional Suite v5.0 | Archive / Legacy | Legacy Reference | `archive/legacy/smart-egx-institutional-suite/Smart-EGX-Institutional-Suite_v5.0_Legacy-Full-Reference.pine` |
| Smart Market Behavior Pro – v6 Ultimate Clean | Archive / Broken or Test | Incomplete / Broken | `archive/broken-or-test/smart-market-behavior-pro/Smart-Market-Behavior-Pro_v6_Ultimate-Clean_INCOMPLETE.pine` |

## Needs Cleanup / Triage

No active triage items currently listed. Remaining legacy PRs should be reviewed in separate small cleanup batches.

## Status Definitions

- **Beta / Active Beta:** usable for chart review and further testing, but still subject to refinement.
- **Experimental:** research/prototype logic that should be visually validated before relying on it.
- **Long Only:** strategy behavior designed around long entries and exits, suitable for EGX-style retail backtesting assumptions.
- **Legacy Reference:** preserved for study and historical reference, not the preferred production script.
- **Incomplete / Broken:** preserved only to avoid losing submitted source, but should not be treated as working production code.

## Notes

The old large migration PRs are being split into smaller cleaned PRs to keep the repository maintainable and avoid merging diverged branches.
