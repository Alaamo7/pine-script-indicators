# Smart Correction Signals Pro v1.0

**Status:** Beta  
**Category:** Momentum / Correction Indicator  
**Platform:** TradingView Pine Script v6

## Purpose

Smart Correction Signals Pro helps identify potential correction zones inside an existing trend. It combines EMA trend context, RSI, MACD, Bollinger Bands, confirmed swing pivots, and Fibonacci retracement levels.

## Core Features

- EMA 20 / EMA 50 trend filter.
- RSI overbought and oversold markers.
- MACD bullish and bearish crosses.
- Bollinger Bands for volatility context.
- Confirmed pivot-based swing highs and lows.
- Fibonacci 38.2%, 50%, and 61.8% retracement levels.
- Correction buy/sell setup alerts.

## Improvements in This Version

- Uses `ta.pivothigh()` and `ta.pivotlow()` instead of noisy highest/lowest-bar swing detection.
- Adds `na` protection before calculating Fibonacci levels.
- Adds trend context before generating correction setup labels.
- Adds structured alerts.

## Suggested Use

This indicator is designed as a correction-zone helper, not a standalone trading system. A buy setup is stronger when the main trend is bullish and price reacts near the 50%–61.8% retracement zone. A sell setup is stronger when the main trend is bearish and price rejects near the 38.2%–50% zone.

## Caution

Confirmed pivots appear after the right-side confirmation bars have completed. This reduces noise but means swing labels are intentionally delayed.
