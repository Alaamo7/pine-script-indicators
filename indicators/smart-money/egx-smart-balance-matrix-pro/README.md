# EGX Smart Balance Matrix Pro

## Overview
A multi-factor Pine Script indicator for EGX-oriented market analysis, combining trend, momentum, volume expansion, price structure, liquidity sweeps, and a score-based dashboard.

## Type
Indicator

## Status
Beta

## Version
v1.0

## Purpose
This script is designed to provide a broader analytical view of the chart rather than a single-condition signal. It combines multiple components:
- trend bias using EMA structure
- momentum confirmation using RSI and MACD
- liquidity and volume spike analysis
- swing-based structure breaks
- liquidity sweep detection
- score-based decision output

## Main Logic
The indicator calculates:
- medium and major trend using EMA fast and EMA slow
- momentum bias from RSI and MACD
- liquidity state from volume spikes
- swing highs/lows using pivot logic
- BOS and sweep conditions
- a cumulative score that produces a final directional decision

## Inputs
- EMA fast length
- EMA slow length
- RSI settings
- MACD settings
- Volume MA and spike multiplier
- Pivot length
- Dashboard position and visibility

## Outputs / Chart Behavior
- EMA overlays
- buy/sell triangles
- sweep markers
- dashboard with levels, liquidity, momentum, score, and final decision
- alerts for buy, sell, and sweep-low events

## Recommended Timeframes
- 15m
- 1h
- 4h
- Daily

## Limitations
- blends multiple methods into one script, which may reduce interpretability
- requires behavioral validation across symbols
- naming is broader than the actual technical implementation
- some comments and presentation style should be normalized for repository standards

## Refactor Notes
- remove personal-style comments
- normalize naming and section comments
- verify type handling for dashboard position logic
- separate score model explanation more clearly