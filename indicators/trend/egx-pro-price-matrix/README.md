# EGX Pro Price Matrix

## Overview
A level-centric EGX indicator focused on pivot zones, targets, supports, resistances, and directional overlays using EMA 50 and EMA 200.

## Type
Indicator

## Status
Beta

## Version
v1.0

## Purpose
This script is designed to provide a structured visual map of daily balance, support/resistance zones, golden targets, and directional bias for discretionary chart reading.

## Main Logic
- calculates classic daily pivot levels from previous-day OHLC
- derives R1/R2/R3 and S1/S2/S3 levels
- adds extended golden target levels based on range expansion
- overlays EMA 50 and EMA 200 for context
- generates buy/sell signals from pivot crossover behavior
- presents dashboard summary for market state and volume condition

## Inputs
- label visibility
- label offset

## Outputs / Chart Behavior
- right-side price labels
- EMA overlays
- buy/sell signal markers
- compact market summary dashboard

## Recommended Timeframes
- 15m
- 1h
- 4h
- Daily

## Limitations
- highly visual and discretionary in nature
- relies on previous-day levels and may not fit all instruments equally
- `lookahead_on` is used for daily level fetching and should be reviewed carefully
- label creation logic may need cleanup for large-scale use
