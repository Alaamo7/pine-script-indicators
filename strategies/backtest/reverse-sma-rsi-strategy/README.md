# Reverse SMA+RSI Strategy v1.0

**Status:** Backtest / Long Only  
**Category:** Strategy / Reverse Scalping / EGX Backtest  
**Platform:** TradingView Pine Script v6

## Purpose

Reverse SMA+RSI Strategy is an EGX-friendly long-only backtest strategy based on SMA 9/21 crossovers and recent RSI extremes.

## Why Long Only?

The old prototype used both long and short entries. This cleaned version is long-only because short selling is not a practical default assumption for most EGX retail backtesting workflows.

Bearish or overbought conditions close existing long positions instead of opening short positions.

## Core Features

- SMA 9 / SMA 21 crossover logic by default.
- RSI oversold lookback for long entries.
- RSI overbought / SMA weakness exit logic.
- Optional ATR stop loss and take profit.
- Dashboard showing trend, RSI, score, and position state.
- Alerts for long entry and exit.

## Default Logic

### Long Entry

A long entry is triggered when:

- Fast SMA crosses above Slow SMA.
- RSI was oversold within the configured recent lookback window.

### Exit

The strategy exits when:

- Fast SMA crosses below Slow SMA, or
- RSI was overbought within the configured recent lookback window.

If ATR risk management is enabled, the strategy also places an ATR-based stop and target.

## Caution

This is a research/backtest strategy, not a live trading recommendation. Validate across different EGX symbols, sessions, and timeframes before using the logic in any workflow.
