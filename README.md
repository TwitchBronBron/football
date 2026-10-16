# Football Playtime Tracker 🏈

A mobile-first, high-contrast sideline Progressive Web App (PWA) designed for youth football coaches to balance playing time, manage substitutions, and track player positions in real time under bright outdoor sunlight.

Live site: [football.bronley.com](https://football.bronley.com)

## Features

- **Sideline Ergonomics**: High-contrast, vibrant saturated cards and large typography for instant glanceability in direct sunlight.
- **On Field & On Bench Sections**: Clear separation between active players and resting players with live sub badges.
- **Queue & Swap Workflow**: Tap kids to stage substitutions (`↓ OFF` and `↑ ON`), then tap `SWITCH` to swap.
- **Position Tracking**: Color-coded position badges (`C`, `QB`, `RB`, `WR`) displayed on each card.
- **Play Logging & Streaks**: Single-tap `LOG PLAY` updates play counters and highlights consecutive plays in a row.
- **Roster & Game Management**: Persistent local roster, multi-game tracking, and attendance toggles.
- **PWA & Offline-First**: Works offline with local persistence (`localStorage`) and wake lock to keep the screen active on the sidelines.

## Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
```

Build output is written to `dist/` and deployed automatically to GitHub Pages via GitHub Actions.

