# 📓 Daily Research Log

A browser-based daily work journal for researchers. No installation, no server — just open `index.html` and start writing.

## ✨ Features

- 📅 **Monthly Calendar** — Navigate months, see log entries at a glance with mood indicators
- ✍️ **Multiple Entries Per Day** — Add as many log blocks as you need, each with its own title, content, and mood
- 😊 **Mood Tracker** — 14 emoji moods to tag how you felt each day (toggleable on/off)
- 🖼️ **Image Support** — Paste screenshots with Ctrl+V, or pick files from disk
- 💾 **Auto-Save** — Saves automatically as you type; Ctrl+S to force save
- 🔍 **Full-Text Search** — Search across all months and entries
- 📤 **Export Options** — ZIP (with images), plain .md file, or copy to clipboard
- 📋 **List Overview** — Card-style view of all entries in the current month
- ⏰ **Daily Reminder** — Optional popup reminder at a configurable time to write your log
- 🌓 **Dark Mode** — Toggle between light and dark themes
- 🔤 **Font Size Control** — Adjust text size, preference is remembered

## 🚀 Getting Started

Just open `index.html` in your browser (Microsoft Edge or Chrome recommended).

Or double-click `打开日志.bat` to launch with Edge on Windows.

## 💾 Storage

All data is stored in your browser's **localStorage**, organized by month. Data persists across sessions and is not tied to the file location.

> ⚠️ Clearing browser data will delete your logs. Use the Export feature regularly to back up (📤 → Export ZIP).

## 📦 Export Formats

| Format | Description |
|--------|-------------|
| ZIP Archive | Markdown file + image folder; unzip and view with Typora / VS Code |
| Plain .md | Markdown text only, no images |
| Clipboard | Copy Markdown to paste into other apps |

## 🛠 Tech Stack

- Single-file HTML/CSS/JS application
- Zero dependencies (JSZip loaded from CDN for ZIP export only)
- localStorage for persistence
- Works offline (except ZIP export)

## 📄 License

MIT
