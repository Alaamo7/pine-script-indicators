# Smart EGX Trend Engine v1.0

**Status:** Beta  
**Category:** Trend Indicator  
**Platform:** TradingView Pine Script v6

## Purpose

Smart EGX Trend Engine is a trend and momentum dashboard designed for EGX-style technical analysis. It combines moving averages, VWAP, RSI, ADX, and multi-timeframe bias into one lightweight overlay indicator.

## Core Features

- EMA trend stack: fast, base, mid, institutional, and long-term EMAs.
- VWAP overlay.
- RSI and ADX momentum/strength readings.
- Multi-timeframe bias using proper `request.security()` calculations.
- Compact dashboard.
- Bullish and bearish shift alerts.

## Default EGX-Oriented Settings

| Component | Default |
|---|---:|
| Fast EMA | 13 |
| Base EMA | 30 |
| Mid EMA | 72 |
| Institutional EMA | 144 |
| Long EMA | 288 |
| RSI | 14 |
| ADX | 14 |
| MTF EMA | 50 |

## Notes

This version fixes the multi-timeframe logic by calculating both higher-timeframe close and higher-timeframe EMA inside `request.security()` with `barmerge.lookahead_off`.

## Suggested Use

Use this indicator as a directional filter, not as a standalone buy/sell system. Stronger readings occur when price, VWAP, RSI, ADX, and higher-timeframe bias align.
