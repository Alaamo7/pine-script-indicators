# EGX Pine Script Technical Analysis Toolkit

A structured TradingView/Pine Script repository focused on EGX technical-analysis tools, strategy prototypes, testing evidence, documentation, and long-term maintainability.

This project covers trend analysis, momentum, liquidity, smart-money concepts, trap detection, price matrices, risk dashboards, and long-only backtesting workflows.

[![Portfolio quality](https://github.com/Alaamo7/pine-script-indicators/actions/workflows/portfolio-quality.yml/badge.svg)](https://github.com/Alaamo7/pine-script-indicators/actions/workflows/portfolio-quality.yml)

## Verified TradingView Validation Snapshot

A full validation run was completed on **2026-08-22** against the archived TradingView export.

| Validation item | Result |
|---|---:|
| Pine scripts tested individually | **120** |
| Loaded and rendered successfully after repair and re-test | **120** |
| Original compilation errors repaired and re-tested | **5 / 5** |
| Strategies tested | **7** |
| Strategy Tester evidence captured | **7 / 7** |

Testing was performed individually on `EGX:RMDA`, clearing the chart between tests. Each tested `.pine` file has adjacent validation evidence, including a `TEST-REPORT.md` and TradingView screenshot(s).

**Full validation evidence:** [`tradingview-export/2026-08-21/test-results/2026-08-22/`](tradingview-export/2026-08-21/test-results/2026-08-22/)

**Engineering case study:** [`docs/case-studies/2026-08-22-tradingview-validation.md`](docs/case-studies/2026-08-22-tradingview-validation.md)

> A successful compile and chart render confirm technical compatibility for the tested setup; they do not prove trading profitability or future performance.

## Portfolio Positioning

This repository demonstrates the ability to design, organize, test, document, and maintain technical-analysis tools for:

- TradingView indicator development.
- EGX-focused technical-analysis workflows.
- Brokerage or fintech technical-research tooling prototypes.
- Backtesting and validation workflows.
- AI-ready technical-analysis reporting and automation pipelines.

The current Pine Script layer is primarily rule-based. AI-assisted reporting and automation are documented as a future roadmap, not as a current machine-learning claim.

## Curated Toolkit Summary

The maintained toolkit is separated from the larger archival TradingView export so experimental, legacy, and portfolio-ready work are not presented as equivalent.

| Type | Count | Notes |
|---|---:|---|
| Active / Beta indicators | 9 | Usable for chart review and further testing. |
| Experimental indicators | 3 | Research-oriented tools requiring continued validation. |
| Backtest strategies | 2 | EGX-friendly long-only strategy prototypes. |
| Legacy / Archive scripts | 3 | Preserved for reference, not primary production use. |
| Archived TradingView scripts | 120 | Individually tested; 120 / 120 passed loading/render checks after five original compile errors were repaired and re-tested. |

See the maintained toolkit index: [`docs/scripts-index.md`](docs/scripts-index.md)

See the archived TradingView export: [`tradingview-export/2026-08-21/`](tradingview-export/2026-08-21/)

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
| `docs/` | Documentation, script index, roadmap, disclaimers, case studies, and knowledge base. |
| `tradingview-export/` | Source-preserving TradingView archive plus validation evidence. |

## Quality Principles

The repository cleanup and maintenance process focuses on:

- Evidence-backed TradingView testing.
- Small, reviewable pull requests.
- Clear script status labels: Beta, Experimental, Legacy, Incomplete.
- Keeping archival source separate from curated portfolio work.
- Documenting scripts and known limitations.
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

Read more: [`docs/AI-ROADMAP.md`](docs/AI-ROADMAP.md)

## Case Studies

### TradingView validation of 120 Pine Scripts

A documented QA case study covering the **120-script** TradingView validation run, including methodology, results, evidence structure, engineering decisions, limitations, and next steps.

[`Read the validation case study →`](docs/case-studies/2026-08-22-tradingview-validation.md)

### Verified strategy case studies

- [`Ultimate Scalping Pro v2.6`](docs/case-studies/ultimate-scalping-pro-v2-6.md) — positive historical result with documented assumptions and limitations.
- [`Integrated Swing Strategy`](docs/case-studies/integrated-swing-strategy.md) — negative historical result documented transparently with engineering lessons.

### Future market-behavior case studies

A reusable template is available for future chart-review and signal-outcome studies where sufficient evidence exists:

[`docs/case-studies/CASE-STUDY-TEMPLATE.md`](docs/case-studies/CASE-STUDY-TEMPLATE.md)

Potential candidates include:

- Smart EGX Liquidity S/R Dashboard on EGX30 daily.
- MM Trap Pro on a 15-minute EGX stock chart.
- EGX Pro Price Matrix on a swing-trading setup.
- Reverse SMA+RSI Strategy backtest on selected EGX symbols.

## License

Source is published for portfolio viewing and education. Redistribution, resale, modification, or commercial use requires written permission; see [`LICENSE`](LICENSE).

## Important Disclaimer

This repository is for education, research, software demonstration, and technical portfolio purposes only. It does not provide financial advice, investment recommendations, brokerage advice, or guaranteed trading signals.

Read the full disclaimer: [`docs/DISCLAIMER.md`](docs/DISCLAIMER.md)

## Author

Developed and maintained by **Alaa Hamza** as a Pine Script and EGX technical-analysis tools portfolio.
