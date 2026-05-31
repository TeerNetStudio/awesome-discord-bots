# 🤝 Contributing to Awesome Discord Bots

First off — thank you for wanting to contribute. This project grows through community effort, and every addition matters, whether it's a new bot, a fixed typo, or an improved description.

This guide is written for beginners. If you've never contributed to an open-source project before, you're in the right place.

---

## 📋 Table of Contents

- [Before You Start](#-before-you-start)
- [How to Add a Bot](#-how-to-add-a-bot)
- [How to Update Existing Information](#-how-to-update-existing-information)
- [Pull Request Guidelines](#-pull-request-guidelines)
- [Markdown Formatting Guidelines](#-markdown-formatting-guidelines)
- [Quality Standards](#-quality-standards)
- [What Gets Rejected](#-what-gets-rejected)
- [Need Help?](#-need-help)

---

## 🚦 Before You Start

**Check these first — they'll save you time:**

1. **Is the bot already listed?** Search the [`bots/`](bots/) folder and the relevant [category page](categories/) before adding.
2. **Does the bot meet the criteria?** Read the [Quality Standards](#-quality-standards) section below.
3. **Is the invite link working?** Test it in a browser before submitting.
4. **Is this your first GitHub contribution?** That's completely fine — the steps below will guide you through everything.

---

## ➕ How to Add a Bot

### Step 1 — Fork the repository

Click the **Fork** button in the top-right corner of this page. This creates your own copy of the project.

### Step 2 — Clone your fork

```bash
git clone https://github.com/YOUR-USERNAME/awesome-discord-bots.git
cd awesome-discord-bots
```

### Step 3 — Create a new branch

Name your branch after the bot you're adding:

```bash
git checkout -b add-carl-bot
```

### Step 4 — Copy the bot template

Copy [`../templates/bot-template.mdbot-template.md`](../templates/bot-template.mdbot-template.md) into the correct category folder:

```
bots/{category}/{bot-name}.md
```

**Example:**
```
bots/moderation/carl-bot.md
bots/security/wick.md
bots/tickets/ticket-tool.md
```

Use **lowercase** and **hyphens** only. No spaces, no capitals, no underscores.

### Step 5 — Fill in the template

Open your new file and complete every field. Do not leave fields blank — write `N/A` or `Unknown` if a field genuinely doesn't apply, but try to fill everything in.

A complete bot page looks like this:

```markdown
# 🤖 Carl-bot

> A powerful, flexible Discord bot for moderation, logging, and server management.

## Overview
Carl-bot is one of the most widely used moderation bots on Discord...

## Key Features
- Advanced automod with customizable filters
- Detailed logging for messages, roles, and joins
- Reaction roles and embeds
- Custom commands and tags

## Pricing
| Plan | Price | Limits |
|------|-------|--------|
| Free | $0 | Up to 15 reaction role messages |
| Premium | $5/mo | Unlimited |

## Dashboard
Yes — [carl.gg](https://carl.gg)

## Permissions Required
- Manage Messages
- Manage Roles
- Read Message History
- View Audit Log

## Links
- [Invite](https://discord.com/oauth2/authorize?...)
- [Website](https://carl.gg)
- [Documentation](https://docs.carl.gg)
- [Support Server](https://discord.gg/...)

## Last Verified
2025-01-01
```

### Step 6 — Add the bot to its category page

Open [`categories/{category}.md`](categories/) and add a row to the bots table:

```markdown
| [Carl-bot](../bots/moderation/carl-bot.md) | Automod, logging, reaction roles | ✅ Free tier | ✅ Yes |
```

Keep the table sorted alphabetically by bot name.

### Step 7 — Commit and push

```bash
git add .
git commit -m "Add Carl-bot to moderation"
git push origin add-carl-bot
```

### Step 8 — Open a Pull Request

Go to your fork on GitHub and click **Compare & pull request**. Fill in the PR template — describe what bot you're adding and confirm the checklist.

---

## ✏️ How to Update Existing Information

Found outdated info, a broken link, or a wrong price? Please fix it.

1. Fork and clone the repo (same as Steps 1–2 above)
2. Create a branch: `git checkout -b update-wick-pricing`
3. Make your changes in the relevant file
4. Update the `Last Verified` date at the bottom of the bot page to today
5. Commit with a clear message: `Update Wick pricing — premium now $4.99/mo`
6. Open a Pull Request describing what changed and why

**Good commit messages:**
```
✅ Fix broken invite link for Ticket Tool
✅ Update Arcane free tier limits
✅ Correct TempVoice dashboard URL
```

**Avoid vague messages like:**
```
❌ Update file
❌ Fix stuff
❌ Changes
```

---

## 📬 Pull Request Guidelines

### One change per PR

Keep PRs focused. One bot per PR. One fix per PR. This makes reviews faster and easier.

| ✅ Good | ❌ Avoid |
|--------|---------|
| Add one new bot | Add 5 bots in one PR |
| Fix one broken link | Mix bot additions with formatting changes |
| Update one bot's pricing | Restructure multiple category files at once |

### PR title format

```
Add [Bot Name] to [Category]
Update [Bot Name] — [what changed]
Fix broken link in [Bot Name]
```

### PR checklist

Before submitting, confirm all of the following:

- [ ] Bot is not already listed in the directory
- [ ] Bot meets all [Quality Standards](#-quality-standards)
- [ ] Bot page uses the official [template](../templates/bot-template.mdbot-template.md)
- [ ] All links have been tested and work
- [ ] Bot is added to the correct category page
- [ ] File is named in `kebab-case.md` format
- [ ] `Last Verified` date is set to today
- [ ] No spelling or formatting errors

---

## 📝 Markdown Formatting Guidelines

Consistent formatting makes the directory easier to read and maintain. Follow these rules:

### File naming
```
✅ carl-bot.md
✅ ticket-tool.md
✅ dank-memer.md

❌ CarlBot.md
❌ ticket_tool.md
❌ DankMemer.md
```

### Headings
Use headings in order — don't skip levels:
```markdown
✅ # Title → ## Section → ### Subsection
❌ # Title → ### Subsection  (skipped ##)
```

### Links
Always use descriptive link text — never raw URLs in body text:
```markdown
✅ [Carl-bot Dashboard](https://carl.gg)
❌ https://carl.gg
❌ [Click here](https://carl.gg)
```

### Tables
Keep tables aligned and consistent. Always include a header separator row:
```markdown
| Bot | Feature | Free Tier |
|-----|---------|-----------|
| Carl-bot | Automod | ✅ |
```

### Checkmarks
Use these consistently across all bot pages:

| Symbol | Meaning |
|--------|---------|
| ✅ | Yes / Available / Supported |
| ❌ | No / Not available |
| ⚠️ | Partial / Limited / With conditions |

### Blank lines
Always leave a blank line before and after headings, tables, and code blocks. This prevents rendering issues on GitHub.

### No trailing spaces
Remove trailing whitespace at the end of lines.

---

## 🏅 Quality Standards

Every bot listed must meet **all** of the following:

| Standard | Requirement |
|----------|-------------|
| **Active** | Updated or confirmed working within the last 12 months |
| **Invite works** | The bot's invite link resolves and functions |
| **Documented** | Has a website, docs page, or active support server |
| **Clear purpose** | Serves a specific, defined use case |
| **Discord ToS compliant** | Does not violate [Discord's Terms of Service](https://discord.com/terms) |
| **Not a personal bot** | Publicly available for any server to add |

### What makes a strong submission

Beyond the minimum criteria, strong bot pages include:

- A clear, honest description (not copied from the bot's own marketing)
- Accurate pricing — including what the free tier actually allows
- A full permissions list so server owners can make informed decisions
- A working support server or documentation link
- A realistic `Last Verified` date

---

## 🚫 What Gets Rejected

To keep the directory high quality, the following will not be accepted:

- Bots with broken or expired invite links
- Bots not updated in over 12 months with no sign of activity
- Personal or private bots not available to the public
- Duplicate entries
- Bot pages with missing required fields
- PRs that modify multiple unrelated files
- Submissions that appear to be promotional or paid placements

If your PR is rejected, the reviewer will explain why. Most rejections can be fixed and resubmitted.

---

## 💬 Need Help?

**Not sure if a bot qualifies?** Open an [Issue](https://github.com/TeerNetStudio/awesome-discord-bots/issues) and ask before spending time on the PR.

**Something broken or confusing in this guide?** Open an Issue for that too — improving the contributor experience is always welcome.

**First time using Git or GitHub?** These free resources are a great start:
- [GitHub's official "Hello World" guide](https://docs.github.com/en/get-started/quickstart/hello-world)
- [How to make your first Pull Request](https://opensource.guide/how-to-contribute/#opening-a-pull-request)

---

*Thank you for helping make this the best Discord bot directory on GitHub.* 🤖