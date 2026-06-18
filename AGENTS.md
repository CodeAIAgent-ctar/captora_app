# Captora Website — Agent Guide

## Architecture

Single-page static site with no build pipeline. All content lives in `index.html`.

## Key files

| File | Purpose |
|------|---------|
| `index.html` | Full website — ~49 KB self-contained HTML |
| `logo_*.png` | Logos at 64 / 128 / 250 px sizes |
| `netlify.toml` | Security headers config |

## Conventions

- No framework, no dependencies, no node_modules needed for the site itself
- Edits go directly into `index.html`
- Images are served from the repo root alongside `index.html`
