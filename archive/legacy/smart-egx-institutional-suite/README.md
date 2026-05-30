# Smart EGX Institutional Suite v5.0

**Status:** Legacy Reference  
**Category:** Archive / Legacy / Institutional-Style EGX Indicator  
**Platform:** TradingView Pine Script v6

## Purpose

Smart EGX Institutional Suite v5.0 is preserved as a legacy reference for older institutional-style EGX dashboard logic. It combines moving averages, RSI, ADX, directional movement, volume spikes, simplified market structure, stop-hunt detection, simplified order-block logic, and a compact dashboard.

## Why Archived?

This script is placed under `archive/legacy` because newer modular indicators now cover its ideas more cleanly:

- Smart EGX Trend Engine
- Smart EGX Smart Money Core
- Expert EGX Analyst Pro

The suite is still useful as a historical full-reference script, but it should not be treated as the primary production indicator.

## Core Features

- EMA 13, EMA 30, EMA 72, and EMA 144.
- RSI and ADX readings.
- +DI / -DI directional bias.
- Volume spike detection.
- Confirmed pivot-based BOS logic.
- Stop-hunt markers.
- Simplified order-block labels.
- Compact institutional-style dashboard.
- Managed label cleanup to reduce TradingView object clutter.

## Improvements in This Preserved Version

- Removed the misleading placeholder-only version.
- Preserved the fuller reference logic in one clearly named file.
- Added label management.
- Added `na` protection around structure logic.
- Added structured alerts.
- Clarified that the script is a legacy reference, not the main production indicator.

## Caution

Order-block and stop-hunt definitions are simplified. Use this script for study, historical comparison, and internal reference rather than direct mechanical trading decisions.
