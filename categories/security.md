# 🔒 Security Bots

> Bots focused on protecting Discord servers from raids, nukes, spam attacks, alt accounts, malicious users, and unauthorized actions.

**Navigation:** [Main Directory](../README.md) · [All Categories](../README.md#-categories)

Security bots act as a server's first line of defense. While moderation bots help manage communities, security bots focus on preventing attacks before they become moderation problems.

This category covers anti-raid systems, anti-nuke protection, verification systems, alt-account detection, join screening, lockdown tools, and security monitoring solutions.

---

## 📋 Contents

* [Category Overview](#-category-overview)
* [Common Features](#-common-features)
* [Recommended Bots](#-recommended-bots)
* [Bots in This Category](#-bots-in-this-category)
* [Comparison Table](#-comparison-table)
* [Choosing the Right Bot](#-choosing-the-right-bot)
* [Best Use Cases](#-best-use-cases)
* [Recommended Stacks](#-recommended-stacks)
* [Related Categories](#-related-categories)
* [Additional Resources](#-additional-resources)

---

## 📌 Category Overview

### What this category covers

Bots in this category provide one or more of the following:

* Anti-raid protection
* Anti-nuke systems
* Verification systems
* Anti-alt detection
* Join screening
* Security monitoring
* Emergency lockdown tools
* Suspicious account detection
* Permission abuse prevention

### What qualifies for inclusion

A bot belongs in this category if it:

* Primarily focuses on server security
* Helps prevent or mitigate attacks
* Is actively maintained
* Provides meaningful security features beyond basic moderation

### What does NOT qualify

The following do not belong in this category:

* General moderation bots
* Logging-only bots
* Utility bots with minor security features
* Private or invite-only security systems
* Abandoned projects

---

## ✨ Common Features

| Feature               | Description                                          |
| --------------------- | ---------------------------------------------------- |
| Anti-Raid             | Detects and blocks mass joins or coordinated attacks |
| Anti-Nuke             | Prevents destructive administrative actions          |
| Verification          | Verifies users before granting access                |
| Alt Detection         | Identifies suspicious alternate accounts             |
| Lockdown              | Restricts server activity during emergencies         |
| Security Logging      | Tracks high-risk events                              |
| Join Screening        | Evaluates new members before entry                   |
| Permission Monitoring | Detects dangerous permission changes                 |

---

## 🏆 Recommended Bots

| Recommendation              | Bot                                            | Reason                                  |
| --------------------------- | ---------------------------------------------- | --------------------------------------- |
| Best Overall                | [Wick](../bots/security/wick.md)               | Industry-standard protection suite      |
| Best Verification           | [Captcha.bot](../bots/security/captcha-bot.md) | Strong user verification system         |
| Best Anti-Alt               | [Beemo](../bots/security/beemo.md)             | Specialized alt-account detection       |
| Best Free Option            | [Captcha.bot](../bots/security/captcha-bot.md) | Effective protection without complexity |
| Best for Large Servers      | [Wick](../bots/security/wick.md)               | Proven at massive scale                 |
| Best for Public Communities | [Beemo](../bots/security/beemo.md)             | Strong onboarding protection            |

---

## 🤖 Bots in This Category

### [Wick](../bots/security/wick.md)

One of Discord's most respected security bots. Wick specializes in anti-nuke protection, anti-raid systems, lockdown tools, and advanced threat prevention. It is commonly used by large public communities and professional Discord networks.

**Best for:** Large communities and high-security environments.
**Free tier:** Available.
**Dashboard:** Yes.
**Open source:** No.

---

### [Captcha.bot](../bots/security/captcha-bot.md)

A verification-focused security bot that uses CAPTCHA challenges to prevent automated joins and bot attacks. Widely used by public communities seeking simple but effective protection.

**Best for:** Verification and join screening.
**Free tier:** Generous.
**Dashboard:** Yes.
**Open source:** No.

---

### [Beemo](../bots/security/beemo.md)

A security bot focused on identifying suspicious accounts, alternate accounts, and risky members before they gain access to a community.

**Best for:** Anti-alt protection.
**Free tier:** Available.
**Dashboard:** Yes.
**Open source:** No.

---

### [Double Counter](../bots/security/double-counter.md)

A specialized anti-alt bot that attempts to detect users joining from multiple accounts. Frequently used in gaming communities, giveaways, and public servers where alt abuse is common.

**Best for:** Alternative account prevention.
**Free tier:** Available.
**Dashboard:** Limited.
**Open source:** No.

---

## 📊 Comparison Table

| Bot            | Verification | Anti-Raid | Anti-Nuke | Dashboard | Best For            |
| -------------- | :----------: | :-------: | :-------: | :-------: | ------------------- |
| Beemo          |       ✅      |     ⚠️    |     ❌     |     ✅     | Anti-alt detection  |
| Captcha.bot    |       ✅      |     ⚠️    |     ❌     |     ✅     | Verification        |
| Double Counter |      ⚠️      |     ❌     |     ❌     |     ⚠️    | Alt prevention      |
| Wick           |       ✅      |     ✅     |     ✅     |     ✅     | Full security suite |

**Key:** ✅ Supported · ⚠️ Partial/Limited · ❌ Not Primary Focus

---

## 🎯 Choosing the Right Bot

| If your priority is...    | Consider       |
| ------------------------- | -------------- |
| Maximum protection        | Wick           |
| User verification         | Captcha.bot    |
| Alt-account prevention    | Beemo          |
| Gaming community security | Double Counter |
| Large public server       | Wick           |
| Easy deployment           | Captcha.bot    |

### Key Questions

**Do you regularly experience raids?**
→ Wick should be your first choice.

**Do you primarily need verification?**
→ Captcha.bot is usually sufficient.

**Do alt accounts cause problems?**
→ Beemo or Double Counter.

**Do you manage a large public community?**
→ Combine Wick and Captcha.bot.

---

## 📋 Best Use Cases

### Public Communities

Strong verification and anti-raid systems prevent abuse from open invites.

### Gaming Servers

Alt-account prevention helps protect rankings, giveaways, and tournaments.

### Creator Communities

Verification systems reduce spam and fake accounts.

### Large Networks

Advanced anti-nuke protection protects staff mistakes and malicious actions.

---

## ⚙️ Recommended Stacks

<details>
<summary><b>Public Community Stack</b></summary>

| Role         | Bot         |
| ------------ | ----------- |
| Security     | Wick        |
| Verification | Captcha.bot |
| Moderation   | Carl-bot    |
| Logging      | Logger      |

</details>

<details>
<summary><b>Gaming Server Stack</b></summary>

| Role       | Bot            |
| ---------- | -------------- |
| Security   | Beemo          |
| Anti-Alt   | Double Counter |
| Moderation | Dyno           |
| Community  | Arcane         |

</details>

---

## 🔗 Related Categories

| Category                        | Why it is relevant                           |
| ------------------------------- | -------------------------------------------- |
| [🛡️ Moderation](moderation.md) | Security and moderation work together        |
| [📜 Logging](logging.md)        | Security events should be recorded           |
| [🎫 Tickets](tickets.md)        | Appeals and security reviews                 |
| [📈 Community](community.md)    | Secure onboarding improves community quality |

---

## 📚 Additional Resources

* Discord Safety Center
* Discord Community Guidelines
* Discord Moderator Academy

---

## 📝 Contributor Notes

### Adding a Security Bot

* Security must be the bot's primary purpose.
* Verify invite links regularly.
* Confirm the bot is actively maintained.
* Avoid listing abandoned anti-raid projects.

### Category-Specific Notes

* Security claims should never be exaggerated.
* If a feature cannot be verified, mark it as unknown.
* Recheck security features periodically because they evolve rapidly.

---

<!--
category    : security
emoji       : 🔒
bot_count   : 4
last_updated: 2026-05-31
maintainer  : Awesome Discord Bots
template_ver: 1.0.0
-->

---

> 📂 [Main Directory](../README.md) · [All Categories](../README.md#-categories) · [Contributing](../CONTRIBUTING.md)
