# Gelmet Site Deployment

This repository is the website.

The easiest long-term setup is to publish directly from:

- branch: `main`
- folder: `/ (root)`

That keeps future updates simple: edit files, commit, push.

## Files that matter most

- `index.html`
- `apps.html`
- `consulting.html`
- `ai.html`
- `about.html`
- `contact.html`
- `styles.css`
- `assets/*`
- `CNAME`

## One-time setup in GitHub

In the repository:

1. Go to `Settings`
2. Open `Pages`
3. Under `Source`, choose `Deploy from a branch`
4. Under `Branch`, choose `main`
5. Choose `/ (root)`
6. Save

## Custom domain

Canonical domain:

`www.gelmet.com`

In GitHub Pages settings:

1. Add `www.gelmet.com` as the custom domain
2. Wait for GitHub to provision HTTPS
3. Enable `Enforce HTTPS` when available

## GoDaddy DNS

Recommended setup:

- `CNAME` record for `www` -> `rudygarr.github.io`
- Forward `gelmet.com` to `https://www.gelmet.com` with a permanent `301`
