# Wareth Pump 💪

Personal training + weight-loss tracker. A single-file web app — no build, no server, no accounts. All data (logs and progress photos) stays in the browser it runs in.

## Features

- **Training plan** — weekly split built from your available days (3/4/5/6): full body, upper/lower, or push/pull/legs. Flexible days offer a chooser: rest, padel, tennis, cycling, or a shoulders/traps/abs session.
- **Weight-loss estimate** — Mifflin-St Jeor BMR → TDEE → deficit, capped at a safe 1% of body weight per week. Re-plans itself from every logged weight. Chart shows actual vs projected vs goal.
- **10,000 daily steps** — animated progress ring, counts toward streaks.
- **Fuel (food & calories)** — ~70-item food database (gym staples plus Middle-East staples), portion hints, calorie total vs daily target. Carb-heavy junk is flagged ⚠️ with a suggested swap.
- **Progress photos** — one a day, stored locally (IndexedDB), photo diary grid and a then-vs-now compare slider.
- **Rewards** — streak, weight, step, food and workout milestone badges with editable prizes.

## Run it

Open `index.html` in any browser — that's it. To host it, enable GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root) and it serves at your Pages URL.

## Notes

Estimates are a guide, not medical advice. Values in the food database are typical estimates.
