# Expert EGX Analyst Pro

## Overview
A hybrid EGX Pine Script indicator combining trend overlays, market structure, liquidity pools, fair value gap detection, order block flags, volume spikes, MTF bias, and a compact score dashboard.

## Type
Indicator

## Status
Experimental

## Version
v5.0

## Purpose
This script appears to represent a transitional research layer between trend dashboards and broader smart-money style overlays for EGX charts.

## Main Logic
- overlays EMA 13, 30, 72, 144, plus VWAP
- computes RSI and ADX
- tracks pivot-based market structure and BOS conditions
- draws liquidity pool lines from pivots
- detects simple bullish and bearish FVG patterns
- flags simplified order block conditions
- incorporates volume spike detection
- derives higher-timeframe bias from daily trend context
- builds a score summary dashboard

## Inputs
- moving average visibility
- signal visibility
- dashboard visibility

## Outputs / Chart Behavior
- EMA and VWAP overlays
- BOS labels
- liquidity lines
- FVG boxes
- order block labels
- dashboard summary

## Recommended Timeframes
- 15m
- 1h
- 4h

## Limitations
- multiple drawing objects are created without lifecycle management
- smart-money concepts are simplified and not institution-grade
- combines many ideas in one script, reducing maintainability and clarity
- best treated as an experimental research indicator rather than a production-grade tool

## Refactor Notes
- manage object creation more safely
- split the trend and smart-money logic into clearer modules
- add alerting only after concept cleanup
