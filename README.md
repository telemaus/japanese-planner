# Japanese Planner

A self-contained study planner for working through Genki I & II (3rd edition) from zero to JLPT N4/3. Designed for people who struggle with self-motivation and need a completely brain-dead, day-by-day schedule with zero decisions required.

Live at: `https://telemaus.github.io/japanese-planner/`

---

## What it does

- 7-day weekly schedule per chapter, covering all 23 Genki lessons
- Tells you exactly what to do each day — no thinking required
- WaniKani Apprentice tracker with a traffic light telling you how many lessons to do
- Direct links to Quizlet vocab, kanji, and conjugation decks for every lesson
- Direct links to official Genki dialogue videos (Vimeo)
- Links to Seth Clydesdale's Genki drill site
- Progress saved to localStorage (per device)
- Cloud sync via GitHub Gist (one token, works across all devices)
- Export / import as JSON for manual backup
- Installable as a PWA on iPhone, Android, and desktop

---

## Installing on your phone

**iPhone / iPad:** Open the URL in Safari → tap the Share icon → "Add to Home Screen"

**Android:** Open in Chrome → tap the three-dot menu → "Add to Home Screen" or "Install app"

**Desktop Chrome:** Click the install icon in the address bar (right side)

---

## Cloud sync setup

Progress is stored locally per browser by default. To sync between devices:

1. Go to **Settings** in the app and tap **"How? ↗"** — this opens GitHub's token creation page
2. On that page: give the token any name, set expiration as you prefer, and check **only the `gist` scope** — nothing else
3. Click "Generate token" and copy it
4. Paste it into the token field in the app Settings — it saves automatically

After that:
- Tap **"Save to cloud"** after any study session
- On another device: open the app, paste your token once, tap **"Load from cloud"**

The Gist is **private** by default. Only someone with your token can access it.

---

## Stack

Plain HTML + CSS + JS, no framework, no build step. One file (`index.html`). All data lives in the browser's localStorage or a private GitHub Gist. No backend, no database, no server costs.

---

## After Genki

Genki I + II covers roughly JLPT N4. To reach N3, continue with **Quartet** (by the same Japan Times publisher, same format, same Quizlet/drill ecosystem). A Quartet planner can be added later using the same structure.