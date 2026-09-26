# TarkovTracker-org Community Health & Organization Defaults

This repository (`tarkovtracker-org/.github`) hosts the organization profile and the organization-wide default community health files for the **[TarkovTracker.org](https://tarkovtracker.org)** open-source ecosystem.

GitHub automatically inherits these files across all repositories in the `tarkovtracker-org` organization that do not define their own repository-level equivalents:

- **[Code of Conduct](CODE_OF_CONDUCT.md)** — Contributor Covenant v2.1 adapted for TarkovTracker-org
- **[Contributing Guidelines](CONTRIBUTING.md)** — cross-repo contributor workflow, reporting guidelines, and pull-request standards
- **[Security Policy](SECURITY.md)** — coordinated vulnerability disclosure, scope, private reporting channels, and SLAs
- **[Support Directory](SUPPORT.md)** — triage routing for user help, bugs, features, game data, accounts, and security
- **[Default Issue Templates](.github/ISSUE_TEMPLATE/)** — structured Bug Report and Feature Request forms with `config.yml` routing
- **[Default Pull Request Template](.github/pull_request_template.md)** — consistent checklist covering testing, docs, and conventions
- **[Organization Profile](profile/README.md)** — public landing page rendered at [github.com/tarkovtracker-org](https://github.com/tarkovtracker-org)

## Precedence Rule

Per GitHub's community health file inheritance rules, any repository in this organization can override a default file simply by committing its own version at its root, in `.github/`, or under `docs/`.

Our flagship repository, [`TarkovTracker`](https://github.com/tarkovtracker-org/TarkovTracker), maintains its own specialized issue forms and workflow automation suited to its Nuxt 4 + Supabase architecture. All other current and future repositories in the organization automatically inherit the defaults hosted here.

## Ecosystem Quick Links

- 🌐 **Live Web Application:** <https://tarkovtracker.org>
- 💬 **Discord Community:** <https://discord.gg/M8nBgA2sT6>
- 🌐 **Crowdin Localization:** <https://crowdin.com/project/tarkovtrackerorg>
- 🔒 **Security Inquiries:** <mailto:security@tarkovtracker.org>
- ✉️ **General Contact:** <mailto:contact@tarkovtracker.org>

## Repository Hygiene

Changes to files in this repository affect every repository across the organization that relies on default templates. All Markdown files in this repository are validated against [markdownlint](https://github.com/DavidAnson/markdownlint) and checked for broken links using [Lychee](https://github.com/lycheeverse/lychee).
