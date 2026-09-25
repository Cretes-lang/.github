# Contributing to Cretes

Thank you for helping establish Cretes. This is Phase 0: governance, documentation and repository foundation. Language syntax and compiler implementation have not begun. There is no compiler build command or development toolchain to install yet.

## Before a change

1. Read the repository README, governance, security policy and Code of Conduct.
2. Search existing issues and RFCs. Open a focused issue describing the problem and acceptance criteria.
3. Use the RFC process for semantic, architecture, compatibility or governance changes.
4. Never submit credentials, personal data, proprietary material or exploit details to public issues.

## Pull request workflow

Create a short-lived branch from `main`, such as `docs/contribution-guide`, `feature/parser` or `fix/diagnostic-span`. Keep each pull request focused. Explain the change, motivation, linked issue/RFC, validation, compatibility impact and remaining limitations. Use descriptive imperative commit messages; conventional prefixes are optional.

For foundation changes, inspect rendered Markdown, relative links, spelling, template syntax and consistency across repositories. Later code changes must include appropriate regression and conformance tests and pass the relevant build, formatting and security checks. Do not claim tests ran when they did not.

Wait for applicable checks and review. Resolve review conversations. Squash merging is the preferred default for a single coherent change. The single-maintainer exception is documented in GOVERNANCE.md. Do not force-push shared `main` or rewrite released tags.

## Licensing and attribution

Submit only work you have the right to contribute. Contributions are intended to be distributed under this repository's Apache-2.0 license. Preserve third-party notices and disclose dependencies and their licenses. No separate CLA or automated DCO gate is configured at this stage. AI-assisted contributions receive the same human review and validation requirements; contributors remain responsible for correctness, provenance and licensing.

## Reporting

Public bugs and documentation improvements belong in repository issues. Potential vulnerabilities follow SECURITY.md. Community conduct reports follow CODE_OF_CONDUCT.md.
