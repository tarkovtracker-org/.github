# TarkovTracker-org Community Health & Organization Defaults

This repository (`tarkovtracker-org/.github`) hosts the organization profile and the organization-wide default community health files for the **[TarkovTracker.org](https://tarkovtracker.org)** open-source ecosystem.

GitHub uses these files as defaults for every repository in the `tarkovtracker-org` organization, regardless of visibility, that does not define its own equivalent:

- **[Code of Conduct](CODE_OF_CONDUCT.md)** — Contributor Covenant v2.1 adapted for TarkovTracker-org
- **[Contributing Guidelines](CONTRIBUTING.md)** — cross-repo contributor workflow, reporting guidelines, and pull-request standards
- **[Security Policy](SECURITY.md)** — coordinated vulnerability disclosure, scope, private reporting channels, and response targets
- **[Support Directory](SUPPORT.md)** — triage routing for user help, bugs, features, game data, accounts, and security
- **[Default Issue Templates](.github/ISSUE_TEMPLATE/)** — structured Bug Report and Feature Request forms with `config.yml` routing
- **[Default Pull Request Template](.github/pull_request_template.md)** — consistent checklist covering testing, docs, and conventions

The **[Organization Profile](profile/README.md)** is the public landing page rendered at [github.com/tarkovtracker-org](https://github.com/tarkovtracker-org).

## Precedence Rule

Per [GitHub's community health file rules](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file), a repository overrides a default file by committing its own version in `.github/`, at its root, or under `docs/`. Issue templates are the exception: a repository that defines valid issue templates or a `config.yml` in its own `.github/ISSUE_TEMPLATE/` directory replaces the entire default issue template set, and copies at the root or under `docs/` have no effect.

Repositories such as [`TarkovTracker`](https://github.com/tarkovtracker-org/TarkovTracker), [`tarkov-data-overlay`](https://github.com/tarkovtracker-org/tarkov-data-overlay), and [`RatScanner`](https://github.com/tarkovtracker-org/RatScanner) maintain their own issue templates. Other repositories, and any new ones, use the defaults hosted here.

## Ecosystem Quick Links

- 🌐 **Live Web Application:** <https://tarkovtracker.org>
- 💬 **Discord Community:** <https://discord.gg/M8nBgA2sT6>
- 🌍 **Crowdin Localization:** <https://crowdin.com/project/tarkovtrackerorg>
- 🔒 **Security Inquiries:** <mailto:security@tarkovtracker.org>
- ✉️ **Support & Conduct Reports:** <mailto:support@tarkovtracker.org>

## Repository Hygiene

Changes to files in this repository affect every repository across the organization that relies on default templates. All Markdown files in this repository are validated against [markdownlint](https://github.com/DavidAnson/markdownlint) and checked for broken links using [Lychee](https://github.com/lycheeverse/lychee).
