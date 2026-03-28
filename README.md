# Pine Script Indicators Repository

A structured private repository for organizing, archiving, documenting, and versioning Pine Script indicators, strategies, and reusable libraries.

## Purpose

This repository is designed to solve the usual chaos of Pine Script development:

- scattered script versions
- duplicated code
- unclear naming
- missing documentation
- no archive policy
- hard rollback and reuse

The goal is to maintain a clean and scalable Pine Script codebase.

---

## Repository Structure

```text
.
├─ indicators/        # Production and categorized indicators
├─ strategies/        # Strategy scripts and backtest ideas
├─ libraries/         # Reusable helper modules and shared logic
├─ templates/         # Templates for new indicators/strategies/docs
├─ archive/           # Legacy, deprecated, and broken test versions
├─ docs/              # Standards, workflows, and repository rules
└─ assets/            # Screenshots, diagrams, and related visuals
```

---

## Categories

### indicators/
Organized Pine indicators by use case:

- `trend/`
- `momentum/`
- `volume/`
- `smart-money/`
- `scalping/`
- `experimental/`

### strategies/
Contains:
- backtesting scripts
- trade logic prototypes
- live ideas that may later become stable

### libraries/
Reusable code blocks, helper functions, shared modules.

### archive/
Used for:
- deprecated versions
- legacy
- broken experiments
- test scripts not suitable for production

---

## Status Labels

Each script should clearly indicate one of the following states in its internal header or folder README:

- **Stable**
- **Beta**
- **Experimental**
- **Deprecated**
- **Archived**

---

## Naming Principles

General naming format:

`Script-Name_vMajor.Minor.pine`

Examples:

- `Smart-EGX-Pro_v1.5.pine`
- `Smart-Money-Pro_v2.0.pine`
- `Scalping-Signals_v0.9.pine`

Folder-level organization is preferred for large scripts with multiple versions.

---

## Versioning Rule

Use semantic-like versioning where possible:

- `v1.0` → first stable release
- `v1.1` → small feature updates / bug fixes
- `v2.0` → major rewrite or architecture change

---

## Documentation Rule

Each serious script should eventually have:

- its own folder
- the `.pine` file
- a dedicated `README.md`
- optional `CHANGELOG.md`
- screenshots if needed

---

## Workflow Summary

1. Start a new script from `templates/`
2. Develop in `experimental/` if still unstable
3. Promote to the correct category when validated
4. Archive old versions instead of mixing them with current files
5. Document major changes in changelog files

---

## Long-Term Goal

Build a reusable, searchable, professional Pine Script knowledge base rather than just a dumping folder for code versions.
