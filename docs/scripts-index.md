# Scripts Index

This document tracks the currently migrated Pine Script assets in the repository.

## Status Legend
- **Beta**: functional and maintainable enough for active use, but still not final
- **Experimental**: useful but structurally rough, prototype-like, or in need of further validation
- **Archived**: retained for lineage and historical reference only
- **Deprecated**: superseded or too basic for active use

---

## Active Indicators

| Script | Type | Category | Status | Path |
|---|---|---|---|---|
| EGX Smart Balance Matrix Pro | Indicator | Smart Money | Beta | `indicators/smart-money/egx-smart-balance-matrix-pro/EGX-Smart-Balance-Matrix-Pro_v1.0.pine` |
| MM Trap Pro | Indicator | Smart Money | Beta | `indicators/smart-money/mm-trap-pro/MM-Trap-Pro_v1.0.pine` |
| EGX Pro Matrix MTF Filter | Indicator | Scalping | Beta | `indicators/scalping/egx-pro-matrix/variants/EGX-Pro-Matrix-MTF-Filter_v1.0.pine` |
| EGX Pro Matrix Risk Manager | Indicator | Scalping | Beta | `indicators/scalping/egx-pro-matrix/variants/EGX-Pro-Matrix-Risk-Manager_v1.0.pine` |
| EGX Pro Price Matrix | Indicator | Trend | Beta | `indicators/trend/egx-pro-price-matrix/EGX-Pro-Price-Matrix_v1.0.pine` |
| Smart EGX Trend Engine | Indicator | Trend | Beta | `indicators/trend/smart-egx-trend-engine/Smart-EGX-Trend-Engine_v1.0.pine` |
| Smart Correction Signals Pro | Indicator | Momentum | Beta | `indicators/momentum/smart-correction-signals-pro/Smart-Correction-Signals-Pro_v1.0.pine` |
| AI Dynamic Liquidity Engine | Indicator | Smart Money | Experimental | `indicators/smart-money/ai-dynamic-liquidity-engine/AI-Dynamic-Liquidity-Engine_v2.0.pine` |
| Smart EGX Smart Money Core | Indicator | Experimental | Experimental | `indicators/experimental/smart-egx-smart-money-core/Smart-EGX-Smart-Money-Core_v1.0.pine` |
| Expert EGX Analyst Pro | Indicator | Experimental | Experimental | `indicators/experimental/expert-egx-analyst-pro/Expert-EGX-Analyst-Pro_v5.0.pine` |

---

## Active Strategies

| Script | Type | Category | Status | Path |
|---|---|---|---|---|
| Reverse SMA RSI Strategy | Strategy | Backtest | Beta | `strategies/backtest/reverse-sma-rsi-strategy/Reverse-SMA-RSI-Strategy_v1.0.pine` |
| Scalping EMA RSI Strategy | Strategy | Backtest | Experimental | `strategies/backtest/scalping-ema-rsi-strategy/Scalping-EMA-RSI-Strategy_v1.0.pine` |

---

## Archived / Legacy

| Script | Type | Status | Path | Notes |
|---|---|---|---|---|
| EGX Smart Trend Dashboard | Indicator | Archived | `archive/legacy/egx-smart-trend-dashboard/EGX-Smart-Trend-Dashboard_v0.9.pine` | older EGX dashboard generation |
| Smart EGX Institutional Suite | Indicator | Archived | `archive/legacy/smart-egx-institutional-suite/Smart-EGX-Institutional-Suite_v5.0.pine` | placeholder archived entry kept with lineage note |
| Smart EGX Institutional Suite Full Legacy Reference | Indicator | Archived | `archive/legacy/smart-egx-institutional-suite/Smart-EGX-Institutional-Suite_v5.0_Legacy-Full-Reference.pine` | complete historical source reference |

---

## Family Notes

### EGX Pro Matrix Family
Grouped under:
- `indicators/scalping/egx-pro-matrix/`

Members:
- EGX Pro Matrix MTF Filter
- EGX Pro Matrix Risk Manager

### EGX Legacy Lineage
Older EGX family branches currently identified:
- Smart EGX Trend Engine
- Smart EGX Smart Money Core
- Expert EGX Analyst Pro
- Smart EGX Institutional Suite
- EGX Smart Trend Dashboard

### Mainline Candidate
At the current migration stage, the strongest mainline-style analytical script in the EGX family is:
- **EGX Smart Balance Matrix Pro**

---

## Migration Notes
- Scripts were migrated in batches and may still be awaiting merge into `main`.
- Some archived or experimental scripts are preserved for lineage even if stronger successors now exist.
- Any script using claims such as non-repainting or institutional logic should be re-validated before promotion to Stable.
