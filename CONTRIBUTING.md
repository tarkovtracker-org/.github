# Contributing to TarkovTracker-org

Thank you for your interest in contributing to the **TarkovTracker.org** ecosystem! We build free, open-source tools for Escape from Tarkov players, and we welcome contributions of all shapes and sizes — code, bug reports, documentation improvements, data corrections, and translations.

> **Note on Precedence:** This document defines the organization-wide default contributing process. Repositories in the organization (such as [`TarkovTracker`](https://github.com/tarkovtracker-org/TarkovTracker)) may include their own `CONTRIBUTING.md` or `AGENTS.md` tailored to their specific tech stack. When a repository provides its own guide, that guide takes precedence.

---

## Code of Conduct

All participation in our repositories and community spaces is governed by the [TarkovTracker-org Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold its standards. Please report unacceptable behavior to <mailto:support@tarkovtracker.org> or via private message to a maintainer on [Discord](https://discord.gg/M8nBgA2sT6).

---

## Ways to Contribute

1. **Bug Reports & Feedback:** If you encounter unexpected behavior, broken task progression, or UI glitches, file an issue using the appropriate template in the repository.
2. **Game Data Corrections:** If task requirements, item spawn locations, or hideout recipes are out of date, report them to [`tarkov-data-overlay`](https://github.com/tarkovtracker-org/tarkov-data-overlay) or submit a pull request there.
3. **Localization:** Help translate the tracker into other languages at [translate.tarkovtracker.org](https://translate.tarkovtracker.org) via [Crowdin](https://crowdin.com/project/tarkovtrackerorg). Please contribute translations through Crowdin rather than editing non-English locale files directly.
4. **Code & Documentation:** Submit pull requests for bug fixes, performance improvements, documentation enhancements, and features.
5. **Community Support:** Help triage questions and share tips with fellow players on our [Discord](https://discord.gg/M8nBgA2sT6).

---

## Reporting Issues

Before opening a new issue:

1. **Search existing issues** (both open and closed) to see if the topic is already being tracked.
2. **Verify against the latest version** — if you are testing the web app, check <https://tarkovtracker.org> to confirm the issue reproduces on the live deployment.
3. **Open the issue in the affected repository** and use its structured issue templates whenever available:
   - **Bug Report:** Include clear reproduction steps, expected behavior, actual behavior, screenshots, and browser/OS environment.
   - **Feature Request:** Describe the problem you are trying to solve and your proposed solution.
4. **Security Vulnerabilities:** Do **not** open a public issue for security concerns. Follow our [Security Policy](SECURITY.md) instead.

---

## Finding Work to Pick Up

- Browse repositories for issues labeled [good first issue](https://github.com/search?q=org%3Atarkovtracker-org+is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22%2Cgood-first-issue&type=issues) or [help wanted](https://github.com/search?q=org%3Atarkovtracker-org+is%3Aissue+is%3Aopen+label%3A%22help+wanted%22%2Chelp-wanted&type=issues).
- Before starting work on an existing issue, leave a comment stating your intention and wait for maintainer confirmation to prevent duplicate effort.
- For major new features or architectural changes, please open a feature request first to align on scope and direction before writing code.

---

## Pull Request Guidelines

To keep reviews smooth and our release cycle predictable:

1. **One Change per PR:** Keep pull requests focused on a single logical change. Do not bundle unrelated refactors, dependencies, or formatting changes into a single PR.
2. **Branch from the Default Branch:** Branch off `main` using descriptive names:
   - `fix/description` for bug fixes
   - `feat/description` for new features
   - `docs/description` for documentation improvements
   - `refactor/description` for code refactoring
   - `chore/description` for tooling, CI, or dependency updates
3. **Follow Repository Conventions:** Respect the repository's linter, formatter, and coding conventions (e.g. ESLint, Prettier, TypeScript strict mode, or .NET coding standards).
4. **Validate Locally:** Run all existing test suites, linters, and type checkers before opening the PR.
5. **Complete the PR Template:** Fill in the provided pull request template, describe your testing methodology, link any related issues (e.g., `Closes #123`), and provide screenshots for UI changes.
6. **Address Feedback:** Maintainers may suggest changes during code review. Keep discussions constructive, make updates on the same branch, and re-request review when ready.

---

## AI-Assisted Contributions

We welcome contributions developed with the assistance of AI coding tools, subject to the following requirements:

- You are personally responsible for all code submitted. Understand every line of your PR.
- Verify that tests pass, generated code adheres to repository style, and no hallucinations (invented APIs, non-existent packages, or dead imports) are introduced.
- For contributions to the flagship web app, review the specialized guidance in [`TarkovTracker/AGENTS.md`](https://github.com/tarkovtracker-org/TarkovTracker/blob/main/AGENTS.md).

---

## Questions?

- Join our [Discord community](https://discord.gg/M8nBgA2sT6) and ask in the appropriate channel.
- See our [Support Directory](SUPPORT.md) for a complete list of contact and routing channels.
