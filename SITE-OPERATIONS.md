# Site Operations

This repository is intentionally simple so site updates stay easy.

## Core editing files

- `index.html` controls the homepage and main studio framing
- `apps.html` controls app and product messaging
- `consulting.html` controls consulting messaging
- `ai.html` controls AI messaging
- `styles.css` controls the shared visual system

## Publishing

GitHub Pages publishes directly from:

- branch: `main`
- folder: `/ (root)`

That means the update loop is:

1. Edit files
2. Commit changes
3. Push `main`
4. Wait for GitHub Pages to rebuild

## Domain

- Primary domain: `www.gelmet.com`
- Root domain: `gelmet.com` forwards to `https://www.gelmet.com`

## Notes for future updates

- Keep the site static unless there is a very strong reason to add complexity.
- Prefer editing shared styles instead of adding one-off inline styles.
- Keep app messaging grounded in real status and real use cases.
- When in doubt, make the copy more specific, not more grand.
