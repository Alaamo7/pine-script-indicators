# Expert EGX Analyst Pro v5.0

**Status:** Experimental  
**Category:** Experimental / Multi-Module EGX Indicator  
**Platform:** TradingView Pine Script v6

## Purpose

Expert EGX Analyst Pro v5.0 is a combined EGX technical-analysis helper that brings together trend, momentum, market structure, liquidity levels, FVG detection, order-block labels, volume context, and a compact dashboard.

## Core Features

- EMA trend stack: fast, base, mid, and institutional EMAs.
- VWAP overlay.
- RSI and ADX readings.
- Confirmed pivot-based market structure.
- Break of Structure labels and alerts.
- Liquidity lines from confirmed pivots.
- FVG zones with minimum size filtering.
- Simplified order-block labels.
- Stop-hunt markers.
- Volume spike detection.
- Daily higher-timeframe bias.
- Managed object cleanup for labels, lines, and boxes.

## Improvements in This Version

- Adds object management arrays for labels, lines, and boxes.
- Adds configurable maximum counts for visual objects.
- Adds `na` protection for BOS and higher-timeframe calculations.
- Uses `barmerge.lookahead_off` in higher-timeframe requests.
- Adds a minimum FVG size filter to reduce visual noise.
- Keeps this version as Experimental because several smart-money definitions are simplified.

## Suggested Use

Use this script as a research and confluence dashboard. It is not a mechanical buy/sell system. Signals should be validated against market context, liquidity zones, support/resistance, and higher-timeframe direction.

## Caution

The script contains simplified definitions for order blocks, stop hunts, and FVGs. It should be visually reviewed on historical charts before use in any real trading decision workflow.
