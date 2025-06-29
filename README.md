# 🚀 DiscordModBot

[![PyPI version](https://badge.fury.io/py/discordmodbot.svg)](https://pypi.org/project/discordmodbot/)
[![Python versions](https://img.shields.io/pypi/pyversions/discordmodbot.svg)](https://pypi.org/project/discordmodbot/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

🎯 **DiscordModBot** is a powerful, production-ready Python moderation bot library I built for Discord. It supports both **slash** and **prefix** commands, advanced case tracking, warnings, mass moderation, customizable messages, and a built-in SQLite database — everything you need to moderate a Discord server with ease.

## ✨ Features

✅ Ban, kick, timeout, warn, unban, unwarn
✅ Mass moderation (ban, kick, timeout, unban multiple users at once)
✅ Dual command support (slash + prefix)
✅ Advanced embed logging
✅ Fully customizable messages
✅ User moderation history and statistics
✅ Production-grade permission & error handling

---

## ⚡ Quick Start

```python
from discord_mod_bot import ModerationBot, BotConfig

config = BotConfig(
    token="YOUR_BOT_TOKEN",
    prefix="!",
    system_mode="prefix&slash"
)

bot = ModerationBot(config)
bot.run_bot()
```

---

🌟 I developed this library to help server admins manage their communities more effectively with **minimal setup and maximum control**.

📚 **Full documentation & installation** 👉 [PyPI - discordmodbot](https://pypi.org/project/discordmodbot/1.0.0/)

---

> Made with ❤️ for the Discord community
