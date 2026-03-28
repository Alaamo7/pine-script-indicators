# Repository Structure

## Core Philosophy

This repository is built around one principle:

**separate active development, reusable modules, and archived history clearly.**

Without structure, Pine Script repositories become difficult to maintain very quickly.

---

## Directory Roles

### `/indicators`
Production or near-production indicators categorized by purpose.

### `/strategies`
Backtest scripts, trading logic experiments, and executable strategy concepts.

### `/libraries`
Reusable functions and modules shared across multiple scripts.

### `/templates`
Standard starting points for new files to enforce consistency.

### `/archive`
Old, deprecated, broken, or replaced versions.

### `/docs`
Rules, standards, workflow, and internal documentation.

### `/assets`
Images, screenshots, diagrams, and visual references.

---

## Recommended Script Folder Pattern

For major scripts:

```text
indicators/smart-money/Smart-Money-Pro/
├─ Smart-Money-Pro_v2.0.pine
├─ README.md
├─ CHANGELOG.md
└─ assets/
```

For small scripts:

```text
indicators/momentum/RSI-Enhancer_v1.0.pine
```
