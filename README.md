# QuestBoard — Gamified Kanban Task Tracker

A productivity tool that combines Kanban boards with RPG-style gamification. Earn XP, level up, maintain streaks, and unlock achievements by completing tasks.

---

## Screenshot

> _Screenshot coming soon._

---

## Features

- **Kanban drag-and-drop** — move tasks across To Do, In Progress, and Done columns
- **XP and leveling system** — earn XP on completion; progress from Wanderer to Overlord across 10 levels
- **Daily streaks with multiplier** — keep a streak alive for up to 3× XP on completions
- **Achievement badges** — unlock six badges including First Quest, Boss Slayer, and Board Clearer
- **Dark gaming theme** — built for long sessions with a high-contrast, purple-accented UI
- **PWA — installable on phone** — add to home screen for a native app experience
- **Works offline** — service worker caches the full app shell so it runs without a connection
- **Data saved locally** — all tasks and progress persist in localStorage, no account needed

---

## Live App

Visit **[https://sayush2807.github.io/questboard](https://sayush2807.github.io/questboard)**

For the best experience, tap **"Add to Home Screen"** in your browser — the app will open fullscreen like a native app, with offline support.

---

## Run Locally

```bash
git clone git@github.com:sayush2807/questboard.git
cd questboard
open index.html        # macOS
# or: xdg-open index.html  (Linux)
# or: just double-click index.html in your file manager
```

No build step, no dependencies.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, keyframe animations) |
| Logic | Vanilla JavaScript (ES2020) |
| Offline | PWA — Service Worker + `manifest.json` |
| Storage | `localStorage` |

---

## License

[MIT](https://opensource.org/licenses/MIT) © Ayush Srivastava
