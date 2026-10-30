# HA — To-Do List

A single-file, zero-dependency To-Do web app (pure HTML/CSS/JS).

**Features:** add / edit / delete / mark-done, undo for delete & clear,
filters (all / active / done), progress bar, light & dark theme,
persistence via `localStorage`, responsive for mobile.

**Live:** https://alantamproject.github.io/HA/

## Local development

Just open `index.html` in a browser — no build step, no dependencies.

## Deployment

Every push to `main` triggers `.github/workflows/pages.yml`, which
validates the page and deploys the repo root to GitHub Pages.
