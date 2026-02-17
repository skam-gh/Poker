# 🃏 Poker Night Tracker

A sleek, self-contained poker night money tracker. Track borrows, returns, and settlements for up to 15 players.

## Features

- **Player Management** — Add up to 15 players per session
- **Real-time Tracking** — Log borrows and returns with timestamps
- **Daily Limits** — 10 borrows per player per day (resets at midnight)
- **Settlement Calculator** — Instantly see who owes what
- **Persistent Storage** — Data saved to browser localStorage
- **Export/Import** — Backup and restore your data as JSON files
- **Mobile Friendly** — Works on desktop, tablet, and phone

## Quick Start

### Option 1: GitHub Pages (Recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your app is live at `https://<username>.github.io/poker-night/`

### Option 2: Local

Just open `index.html` in any browser. That's it.

## Data Safety

Your poker data is stored in `localStorage` and persists across browser sessions. For long-term safety:

1. **Export regularly** — Use the Backup tab to download a `.json` file after each session
2. **Store in the cloud** — Save exports to Google Drive, OneDrive, etc.
3. **Import anytime** — Restore from any backup file, data is merged intelligently (no duplicates)

## Tech

Single HTML file. No build tools, no dependencies, no server needed. Just HTML + CSS + vanilla JS.

## License

MIT — do whatever you want with it.
