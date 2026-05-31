# AI Dynamic Liquidity Engine v2.0

**Status:** Experimental  
**Category:** Smart Money / Dynamic Liquidity / Experimental  
**Platform:** TradingView Pine Script v6

## Purpose

AI Dynamic Liquidity Engine is an experimental dynamic liquidity-zone detector. It tracks repeated swing-high and swing-low areas, counts retests, and highlights qualified supply/demand zones.

## Important Naming Note

The script name uses `AI` as a project naming convention. The current Pine Script logic is rule-based, not machine-learning based. It is designed to be AI-ready for future reporting, scoring, or external automation workflows.

## Core Features

- Swing-high and swing-low detection.
- Retest counting around repeated liquidity levels.
- Configurable zone tolerance.
- Managed supply and demand boxes.
- Dashboard showing qualified supply/demand zones and stored levels.
- Alert conditions for active supply and demand zones.

## Improvements from Old PR #5 Version

- Adds managed box arrays to reduce TradingView object clutter.
- Adds configurable maximum stored zones.
- Adds clearer settings and dashboard fields.
- Adds alert conditions.
- Keeps the script under `indicators/experimental` because the logic is still research-oriented.

## Caution

This is not a standalone trading system. Liquidity zones should be validated with trend, volume, structure, support/resistance, and higher-timeframe context.
