# AboSamra Pro v1.1

**Status:** Active Beta  
**Category:** Trend / Momentum / Manual S&R Dashboard  
**Platform:** TradingView Pine Script v6

## Purpose

AboSamra Pro is a trend and momentum overlay indicator designed for quick EGX-style chart review. It combines EMA trend stacking, RSI momentum classification, manually configured support/resistance levels, buy/sell markers, alerts, and an Arabic dashboard.

## Core Features

- EMA 9, EMA 21, EMA 50, and EMA 200 trend stack.
- RSI momentum classification.
- Manual support and resistance level inputs.
- Buy and sell markers based on EMA 9/21 cross and RSI momentum context.
- Arabic dashboard with current price, trend, RSI, EMA state, support/resistance distance, signal, and final decision.
- Alerts for buy/sell signals and trend changes.

## Current Strengths

- Useful visual dashboard for fast review.
- Manages support/resistance lines using reusable line objects instead of creating unlimited new lines.
- Has clear author/version metadata in the script header.

## Current Limitations

- Support and resistance levels are manual inputs, not automatically detected.
- Buy/sell labels are signal helpers, not a complete trading system.
- The final decision text is heuristic and should be reviewed against price action.

## Repository Placement

- **Path:** `indicators/trend/AboSamra-Pro/AboSamra-Pro_v1.1.pine`
- **Status:** Active Beta

## Suggested Next Improvements

- Add optional automatic pivot-based support/resistance.
- Add volume confirmation filter.
- Add multi-timeframe trend bias.
- Consider normalizing folder naming to lowercase/kebab-case in a future cleanup.
