# Bisaya Vocab Quiz

A small, single-file, no-dependency web app for drilling Cebuano (Bisaya) vocabulary — multiple choice, Cebuano to English. Built for self-study, no backend, no build step.

**[Play it here](#)** — replace with your live GitHub Pages URL, e.g. `https://ejiije.github.io/bisaya-vocab-quiz/`

## Features

- **Play** — multiple-choice rounds pulled from your word bank, with score and streak tracking
- **Word bank** — add or remove words directly in the app, no code editing required
- **Settings** — choose how many questions per round (5–30) and optionally turn on a per-question timer (5–30 seconds)
- **Persistence** — your word bank, settings, and best score are saved in the browser via `localStorage`, so they stick around between visits on the same device

## Tech

Plain HTML, CSS, and vanilla JavaScript in a single file (`index.html`). No frameworks, no build tools, no external dependencies. Works offline once loaded, and adapts to light/dark mode automatically.

## Running locally

Just open `index.html` in any browser — no server needed.

## Deploying

Hosted for free on [GitHub Pages](https://pages.github.com/):

1. Push `index.html` to the `main` branch
2. In the repo, go to **Settings → Pages**
3. Under **Build and deployment**, set source to **Deploy from a branch**, branch `main`, folder `/ (root)`
4. Your site goes live at `https://yourusername.github.io/repo-name/`

## Notes

- Word bank and progress are stored **per browser**, not synced across devices
- The repo is public (required for free GitHub Pages), so anyone with the link can view and use the quiz
- To reset the word list to the built-in defaults, use the **Reset to default list** button on the Word bank screen

## License

Personal project — use, fork, or modify freely.
