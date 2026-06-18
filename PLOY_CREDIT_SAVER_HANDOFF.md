# Ploy Credit-Saver Handoff

Status: use this to make Ploy spend as few credits as possible.

## Decision

Codex owns the source, copy, visual direction, and static page build. Ploy should not be used as a brainstorming scratchpad. Ploy should import the existing page, preserve the direction, and add only the platform pieces that are expensive or annoying to hand-build.

## What Ploy Should Do

1. Slurp/import the live page or GitHub repo.
2. Preserve the current layout, visual hierarchy, colors, copy, and `landing-growth-loop.svg` hero direction.
3. Replace the `mailto:` form with a native early-list form.
4. Add Ploy analytics and visitor identification if available on Dave's plan.
5. Prepare the cleanest path to publish `www.gnt.ai`.
6. Suggest only one high-impact improvement at a time after launch.

## What Ploy Should Not Do

- Do not redesign from scratch.
- Do not expand the copy.
- Do not add product screenshots, private workflows, player names, club examples, Quo, CourtReserve, Twilio, or roadmap claims.
- Do not add a blog, pricing page, comparison page, or SEO cluster yet.
- Do not invent integrations or operational features.
- Do not replace the visual system with stock photos.

## Paste Into Ploy

Use this prompt first:

```text
Import this public Give n Take landing page and preserve the current direction:

Live page: https://proposaldave.github.io/gnt-ai-landing-seed/
GitHub repo: https://github.com/proposaldave/gnt-ai-landing-seed

Goal: publish a public-safe landing page for www.gnt.ai while using as few Ploy credits as possible.

Do not redesign from scratch. Treat the current page as the approved V1 art direction and content strategy.

Keep the core story:
- Fill the next pickleball event with followers and referrals.
- Run one great event, then build a group that keeps coming back.
- Run great events.
- Followers keep up with great community builders.
- Community builders invite followers into the right events.
- Followers refer friends.
- The group grows naturally.

Keep the design direction:
- Premium, calm, blue/mint/white/gold Give n Take palette.
- Short copy.
- One strong hero visual.
- The four-step growth loop visible near the top of the page.
- One early-list form.
- No private club examples.
- No player data.
- No production product screenshots.

Only do these tasks:
1. Import/slurp the page.
2. Preserve the layout and copy unless a change is required to publish.
3. Replace the mailto form with a native early-list form.
4. Add analytics/visitor identification if included.
5. Prepare the simplest safe path to publish on www.gnt.ai.

Before making any major visual or copy change, explain the exact change and why it is necessary.
```

## What Codex Can Keep Doing Instead Of Ploy

- Copy changes.
- Visual direction and SVG assets.
- Static landing page build.
- GitHub commits and GitHub Pages deploys.
- Public-safe product positioning.
- Ploy prompts and briefs.
- A/B copy variants as separate files before spending Ploy credits.
- Product specs for future Give n Take features.

## When To Spend Ploy Credits

Spend Ploy credits only when the work requires Ploy's platform layer:

- Native form capture.
- Analytics and visitor identification.
- Domain publishing flow.
- Post-launch optimization.
- Account-based landing pages.
- SEO/AEO generation after the core brand page is approved.
- Ad landing pages after the offer is clear.

## Next Safe Ploy Step

Paste the prompt above into Ploy with the live page URL and GitHub repo. If Ploy proposes a full redesign, reject it and ask it to import/preserve instead.
