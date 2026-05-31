# MM Trap Pro v1.0

**Status:** Active Beta  
**Category:** Smart Money / Trap Detection  
**Platform:** TradingView Pine Script v6

## Purpose

MM Trap Pro is a lightweight trap-candle detector built around volume expansion, candle body validation, and previous-bar reference behavior.

## Origin

This version normalizes the old compact script previously stored at:

```text
indicators/mm-trap-pro/mm-trap-pro.pine
```

The compact version was intentionally minimal and lacked clear inputs, alerts, dashboard documentation, and repository-standard naming.

## Core Features

- High-volume detection using a configurable volume moving average and multiplier.
- Minimum candle-body percentage filter.
- Bull trap and bear trap labels.
- Optional background highlighting.
- Mobile-friendly label sizing.
- Compact dashboard.
- Alert conditions for bull and bear traps.

## Logic Summary

### Bear Trap

Detected when:

- Candle closes green.
- Volume is above the configured high-volume threshold.
- Close remains below the previous high.
- Candle body is larger than the configured minimum body percentage.

### Bull Trap

Detected when:

- Candle closes red.
- Volume is above the configured high-volume threshold.
- Close remains above the previous low.
- Candle body is larger than the configured minimum body percentage.

## Caution

Trap definitions are simplified and should be visually validated against trend, support/resistance, liquidity zones, and market context.
