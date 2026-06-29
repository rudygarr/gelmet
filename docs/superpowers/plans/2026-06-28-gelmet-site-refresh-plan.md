# Gelmet Site Refresh Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Refresh the Gelmet website so the homepage better represents the studio, the apps page reads like real product work, and the repo is easier to maintain.

**Architecture:** Keep the site as simple static HTML and CSS published from the repo root on GitHub Pages. Improve content structure and shared styling rather than introducing frameworks or a CMS.

**Tech Stack:** HTML, CSS, GitHub Pages

---

### Task 1: Strengthen homepage structure and messaging

**Files:**
- Modify: `index.html`

- [ ] Rewrite the hero so Gelmet reads as a studio with apps, consulting, and AI support rather than only as an app brand.
- [ ] Expand the capability and featured-work sections with clearer, more specific messaging.
- [ ] Add stronger CTA structure that points users toward apps and contact.

### Task 2: Expand the apps page into product-focused sections

**Files:**
- Modify: `apps.html`

- [ ] Replace the simple stack of app summaries with richer product sections.
- [ ] Add useful metadata for Spot Projector and SpotMover such as stage, platform, and audience.
- [ ] Add a future-tools section that keeps the roadmap visible without overselling unfinished work.

### Task 3: Extend shared site styling for product storytelling

**Files:**
- Modify: `styles.css`

- [ ] Add reusable section styles for product cards, metadata rows, and compact maintenance notes.
- [ ] Keep the current dark, glassy system while increasing hierarchy and scanability.
- [ ] Make sure new patterns stay responsive on smaller screens.

### Task 4: Add a tiny maintenance map for future updates

**Files:**
- Create: `SITE-OPERATIONS.md`
- Modify: `README.md`

- [ ] Add one lightweight operations file describing where the core site content lives and how publishing works.
- [ ] Update the README so the site structure and update flow are obvious at a glance.

### Task 5: Verify and publish

**Files:**
- Modify: as needed from Tasks 1-4

- [ ] Open and review the edited pages locally.
- [ ] Commit the refresh cleanly.
- [ ] Push `main` so GitHub Pages republishes the site.
