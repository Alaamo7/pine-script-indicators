# EGX Pro Matrix Family

## Overview
This folder contains related EGX matrix-style indicator variants built around pivot levels, EMA-based trend filtering, higher-timeframe confirmation, and dashboard-style visual guidance.

## Family Structure
- `variants/EGX-Pro-Matrix-MTF-Filter_v1.0.pine`
- `variants/EGX-Pro-Matrix-Risk-Manager_v1.0.pine`

## Design Pattern
These scripts share a common design philosophy:
- previous-day pivot and level mapping
- local trend filter using EMA
- optional higher-timeframe confirmation
- tactical visual dashboard
- discretionary chart-reading support

## Status
Beta family

## Notes
These variants are related but not equivalent.
They should be treated as sibling tactical overlays rather than fully separate script families.

## Review Warning
Several family members use `request.security(..., lookahead=barmerge.lookahead_on)`.
Any non-repainting claims must be validated carefully before promoting a member of this family to Stable.
