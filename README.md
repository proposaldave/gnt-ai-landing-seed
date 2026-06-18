# Give n Take Landing Seed

Status: public-safe static seed for Ploy or GitHub Pages.

GitHub: https://github.com/proposaldave/gnt-ai-landing-seed

## Decision

Use this as a concrete visual/copy reference for Ploy. It is intentionally broad and brand-first. It should not expose private workflows, club operations, integrations, player data, or roadmap detail.

## Files

- `index.html` - static landing page
- `styles.css` - standalone styles, no build step
- `assets/hero-community-growth.svg` - public-safe visual asset with no real people, logos, or readable data

## How To Preview

Open `index.html` directly in a browser, or publish the folder with GitHub Pages, Netlify, Vercel, or Ploy.

## GitHub Pages

This folder can be pushed as the root of a standalone GitHub repo. The included `.github/workflows/pages.yml` publishes the static files from `main` to GitHub Pages.

Do not add a custom-domain `CNAME` file until Dave has reviewed the page and chosen whether GitHub Pages or Ploy should own `www.gnt.ai`.

## Ploy Use

Give Ploy this folder as the reference, then ask:

> Recreate this public brand page for `www.gnt.ai`, preserve the quiet visual direction and short copy, and sharpen the positioning around one simple growth loop: run a great pickleball event, invite a group or open it to anyone, let followers keep up with great hosts, ask invitees to refer friends, and grow groups, experiences, and community. Replace the mailto form with a native Ploy early-list form. Do not add product details, roadmap claims, integrations, private workflows, or specific club examples.

## Safety Rules

- Do not connect this seed to production GNT code.
- Do not add rosters, contact lists, private club examples, or screenshots.
- Do not auto-publish Ploy changes without Dave approval.
- Keep `v2.gnt.ai` untouched.
