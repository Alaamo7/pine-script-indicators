# Release Workflow

## Basic Lifecycle

1. Start from template
2. Build in experimental area if unstable
3. Test and refine
4. Promote to stable category
5. Document changes
6. Archive superseded versions

---

## Suggested Status Flow

`Experimental -> Beta -> Stable -> Deprecated -> Archived`

---

## Version Bump Rules

### Patch-like change
Small fixes, minor logic cleanup:
- `v1.0 -> v1.1`

### Minor feature update
New filters, dashboard additions, extra confirmations:
- `v1.1 -> v1.2`

### Major architecture rewrite
Core logic changes, full structural redesign:
- `v1.x -> v2.0`

---

## Changelog Rule

Any meaningful public or stable script change should be reflected in:
- local script README
- repository changelog if major
