# AGENTS.md

## Repo overview

Single-page static site (`index.html`) with Tailwind CSS loaded via CDN. No build step, no package manager, no framework.

## GitHub Pages

- Workflow: `.github/workflows/deploy.yml` — deploys on push to `main` or `workflow_dispatch`.
- **Prerequisite:** Repo **Settings > Pages > Source** must be set to **"GitHub Actions"** (not "Deploy from a branch").
- No configuration needed beyond that — the workflow already has `pages: write` and `id-token: write` permissions.

## What to edit

- `index.html` — all content, styles, and JS live in this single file.
- `README.md` — Portuguese rules document; can be updated independently.
