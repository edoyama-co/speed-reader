# Speed Reader

RSVP (Rapid Serial Visual Presentation) speed reader for PDFs. Single self-contained HTML file — no build step, no dependencies to install.

**Live:** https://edoyama-co.github.io/speed-reader/

## What it does

Drop in a PDF (or .txt), pick your WPM, and the app flashes one word (or a chunk of words) at a time in the center of the screen. A red highlight marks the ORP (Optimal Recognition Point) of the pivot word — the letter your eye naturally focuses on.

## Features

- **PDF text extraction** in-browser via PDF.js (no upload, nothing leaves your machine)
- **100–2000 WPM** with variable timing (long words and punctuation get a longer beat)
- **1–5 word chunks per flash**
- **Jump to any word** by number
- **% counter + ETA**
- **Auto-resume** — position saved to localStorage per file (filename + word count), so you pick up where you left off

## Keyboard

- `Space` — play/pause
- `←` / `→` — back/forward 10 words
- `↑` / `↓` — WPM ±25
- `[` / `]` — chunk size ±1
- `R` — restart

## Local use

Save `index.html` anywhere, double-click. Works offline once PDF.js has loaded once.

## Deploy

Any static host. This copy is served from GitHub Pages via `main` branch root.
