# Discord Timestamp Generator (Web App)

<p align="center">
  <a href="https://discordtimestamp.online">
    <img alt="Discord Timestamp Generator" src="https://img.shields.io/badge/Discord%20Timestamp%20Generator-Web%20App-blue" />
  </a><br/>
  <sub>Generate & preview all 7 styles — <code>t / T / d / D / f / F / R</code></sub>
</p>

<p align="center">
  <a href="https://discordtimestamp.online"><img alt="Website status" src="https://img.shields.io/website?url=https%3A%2F%2Fdiscordtimestamp.online" /></a>
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg" /></a>
  <a href="https://github.com/mortyxiao/discordtimestamp/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/mortyxiao/discordtimestamp?style=social" /></a>
  <a href="https://discordtimestamp.online/blog"><img alt="Guides & Examples" src="https://img.shields.io/badge/Guides-%26%20Examples-informational" /></a>
</p>

> **Open the tool:** **[Discord Timestamp Generator](https://discordtimestamp.online)** — build countdowns, convert Unix time, and parse Discord snowflake IDs.  
> Reference: **[Discord Developer Docs — Timestamp styles](https://discord.com/developers/docs/reference#message-formatting-timestamp-styles)**

---

## Table of Contents
- [Features](#features)
- [Quick Start](#quick-start)
- [Examples](#examples)
- [Tools](#tools)
- [Why timestamps?](#why-timestamps)
- [Contributing](#contributing)
- [License](#license)

---

## Features
- **All 7 timestamp styles** with live preview (`t`, `T`, `d`, `D`, `f`, `F`, `R`).
- **One-click copy** of `<t:...>` snippets for messages, pins, and embeds.
- **Countdown generator** for localized event announcements.
- **Unix ↔ `<t:...>`** conversion.
- **Discord Snowflake → Timestamp** (timezone-aware display).
- Mobile-friendly, no sign-in required.

---

## Quick Start
1. Open the web app and pick a date/time & a format (e.g., `f` or `R`).  
2. Copy the generated `<t:UNIX:FORMAT>` code.  
3. Paste it into Discord — it auto-localizes for each reader.

## Examples
```text
<t:1640995200:f>  →  January 1, 2022 12:00 AM
<t:1640995200:R>  →  3 years ago
```

---

## Tools

| Tool | Purpose | Link |
|---|---|---|
| **Discord Countdown Timer** | Create a localized countdown timestamp for announcements. | [Open Countdown](https://discordtimestamp.online/countdown) |
| **Unix Timestamp Converter for Discord** | Convert epoch seconds to/from `<t:...>` code. | [Open Unix Converter](https://discordtimestamp.online/unix) |
| **Discord Snowflake → Timestamp** | Parse snowflake IDs to human-readable time. | [Open Snowflake Converter](https://discordtimestamp.online/snowflake) |
| **Guides & Examples** | Tips, templates, and best practices. | [Open Blog](https://discordtimestamp.online/blog) |

> Also see the official reference: **[Discord Developer Docs — Timestamp styles](https://discord.com/developers/docs/reference#message-formatting-timestamp-styles)**

---

## Why timestamps?
- Let Discord handle **time zones** & **daylight saving** automatically.
- Express **relative time** with `R` (e.g., *in 2 hours*, *3 days ago*).
- Improve clarity in event announcements, giveaways, schedules, and bot embeds.

---

## Contributing
Pull requests and issue reports are welcome. For UI/UX changes, please include a short before/after screenshot or a small repro.

---

## License
Released under the **MIT License**. See [`LICENSE`](./LICENSE).

---
