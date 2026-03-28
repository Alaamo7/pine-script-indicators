# Smart EGX Trend Engine

## Overview
A trend-focused EGX Pine Script indicator built around layered exponential moving averages, VWAP context, RSI, ADX, and a compact multi-timeframe dashboard.

## Type
Indicator

## Status
Beta

## Version
v1.0

## Purpose
This script is intended to provide directional trend context for EGX charts using a stack of moving averages and simple momentum confirmation.

## Main Logic
- calculates EMA 13, 30, 72, 144, and 288
- overlays VWAP for additional price context
- computes RSI and ADX
- derives local trend state from price relative to EMA 13 and EMA 30
- derives simple 15m, 1H, and daily bias from higher-timeframe closes versus EMA 50
- builds a score-based trend summary dashboard

## Inputs
- moving average visibility
- dashboard visibility

## Outputs / Chart Behavior
- EMA overlays
- VWAP overlay
- dashboard with trend, score, RSI, ADX, and short-term MTF bias

## Recommended Timeframes
- 15m
- 1h
- 4h
- Daily

## Limitations
- higher-timeframe trend logic is simple and based on close versus EMA rather than richer structure
- dashboard is compact and does not include alerts or signal markers
- better suited for directional context than exact entries

## Refactor Notes
- consider normalizing MTF bias logic more cleanly
- add optional alerts and stronger trend-state color logic
- evaluate whether EMA 288 is always necessary for the intended use case
