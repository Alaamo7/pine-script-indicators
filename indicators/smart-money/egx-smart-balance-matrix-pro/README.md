# EGX Smart Balance Matrix Pro v1.0

**Status:** Active Beta  
**Category:** Smart Money / Balance Matrix / EGX Dashboard  
**Platform:** TradingView Pine Script v6

## Purpose

EGX Smart Balance Matrix Pro combines trend, momentum, volume/liquidity, pivot balance levels, SMC-lite structure events, and a dashboard into one EGX-oriented overlay indicator.

## Core Features

- EMA 50 / EMA 200 trend context by default.
- RSI and MACD momentum confirmation.
- Volume spike detection.
- Pivot high/low structure tracking.
- BOS Up / BOS Down detection.
- Liquidity sweep high/low detection.
- Score-based decision text.
- Pivot balance levels: Pivot, R1, R2, S1, S2.
- Dashboard with liquidity, momentum, structure, score, and final decision.
- Alert conditions for buy/sell score signals, sweeps, and BOS events.

## Improvements from Legacy PR Version

- Adds safer `na` handling around structure references.
- Protects wick/body calculations from zero-body division issues.
- Normalizes naming to the repository standard.
- Keeps labels lightweight by using `plotshape()` instead of unmanaged label creation.
- Uses English dashboard terms for consistency with other cleaned repository scripts.

## Suggested Use

Use this script as a confluence dashboard. It is not a standalone trading system. Best use is with support/resistance, liquidity zones, trend context, and higher timeframe confirmation.

## Caution

The score system is heuristic. It should be visually validated across multiple EGX stocks and timeframes before relying on it in any workflow.
