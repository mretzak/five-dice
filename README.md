# Five Dice! 🎲

A pass-and-play dice game for 1–3 players, inspired by the classic 2008 "Five Dice!" iOS app. Built as a single self-contained HTML file — no installs, no accounts, no ads.

**[Play it here](#)** ← replace with your GitHub Pages link once it's live

## Features

- **1–3 players**, pass-and-play on one device, with custom names
- Full classic scoring: Aces through Sixes, 3/4 of a Kind, Full House, Small/Large Straight, Five Dice!, and Chance
- Upper-section bonus tracker that shows live progress (e.g. `47/63`)
- Stacking **+100 bonus** for extra Five-of-a-Kinds after your first
- Sound effects for rolling, holding, scoring, and winning (toggleable)
- **Wall of Fame** — top 10 high scores, saved on your device between visits
- Designed to feel like an installed app: add it to your phone's home screen for a full-screen, no-browser-chrome experience

## Adding it to your Home Screen

1. Open the link above in **Safari** (iOS) or **Chrome** (Android)
2. Tap the **Share** button → **Add to Home Screen**
3. Launch it from the icon — it opens full-screen, just like a native app

## Tech notes

- Single `index.html` file — no frameworks, no build step, no external dependencies
- High scores are saved with the browser's `localStorage`, scoped to your device — no login, no server, no shared leaderboard
- Works offline after the first load

## Updating the game

To push changes, just replace `index.html` in this repo with a new version and commit — GitHub Pages redeploys automatically within a minute or two.

---

*A love letter to the original Five Dice! (2008, Pelted Software) — rebuilt from memory with Claude.*
