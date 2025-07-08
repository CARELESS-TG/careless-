# 🎧 Telegram Music Bot

A powerful and feature-rich **Telegram Music Bot** to stream songs in group voice chats using **Pyrogram & Py-TgCalls**.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Pyrogram](https://img.shields.io/badge/Powered%20By-Pyrogram-orange)
![License](https://img.shields.io/github/license/your-username/music-bot)
![Deploy](https://img.shields.io/badge/Deploy%20To-Heroku-purple)
![Stars](https://img.shields.io/github/stars/CARELESS-TG/music-bot?style=social)

---

## 📌 Features

- 🎵 Stream music from **YouTube**, **Spotify**, **SoundCloud**
- 🎤 Group Voice Chat streaming
- 🔎 Inline search for songs
- 🎚 Admin-only controls
- 📁 Playlist management
- 🖥️ Compatible with **Linux**, **VPS**, and **Heroku**
- 🔒 Safe & Secure (uses official APIs)

---

## ⚙️ Requirements

- Python 3.10+
- Telegram API ID & Hash
- Bot Token from [@BotFather](https://t.me/BotFather)
- MongoDB URI
- (Optional) Spotify credentials

---

## 🚀 Installation

```bash
# Clone the repo
git clone https://github.com/CARELESS-TG/music-bot.git
cd music-bot

# Install dependencies
pip install -r requirements.txt

# Fill in your config
cp config.sample.py config.py

# Run the bot
python3 main.py
