# Security Policy

The TarkovTracker-org organization takes the security of our software, infrastructure, and user data seriously. This document outlines our vulnerability disclosure process, response commitments, and project scope across all repositories under the `tarkovtracker-org` organization.

> **Precedence Note:** This policy acts as the organization-wide default. Individual repositories (such as the flagship [`TarkovTracker`](https://github.com/tarkovtracker-org/TarkovTracker/blob/main/SECURITY.md) web app) may publish their own `SECURITY.md` detailing repository-specific scopes, endpoints, or infrastructure. When present, the repository-level policy takes precedence.

---

## Supported Versions

Unless explicitly stated otherwise in an individual repository:

- **Web applications & services** (e.g., TarkovTracker, Cloudflare Workers, Supabase functions): Only the latest deployment of the default branch (`main`) is actively supported with security fixes.
- **Desktop utilities & bots** (e.g., RatScanner, TarkovMonitor, TrackerBot): Only the latest tagged release and current `main` branch receive security patches.
- Older versions, superseded tags, and archived repositories are not maintained and will not receive backported security patches.

---

## Reporting a Vulnerability

**Please DO NOT report security vulnerabilities through public GitHub issues, pull requests, public Discord messages, or social media.**

To protect users and their data, report security issues through either of the following private channels:

### 1. GitHub Private Vulnerability Reporting (Preferred)

Submit a private advisory directly through GitHub on the affected repository:

- Go to the repository's **Security** tab.
- Click **Report a vulnerability** (or use the direct URL pattern: `https://github.com/tarkovtracker-org/<repo-name>/security/advisories/new`).
- This opens a private advisory workflow visible only to the organization maintainers.

### 2. Direct Email

If GitHub Private Vulnerability Reporting is unavailable, send an encrypted or direct email to:

- ✉️ <mailto:security@tarkovtracker.org>
- *Subject Line Format:* `[SECURITY REPORT] <Repository/Component> - <Brief Description>`

---

## What to Include in Your Report

To help us evaluate and address your finding promptly, please provide:

1. **Affected Component:** Repository name, URL, service, file path, or API endpoint.
2. **Vulnerability Type:** e.g., Cross-Site Scripting (XSS), SQL / RLS bypass, Broken Authentication, Sensitive Data Exposure, Remote Code Execution.
3. **Step-by-step Reproduction:** Clear, repeatable steps demonstrating the issue.
4. **Proof of Concept (PoC):** Minimal, benign reproduction script, screenshot, or HTTP request payload.
5. **Impact Assessment:** Explanation of what an attacker could realistically achieve by exploiting the vulnerability.
6. **Suggested Remediation:** Proposed code fix or configuration change, if known.

---

## Response Commitments & SLAs

When you disclose a vulnerability responsibly, our maintainers commit to:

- **Acknowledgment:** Within **72 hours** of receiving your report.
- **Initial Triage & Assessment:** Within **7 days**, confirming reproducibility, severity, and planned remediation.
- **Fix & Deployment:** We strive to release fixes promptly based on CVSS severity:
  - Critical / High: Within 7 to 14 days of triage.
  - Medium / Low: Next scheduled release or deployment cycle.
- **Coordinated Disclosure:** We work collaboratively with reporters on disclosure timing. We request that you refrain from public disclosure until an official fix is deployed.

---

## Out of Scope

The following areas and testing methods are strictly outside our security scope:

- Denial of Service (DoS/DDoS) attacks against production infrastructure or live APIs.
- Automated vulnerability scanner dumps without manual verification and reproducible proof of impact.
- Social engineering, phishing, or physical attacks against maintainers or contributors.
- Third-party upstream platform issues (e.g., Supabase, Cloudflare, Discord, GitHub, or Battlestate Games services) that do not originate from our configuration or codebase.
- Data correctness issues in [tarkov.dev](https://tarkov.dev) or [tarkov-data-overlay](https://github.com/tarkovtracker-org/tarkov-data-overlay) (report these via normal issue trackers).

---

## Recognition & Safe Harbor

- **Hall of Fame:** With your permission, we are delighted to credit security researchers in release notes and security advisories. If you prefer to remain anonymous, let us know and we will respect your privacy.
- **Safe Harbor:** We will not pursue legal action against individuals who discover and report vulnerabilities in good faith according to this policy, avoid data destruction or privacy violation, and provide reasonable time for remediation prior to public disclosure.
