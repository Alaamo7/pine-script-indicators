# EGX Pro Price Matrix v1.0

**Status:** Beta  
**Category:** Trend / Price Matrix / Pivot Levels  
**Platform:** TradingView Pine Script v6

## Purpose

EGX Pro Price Matrix provides daily pivot-based price levels, trend context, liquidity signals, and a compact dashboard for EGX-style chart review.

## Core Features

- Daily pivot, R1/R2/R3, S1/S2/S3 levels.
- Golden target levels based on the previous daily range.
- Transformation line between Pivot and R1.
- EMA 50 / EMA 200 trend context by default.
- Liquidity entry/exit signals around Pivot.
- Managed right-side labels.
- Compact dashboard.
- Alert conditions for entry and exit.

## Cleanup Notes

The old PR #4 version used `barmerge.lookahead_on`. This cleaned version uses `barmerge.lookahead_off` to avoid future-looking bias.

## Caution

This script provides levels and context. It should not be used as a standalone trading system without confirmation from market structure, trend, volume, and risk management.
