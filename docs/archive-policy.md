# Archive Policy

## Why Archive Instead of Delete?

Deleting old Pine versions blindly causes:
- lost logic history
- impossible rollback
- repeated mistakes
- confusion about which version was stable

Archiving preserves development history without polluting active folders.

---

## Archive Buckets

### `/archive/legacy`
Old structures or previous stable generations.

### `/archive/deprecated`
Versions intentionally retired and no longer recommended.

### `/archive/broken-or-test`
Failed experiments, broken scripts, partial rewrites, quick tests.

---

## When to Archive

Archive a script when:
- a new version fully replaces it
- the script is no longer maintained
- the script is broken and not suitable for active use
- the logic is historically useful but not current

---

## What Not to Archive

Do not archive:
- currently maintained stable versions
- reusable helpers still in use
- scripts under active debugging unless clearly separated as experimental
