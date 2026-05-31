# 🎫 Ticket Bots

> Back to [Main Directory](../README.md)

Ticket bots turn your Discord server into a structured support system — giving members a private, organized way to ask for help, report issues, or submit requests without cluttering public channels.

Without a ticket system, support happens in public channels, DMs that staff can't oversee, or gets lost entirely. Ticket bots solve this by creating private threads or channels for each request, routing them to the right staff, and keeping a record of every conversation from open to close.

This page covers the best ticket bots available, how to choose the right one, and how to build a support system that actually works.

---

## 📋 Contents

- [Why Ticket Bots Matter](#-why-ticket-bots-matter)
- [What Good Ticket Systems Cover](#-what-good-ticket-systems-cover)
- [Bots in This Category](#-bots-in-this-category)
- [Comparison Table](#-comparison-table)
- [Recommendations](#-recommendations)
- [Common Ticket System Mistakes](#-common-ticket-system-mistakes)
- [Ticket System Glossary](#-ticket-system-glossary)

---

## 📌 Why Ticket Bots Matter

Public support channels have a fundamental problem: every member can see every conversation. Sensitive issues — ban appeals, payment disputes, personal reports, staff complaints — can't be handled transparently in front of the whole community.

Ticket bots solve this with three core benefits:

**Privacy** — Each ticket is a private channel or thread visible only to the member who opened it and the staff assigned to it. Sensitive conversations stay confidential.

**Organisation** — Instead of staff monitoring multiple public channels for questions, every request comes through one structured system. Tickets can be categorized, assigned, prioritized, and tracked from open to close.

**Accountability** — Every ticket creates a record: who opened it, when, what was discussed, and how it was resolved. Staff can't selectively ignore requests, and members can't claim their issue was never addressed.

---

## 🗃️ What Good Ticket Systems Cover

A well-configured ticket system handles more than just opening and closing channels. Look for these capabilities:

### Ticket Creation
- Panel-based creation — a message with buttons members click to open a ticket
- Category selection — members choose the type of request before opening (Support / Report / Appeal / Purchase)
- Opening questions — an optional form members fill in when creating a ticket, so staff have context before they even respond

### Ticket Management
- Ticket assignment — route tickets to specific staff members or roles
- Ticket claiming — staff can "claim" a ticket, signalling ownership and preventing double responses
- Priority levels — mark tickets as urgent, normal, or low priority
- Ticket transfer — hand off a ticket to a different staff member or department

### Ticket Closure
- Controlled closing — prevent members from closing their own tickets prematurely
- Close with reason — staff add a resolution note when closing
- Transcript generation — a text or HTML log of the full conversation, saved for records

### Staff Tools
- Internal notes — staff-only messages within a ticket that the member can't see
- Ticket statistics — how many tickets opened, average response time, tickets per staff member
- Reopen functionality — allow members to reopen a closed ticket within a set window

---

## 🤖 Bots in This Category

### [Ticket Tool](../bots/tickets/ticket-tool.md)

The most widely used dedicated ticket bot on Discord. Ticket Tool offers panel-based ticket creation, full transcript generation, customizable categories, staff claiming, and a clean web dashboard — all on a genuinely usable free tier. It handles the full ticket lifecycle reliably and is actively maintained.

For most servers, Ticket Tool is the default recommendation. It's the tool most Discord server owners have seen in action somewhere.

**Best for:** Any server size. The standard starting point for ticket systems.
**Free tier:** Available — core features accessible without premium.
**Dashboard:** Yes

---

### [Helper.gg](../bots/tickets/helper-gg.md)

A ticket bot built specifically for support-focused communities — software projects, game servers, and services where the support team handles high volumes. Helper.gg adds team management features — department routing, agent assignment, response templates — that go beyond what Ticket Tool offers at scale.

**Best for:** Support-heavy servers with organized staff teams and high ticket volumes.
**Free tier:** Available with limits.
**Dashboard:** Yes

---

### [Modmail](../bots/tickets/modmail.md)

A fundamentally different approach to tickets. Instead of creating channels inside your server, Modmail routes support conversations through the bot's DMs — members message the bot directly, and staff respond through a dedicated server the bot manages. This keeps your main server completely clean of ticket channels.

Open source and self-hostable, which means no dependency on a third-party service and full control over your data.

**Best for:** Communities that want DM-based support and are comfortable with self-hosting or a managed instance.
**Free tier:** Free if self-hosted. Managed hosting options available.
**Dashboard:** Limited — primarily command-based.

---

### [Ticketeer](../bots/tickets/ticketeer.md)

A modern ticket bot with a focus on clean UI and form-based ticket creation. Ticketeer's opening forms — where members answer questions before their ticket is created — reduce the back-and-forth of basic information gathering and help staff arrive at conversations with context already in hand.

**Best for:** Servers where ticket quality matters more than volume — structured intake, detailed forms, organized workflows.
**Free tier:** Available.
**Dashboard:** Yes

---

### [YAGPDB](../bots/moderation/yagpdb.md)

YAGPDB's ticket module is less polished than dedicated ticket bots but highly customizable through its scripting system. For servers already using YAGPDB for moderation, the built-in ticket system avoids adding another bot. For servers with specific workflows that off-the-shelf ticket bots can't accommodate, YAGPDB's flexibility is its advantage.

**Best for:** Servers already using YAGPDB that want to consolidate, or advanced users needing custom ticket workflows.
**Free tier:** Fully free.
**Dashboard:** Yes

---

### [Carl-bot](../bots/moderation/carl-bot.md)

Carl-bot includes basic ticket functionality as part of its broader feature set. It's not as capable as Ticket Tool for complex support systems, but for small servers that already use Carl-bot for moderation and want simple ticket creation without adding another bot, it's a reasonable starting point.

**Best for:** Small servers already on Carl-bot that want basic ticket support without a dedicated bot.
**Free tier:** Generous.
**Dashboard:** Yes

---

## 📊 Comparison Table

| Bot | Panel Support | Forms / Intake | Transcripts | Staff Claiming | Departments | Dashboard | Free Tier |
|-----|:------------:|:--------------:|:-----------:|:--------------:|:-----------:|:---------:|:---------:|
| [Ticket Tool](../bots/tickets/ticket-tool.md) | ✅ Yes | ⚠️ Basic | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes |
| [Helper.gg](../bots/tickets/helper-gg.md) | ✅ Yes | ✅ Advanced | ✅ Yes | ✅ Yes | ✅ Advanced | ✅ Yes | ⚠️ Limited |
| [Modmail](../bots/tickets/modmail.md) | ❌ DM-based | ❌ No | ✅ Yes | ✅ Yes | ⚠️ Basic | ⚠️ Limited | ✅ Free (self-hosted) |
| [Ticketeer](../bots/tickets/ticketeer.md) | ✅ Yes | ✅ Advanced | ✅ Yes | ✅ Yes | ⚠️ Basic | ✅ Yes | ✅ Yes |
| [YAGPDB](../bots/moderation/yagpdb.md) | ⚠️ Basic | ⚠️ Custom | ⚠️ Basic | ❌ No | ❌ No | ✅ Yes | ✅ Full |
| [Carl-bot](../bots/moderation/carl-bot.md) | ✅ Yes | ❌ No | ❌ No | ❌ No | ❌ No | ✅ Yes | ✅ Generous |

**Key:** ✅ Available / supported — ⚠️ Partial or limited — ❌ Not available

---

## 💡 Recommendations

### 🟢 Setting up tickets for the first time?

Start with **Ticket Tool**.

Create a single `#support` panel with two categories to begin — General Support and Report a Member. Keep it simple until you understand your ticket volume and what members actually ask for. A complex system nobody uses is worse than a simple one that works.

**Minimal first setup:**

| Step | Action |
|------|--------|
| 1 | Invite Ticket Tool and connect via its dashboard |
| 2 | Create a `#support` channel with a panel message |
| 3 | Add two categories: General Support, Report a Member |
| 4 | Set a staff role that can see and manage tickets |
| 5 | Enable transcripts — save them to a private `#ticket-logs` channel |

---

### 🟡 Medium server with a defined support team?

Add **category routing** and **staff claiming** in Ticket Tool.

At this stage you likely have different staff roles for different functions — moderators, admins, helpers. Route ticket categories to the right role automatically rather than having all staff see all tickets. Claiming prevents two staff members from responding to the same ticket simultaneously.

**Suggested categories by server type:**

| Server Type | Ticket Categories |
|-------------|------------------|
| Gaming | Support · Ban Appeal · Report · Bug Report |
| Community | General Help · Report a Member · Staff Application |
| Creator | Support · Collaboration · Business Enquiry |
| Developer | Bug Report · Feature Request · General Support |

---

### 🔴 High-volume support server?

Move to **Helper.gg** for department-level routing and agent management.

When ticket volume is high enough that "staff role sees all tickets" breaks down — when you have separate teams for billing, technical support, and moderation — Helper.gg's department and agent system handles the routing that Ticket Tool's free tier wasn't designed for.

Pair with a dedicated `#ticket-stats` log to review response times and staff workload weekly.

---

### 🔵 Want DM-based support with no ticket channels in your server?

Use **Modmail**.

Modmail creates a completely clean main server — no open ticket channels, no panels, no visible support infrastructure. Members DM the bot, staff respond from a separate management server. For communities where the presence of ticket channels feels cluttered or out of place (creative servers, small close-knit communities), this approach feels more personal.

Note: Modmail requires either self-hosting or using a third-party managed instance. It's the right choice if you're comfortable with that trade-off.

---

### ⚡ Need custom intake forms or workflows?

Use **Ticketeer** for structured intake or **YAGPDB** for fully custom logic.

Ticketeer's forms let you ask members specific questions when they open a ticket — "What is your username?", "Which product did you purchase?", "Describe the issue in detail." Staff arrive at every ticket with the information they need, rather than spending the first exchange gathering basics.

YAGPDB is the right choice only if you need ticket logic that no off-the-shelf bot supports — conditional routing, integration with other YAGPDB modules, or a fully scripted workflow.

---

## 🚫 Common Ticket System Mistakes

---

### 1. No transcript logging

When a ticket closes, the conversation disappears unless transcripts are enabled. Without them, you have no record of what was resolved, what was promised, or what a member was told.

**Fix:** Enable transcripts from day one. Save them to a private `#ticket-logs` channel visible only to admins.

---

### 2. Too many ticket categories at launch

A panel with eight categories confuses members and spreads your staff thin. Most of those categories will receive one ticket a month.

**Fix:** Launch with two or three categories. Add more only when a clear need emerges from actual ticket volume.

---

### 3. All staff can see all tickets

When every staff member sees every ticket, accountability disappears — no one owns anything, and tickets get ignored because everyone assumes someone else will handle it.

**Fix:** Use staff claiming, or route categories to specific roles. Every open ticket should have one named owner.

---

### 4. Members can close their own tickets

A member who opens a ticket to report another member shouldn't be able to close it before staff have reviewed it. A member in an escalating situation shouldn't be able to close their own ban appeal.

**Fix:** Configure ticket closure to require a staff action. Most ticket bots support this as a toggle.

---

### 5. No defined response time expectation

Members open tickets and wait. Without any indication of expected response time, they open duplicate tickets, post in public channels, or assume they're being ignored.

**Fix:** Add a response time statement to your panel message or your ticket opening embed. Even "We aim to respond within 24 hours" sets a realistic expectation.

---

### 6. Using tickets for everything

Ticket bots work well for complex, private, or sensitive issues. They're poor for quick questions, general help, or anything that benefits from community input. Routing everything through tickets creates unnecessary overhead.

**Fix:** Keep public help channels alongside your ticket system. Tickets are for issues that need privacy or dedicated staff attention — not every interaction.

---

### 7. Never reviewing closed tickets

Closed ticket transcripts are a goldmine of information: what your community struggles with, what questions get asked repeatedly, how your staff communicate under pressure. Most servers never look at them.

**Fix:** Review a sample of closed tickets monthly. Use patterns to improve your FAQ, your rules, or your staff training.

---

## 📖 Ticket System Glossary

| Term | What it means |
|------|--------------|
| **Panel** | An embedded message with buttons that members click to open a ticket |
| **Category** | A type of ticket — e.g. Support, Appeal, Report — that routes to the right staff |
| **Claiming** | A staff member taking ownership of a ticket so others know it's being handled |
| **Transcript** | A saved log of a ticket conversation, generated when the ticket closes |
| **Intake form** | Questions a member answers when opening a ticket, before the channel is created |
| **Routing** | Automatically directing tickets to the correct staff role based on category |
| **SLA** | Service Level Agreement — a defined target for response or resolution time |
| **Thread-based ticket** | A ticket created as a Discord thread rather than a full channel — lighter weight |
| **Channel-based ticket** | A ticket created as a private channel — more visible, easier for some staff workflows |

---

> 📂 Back to [Main Directory](../README.md) · See also: [🛡️ Moderation](moderation.md) · [📝 Forms](forms.md) · [📜 Logging](logging.md)