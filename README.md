# Give n Take Landing Seed

Status: public-safe static seed for Ploy or GitHub Pages.

GitHub: https://github.com/proposaldave/gnt-ai-landing-seed

## Decision

Use this as a concrete visual/copy reference for Ploy. It is intentionally simple, public-safe, and brand-first. It should not expose private workflows, club operations, integrations, player data, or roadmap detail.

## Files

- `index.html` - static landing page
- `styles.css` - standalone styles, no build step
- `assets/blue-hour-court.svg` - active full-bleed hero visual

## How To Preview

Open `index.html` directly in a browser, or publish the folder with GitHub Pages, Netlify, Vercel, or Ploy.

## GitHub Pages

This folder can be pushed as the root of a standalone GitHub repo. The included `.github/workflows/pages.yml` publishes the static files from `main` to GitHub Pages.

Do not add a custom-domain `CNAME` file until Dave has reviewed the page and chosen whether GitHub Pages or Ploy should own `www.gnt.ai`.

## Ploy Use

Start with `PLOY_CREDIT_SAVER_HANDOFF.md`. The rule is: Codex builds the page and assets; Ploy imports, publishes, captures the early list, and handles platform/growth features only when needed.

If Ploy needs a short prompt, use:

> Recreate this public brand page for `www.gnt.ai`, preserve the one-screen premium sports direction, and keep the page brutally simple. Headline: Great pickleball starts with the right host. Subhead: Follow hosts you trust, get invited, and bring friends into the next game. Keep only a first-name, email, and club/city early-list form. Replace the mailto form with a native Ploy form. Do not add feature grids, product details, roadmap claims, integrations, private workflows, or specific club examples.

## Safety Rules

- Do not connect this seed to production GNT code.
- Do not add rosters, contact lists, private club examples, or screenshots.
- Do not auto-publish Ploy changes without Dave approval.
- Keep `v2.gnt.ai` untouched.
