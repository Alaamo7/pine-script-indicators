# Scalping EMA+RSI Strategy v1.0

**Status:** Backtest / Long Only  
**Category:** Strategy / Backtest  
**Platform:** TradingView Pine Script v6

## Purpose

Scalping EMA+RSI Strategy v1.0 is an EGX-friendly long-only backtest strategy based on EMA crossover confirmation, RSI momentum, and optional ATR-based risk management.

## Why Long Only?

The old prototype used both long and short entries. This version is long-only by design because short selling is not a practical default assumption for most EGX retail workflows.

Instead of opening short trades, bearish conditions close existing long positions.

## Core Features

- EMA 9 / EMA 21 crossover logic by default.
- RSI confirmation for entry and weakness exit.
- Optional ATR stop loss and take profit.
- Entry and exit markers.
- Lightweight dashboard.
- Alert conditions for long entry and exit.

## Default Logic

### Long Entry

A long entry is triggered when:

- Fast EMA crosses above Slow EMA.
- RSI is above the entry threshold.

### Exit

The strategy exits when:

- Fast EMA crosses below Slow EMA, or
- RSI falls below the weakness threshold.

If ATR risk management is enabled, the strategy also places an ATR-based stop and target.

## Caution

This script is for backtesting and research only. Before using the logic in live workflows, test it across multiple EGX stocks, timeframes, and market conditions.
