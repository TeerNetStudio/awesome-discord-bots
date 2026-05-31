# 📜 Logging Bots

> Back to [Main Directory](../README.md)

Logging is the part of server management most people set up last and regret not setting up first.

When a member gets banned and asks why, when a moderator's action is disputed, when someone claims a message "never existed" — your logs are the only objective record. Without them, you're managing a community on memory and trust alone. With them, you have evidence, accountability, and a trail that protects both your staff and your members.

This page covers the best logging bots available, what they track, how to use them effectively, and the mistakes that leave servers blind when they need answers most.

---

## 📋 Contents

- [Why Logging Matters](#-why-logging-matters)
- [What Good Logging Covers](#-what-good-logging-covers)
- [Audit Trails and Evidence Collection](#-audit-trails-and-evidence-collection)
- [Bots in This Category](#-bots-in-this-category)
- [Comparison Table](#-comparison-table)
- [Recommendations](#-recommendations)
- [Common Logging Mistakes](#-common-logging-mistakes)

---

## 📌 Why Logging Matters

Most Discord servers don't think about logging until something goes wrong. By then it's too late — the messages are deleted, the context is gone, and you're left with two conflicting accounts of what happened.

Logging solves three distinct problems:

**Accountability** — When every moderation action is recorded (who issued it, when, against whom, and why), staff can't act arbitrarily and can't deny actions they took. This protects members from abuse and protects you from false accusations against your team.

**Evidence** — Discord does not give server owners access to deleted messages, audit log history beyond 90 days, or a complete record of member activity. A logging bot fills that gap. When a member is harassing others through deleted messages, your logs prove it.

**Recovery** — When something goes wrong — a raid, a rogue moderator, a mistaken mass action — logs tell you exactly what happened, in what order, and by whom. Without them, recovery is guesswork.

---

## 🗂️ What Good Logging Covers

A comprehensive logging setup captures events across five areas:

### Message Logs
- Message edits — original and edited content, timestamp, channel
- Message deletions — content, author, channel, who deleted it if known
- Bulk message deletions — often a sign of a raid or a nuke attempt
- Pinned message changes

### Member Logs
- Joins and leaves — account creation date on join (critical for alt detection)
- Nickname changes
- Role additions and removals — who changed them and when
- Member bans, unbans, kicks, and timeouts — with reason if provided

### Channel and Server Logs
- Channel creation, deletion, and edits
- Role creation, deletion, and permission changes
- Server setting changes (name, icon, verification level)
- Invite creation and deletion

### Voice Logs
- Voice channel joins, leaves, and moves
- Server mutes and deafens
- Stage events

### Moderation Logs
- All actions taken by your moderation bot (warns, mutes, bans)
- Actions taken directly by staff through Discord's native tools
- Automod triggers and outcomes

---

## 🔍 Audit Trails and Evidence Collection

An audit trail is a chronological, tamper-resistant record of who did what and when. Discord provides a native audit log, but it has significant limitations: it only retains 90 days of history, doesn't log message content, and can be slow to update during high-activity events.

Logging bots extend this by capturing events in real time and storing them in dedicated channels that your team controls.

### Building a reliable audit trail

**Use dedicated log channels** — Separate channels for different log types (message logs, mod logs, join/leave logs) keep things readable. A single channel receiving every log event becomes unusable fast.

**Restrict access properly** — Log channels should be visible only to senior staff. If a moderator being investigated can read or delete the logs about their own actions, the logs are worthless as evidence.

**Log to a private category** — Create a staff-only category with channels like `#mod-log`, `#message-log`, `#join-log`, `#voice-log`, and `#server-log`. Deny read permissions for all roles except senior moderators and admins.

**Never delete log messages** — Treat log channels as append-only. Deleting or editing log messages to "clean things up" destroys the integrity of your records.

### Using logs as evidence

When a situation escalates — a ban appeal, a harassment report, a staff misconduct claim — logs let you reconstruct events accurately:

1. **Identify the timeframe** — When did the behavior start? When was it reported?
2. **Search the relevant log channels** — Message logs, mod logs, and join logs are usually the most relevant
3. **Screenshot with context** — Capture enough surrounding log entries to show the full picture, not just isolated messages
4. **Note the actors** — Discord IDs (not just usernames) are permanent; usernames change

> 💡 **Tip:** Discord IDs never change, even when a user changes their username or avatar. Always log and reference user IDs, not display names.

---

## 🤖 Bots in This Category

### [Carl-bot](../bots/moderation/carl-bot.md)

Carl-bot's logging module is one of the most complete available on a free tier. It covers message edits and deletions, member joins and leaves, role changes, channel edits, voice activity, and moderation actions — all configurable per event type and per channel. The web dashboard makes setup straightforward without needing to memorize commands.

**Best for:** Servers of any size wanting reliable, comprehensive logging without a dedicated logging bot.
**Free tier:** Generous — logging is available without premium.
**Dashboard:** Yes

---

### [Logger](../bots/logging/logger.md)

A bot built specifically for logging rather than general moderation. Logger focuses on depth over breadth — detailed message tracking, precise timestamps, user history, and clean embed formatting that makes logs easy to read at a glance. A good choice when logging is your primary requirement and you want a dedicated tool.

**Best for:** Servers that want a dedicated logging bot with clean, readable output.
**Free tier:** Available.
**Dashboard:** Limited

---

### [Dyno](../bots/moderation/dyno.md)

Dyno includes a solid logging module as part of its broader moderation toolkit. It covers the core events — message logs, member logs, moderation actions — with decent formatting. Not as detailed as Carl-bot's logging at the free tier, but suitable for servers already using Dyno for moderation who want to consolidate bots.

**Best for:** Servers already using Dyno for moderation that want integrated logging.
**Free tier:** Available with some restrictions.
**Dashboard:** Yes

---

### [GiselleBot](../bots/moderation/gisellebot.md)

GiselleBot includes detailed logging alongside its moderation features, with strong support for moderation action logs and member activity tracking. Its log output is well-formatted and consistent — useful for servers where log readability matters to a larger staff team.

**Best for:** Medium to large servers that want clean, well-formatted logs paired with active moderation.
**Free tier:** Available.
**Dashboard:** Yes

---

### [Combot](../bots/moderation/combot.md)

Combot approaches logging differently — it combines event logging with community analytics, giving you not just a record of what happened but patterns over time. Activity graphs, message volume, member growth, and top contributors are tracked alongside moderation events. Useful when you want logs and insights in the same tool.

**Best for:** Community managers who want logging combined with server analytics and activity data.
**Free tier:** Available with limits.
**Dashboard:** Yes

---

## 📊 Comparison Table

| Bot | Message Logs | Mod Action Logs | Member Logs | Voice Logs | Server/Role Logs | Dashboard | Free Tier |
|-----|:------------:|:---------------:|:-----------:|:----------:|:----------------:|:---------:|:---------:|
| [Carl-bot](../bots/moderation/carl-bot.md) | ✅ Advanced | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Generous |
| [Logger](../bots/logging/logger.md) | ✅ Advanced | ✅ Yes | ✅ Yes | ✅ Yes | ⚠️ Basic | ⚠️ Limited | ✅ Yes |
| [Dyno](../bots/moderation/dyno.md) | ✅ Good | ✅ Yes | ✅ Yes | ⚠️ Basic | ⚠️ Basic | ✅ Yes | ⚠️ Limited |
| [GiselleBot](../bots/moderation/gisellebot.md) | ✅ Good | ✅ Yes | ✅ Yes | ⚠️ Basic | ✅ Yes | ✅ Yes | ✅ Yes |
| [Combot](../bots/moderation/combot.md) | ⚠️ Basic | ✅ Yes | ✅ Yes | ❌ No | ⚠️ Basic | ✅ Yes | ⚠️ Limited |

**Key:** ✅ Available / supported — ⚠️ Partial or limited — ❌ Not available

---

## 💡 Recommendations

### 🟢 Setting up logging for the first time?

Start with **Carl-bot**.

Enable logging through the [carl.gg](https://carl.gg) dashboard and set up three channels to begin:

| Channel | What to log |
|---------|------------|
| `#message-log` | Message edits and deletions |
| `#member-log` | Joins, leaves, bans, kicks, role changes |
| `#mod-log` | All moderation actions from Carl-bot |

This three-channel setup covers the events you'll actually need most, without flooding a single channel with everything at once. You can expand later.

---

### 🟡 Medium server with an active moderation team?

Add a dedicated `#staff-log` or `#admin-log` channel visible only to senior staff, and expand Carl-bot's logging to include voice events and server changes.

Consider adding **GiselleBot** if you want cleaner, more readable mod action formatting that's easier to parse during busy periods.

---

### 🔴 Large server or high-volume community?

Use **Carl-bot** for comprehensive event logging and **Combot** if you want activity pattern data alongside raw logs.

At high volume, a single `#message-log` becomes impossible to monitor in real time. Instead:

- Create per-category log channels for high-traffic areas
- Set up a `#flagged-log` channel that only receives alerts for high-priority events (mass deletions, ban triggers, new account joins)
- Review logs on a scheduled basis — weekly mod log reviews are standard practice in well-run large communities

---

### 🔵 Need logs for ban appeals or staff accountability?

Prioritize **mod action logging** above everything else.

Every warn, mute, kick, and ban should be logged with the responsible staff member's ID, the target user's ID, a timestamp, and a reason. Without reasons on moderation actions, your logs are incomplete records that won't hold up in a dispute.

In Carl-bot, enforce this by requiring a reason on every moderation command. Most moderation bots support this as a configurable option.

---

## 🚫 Common Logging Mistakes

These are the errors that leave servers without the records they need when it matters most.

---

### 1. Logging everything to one channel

A single `#logs` channel receiving every event type becomes unreadable within hours on any active server. When you actually need to find something, it's buried under hundreds of irrelevant entries.

**Fix:** Separate channels for message logs, member logs, mod logs, and server/role logs at minimum.

---

### 2. Staff can see or manage log channels

If the people being logged can read, edit, or delete the log channel, the logs have no integrity. A moderator who knows their actions are logged in a channel they can access has an incentive to interfere.

**Fix:** Log channels visible to senior staff and admins only. Deny manage messages permissions even for staff in log channels.

---

### 3. Not logging moderation reasons

A ban log entry that says "User banned" is almost useless. A ban log entry that says "User banned — User ID: 123456789 — Reason: repeated harassment after two warnings — Moderator: Moderator ID 987654321" is a complete record.

**Fix:** Require reasons on all moderation commands. Most bots support mandatory reason fields.

---

### 4. Setting up logs and never reviewing them

Logs only provide value if someone reads them. Many servers have perfect logging configured and zero process for actually using it.

**Fix:** Build a habit of weekly mod log reviews. Look for patterns — repeated warnings to the same user, the same moderator acting disproportionately, clusters of raids at specific times.

---

### 5. Not logging message edits

"I never said that" is one of the most common bad-faith claims in server disputes. Without message edit logs, you can't disprove it.

**Fix:** Always enable message edit logging. Carl-bot's message log captures the before and after content of every edit.

---

### 6. Forgetting account creation dates on joins

A new account joining your server — especially during a raid — is a key signal. If your join logs don't include the account creation date, you're missing the most important piece of context.

**Fix:** Enable join logging with account age display. Carl-bot and most logging bots include this by default.

---

### 7. Skipping voice logs

Voice channel activity — who joined, who was moved, who was server-muted — is often relevant in harassment reports and staff conduct reviews. Many servers log text events only and have no record of voice activity.

**Fix:** Enable voice logs to a dedicated `#voice-log` channel. Volume is typically low enough that a single channel handles it fine.

---

> 📂 Back to [Main Directory](../README.md) · See also: [🛡️ Moderation](moderation.md) · [🔒 Security](security.md) · [✅ Verification](verification.md)