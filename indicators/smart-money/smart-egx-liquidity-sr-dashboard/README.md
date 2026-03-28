# Smart EGX Liquidity SR Dashboard

## Summary
A multi-component Pine Script indicator for dynamic support and resistance visualization, liquidity sweep detection, structure breaks (BOS/CHOCH), trap hints, and a compact dashboard for quick chart review.

## Script Info
- **Type:** Indicator
- **Category:** Smart Money / Market Structure
- **Status:** Beta
- **Version:** v0.9
- **Pine Version:** v6
- **File:** `Smart-EGX-Liquidity-SR-Dashboard_v0.9.pine`

## Purpose
This script combines several chart-reading components into one overlay indicator:
- Supply and demand zone plotting
- BOS / CHOCH structure markers
- Liquidity sweep detection
- Basic trap hints
- Optional EGX EMA pack and VWAP
- Compact dashboard for nearest support/resistance and bias

## Main Logic
1. Detect pivot highs and lows.
2. Build supply and demand zones using ATR-based thickness.
3. Extend zones forward and mark breaks.
4. Track BOS and CHOCH using the latest pivots.
5. Detect liquidity sweeps using wick/body behavior and lookback highs/lows.
6. Build a simple market score from trend, momentum, volume, and liquidity context.
7. Show a dashboard with nearest resistance, support, last break, bias, and active levels.

## Main Inputs
- Pivot Length
- Zone Thickness ATR Multiplier
- Minimum Distance Between Zones
- Zone Extend Bars
- Max Active Zones
- Liquidity Lookback
- Minimum Wick/Body Ratio
- RSI Length
- Volume MA Length
- Volume Spike Multiplier
- Visibility toggles for zones, breaks, liquidity, dashboard, and EGX pack

## Outputs / Chart Behavior
- Supply and demand boxes on chart
- BOS / CHOCH markers
- Liquidity sweep dots
- Optional EMA 13 / 30 / 72 / 144 / 288 and VWAP overlay
- Dashboard showing:
  - Resistance
  - Support
  - Last Break
  - Bias
  - Active Levels

## Recommended Timeframes
Best suited for:
- 15m
- 1h
- 4h
- 1D

Lower timeframes may generate more noise.

## Current Limitations
- Broken zones remain tracked instead of being reclassified or removed
- No retest / mitigation logic for zones
- No zone strength ranking
- Trap logic is simplified
- Bias score is heuristic, not weighted rigorously
- Dashboard last-break state is event-driven and may not always reflect the most meaningful structural event
- Visual load can become high on busy charts

## Refactor Notes
Recommended next improvements:
- Separate zone engine from structure engine
- Separate dashboard state from signal generation
- Add zone freshness / mitigation state
- Add stronger filtering for zones and breaks
- Reduce label noise and move more status into the dashboard
- Normalize scoring into trend / structure / liquidity components

## Repository Placement
- **Path:** `indicators/smart-money/smart-egx-liquidity-sr-dashboard/`
- **Status:** Active Beta

## Notes
This script is useful and practical, but it is not yet considered the repository’s stable reference version. It should be treated as a structured beta pending cleanup and refactoring.