# Reverse SMA RSI Strategy

## Overview
A Pine Script backtest strategy based on SMA 9/21 crossover logic with RSI oversold/overbought confirmation.

## Type
Strategy

## Status
Beta

## Version
v1.0

## Purpose
This strategy is designed to test reversal-style entries where moving average crossover aligns with recent RSI exhaustion.

## Main Logic
The strategy:
- calculates SMA fast and SMA slow
- computes RSI
- checks whether RSI recently reached oversold or overbought zones
- opens long on bullish crossover with oversold confirmation
- opens short on bearish crossover with overbought confirmation
- closes positions on opposite crossover

## Inputs
- SMA fast length
- SMA slow length
- RSI length
- RSI oversold threshold
- RSI overbought threshold
- dashboard visibility

## Outputs / Chart Behavior
- strategy entries and exits
- SMA overlays
- buy/sell markers
- dashboard state
- alert conditions

## Recommended Timeframes
- 5m
- 15m
- 1h

## Limitations
- no stop loss or take profit
- no position scaling
- no volatility or session filter
- citation artifacts were removed during repository migration cleanup

## Refactor Notes
- clarify whether the score system is informational or operational
- add configurable risk controls in a future version
