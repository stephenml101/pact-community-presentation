# PACT Community presentation

This folder contains the revised static presentation site.

## Files

- `index.html` — presentation layout, styling, and interaction
- `assets/pact.jpg` — PACT brand artwork
- `assets/stephen-headshot.jpeg` — presenter portrait
- `assets/gsd-mode.png` — GSD Mode hero artwork
- `assets/next-level-agents.png` — Next Level Agents hero artwork
- `assets/exp-realty.png` — eXp Realty hero artwork
- `assets/fastlead.png` — FastLead hero artwork
- `assets/fastlead-gallery/` — 35 optimized FastLead result images
- `assets/best-life-builders.jpg` — BEST Life Builders hero artwork
- `assets/best-life-gallery/` — 24 optimized BEST Life Builders community photos
- `assets/best-life-stories/` — five BEST Life Builders success-story portraits

Publish the folder as a static website with `index.html` at the site root and the `assets` folder beside it.

## Editing and publishing

Edit `index.html` for layout, copy, styling, and interactions. Keep images in `assets/` and use relative paths so local previews and the published site stay in sync.

The `main` branch is connected to the production site on Vercel. Changes merged or pushed to `main` publish automatically after Vercel finishes its deployment checks.

The presentation keeps PACT at the center with six supporting programs and 23 smaller perimeter bubbles that summarize what comes included:

- Next Level Agents
- GSD Mode
- Best Life Builders
- FastLead.io
- eXp Realty
- VA Real Estate Team

All exploration happens on the page through an accessible detail window. No resource opens a separate website. The GSD Mode and Next Level Agents podcasts plus the BEST Life Builders, FastLead, and eXp videos load inside the presentation only after the visitor presses **Play here**. Each detail view includes a disabled placeholder for the future website link.
