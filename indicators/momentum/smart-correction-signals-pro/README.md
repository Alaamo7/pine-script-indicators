# Smart Correction Signals Pro

## Overview
A momentum-oriented Pine Script indicator combining EMA context, RSI extremes, MACD crosses, Bollinger Bands, swing highs/lows, and Fibonacci retracement levels.

## Type
Indicator

## Status
Beta

## Version
v1.0

## Purpose
This script is designed to help identify correction zones and momentum confluence points using a blend of common technical indicators.

## Main Logic
- calculates EMA 20 and EMA 50
- flags RSI overbought and oversold states
- flags MACD bullish and bearish crosses
- plots Bollinger Bands and their basis
- detects local swing highs and lows
- derives Fibonacci retracement levels from the latest detected swing range

## Inputs
- EMA visibility and lengths
- RSI length
- MACD settings
- Bollinger Band settings
- swing length

## Outputs / Chart Behavior
- EMA overlays
- RSI and MACD markers
- Bollinger Bands
- swing markers
- last high/low and Fibonacci retracement level plots

## Recommended Timeframes
- 15m
- 1h
- 4h

## Limitations
- Fibonacci logic depends on the most recently detected swing high and low and may need stricter structure control
- no dashboard or alert system is currently included
- script is confluence-oriented rather than signal-perfect

## Refactor Notes
- add optional alerts for confluence setups
- improve swing anchoring logic for Fibonacci calculations
- consider separating visual clutter controls more granularly
