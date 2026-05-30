# Smart EGX Smart Money Core v1.0

**Status:** Experimental  
**Category:** Smart Money / Market Structure  
**Platform:** TradingView Pine Script v6

## Purpose

Smart EGX Smart Money Core is a lightweight experimental indicator for mapping market-structure events such as BOS, liquidity sweeps, trap candles, and volume spikes.

## Core Features

- Confirmed pivot-based market structure.
- Break of Structure alerts.
- Liquidity sweep detection.
- Bull trap and bear trap detection.
- Volume spike detection.
- Compact dashboard.
- Managed labels with a configurable maximum label count.

## Improvements in This Version

- Adds `na` protection before BOS calculations.
- Prevents repeated BOS label spam while price remains beyond the same level.
- Uses an internal label array to delete older labels after the configured limit.
- Adds structured alert conditions.
- Keeps the script classified as Experimental because the smart-money definitions are intentionally lightweight.

## Suggested Use

Use this script as a context helper, not a mechanical entry/exit strategy. The best signals are usually those that align with trend, volume, support/resistance, and higher timeframe direction.

## Caution

Liquidity sweeps and traps are simplified definitions. They should be reviewed visually before being used in any trading workflow.
