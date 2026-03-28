# Scalping EMA RSI Strategy

## Overview
A minimal EMA crossover and RSI-confirmed Pine Script strategy intended for short-term experimental backtesting.

## Type
Strategy

## Status
Experimental

## Version
v1.0

## Purpose
This script serves as a lightweight prototype strategy for testing short-term trend-following entries using EMA 9/21 crossover and RSI directional confirmation.

## Main Logic
- calculates EMA 9 and EMA 21
- computes RSI 14
- enters long when EMA 9 crosses above EMA 21 and RSI is above 50
- enters short when EMA 9 crosses below EMA 21 and RSI is below 50

## Inputs
- none beyond the hardcoded indicator lengths in the current version

## Outputs / Chart Behavior
- EMA overlays
- strategy long and short entries

## Recommended Timeframes
- 5m
- 15m

## Limitations
- no explicit stop loss or take profit
- no exit logic beyond opposite entries
- no dashboard, filters, or alerts
- best treated as a prototype rather than a mature trading system

## Refactor Notes
- add configurable inputs
- add exits, risk controls, and alerting
- document realistic backtest assumptions before promotion
