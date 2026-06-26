<div align="center">
  <h1><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/crosshair.svg" width="36" height="36" align="center" /> Discord Russian Roulette</h1>
  <p><strong>A high-stakes, ruthless mini-game bot for your Discord server.</strong></p>
  
  <br>
  
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Discord.py-5865F2.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  <img src="https://img.shields.io/badge/Status-Lethal-FF0000.svg?style=for-the-badge" alt="Status" />
</div>

---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/skull.svg" width="24" height="24" align="center" /> Overview
Dc Russian Roulette Is a moderation based mini-game bot for Discord that focuses on a specific role and will eliminate a randomly picked percent of the rolemembers with a variable probability. If you lose the roll you are instantly kicked off the server.

*Perfect for server purges, high-stakes community events, or just testing your members' luck.*

---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/target.svg" width="24" height="24" align="center" /> Features

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/zap.svg" width="20" height="20" align="center" /> Modern Architecture</h3>
      Fully utilizes Discord's modern <strong>Slash Commands</strong> (<code>/roulette</code>) for a clean, user-friendly UI without cluttering chat channels.
    </td>
    <td width="50%" valign="top">
      <h3><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/shield-check.svg" width="20" height="20" align="center" /> Safe Execution</h3>
      Automatically filters out other bots from the target pool. Includes robust error handling for members with higher hierarchy roles.
    </td>
  </tr>
</table>

---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/settings.svg" width="24" height="24" align="center" /> Prerequisites

1. Turn on Server Members Intent in the Discord Developer Portal (this is necessary for role members to load).
2. Bot must have the Kick Members permission.
3. Ensure your bot’s role in server settings is above the role that it will be kicking

---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/terminal-square.svg" width="24" height="24" align="center" /> Setup & Installation

**1. Clone and Install Dependencies**
Ensure you have Python 3.8+ installed.
```bash
pip install discord.py python-dotenv
```

<br>
<hr>
<p align="center">
  <small>Made with 🤍 by <a href="https://github.com/yamanist0">yamanist</a></small>
</p>
