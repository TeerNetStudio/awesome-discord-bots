# 🎵 Music Bots

> Back to [Main Directory](../README.md)

Music bots bring audio playback into Discord voice channels — streaming tracks from platforms like YouTube, Spotify, SoundCloud, and internet radio directly into your community.

They range from simple single-server players to feature-rich platforms with queue management, playlists, equalizers, 24/7 playback, and multi-server support. The right choice depends on your server's size, the platforms your members use, and how much control you need over the listening experience.

This page covers the best music bots currently available, how they compare, and what to consider before choosing one.


> ⚠️ Music bot functionality changes frequently due to third-party platform restrictions. Verify source compatibility before deployment.

## 🏆 Recommended Music Bots
### Best Overall
- Jockie Music
### Best Open Source
- FredBoat
### Best Dashboard Experience
- Hydra
### Best Audio Filters
- Uzox
### Best Multi-Channel Setup
- Jockie Music
### Best 24/7 Playback
- 24/7

---

## 📋 Contents

- [What Music Bots Are](#-what-music-bots-are)
- [Common Features](#-common-features)
- [Bots in This Category](#-bots-in-this-category)
- [Comparison Table](#-comparison-table)
- [Choosing the Right Music Bot](#-choosing-the-right-music-bot)
- [Best Use Cases](#-best-use-cases)
- [Setup Recommendations](#-setup-recommendations)
- [Related Categories](#-related-categories)

---

## 📌 What Music Bots Are

Music bots join a Discord voice channel and stream audio to every member listening in that channel. They act as a shared player — anyone with the right permissions can search for tracks, add to the queue, skip songs, or adjust playback.

Most music bots source audio from one or more of the following:

- **YouTube** — the most common source; largest catalogue
- **Spotify** — support varies significantly between bots and may change over time; some bots support Spotify links by resolving them through YouTube
- **SoundCloud** — supported by many bots as a secondary source
- **Internet radio** — stream URLs for live radio stations
- **Direct file links** — some bots support MP3 or other audio URLs

> **Note on platform availability:** Music bot functionality has changed significantly since YouTube and Spotify have restricted API access for third-party bots. Always verify which platforms a bot currently supports before building your setup around it. Check the bot's official website or support server for current source availability.

---

## ✨ Common Features

Understanding what music bots offer helps you compare them accurately.

| Feature | What it means |
|---------|--------------|
| **Queue management** | Add, remove, reorder, and view tracks in the playback queue |
| **Playlists** | Save and load collections of tracks — personal or server-wide |
| **Shuffle / loop** | Randomize queue order or repeat a track or the full queue |
| **Volume control** | Adjust playback volume per server or per user |
| **Equalizer** | Adjust bass, treble, and audio frequency profiles |
| **24/7 mode** | Bot stays in the voice channel even when no members are present |
| **DJ role** | Restrict music controls to members with a designated role |
| **Multi-source support** | Pull audio from more than one platform (YouTube + SoundCloud, etc.) |
| **Filters** | Apply audio effects — nightcore, bassboost, vaporwave, karaoke, etc. |
| **Now playing display** | Embed showing current track, progress bar, and queue position |

---

## 🤖 Bots in This Category

### [Jockie Music](../bots/music/jockie-music.md)

One of the most actively used music bots following the shutdown of Groovy and Rythm. Jockie Music supports multiple simultaneous instances, meaning you can run up to four separate Jockie bots in different voice channels on the same server. Supports YouTube, SoundCloud, and other sources. Reliable uptime and active development.

**Best for:** Servers that need music in multiple voice channels simultaneously.
**Free tier:** Available — multiple instances may require premium.
**Dashboard:** Check official website.

---

### [FredBoat](../bots/music/fredboat.md)

A long-standing open source music bot with a straightforward feature set. FredBoat supports YouTube, SoundCloud, Bandcamp, Twitch streams, and direct file links. It is self-hostable, meaning technically capable servers can run their own instance rather than depending on a shared service. Simple to use with no dashboard required.

**Best for:** Servers that want a reliable, no-frills music bot or prefer open source and self-hosting options.
**Free tier:** Free — no paid plans on the public instance.
**Dashboard:** No — command-based configuration.

## 🏠 Self-Hosted Recommendation

If you require complete control over music playback, uptime, and data, consider self-hosting FredBoat or a Lavalink-based solution.

---

### [Lava Music](../bots/music/lava-music.md)

A modern music bot built with audio quality and feature depth in mind. Lava Music includes equalizer presets, audio filters, playlist support, and a clean now-playing interface. Actively developed with slash command support.

**Best for:** Servers that prioritize audio quality and want filter and equalizer controls.
**Free tier:** Available.
**Dashboard:** Check official website.

---

### [Chip Bot](../bots/music/chip-bot.md)

A widely used music bot known for its reliability and clean interface. Chip supports YouTube and other sources, offers playlist management, and includes a DJ role system for controlling who can manage playback. Simple enough for casual servers, feature-complete enough for dedicated music communities.

**Best for:** General-purpose servers wanting a clean, reliable music experience.
**Free tier:** Available — some features require premium.
**Dashboard:** Yes.

---

### [BMO](../bots/music/bmo.md)

A music and entertainment bot with a focus on ease of use. BMO handles music playback alongside light utility features, making it suitable for smaller servers that want music without running multiple bots. Supports common audio sources and basic queue management.

**Best for:** Small to medium servers wanting simple music playback with minimal configuration.
**Free tier:** Available.
**Dashboard:** Check official website.

---

### [Uzox](../bots/music/uzox.md)

A music bot with support for multiple audio sources and a focus on audio filters and effects. Uzox includes bassboost, nightcore, and other audio presets alongside standard playback features. Actively maintained with slash command support.

**Best for:** Servers that want audio filter and effects support alongside standard playback.
**Free tier:** Available.
**Dashboard:** Check official website.

---

### [Hydra](../bots/music/hydra.md)

A feature-rich music bot with a web-based dashboard for managing playback, queues, and settings from a browser. Hydra supports multiple audio sources and includes DJ role management, auto-play, and a clean now-playing embed. The dashboard differentiates it from most music bots, which are command-only.

**Best for:** Servers that want browser-based music management and a polished interface.
**Free tier:** Available — advanced features require premium.
**Dashboard:** Yes.

---

### [Green-bot](../bots/music/green-bot.md)

A music bot with a straightforward feature set covering standard playback, queue management, and playlist support. Green-bot is known for consistent uptime and simple setup, making it a low-maintenance option for servers that want music without complexity.

**Best for:** Servers that want reliable music playback with minimal setup and maintenance.
**Free tier:** Available.
**Dashboard:** Check official website.

---

### [24/7](../bots/music/24-7.md)

A bot specifically designed for continuous, uninterrupted playback — staying in a voice channel around the clock to stream music or radio even when no staff are present. Useful for community servers, lounge channels, or servers that want ambient audio running at all times.

**Best for:** Servers that want a permanent music or radio presence in a voice channel.
**Free tier:** Available — continuous uptime features may require premium.
**Dashboard:** Check official website.

---

### [Tempo Bot](../bots/music/tempo-bot.md)

A music bot with multi-source support and a focus on playlist and queue management. Tempo includes shuffle, loop, and queue history features alongside standard playback controls. Actively maintained with regular updates.

**Best for:** Servers that prioritize playlist management and queue control.
**Free tier:** Available.
**Dashboard:** Check official website.

---

## 📊 Comparison Table

| Bot | Free Tier | Dashboard | Playlists | 24/7 Support | Best For |
|-----|:---------:|:---------:|:---------:|:------------:|----------|
| [Jockie Music](../bots/music/jockie-music.md) | ✅ | ⚠️ Varies | ✅ | ⚠️ Varies | Multi-channel playback |
| [FredBoat](../bots/music/fredboat.md) | ✅ Full | ❌ | ✅ | ✅ | Open source, self-hosting |
| [Lava Music](../bots/music/lava-music.md) | ✅ | ⚠️ Varies | ✅ | ⚠️ Varies | Audio quality, filters |
| [Chip Bot](../bots/music/chip-bot.md) | ⚠️ Limited | ✅ | ✅ | ⚠️ Premium | General-purpose reliability |
| [BMO](../bots/music/bmo.md) | ✅ | ⚠️ Varies | ⚠️ Basic | ❌ | Small servers, simplicity |
| [Uzox](../bots/music/uzox.md) | ✅ | ⚠️ Varies | ✅ | ⚠️ Varies | Audio effects and filters |
| [Hydra](../bots/music/hydra.md) | ⚠️ Limited | ✅ | ✅ | ⚠️ Premium | Dashboard-based management |
| [Green-bot](../bots/music/green-bot.md) | ✅ | ⚠️ Varies | ✅ | ⚠️ Varies | Reliable, low-maintenance |
| [24/7](../bots/music/24-7.md) | ⚠️ Limited | ⚠️ Varies | ⚠️ Basic | ✅ | Continuous/radio playback |
| [Tempo Bot](../bots/music/tempo-bot.md) | ✅ | ⚠️ Varies | ✅ | ⚠️ Varies | Queue and playlist control |

**Key:** ✅ Available / supported — ⚠️ Partial, limited, or verify with official source — ❌ Not available

> Music bots change frequently. Always verify current feature availability on the bot's official website or support server before committing to a setup.

---

## 🎯 Choosing the Right Music Bot

### Prioritize source compatibility first

Before comparing features, confirm the bot supports the platforms your community actually uses. A bot with a great equalizer is useless if it can't play the sources your members request.

- Members primarily use **YouTube links** → most bots work; choose based on features
- Members use **Spotify links** → verify current Spotify support carefully; this changes frequently
- You want **radio or ambient streams** → look specifically at 24/7 or bots with stream URL support
- You want **self-hosted control** → FredBoat is the primary open source option

### Consider your server's use pattern

| Pattern | Recommendation |
|---------|---------------|
| Casual listening, occasional use | FredBoat or Green-bot — simple, reliable, free |
| Active music community, frequent requests | Jockie Music or Chip Bot — queue management, DJ roles |
| Multiple simultaneous voice channels | Jockie Music — multiple instances on one server |
| Audio quality and effects matter | Lava Music or Uzox — equalizer and filter support |
| Continuous background music or radio | 24/7 — built specifically for this use case |
| Browser-based queue management | Hydra — dashboard differentiates it from command-only bots |

### Free tier limitations

Most music bots that offer a free tier restrict one or more of the following on the free plan:

- Queue length limits
- Playlist count or size
- 24/7 uptime or continuous playback
- Audio quality or bitrate
- Number of instances

Review the bot's official pricing page before building your server's setup around features that may require a subscription.

---

## 📋 Best Use Cases

**Casual community servers** — Most members want simple playback: search a song, add it to the queue, skip when needed. FredBoat, Green-bot, or BMO cover this without complexity or cost.

**Dedicated music servers** — Servers built around music sharing benefit from robust queue management, playlist saving, and DJ role controls. Jockie Music, Chip Bot, or Tempo Bot suit this well.

**Gaming servers with voice activity** — Music running in a dedicated lounge channel while members play. Low-configuration bots with reliable uptime work best here. Avoid bots with aggressive free tier limits that interrupt playback mid-session.

**Lounge or chill servers** — Continuous ambient audio or curated radio streams. 24/7 is designed specifically for this; FredBoat with a stream URL also works.

**Servers with multiple active voice channels** — Jockie Music's multi-instance support is the primary solution for running independent queues in different voice channels simultaneously.

---

## ⚙️ Setup Recommendations

### Basic setup — single music channel

Suitable for most servers. Restricts music commands to a dedicated channel so they don't clutter general conversation.

| Step | Action |
|------|--------|
| 1 | Invite your chosen music bot |
| 2 | Create a `#music-commands` text channel |
| 3 | Restrict bot responses to that channel using the bot's channel lock setting |
| 4 | Create a `Music Lounge` voice channel for playback |
| 5 | Set a DJ role if the bot supports it — assign to trusted members |

### Recommended music server stack

A complete setup for servers where music is a core part of the community:

| Role | Bot |
|------|-----|
| Music playback | FredBoat or Jockie Music |
| Voice channel management | [TempVoice](../bots/voice/tempvoice.md) |
| Moderation | [Carl-bot](../bots/moderation/carl-bot.md) |
| Leveling and engagement | [Arcane](../bots/community/arcane.md) |

### Permissions required

Most music bots request the following permissions to function correctly:

- Connect — join voice channels
- Speak — stream audio in voice channels
- View Channel — read text channels for commands
- Send Messages — respond to commands and post now-playing embeds
- Embed Links — display rich now-playing and queue embeds
- Read Message History — required by some bots for command handling

Grant only the permissions the bot requires. Avoid granting Administrator unless the bot's documentation explicitly requires it and you understand the risk.

---

## 🔗 Related Categories

| Category | Relevance |
|----------|-----------|
| [🎧 Voice](voice.md) | Voice channel management — Join-To-Create and channel controls often paired with music bots |
| [📈 Community](community.md) | Leveling and engagement bots that complement music-focused communities |
| [🧰 Utility](utility.md) | General-purpose tools for server management alongside entertainment bots |

---

> 📂 Back to [Main Directory](../README.md) · See also: [🎧 Voice](voice.md) · [📈 Community](community.md) · [🧰 Utility](utility.md)