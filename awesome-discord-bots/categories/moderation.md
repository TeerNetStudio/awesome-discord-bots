# 🛡️ Moderation Bots

> Back to [Main Directory](../README.md)

Moderation bots help server owners and staff enforce rules, manage members, and maintain a healthy community — automatically and at scale.

A good moderation bot handles the work that human moderators can't do 24/7: catching spam the moment it's posted, logging every action for accountability, warning users consistently, and escalating behavior before it becomes a serious problem.

This page covers the best moderation bots available, how they compare, and which ones suit different server sizes and needs.

---

## ⚡ Quick Picks

| Need | Bot |
|--------|--------|
| Best Overall | Carl-bot |
| Best Free | YAGPDB |
| Best Dashboard | Carl-bot |
| Best Security | Wick |
| Best For Beginners | Dyno |
| Most Advanced | YAGPDB |

---

## 📋 Contents

- [What to Look For](#-what-to-look-for)
- [Bots in This Category](#-bots-in-this-category)
- [Comparison Table](#-comparison-table)
- [Recommendations](#-recommendations)
- [Feature Glossary](#-feature-glossary)

---

## 🔍 What to Look For

Not all moderation bots are equal. Before choosing one, consider:

**Automod** — Can it automatically detect and act on spam, links, slurs, and mass mentions without human input?

**Logging** — Does it record moderation actions, message edits, deletions, and member joins in a readable format?

**Punishment system** — Does it support warnings, mutes, kicks, bans, and temporary bans? Can punishments escalate automatically after a threshold?

**Dashboard** — Can staff configure the bot through a web interface, or only through commands?

**Free tier limits** — Some bots lock essential features behind a paywall. Know what you're getting before you build around a bot.

**Slash command support** — Modern Discord bots use slash commands (`/ban`, `/warn`). Prefix-only bots (`!ban`) are a sign of age.

---

## 🤖 Bots in This Category

### [Carl-bot](../bots/moderation/carl-bot.md)

One of the most widely used and trusted moderation bots on Discord. Carl-bot covers automod, detailed logging, reaction roles, custom commands, and a web dashboard — all on a generous free tier. It's the closest thing to a complete moderation solution in a single bot.

**Best for:** Servers of any size. Recommended as a first moderation bot.
**Free tier:** Generous — most features available without paying.
**Dashboard:** Yes — [carl.gg](https://carl.gg)

---

### [Dyno](../bots/moderation/dyno.md)

A long-established moderation bot with a clean dashboard and solid core features. Dyno handles automod, logging, and a warning system well, but some advanced features require a premium subscription. Still a reliable choice for communities that want a simple, proven setup.

**Best for:** Small to medium servers wanting a familiar, easy-to-configure bot.
**Free tier:** Available with some feature restrictions.
**Dashboard:** Yes

---

### [YAGPDB](../bots/moderation/yagpdb.md)

Yet Another General Purpose Discord Bot — the name undersells it. YAGPDB is one of the most powerful and flexible moderation bots available, with deep automod rules, custom command scripting, and detailed logging. The learning curve is steeper than Carl-bot or Dyno, but the ceiling is much higher.

**Best for:** Technical server owners and large communities with complex moderation needs.
**Free tier:** Fully free — no paid plans.
**Dashboard:** Yes

---

### [GiselleBot(Not Recommended)](../bots/moderation/gisellebot.md)

A feature-rich moderation bot with strong logging, a clean warning system, and good slash command support. GiselleBot is actively developed and has grown into a reliable choice for servers wanting a modern moderation stack.

**Best for:** Medium to large servers wanting modern features and active development.
**Free tier:** Available.
**Dashboard:** Yes

---

### [Combot](../bots/moderation/combot.md)

One of the oldest moderation bots on the platform with deep analytics and anti-spam systems. Combot's analytics features — activity graphs, message statistics, top members — set it apart from pure moderation tools. Well suited to servers where data matters.

**Best for:** Servers that want moderation combined with community analytics.
**Free tier:** Available with limits.
**Dashboard:** Yes

---

### [Wick](../bots/security/wick.md)

Primarily listed under [Security](security.md), Wick is included here because its automod and raid protection features overlap significantly with moderation. Many servers run Wick alongside Carl-bot — Wick handles protection and raids, Carl-bot handles day-to-day moderation.

**Best for:** Servers needing both moderation and active raid/nuke protection.
**Free tier:** Available.
**Dashboard:** Yes

---

## 📊 Comparison Table

| Bot | Automod | Logging | Warning System | Dashboard | Slash Commands | Free Tier | Open Source |
|-----|:-------:|:-------:|:--------------:|:---------:|:--------------:|:---------:|:-----------:|
| [Carl-bot](../bots/moderation/carl-bot.md) | ✅ Advanced | ✅ Detailed | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Generous | ❌ No |
| [Dyno](../bots/moderation/dyno.md) | ✅ Good | ✅ Good | ✅ Yes | ✅ Yes | ✅ Yes | ⚠️ Limited | ❌ No |
| [YAGPDB](../bots/moderation/yagpdb.md) | ✅ Advanced | ✅ Detailed | ✅ Yes | ✅ Yes | ⚠️ Partial | ✅ Full | ✅ Yes |
| [GiselleBot](../bots/moderation/gisellebot.md) | ✅ Good | ✅ Detailed | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | ❌ No |
| [Combot](../bots/moderation/combot.md) | ✅ Good | ⚠️ Basic | ✅ Yes | ✅ Yes | ⚠️ Partial | ⚠️ Limited | ❌ No |
| [Wick](../bots/security/wick.md) | ✅ Advanced | ✅ Yes | ⚠️ Limited | ✅ Yes | ✅ Yes | ✅ Yes | ❌ No |

**Key:** ✅ Available / supported — ⚠️ Partial or limited — ❌ Not available

---

## 💡 Recommendations

### 🟢 New to Discord moderation?

Start with **Carl-bot**.

It covers everything a new server needs — automod, logging, a warning system, and reaction roles — through a clean web dashboard. The free tier is genuinely usable without hitting paywalls on core features. Most experienced server owners have used it at some point; the community documentation and guides are extensive.

**Suggested setup:**
1. Invite Carl-bot and connect it to your server via [carl.gg](https://carl.gg)
2. Set up a logging channel for moderation actions and message deletions
3. Configure automod filters for spam, mass mentions, and invite links
4. Add a warning threshold — e.g. 3 warnings = automatic mute

---

### 🟡 Running a medium server (100–1,000 members)?

Use **Carl-bot** for day-to-day moderation and add **Wick** for protection.

At this scale, raid attempts and targeted spam become more likely. Carl-bot handles the routine work; Wick adds a protection layer that automatically responds to raids, nukes, and suspicious join patterns.

---

### 🔴 Running a large or complex server (1,000+ members)?

Consider **YAGPDB** as your primary moderation bot, or use **Carl-bot** with a fully configured automod ruleset.

YAGPDB's custom command scripting allows for moderation logic that no other free bot can match — conditional punishments, complex filters, role-based permissions, and automated workflows. It takes time to configure correctly but pays off for large communities with specific needs.

**Complement with:** Wick (security), Statbot (analytics), Ticket Tool (support).

---

### 🔵 Want moderation + community data in one?

Try **Combot** if server analytics matter to your team. It combines anti-spam with activity tracking, giving moderators context (is this user normally active? did behavior change recently?) that pure moderation bots don't provide.

---

## 📖 Feature Glossary

New to Discord moderation? Here's what the key terms mean:

| Term | What it means |
|------|--------------|
| **Automod** | Automatic rule enforcement — the bot acts without a moderator needing to type a command |
| **Logging** | A record of actions: who was banned, what messages were deleted, who changed roles |
| **Warning system** | A structured way to issue warnings that track per-user and can trigger automatic escalation |
| **Mute** | Prevents a user from sending messages, either temporarily or indefinitely |
| **Slowmode** | Forces a delay between messages in a channel — useful during high-traffic moments |
| **Raid protection** | Automatic detection and response to coordinated join floods or mass spam |
| **Dashboard** | A website where you configure the bot using a visual interface instead of commands |
| **Prefix command** | A command triggered by a symbol (e.g. `!ban`) — older style, being phased out |
| **Slash command** | A command triggered with `/` — the current Discord standard, with autocomplete support |

---

> 📂 Back to [Main Directory](../README.md) · See also: [🔒 Security](security.md) · [📜 Logging](logging.md) · [✅ Verification](verification.md)