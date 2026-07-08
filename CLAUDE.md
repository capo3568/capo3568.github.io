# capo3568.github.io

Personal site: a public tracker for Angelo's AI-learning journey, plus a showcase of projects built along the way.

## What this is
- Plain HTML/CSS. No framework, no build step, no JS (yet).
- Deployed via GitHub Pages, served at the repo's own name — `capo3568.github.io` is GitHub's special "user site" convention, so it serves at the root URL instead of a `/repo-name/` subpath.
- Three pages, linked by a shared gradient nav bar (`.site-nav`) repeated at the top of each file (no templating, so it's copy-pasted — keep all three in sync if the nav changes):
  - `index.html` — Home: hero + the Progress tracker
  - `goals.html` — the five phase goals, each with a colored number badge (`--phase-0` … `--phase-4` in `style.css`)
  - `projects.html` — the growing project showcase

## Maintenance
- **Progress** (in `index.html`) is hardcoded to mirror the phase checkboxes in the main `GAMEPLAN.md` (in the `Claude-Code-Journey` folder, a separate repo). Update the `done` / `current` / `upcoming` classes whenever a phase starts or finishes.
- **Projects** (`projects.html`) grows over time — add a new `.project-card` link whenever a new project is finished.
- An "AI news" section was deliberately deferred — revisit once JS/API-fetch skills are learned (Phase 2–3).
