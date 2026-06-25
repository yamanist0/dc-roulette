<div align="center">
  <h1>🔫 Discord Russian Roulette</h1>
  <p><strong>A high-stakes, ruthless mini-game bot for your Discord server.</strong></p>
  
  <br>
  
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Discord.py-5865F2.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  <img src="https://img.shields.io/badge/Status-Lethal-FF0000.svg?style=for-the-badge" alt="Status" />
</div>

---

### 💀 Overview
**Russian Roulette** is a moderation-based mini-game bot for Discord. It targets a specific role and kicks a randomly selected portion of its members based on a customizable probability. Those who lose the roll are instantly eliminated (kicked) from the server. 

*Perfect for server purges, high-stakes community events, or just testing your members' luck.*

---

### 🎯 Features

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Modern Architecture</h3>
      Fully utilizes Discord's modern <strong>Slash Commands</strong> (<code>/roulette</code>) for a clean, user-friendly UI without cluttering chat channels.
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ Safe Execution</h3>
      Automatically filters out other bots from the target pool. Includes robust error handling for members with higher hierarchy roles.
    </td>
  </tr>
</table>

---

### ⚙️ Prerequisites

Before running the bot, ensure you have the following configured in the [Discord Developer Portal](https://discord.com/developers/applications):
1. **Server Members Intent:** Must be ENABLED (required to fetch role members).
2. **Bot Permissions:** The bot needs the `Kick Members` permission.
3. **Role Hierarchy:** The bot's role must be **higher** than the role it is targeting, otherwise the kick action will fail.

---

### 🛠️ Setup & Installation

**1. Clone and Install Dependencies**
Ensure you have Python 3.8+ installed.
```bash
pip install discord.py python-dotenv
