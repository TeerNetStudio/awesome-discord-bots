# 🔒 Security Bots

> Back to [Main Directory](../README.md)

Security bots protect your server from threats that moderation bots aren't designed to stop — coordinated raids, mass-join floods, permission abuse, bot nukes, and account takeovers.

Where moderation bots react to individual user behavior, security bots monitor patterns, detect threats in real time, and respond faster than any human moderator can. For servers of any meaningful size, a dedicated security bot isn't optional — it's the difference between surviving a raid and losing your community in minutes.

This page covers the best security bots available, what they protect against, and how to choose the right one for your server.

---
## ⚡ Quick Picks

| Need | Recommended Bot |
|--------|--------|
| Best Overall | Wick |
| Best Verification | Captcha.bot |
| Best Anti-Nuke | Wick |
| Best For Beginners | Carl-bot |
| Best Layered Setup | Wick + Captcha.bot |
---

## 📋 Contents

- [What to Look For](#-what-to-look-for)
- [Threat Glossary](#-threat-glossary)
- [Bots in This Category](#-bots-in-this-category)
- [Comparison Table](#-comparison-table)
- [Recommendations](#-recommendations)

---

## 🔍 What to Look For

**Anti-raid protection** — Can it detect and lock down a server during a coordinated mass-join attack? How fast does it respond?

**Anti-nuke protection** — If a compromised or rogue admin starts mass-deleting channels or banning members, can the bot detect and revert it?

**Alt account detection** — Can it identify newly created accounts joining your server, which are commonly used in raids?

**Verification gates** — Does it support CAPTCHA or reaction-based verification to filter bots and raiders before they reach your community?

**Audit and alert system** — Does it log suspicious actions and alert staff immediately, with enough context to act fast?

**Permission hierarchy protection** — Can it monitor and lock dangerous permission changes (e.g. someone granting themselves Administrator)?

**Whitelist system** — Can trusted admins and bots be excluded from restrictions so false positives don't disrupt normal operations?

---

## ⚠️ Threat Glossary

Understanding what you're protecting against helps you configure these bots correctly.

| Threat | What it means |
|--------|--------------|
| **Raid** | A coordinated attack where many accounts join simultaneously to spam, harass, or disrupt |
| **Nuke** | A malicious admin or compromised account mass-deletes channels, roles, or bans members |
| **Alt account** | A secondary account created to evade a ban or bypass account-age restrictions |
| **Token grab** | Malware or a malicious bot attempts to steal Discord user tokens for account takeover |
| **Mass mention** | Spamming `@everyone` or mass-mentioning roles to harass or trigger notifications at scale |
| **Phishing** | Deceptive links shared in your server designed to steal credentials or spread malware |
| **Webhook abuse** | Exploiting or spamming Discord webhooks to post malicious or unwanted content |
| **Permission escalation** | A user or bot gaining higher permissions than intended, often as a precursor to a nuke |

---

## 🤖 Bots in This Category

### [Wick](../bots/security/wick.md)

The most widely trusted dedicated security bot on Discord. Wick specializes in anti-raid, anti-nuke, and permission-abuse detection with a response time measured in milliseconds. It monitors everything from suspicious join patterns to admin permission changes, and its whitelist system is reliable enough for servers with complex staff structures.

Wick is the closest thing to an industry standard for Discord server security. Most large communities run it.

**Best for:** Any server that takes security seriously. Essential for servers with 500+ members or a history of raids.
**Free tier:** Available with core features.
**Dashboard:** Yes

---

### [Beemo](../bots/security/beemo.md)

A focused anti-bot and verification bot. Beemo's primary strength is detecting and removing selfbots, user-bots, and automated accounts — the kind that flood servers during raids or are used for spam campaigns. Its verification system is lightweight and low-friction for real users.

**Best for:** Servers that frequently deal with bot raids or want a clean, simple verification layer.
**Free tier:** Available.
**Dashboard:** Yes

---

### [Shieldcord](../bots/security/shieldcord.md)

A dedicated anti-raid bot with a focus on join-flood detection and lockdown automation. When a raid is detected, Shieldcord can automatically pause invites, enable verification, or lock channels — then alert staff with a summary of what happened and who joined.

**Best for:** Servers in public-facing communities or those that have experienced raid attacks before.
**Free tier:** Available.
**Dashboard:** Yes

---

### [Nobibot](../bots/security/nobibot.md)

An anti-nuke and anti-abuse bot that focuses specifically on protecting server structure — channels, roles, webhooks, and admin permissions. If a compromised admin or rogue bot starts making destructive changes, Nobibot detects the pattern and can automatically remove permissions or reverse actions.

**Best for:** Servers with large staff teams where the risk of internal compromise is real.
**Free tier:** Available.
**Dashboard:** Limited

---

### [Captcha.bot](../bots/security/captcha-bot.md)

A dedicated verification bot that requires new members to complete a CAPTCHA before accessing the server. Simple in scope, but highly effective at filtering out automated accounts and basic raid bots that can't solve visual challenges.

**Best for:** Servers that want a low-maintenance, always-on verification gate for new members.
**Free tier:** Available with limits.
**Dashboard:** Yes

---

### [Carl-bot](../bots/moderation/carl-bot.md)

Primarily listed under [Moderation](moderation.md), Carl-bot includes automod features — anti-spam, anti-invite, mass mention detection — that overlap with basic security. It is not a replacement for a dedicated security bot, but for small servers not yet needing Wick, Carl-bot's automod handles the most common threats adequately.

**Best for:** Small servers as a lightweight first line of defence before graduating to Wick.
**Free tier:** Generous.
**Dashboard:** Yes

---

## 📊 Comparison Table

| Bot | Anti-Raid | Anti-Nuke | Alt Detection | Verification | Permission Watch | Dashboard | Free Tier |
|-----|:---------:|:---------:|:-------------:|:------------:|:----------------:|:---------:|:---------:|
| [Wick](../bots/security/wick.md) | ✅ Advanced | ✅ Advanced | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes |
| [Beemo](../bots/security/beemo.md) | ✅ Good | ❌ No | ✅ Advanced | ✅ Yes | ❌ No | ✅ Yes | ✅ Yes |
| [Shieldcord](../bots/security/shieldcord.md) | ✅ Advanced | ⚠️ Basic | ✅ Yes | ✅ Yes | ⚠️ Basic | ✅ Yes | ✅ Yes |
| [Nobibot](../bots/security/nobibot.md) | ⚠️ Basic | ✅ Advanced | ⚠️ Basic | ❌ No | ✅ Advanced | ⚠️ Limited | ✅ Yes |
| [Captcha.bot](../bots/security/captcha-bot.md) | ⚠️ Indirect | ❌ No | ✅ Yes | ✅ Advanced | ❌ No | ✅ Yes | ⚠️ Limited |
| [Carl-bot](../bots/moderation/carl-bot.md) | ⚠️ Basic | ❌ No | ❌ No | ❌ No | ❌ No | ✅ Yes | ✅ Generous |

**Key:** ✅ Available / supported — ⚠️ Partial or limited — ❌ Not available

---
## 🚫 Common Security Mistakes

- Giving Administrator permission to every bot
- Not using a verification gate
- Not configuring whitelists
- Relying on a single security bot
- Ignoring permission changes
---

## 💡 Recommendations

### 🟢 Small server (under 100 members)?

**Carl-bot's automod** is enough to start. Configure anti-spam, anti-invite, and mass-mention filters. You don't need a dedicated security bot yet, but set one up before you grow — it's much harder to configure security correctly during an active raid than before one.

---

### 🟡 Growing server (100–500 members)?

Add **Wick** alongside your moderation bot.

At this size you're visible enough to attract opportunistic raids. Wick's default configuration covers the most common threats out of the box — anti-raid lockdown, new account filtering, and permission change alerts. Spend 30 minutes configuring its whitelist to include your other bots and senior staff.

**Suggested stack:**
- Carl-bot — moderation and logging
- Wick — security and raid protection
- Captcha.bot — new member verification gate

---

### 🔴 Large or public server (500+ members)?

Run **Wick as your primary security bot** with a fully reviewed configuration.

At this scale, you are a target. Large public servers, gaming communities, and politically active servers experience raids regularly. Wick's advanced configuration — raid thresholds, account age filters, permission lock profiles, and action logging — should be reviewed by whoever manages your server infrastructure.

**Suggested stack:**
- Carl-bot or YAGPDB — moderation
- Wick — primary security layer
- Beemo — secondary alt and bot detection
- Captcha.bot — verification gate

---

### 🔵 Large server with a big staff team?

Add **Nobibot** to protect against internal threats.

External raids are the visible risk. Internal compromise — a staff account getting hijacked, a rogue moderator, a poorly permissioned bot — is the less visible but equally real one. Nobibot monitors permission changes and structural actions (channel deletions, role changes) and alerts you when something doesn't look right from the inside.

---

### ⚡ Experienced frequent raids or attacks?

Layer your defences. No single bot covers every attack vector. The most resilient servers combine:

| Layer | Purpose | Bot |
|-------|---------|-----|
| Join protection | Stop raiders before they enter | Captcha.bot + Wick |
| Behaviour detection | Stop active attacks in real time | Wick |
| Internal protection | Stop nuke attempts from inside | Nobibot |
| Logging and evidence | Record everything for recovery | Carl-bot logging |

Security in depth — multiple overlapping layers — is the standard approach for communities that can't afford downtime.

---

> 📂 Back to [Main Directory](../README.md) · See also: [🛡️ Moderation](moderation.md) · [✅ Verification](verification.md) · [📜 Logging](logging.md)