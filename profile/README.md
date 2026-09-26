# TarkovTracker.org

[![Website](https://img.shields.io/badge/website-tarkovtracker.org-2ea44f?logo=googlechrome&logoColor=white)](https://tarkovtracker.org)
[![Discord](https://img.shields.io/badge/Discord-join%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/M8nBgA2sT6)
[![Crowdin](https://badges.crowdin.net/tarkovtrackerorg/localized.svg)](https://crowdin.com/project/tarkovtrackerorg)
[![X](https://img.shields.io/badge/X-@tarkovtracker_-000000?logo=x&logoColor=white)](https://x.com/tarkovtracker_)

Welcome to the **TarkovTracker.org** open-source organization. We maintain free, community-driven tools, web applications, and companion software to help [Escape from Tarkov](https://www.escapefromtarkov.com) players track their progression easily and efficiently — with zero paywalls, zero ads, and no locked features.

---

## 🌟 Ecosystem & Projects

### Active Applications & Services

| Repository | Tech Stack | License | Description |
| --- | --- | --- | --- |
| [**TarkovTracker**](https://github.com/tarkovtracker-org/TarkovTracker) | Nuxt 4, Vue 3, TypeScript, Supabase, Tailwind CSS | GPL-3.0 | Our flagship web application at [tarkovtracker.org](https://tarkovtracker.org). Tracks quests, hideout upgrades, required items, player level, and real-time squad sync separately for PvP and PvE. Works offline with `localStorage` or with a free account for multi-device sync. |
| [**tarkov-data-overlay**](https://github.com/tarkovtracker-org/tarkov-data-overlay) | TypeScript, Node.js | MIT | Community-maintained data overlay providing corrections, additions, and overrides on top of the upstream [tarkov.dev](https://tarkov.dev) GraphQL API. Powers up-to-date quest requirements and game editions. |
| [**TrackerBot**](https://github.com/tarkovtracker-org/TrackerBot) | JavaScript, Node.js 18+, discord.js v14 | MIT | The Discord companion bot powering the [TarkovTracker.org Discord server](https://discord.gg/M8nBgA2sT6). Provides slash commands, reaction roles, onboarding automation, ticket management, and an issue-intake portal. |
| [**TarkovMonitor**](https://github.com/tarkovtracker-org/TarkovMonitor) | C#, .NET | GPL-3.0 | Desktop utility that monitors local Tarkov log files to help players track real-time raid status, matchmaking queues, and group activity. *(Maintained fork from the-hideout)* |
| [**RatScanner**](https://github.com/tarkovtracker-org/RatScanner) | C#, .NET | GPL-3.0 | TarkovTracker.org edition of the popular companion app. Scans in-game item tooltips and provides real-time flea market prices, trader values, and quest/hideout requirements. |
| [**RatEye**](https://github.com/tarkovtracker-org/RatEye) | C#, .NET | GPL-3.0 | Optical image-processing and pattern-matching library used by RatScanner to accurately identify in-game Tarkov items from screen captures. |
| [**RatScannerData**](https://github.com/tarkovtracker-org/RatScannerData) | Python | MIT | Automated pipeline and runtime data bundle builder for RatScanner, packaging icon hashes and item definitions. |
| [**RequestExtract**](https://github.com/tarkovtracker-org/RequestExtract) | Python | MIT | Local diagnostic network request extraction and session capture utility for analyzing client-server interactions during development. |
| [**RequestStash**](https://github.com/tarkovtracker-org/RequestStash) | Python | MIT | Offline session converter and payload decoder designed to work with recordings produced by `RequestExtract`. |

### Meta & Organization Defaults

| Repository | Description |
| --- | --- |
| [**.github**](https://github.com/tarkovtracker-org/.github) | Organization profile, issue/PR templates, and org-wide community health defaults (Code of Conduct, Contributing, Security, and Support). |

### Historical Archives

| Repository | Status | Description |
| --- | --- | --- |
| [**TarkovTracker-Archive**](https://github.com/tarkovtracker-org/TarkovTracker-Archive) | Archived | The legacy Vue 2 single-page application and Firebase backend that originally powered TarkovTracker before the Nuxt 4 + Supabase rewrite. Kept for historical reference. |
| [**Status-Archive**](https://github.com/tarkovtracker-org/Status-Archive) | Archived | Previous status page configuration for TarkovTracker services. |

---

## 🎯 Our Core Principles

- **100% Free & Open Source:** Every core feature — quest tracking, hideout planning, item requirements, squad sync, and API access — is free. All source code is openly licensed.
- **Privacy First:** The tracker works completely offline in your browser with `localStorage` — no account, email, or login required unless you choose to enable cloud backup or squad sync.
- **Community-Driven:** Feature prioritization, game data corrections, and bug fixes happen out in the open through community issues, discussions, and pull requests.
- **Data Integrity:** We cross-validate task requirements, hideout upgrades, and item needs across official game updates, community reports, and the `tarkov-data-overlay` project.

---

## 🤝 Getting Involved

Contributions of any kind and skill level are warmly welcomed across the ecosystem:

- **🎮 Play & Report:** Use [tarkovtracker.org](https://tarkovtracker.org) during your raids. If you spot a missing quest, incorrect item count, or a UI bug, [open an issue](https://github.com/tarkovtracker-org/TarkovTracker/issues/new/choose).
- **🌍 Translations:** Help translate the tracker into your native language at [translate.tarkovtracker.org](https://translate.tarkovtracker.org) via our [Crowdin project](https://crowdin.com/project/tarkovtrackerorg). Currently supporting English, German, Spanish, French, Russian, Ukrainian, and Chinese.
- **💻 Code & Documentation:** Check out our [Contributing Guidelines](https://github.com/tarkovtracker-org/.github/blob/main/CONTRIBUTING.md) to get started with local development. We tag newcomer-friendly issues with `good-first-issue`.
- **💬 Community Support:** Join our Discord and help fellow players navigate quests, hideout modules, and setup questions.

---

## 📞 Connect & Support

- **💬 Discord:** [Join the TarkovTracker.org Community](https://discord.gg/M8nBgA2sT6) — fastest way to ask questions, chat with developers, and share feedback
- **🌐 Website:** [tarkovtracker.org](https://tarkovtracker.org)
- **🐦 Updates:** [@tarkovtracker_](https://x.com/tarkovtracker_) on X
- **✉️ Email:** [contact@tarkovtracker.org](mailto:contact@tarkovtracker.org)
- **🔒 Security Reports:** [security@tarkovtracker.org](mailto:security@tarkovtracker.org) (or use [GitHub Private Vulnerability Reporting](https://github.com/tarkovtracker-org/TarkovTracker/security/advisories/new))
- **📜 Code of Conduct:** Read our [Contributor Covenant Code of Conduct](https://github.com/tarkovtracker-org/.github/blob/main/CODE_OF_CONDUCT.md)

---

<div align="center">
  <sub>TarkovTracker.org is a community-run open-source project. Escape from Tarkov is a registered trademark of Battlestate Games Limited. This project is not affiliated with or endorsed by Battlestate Games.</sub>
</div>
