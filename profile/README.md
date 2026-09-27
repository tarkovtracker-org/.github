# TarkovTracker.org

[![Website](https://img.shields.io/badge/website-tarkovtracker.org-2ea44f?logo=googlechrome&logoColor=white)](https://tarkovtracker.org)
[![Discord](https://img.shields.io/badge/Discord-join%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/M8nBgA2sT6)
[![Crowdin](https://badges.crowdin.net/tarkovtrackerorg/localized.svg)](https://crowdin.com/project/tarkovtrackerorg)

Welcome to the **TarkovTracker.org** GitHub organization. We maintain free, community-driven tools, web applications, and companion software to help [Escape from Tarkov](https://www.escapefromtarkov.com) players track their progression. Core tracking features are free for everyone, and all of our projects are developed in the open.

---

## 🌟 Ecosystem & Projects

### Active Applications & Services

| Repository | Tech Stack | License | Description |
| --- | --- | --- | --- |
| [**TarkovTracker**](https://github.com/tarkovtracker-org/TarkovTracker) | Nuxt 4, Vue 3, TypeScript, Supabase, Tailwind CSS | GPL-3.0 | Our flagship web application at [tarkovtracker.org](https://tarkovtracker.org). Tracks tasks, hideout upgrades, required items, player level, and team progress separately for PvP and PvE. Works without an account using browser storage, or sign in for cross-device sync, teams, and API access. |
| [**tarkov-data-overlay**](https://github.com/tarkovtracker-org/tarkov-data-overlay) | TypeScript, Node.js | MIT | Community-maintained data overlay providing corrections, additions, and overrides on top of the upstream [tarkov.dev](https://tarkov.dev) static JSON API (`json.tarkov.dev`). Powers up-to-date task requirements and game editions. |
| [**TrackerBot**](https://github.com/tarkovtracker-org/TrackerBot) | JavaScript, Node.js 18.17+, discord.js v14 | MIT | The Discord companion bot powering the [TarkovTracker.org Discord server](https://discord.gg/M8nBgA2sT6). Provides slash commands, reaction roles, welcome automation, ticket creation, and a public bug-intake portal that forwards reports to GitHub. |
| [**TarkovMonitor**](https://github.com/tarkovtracker-org/TarkovMonitor) | C#, .NET | GPL-3.0 | Desktop utility that monitors local Tarkov log files to help players track progress, queues, and groups. *(Fork of [the-hideout/TarkovMonitor](https://github.com/the-hideout/TarkovMonitor))* |
| [**RatScanner**](https://github.com/tarkovtracker-org/RatScanner) | C#, .NET | Elastic License 2.0 (based) | TarkovTracker.org edition of the popular companion app, forked from [RatScanner/RatScanner](https://github.com/RatScanner/RatScanner). Scans in-game item tooltips and provides real-time flea market prices, trader values, and quest/hideout requirements. |
| [**RatEye**](https://github.com/tarkovtracker-org/RatEye) | C#, .NET | Elastic License 2.0 (based) | Image-processing and pattern-matching library used by RatScanner to accurately identify in-game Tarkov items from screen captures. |
| [**RatScannerData**](https://github.com/tarkovtracker-org/RatScannerData) | Python | MIT | Automated release builder for the runtime data bundle consumed by RatScanner (item icons, maps, and OCR data). |

### Meta & Organization Defaults

| Repository | Description |
| --- | --- |
| [**.github**](https://github.com/tarkovtracker-org/.github) | Organization profile, issue/PR templates, and org-wide community health defaults (Code of Conduct, Contributing, Security, and Support). |

### Historical Archives

| Repository | Status | Description |
| --- | --- | --- |
| [**TarkovTracker-Archive**](https://github.com/tarkovtracker-org/TarkovTracker-Archive) | Archived | The legacy Vue 3 + Vuetify single-page application and Firebase backend that previously powered TarkovTracker before the Nuxt 4 + Supabase rewrite. Kept for historical reference. |
| [**Status-Archive**](https://github.com/tarkovtracker-org/Status-Archive) | Archived | Previous status page configuration for TarkovTracker services. |

---

## 🎯 Our Core Principles

- **Free Core Features:** Task tracking, hideout planning, item requirements, team progress, and API access are free. Optional [supporter tiers](https://tarkovtracker.org/supporter) help fund hosting and development and add perks such as higher API quotas.
- **Developed in the Open:** Source code is public on GitHub. Each repository's license is listed above and in its `LICENSE` file.
- **Privacy First:** The tracker works in your browser without an account — your progress is stored locally unless you choose to sign in for cloud sync or teams.
- **Community-Driven:** Feature prioritization, game data corrections, and bug fixes happen out in the open through community issues, discussions, and pull requests.
- **Data Integrity:** We cross-validate task requirements, hideout upgrades, and item needs across official game updates, community reports, and the `tarkov-data-overlay` project.

---

## 🤝 Getting Involved

Contributions of any kind and skill level are warmly welcomed across the ecosystem:

- **🎮 Play & Report:** Use [tarkovtracker.org](https://tarkovtracker.org) during your raids. If you spot a UI bug, [open an issue](https://github.com/tarkovtracker-org/TarkovTracker/issues/new/choose); report missing or incorrect task data to [tarkov-data-overlay](https://github.com/tarkovtracker-org/tarkov-data-overlay/issues/new/choose).
- **🌍 Translations:** Help translate the tracker into your native language at [translate.tarkovtracker.org](https://translate.tarkovtracker.org) via our [Crowdin project](https://crowdin.com/project/tarkovtrackerorg).
- **💻 Code & Documentation:** Check out our [Contributing Guidelines](https://github.com/tarkovtracker-org/.github/blob/main/CONTRIBUTING.md) to get started. Look for issues labeled [good first issue](https://github.com/search?q=org%3Atarkovtracker-org+is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22%2Cgood-first-issue&type=issues).
- **💬 Community Support:** Join our Discord and help fellow players navigate quests, hideout modules, and setup questions.

---

## 📞 Connect & Support

- **💬 Discord:** [Join the TarkovTracker.org Community](https://discord.gg/M8nBgA2sT6) — fastest way to ask questions, chat with developers, and share feedback
- **🌐 Website:** [tarkovtracker.org](https://tarkovtracker.org)
- **✉️ Email:** [support@tarkovtracker.org](mailto:support@tarkovtracker.org)
- **🔒 Security Reports:** [security@tarkovtracker.org](mailto:security@tarkovtracker.org) (or use GitHub Private Vulnerability Reporting on the affected repository — see our [Security Policy](https://github.com/tarkovtracker-org/.github/blob/main/SECURITY.md))
- **📜 Code of Conduct:** Read our [Contributor Covenant Code of Conduct](https://github.com/tarkovtracker-org/.github/blob/main/CODE_OF_CONDUCT.md)

---

<div align="center">
  <sub>TarkovTracker.org is a community-run open-source project. Escape from Tarkov is a registered trademark of Battlestate Games Limited. This project is not affiliated with or endorsed by Battlestate Games.</sub>
</div>
