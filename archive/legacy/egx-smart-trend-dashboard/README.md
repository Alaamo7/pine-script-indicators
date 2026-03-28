# EGX Smart Trend Dashboard

## Overview
A legacy Pine Script dashboard indicator focused on trend-state summaries using OBV, ROC, DMI, RSI, and MACD.

## Type
Indicator

## Status
Archived

## Version
v0.9

## Purpose
This script was designed as a visual dashboard for quick directional assessment and signal highlighting based on multiple classical indicators.

## Main Logic
- determines candle direction
- evaluates OBV trend versus OBV EMA
- evaluates ROC momentum direction
- evaluates DMI/ADX directional strength
- evaluates RSI state
- evaluates MACD line versus signal line
- issues buy/sell markers only when all major directional components align

## Inputs
- DMI/ADX period and smoothing
- ROC length
- OBV EMA length
- RSI length
- MACD settings
- legend visibility

## Outputs / Chart Behavior
- buy/sell markers
- top-right dashboard
- left-side visual legend label

## Recommended Timeframes
- 15m
- 1h
- Daily

## Limitations
- legacy v5 implementation
- older architecture compared with newer EGX family scripts
- “Final Version” naming is not repository-grade and was normalized here
- should be preserved for reference, not promoted as an active mainline script

## Archive Reason
Archived because newer EGX scripts provide broader logic, cleaner modularity, and more advanced analytical structure.
