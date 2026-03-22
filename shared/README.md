# Shared Shell Architecture

This folder contains reusable components inherited by all 20 games:

- `shell.js` — Master wrapper component
- `ai.js` — AI opponent framework (Easy/Hard/Expert)
- `leaderboard.js` — Local leaderboard (localStorage)
- `achievements.js` — Achievement system (5 per game)
- `streak.js` — Daily login streak tracker
- `stats.js` — Statistics aggregator
- `dark-mode.js` — Dark mode toggle + system preference
- `promo-panel.js` — 'More Games' cross-promotion panel
- `cosmetics.js` — Theme/skin system
- `premium.js` — Freemium gate
- `win-screen.js` — Standard win screen template
- `tutorial.js` — First-launch tutorial
- `analytics.js` — Google Analytics 4 integration
- `style.css` — Global styles + CSS variables

Each game imports these components → all 20 games inherit features automatically.
