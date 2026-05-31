# 🔒 Security Policy

This document explains how to report security concerns related to the **Awesome Discord Bots** directory — including malicious bots, scam links, compromised invite links, and vulnerabilities in this repository itself.

We take reports seriously. If something looks wrong, please report it — even if you're not certain.

---

## 📋 Table of Contents

- [Scope](#-scope)
- [Reporting a Malicious Bot](#-reporting-a-malicious-bot)
- [Reporting a Scam or Phishing Link](#-reporting-a-scam-or-phishing-link)
- [Reporting a Compromised Invite Link](#-reporting-a-compromised-invite-link)
- [Reporting a Repository Security Issue](#-reporting-a-repository-security-issue)
- [Responsible Disclosure Policy](#-responsible-disclosure-policy)
- [What Happens After You Report](#-what-happens-after-you-report)
- [Out of Scope](#-out-of-scope)

---

## 🎯 Scope

This security policy covers:

| Area | Covered |
|------|---------|
| Bots listed in this directory that are malicious or harmful | ✅ Yes |
| Scam, phishing, or deceptive links in any file | ✅ Yes |
| Compromised or hijacked bot invite links | ✅ Yes |
| Security vulnerabilities in this repository itself | ✅ Yes |
| Security issues with the bots' own platforms or infrastructure | ❌ No — report to the bot developer directly |
| General Discord platform security issues | ❌ No — report to [Discord's Trust & Safety](https://discord.com/safety) |

---

## 🚨 Reporting a Malicious Bot

If you believe a bot listed in this directory is malicious — for example, it steals tokens, distributes malware, performs unauthorized actions, or collects user data deceptively — please report it immediately.

**How to report:**

1. [Open a GitHub Issue](https://github.com/TeerNetStudio/awesome-discord-bots/issues/new) using the title format:
   ```
   [SECURITY] Malicious bot report — [Bot Name]
   ```
2. Include the following information:
   - Bot name and link to its page in this directory
   - Description of the malicious behavior
   - Any evidence you have (screenshots, links, reports from other users)
   - Date you discovered the issue

**What happens next:**

The bot will be reviewed and, if confirmed, removed from the directory within **48 hours**. A note will be added to the relevant category page if the removal is significant enough to warrant one.

> ⚠️ If the bot poses an active, immediate risk to users, also report it directly to [Discord's Trust & Safety team](https://discord.com/safety). This repository cannot take action on Discord itself — only on what is listed here.

---

## 🎣 Reporting a Scam or Phishing Link

If you find a scam link, phishing URL, or any deceptive link anywhere in this repository — in a bot page, category file, guide, or the README — report it right away.

**How to report:**

1. [Open a GitHub Issue](https://github.com/TeerNetStudio/awesome-discord-bots/issues/new) using the title format:
   ```
   [SECURITY] Scam link found — [File Name]
   ```
2. Include:
   - The file path where the link appears (e.g. `bots/moderation/carl-bot.md`)
   - The suspicious URL (you can obscure it as `hxxps://` to avoid accidental clicks)
   - Why you believe it is a scam or phishing attempt

**Do not click the link yourself** if you are unsure — copy the URL text directly and include it in your report.

Links confirmed as malicious will be removed within **24 hours**.

---

## 🔗 Reporting a Compromised Invite Link

Bot invite links can be hijacked or replaced with malicious redirects — especially for bots that have been abandoned or had their domains expire. If an invite link in this directory leads somewhere unexpected, suspicious, or harmful, please report it.

**Signs of a compromised invite link:**

- The link redirects to a non-Discord URL
- The link asks for credentials or personal information
- The link leads to a different bot than listed
- The link points to a domain that has changed ownership

**How to report:**

1. [Open a GitHub Issue](https://github.com/TeerNetStudio/awesome-discord-bots/issues/new) using the title format:
   ```
   [SECURITY] Compromised invite link — [Bot Name]
   ```
2. Include:
   - Bot name and file path
   - The suspicious link (obscure as `hxxps://` if needed)
   - What the link does or where it redirects
   - Date you discovered the issue

The link will be removed or replaced within **24 hours** of confirmation.

---

## 🛡️ Reporting a Repository Security Issue

If you discover a security vulnerability in this repository itself — for example, a workflow that could be exploited, a dependency issue, or a way to inject malicious content through a pull request — please follow responsible disclosure and **do not open a public issue**.

**How to report privately:**

Send a report via **[GitHub's private vulnerability reporting](https://github.com/TeerNetStudio/awesome-discord-bots/security/advisories/new)**, or contact the maintainer directly through GitHub.

Include:
- A clear description of the vulnerability
- Steps to reproduce it
- Potential impact if exploited
- Any suggested fix, if you have one

You will receive an acknowledgment within **72 hours**.

---

## 📢 Responsible Disclosure Policy

This project follows a **coordinated disclosure** approach. Please follow these guidelines:

**Do:**
- Report issues privately before disclosing them publicly
- Give the maintainer reasonable time to investigate and act (see timelines below)
- Include enough detail to reproduce or verify the issue
- Act in good faith — reports are taken seriously and treated with respect

**Do not:**
- Open a public issue for sensitive security reports
- Exploit or demonstrate a vulnerability beyond what is needed to prove it exists
- Share or publish details of a confirmed vulnerability before it has been addressed
- Submit false reports or use security reports to pressure the project

### Response timelines

| Issue Type | Initial Response | Resolution Target |
|------------|-----------------|-------------------|
| Malicious bot | 48 hours | as soon as reasonably possible |
| Scam / phishing link | 24 hours | as soon as reasonably possible |
| Compromised invite link | 24 hours | as soon as reasonably possible |
| Repository vulnerability | 72 hours | as soon as reasonably possible |

These are targets, not guarantees — this is a solo-maintained project. If a report is urgent, say so clearly in the issue title.

---

## ✅ What Happens After You Report

1. **Acknowledgment** — The maintainer confirms the report has been received
2. **Investigation** — The issue is verified against the listed criteria
3. **Action** — The bot, link, or content is removed, replaced, or patched
4. **Follow-up** — You are notified when the issue has been resolved
5. **Credit** — If you'd like to be credited for the report, say so and your GitHub username will be acknowledged in the relevant commit or release note

Reports that cannot be verified will be closed with an explanation.

---

## 🚫 Out of Scope

The following are outside the scope of this security policy:

- Security vulnerabilities in the bots themselves — contact the bot developer directly
- Discord platform bugs or exploits — report to [Discord's Bug Bounty program](https://discord.com/security)
- Vulnerabilities in third-party services linked from this directory
- General feedback or feature requests — use [Issues](https://github.com/TeerNetStudio/awesome-discord-bots/issues) for those

---

## 🙏 Thank You

Security reports, even small ones, help keep this directory trustworthy. If you took the time to report something, it is genuinely appreciated — regardless of whether the issue turns out to be confirmed.

---

*This policy is reviewed periodically.*
*To suggest improvements to this policy, open an [Issue](https://github.com/TeerNetStudio/awesome-discord-bots/issues).*