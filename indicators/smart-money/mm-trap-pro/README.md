# MM Trap Pro

## Overview
A Pine Script indicator for highlighting potential bullish and bearish trap candles using abnormal volume, candle body size, and previous-bar context.

## Type
Indicator

## Status
Beta

## Version
v1.0

## Purpose
This script attempts to identify possible trap conditions where price behavior and volume suggest false directional commitment or exhaustion.

## Main Logic
The indicator computes:
- average volume over a configurable window
- high-volume conditions using a multiplier
- candle body percentage filter
- bearish and bullish trap conditions based on candle direction, previous bar range relationship, and volume context

## Inputs
- Volume Length
- Volume Multiplier
- Minimum Body Percent
- visual toggles for lines, background, signals, and legend
- mobile-friendly mode

## Outputs / Chart Behavior
- trap lines
- background highlights
- bullish/bearish signal labels
- legend/dashboard panel

## Recommended Timeframes
- 5m
- 15m
- 1h

## Limitations
- trap logic is heuristic, not institutional proof
- may produce false positives on thin or noisy charts
- does not include market structure confirmation or sweep validation

## Refactor Notes
- improve naming precision around “trap”
- add alert conditions
- optionally integrate structure confirmation to reduce noise
