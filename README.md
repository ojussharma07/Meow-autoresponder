# 🤖 AutoResponder Bot

A lightweight, fully customizable autoresponder Discord bot built with Python and `discord.py`. It allows server administrators to seamlessly set up word triggers that the bot will automatically react to using standard or custom emojis.

## ✨ Features
* **Slash Commands:** Clean and modern UI for managing all triggers.
* **Smart Matching:** Choose between strict "Exact Word" matches or broad "Anywhere in Sentence" matches.
* **Case-Insensitive:** Automatically handles various capitalizations (e.g., matching `huga`, `HUGA`, or `HuGa` perfectly).
* **Custom Emojis:** Supports standard Discord emojis as well as custom server emojis.
* **Staff Restricted:** Commands are locked to specific moderator roles and channels for security.
* **Cloud Ready:** Built and configured for seamless deployment on Discloud.

## 🛠️ Commands
* `/add [trigger] [emoji] [case_sensitive]` - Add a new word trigger and emoji reaction.
* `/remove [trigger]` - Delete an existing autoresponder.
* `/edit [trigger] [emoji] [case_sensitive]` - Modify an active autoresponder.
* `/list` - View all active autoresponders set up in the server.

## 🚀 Setup & Installation (Local)

1. Clone this repository to your local machine.
2. Install the required dependencies:
```bash
   pip install -r requirements.txt
   Create a hidden .env file in the root directory and add your bot token:

Code snippet
   RESPONDER_TOKEN=your_discord_bot_token_here
Run the bot:

Bash
   python bot.py
(Note: Do not commit your .env or database .json files to public repositories!)
