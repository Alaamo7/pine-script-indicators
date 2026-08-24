# Security Policy

## Supported version

Only the latest commit on `main` is actively maintained.

## Reporting a vulnerability

Do not publish API keys, tokens, credentials, exploit details, or private account data in a public issue.

- Use GitHub's private vulnerability-reporting option when it is available.
- If private reporting is unavailable, open a minimal public issue requesting a private contact channel without including sensitive details.
- Include the affected path, impact, and safe reproduction steps only through a private channel.

## Exposed secrets

If a credential is committed or appears in a workflow log:

1. Revoke or rotate it immediately.
2. Remove it from the current files and configuration.
3. Store replacements in environment variables or GitHub Secrets.
4. Review repository history and logs for additional exposure.
5. Never paste the full secret into an issue, pull request, or test fixture.

## Scope

This repository contains Pine Script research code, test evidence, documentation, and automation helpers. Security reports should distinguish software defects from trading-performance claims.
