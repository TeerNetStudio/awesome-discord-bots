# 📋 Changelog

All notable changes to **Awesome Discord Bots** are documented here.

This project follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) conventions and [Semantic Versioning](https://semver.org/spec/v2.0.0.html) for releases.

> **Format:** `[version] - YYYY-MM-DD` · Changes grouped by type · Most recent release at the top.

---

## [Unreleased]

Changes staged for the next release. Merged to `main` but not yet versioned.

### ➕ Added
- _Nothing yet._

### 🔄 Changed
- _Nothing yet._

### 🔧 Fixed
- _Nothing yet._

### 🗑️ Removed
- _Nothing yet._

---
<!--
    RELEASE TEMPLATE — copy this block when cutting a new release.
    Replace X.Y.Z with version number and YYYY-MM-DD with release date.

## [X.Y.Z] - YYYY-MM-DD

### ➕ Added
#### Category Name
- Bot Name — one-line description of what it does

### 🔄 Changed
- File or section — description of change and reason

### 🔧 Fixed
- File or section — what was broken and how it was resolved

### 🗑️ Removed
- Bot Name from Category — reason for removal (e.g. abandoned, invite broken)

-->
---

## [0.1.0] - 2025-06-01

Initial public release of the Awesome Discord Bots directory.

### ➕ Added

#### 🛡️ Moderation
- **Carl-bot** — Full-featured moderation bot with automod, logging, and reaction roles
- **Dyno** — Established moderation and automod bot with a web dashboard
- **YAGPDB** — Advanced, fully free moderation bot with custom command scripting
- **Sapphire** — Modern moderation bot with slash command support
- **ProBot** — Feature-rich moderation and welcome bot with a visual dashboard

#### 🔒 Security
- **Wick** — Industry-standard anti-raid and anti-nuke protection bot
- **Captcha.bot** — CAPTCHA-based new member verification gate
- **Beemo** — Anti-bot and selfbot detection with lightweight verification

#### 🎫 Tickets
- **Ticket Tool** — Panel-based ticket system with transcripts and category routing
- **Helper.gg** — Support-focused ticket bot with department and agent management
- **Modmail** — DM-based support system, open source and self-hostable
- **Ticketeer** — Modern ticket bot with structured intake forms

#### 📈 Community
- **Arcane** — Leveling and engagement bot with a clean free tier
- **Tatsu** — Community engagement bot with leveling, currency, and profiles
- **Lurkr** — Leveling bot designed to replace MEE6 without paywalled features
- **MEE6** — Widely used leveling and moderation bot with a web dashboard

#### 📊 Analytics
- **Combot** — Server moderation and community analytics with activity graphs
- **Statbot** — Advanced server statistics and growth tracking dashboard

#### 📜 Logging
- **Logger** — Dedicated logging bot with detailed message and member event tracking

#### 🎧 Voice
- **TempVoice** — Join-To-Create voice channel management bot

### 📄 Documentation
- **README.md** — Main directory with categories, featured bots, and recommended stacks
- **CONTRIBUTING.md** — Beginner-friendly guide covering how to add bots, PR guidelines, and quality standards
- **CODE_OF_CONDUCT.md** — Contributor Covenant v2.1 with project-specific enforcement guidelines
- **SECURITY.md** — Policy for reporting malicious bots, scam links, and compromised invites
- **CHANGELOG.md** — This file
- **LICENSE** — MIT License
- **../templates/bot-template.mdbot-template.md** — Standardized template for new bot page submissions
- **../templates/bot-template.mdcategory-template.md** — Template for new category page submissions

### 📂 Category Pages
- **categories/moderation.md** — Moderation category overview with comparison table and recommendations
- **categories/security.md** — Security category overview with threat glossary and layered defence guide
- **categories/logging.md** — Logging category overview with audit trail guide and common mistakes
- **categories/tickets.md** — Tickets category overview with lifecycle guide and setup recommendations

### 🎨 Assets
- Repository banner added to `assets/banners/`
- Branding assets added to `assets/`

---

## 📖 Release Guidelines

This section defines what belongs in each changelog category. Follow these guidelines when contributing changelog entries or cutting a new release.

---

### ➕ Added
New content or features that did not exist in the previous release.

**Use for:**
- A new bot added to any category
- A new category page created
- A new documentation file added
- A new section added to an existing page (e.g. a comparison table added to a category)
- A new template added

**Examples:**
```
### ➕ Added
#### 🛡️ Moderation
- **GiselleBot** — Advanced moderation bot with detailed logging and slash command support

#### 📄 Documentation
- **guides/setup/how-to-setup-carl-bot.md** — Step-by-step Carl-bot setup guide with screenshots
```

---

### 🔄 Changed
Updates to existing content — corrections, improvements, restructures, or rewrites.

**Use for:**
- A bot's pricing, features, or description updated
- A category page restructured or expanded
- A template field added, removed, or renamed
- README sections rewritten or reorganised
- A bot recategorized from one category to another

**Examples:**
```
### 🔄 Changed
- **Ticket Tool** (tickets) — Updated pricing table; premium plan now $6/mo as of 2025-03
- **categories/moderation.md** — Comparison table expanded with Slash Commands column
- **../templates/bot-template.mdbot-template.md** — Added Tags field to Overview table
```

---

### 🔧 Fixed
Corrections to errors, broken links, outdated information, or formatting issues.

**Use for:**
- A broken invite link replaced
- An incorrect price corrected
- A broken internal link repaired
- A formatting error in a bot page or category page resolved
- A typo or factual error corrected

**Examples:**
```
### 🔧 Fixed
- **Wick** (security) — Invite link was returning 404; replaced with current link
- **categories/logging.md** — Corrected Logger dashboard status from ✅ to ⚠️ Limited
- **README.md** — Fixed broken anchor link in Contents navigation
```

---

### 🗑️ Removed
Content deleted from the repository.

**Use for:**
- A bot removed because it is abandoned, invite-broken, or violates Discord ToS
- A deprecated file or template removed
- A category merged into another and its standalone page removed
- An outdated section removed from a page

**Always include a reason** when removing a bot. This creates a record of why it was delisted, which is useful if it's ever re-submitted.

**Examples:**
```
### 🗑️ Removed
- **GroovyBot** (music) — Service permanently shut down by developer
- **OldModerationBot** (moderation) — Invite link broken for 60+ days; no developer response
- **../templates/bot-template.mdold-template.md** — Superseded by updated bot-template.md in v0.2.0
```

---

## 🔢 Versioning Guide

This repository uses **Semantic Versioning** adapted for a content directory:

| Version bump | When to use |
|-------------|-------------|
| `PATCH` (0.1.**1**) | Bug fixes, broken links, small corrections, minor wording changes |
| `MINOR` (0.**2**.0) | New bots added, new category pages, new documentation sections |
| `MAJOR` (**1**.0.0) | Structural overhaul, complete category restructure, major new features (e.g. website launch) |

> The project will move from `0.x.x` to `1.0.0` when the directory reaches a stable, comprehensive state across all core categories.

---

[Unreleased]: https://github.com/TeerNetStudio/awesome-discord-bots/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/TeerNetStudio/awesome-discord-bots/releases/tag/v0.1.0
