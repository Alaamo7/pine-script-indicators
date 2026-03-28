# AI Dynamic Liquidity Engine

## Overview
A Pine Script indicator intended to detect and visualize repeated liquidity reaction zones using swing highs/lows and repeated level tests.

## Type
Indicator

## Status
Experimental

## Version
v2.0

## Purpose
This script attempts to identify dynamic liquidity zones by storing swing-derived levels and increasing confidence when those levels are retested multiple times.

## Main Logic
- detects swing highs and swing lows over a configurable window
- stores those levels in arrays
- increments a test counter when price revisits a stored level within a small tolerance
- draws red and green box zones when the number of tests exceeds a threshold
- displays a minimal dashboard

## Inputs
- Total Lookback Bars
- Swing Window Size
- Volume Sensitivity
- Test Sensitivity
- Zone Box Width

## Outputs / Chart Behavior
- dynamic red/green liquidity zone boxes
- minimal activity dashboard

## Recommended Timeframes
- 15m
- 1h
- 4h

## Limitations
- box creation is not object-managed cleanly and may create repeated visual clutter
- some inputs are currently unused in the implementation
- the script name implies stronger intelligence than the present logic actually delivers
- dashboard is minimal relative to the script scope

## Refactor Notes
- remove or activate unused inputs
- manage drawn box objects more safely
- improve naming and internal structure
- validate whether volume should actually participate in zone scoring
