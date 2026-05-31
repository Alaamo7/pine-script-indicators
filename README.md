# EGX Pine Script Technical Analysis Toolkit

A structured portfolio repository for TradingView Pine Script indicators and backtesting strategy prototypes focused on EGX-style technical analysis.

This project demonstrates practical Pine Script development across trend analysis, momentum, liquidity, smart-money concepts, trap detection, price matrices, risk dashboards, and long-only backtesting workflows.

## Portfolio Positioning

This repository is intended to showcase the ability to design, organize, document, and maintain technical-analysis tools for:

- TradingView indicator development.
- EGX-focused technical-analysis workflows.
- Brokerage or fintech technical-research tooling prototypes.
- AI-ready technical-analysis reporting and automation pipelines.

The current Pine Script layer is primarily rule-based. AI-assisted reporting and automation are documented as a future roadmap, not as a current machine-learning claim.

## Current Toolkit Summary

| Type | Count | Notes |
|---|---:|---|
| Active / Beta indicators | 9 | Usable for chart review and further testing. |
| Experimental indicators | 3 | Research-oriented tools requiring visual validation. |
| Backtest strategies | 2 | EGX-friendly long-only strategy prototypes. |
| Legacy / Archive scripts | 3 | Preserved for reference, not primary production use. |

See the full index:

```text
/docs/scripts-index.md
```

## Indicator Categories

| Need | Suggested Tools |
|---|---|
| Trend review | Smart EGX Trend Engine, AboSamra Pro, EGX Pro Price Matrix |
| Momentum / correction review | Smart Correction Signals Pro |
| Liquidity and smart-money context | Smart EGX Liquidity S/R Dashboard, Smart EGX Smart Money Core, AI Dynamic Liquidity Engine |
| Trap detection | MM Trap Pro |
| Pivot and matrix levels | EGX Pro Price Matrix, EGX Pro Matrix MTF Filter |
| Risk sizing | EGX Pro Matrix Risk Manager |
| Multi-module dashboard review | Expert EGX Analyst Pro, EGX Smart Balance Matrix Pro |
| Strategy research | Scalping EMA+RSI Strategy, Reverse SMA+RSI Strategy |

## Repository Structure

| Area | Purpose |
|---|---|
| `indicators/` | Active, beta, and experimental Pine indicators. |
| `strategies/` | Backtest strategies and trading logic prototypes. |
| `archive/` | Legacy, deprecated, incomplete, or reference-only scripts. |
| `docs/` | Repository documentation, script index, roadmap, disclaimers, and case-study templates. |
| `assets/` | Screenshots, diagrams, and portfolio visuals. |

## Quality Principles

The cleanup process focuses on:

- Small reviewable pull requests.
- Clear script status labels: Beta, Experimental, Legacy, Incomplete.
- Avoiding stale large PR merges.
- Documenting each script with a README where appropriate.
- Reducing object clutter with managed labels, boxes, and arrays.
- Avoiding future-looking higher-timeframe logic by using `barmerge.lookahead_off` in cleaned scripts.
- Keeping EGX retail assumptions in mind, especially long-only backtesting.

## AI-Assisted Roadmap

The repository is designed to become AI-ready through future layers:

1. Pine Script signal and dashboard layer.
2. Data export and backtest validation layer.
3. Python-based report generation.
4. Telegram/email analysis summaries.
5. AI-assisted explanation layer for structured technical-analysis reports.

Read more:

```text
/docs/AI-ROADMAP.md
```

## Case Studies

A reusable template is available for documenting real chart reviews and signal outcomes:

```text
/docs/case-studies/CASE-STUDY-TEMPLATE.md
```

Suggested case-study examples:

- Smart EGX Liquidity S/R Dashboard on EGX30 daily.
- MM Trap Pro on a 15-minute EGX stock chart.
- EGX Pro Price Matrix on a swing-trading setup.
- Reverse SMA+RSI Strategy backtest on selected EGX symbols.

## Screenshot Plan

Screenshots should be stored under:

```text
assets/screenshots/
```

Recommended naming style:

```text
assets/screenshots/smart-egx-trend-engine-egx30-daily.png
assets/screenshots/mm-trap-pro-btfh-15m.png
assets/screenshots/egx-pro-price-matrix-masr-daily.png
```

## Important Disclaimer

This repository is for education, research, and portfolio demonstration only. It does not provide financial advice, investment recommendations, brokerage advice, or guaranteed trading signals.

Read the full disclaimer:

```text
/docs/DISCLAIMER.md
```

## Author

Developed and maintained by Alaa Hamza as a Pine Script and EGX technical-analysis tools portfolio.
