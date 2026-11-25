# Linvo

A lightweight, dependency-free web app for learning English and Polish, with a Ukrainian interface.

## Current version — 0.1 (local prototype)

- English and Polish A1 starter curricula (8 lessons per language, 48 words/phrases each).
- Lessons with audio pronunciation using the browser's speech synthesis.
- Multiple-choice tests for lessons and mixed practice, with optional typed-answer practice.
- Flashcards and interval-based reviews (1 / 3 / 7 / 14 / 30 days).
- Searchable vocabulary library, statistics, XP, daily goal, and learning activity.
- Automatic progress persistence in the current browser through `localStorage`.
- Responsive light interface, accessible keyboard controls, no dependencies or account needed.

## Local use

Option A: open `index.html` in a browser. For consistent browser behavior (including local storage), use a local web server:

```sh
python -m http.server 8080
```

Visit `http://localhost:8080/`.

## Publishing later

No GitHub Actions workflow, build script, CI, or external hosting integration is included, intentionally. When ready to publish, enable GitHub Pages with **Deploy from a branch**, using `main` and `/ (root)`. The source contains all the files required by a static site. Note that GitHub Pages may still use a platform-managed Pages build/deploy internally.

## Data and privacy

All progress currently stays on one device/browser in `localStorage`. It does **not** sync between devices. Clearing browser data can erase progress. No user accounts, analytics, backend, or paid services are connected.

## Next stages

Extend curricula beyond A1, add comprehensive grammar lessons, improved exercises and optional cloud accounts/progress sync.
