# Contributing Guide

This repository follows a structured workflow to keep Pine Script code organized and maintainable.

## General Rules

- Do not place random scripts in the root folder.
- Do not keep multiple unnamed versions in one location.
- Do not overwrite stable versions without updating version number.
- Archive outdated versions instead of deleting them blindly.
- Use the templates in `/templates` when creating new scripts.

---

## Script Placement Rules

### Put scripts in `indicators/` if:
- they are visual analysis tools
- they generate chart signals or overlays
- they are not intended for direct strategy backtesting

### Put scripts in `strategies/` if:
- they use `strategy(...)`
- they are built for backtests or execution logic

### Put scripts in `libraries/` if:
- they contain reusable helper logic
- they are not standalone end-user indicators

### Put scripts in `archive/` if:
- they are deprecated
- broken
- legacy
- experimental leftovers
- replaced by newer architecture

---

## Naming Rules

Preferred filename format:

`Script-Name_vMajor.Minor.pine`

Examples:
- `Smart-Money-Pro_v2.0.pine`
- `EGX-Scalping-Pro_v1.4.pine`

Avoid:
- `final.pine`
- `final2.pine`
- `newfinal.pine`
- `test_last_edit.pine`

Yes, those names are crimes against future maintenance.

---

## Minimum Header Standard

Each Pine file should contain:
- full script name
- version
- type (indicator / strategy / library)
- author
- status
- summary
- default settings note if inputs are intentionally minimized

---

## Promotion Workflow

Suggested flow:
1. create in `experimental/`
2. validate logic
3. move to target category
4. update README or changelog
5. archive replaced versions if necessary
