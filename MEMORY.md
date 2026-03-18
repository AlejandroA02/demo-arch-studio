# MEMORY

## Last Session
- **Date:** 2026-03-18
- **Accomplished:** Built architecture studio demo with split-scroll animations, SVG blueprint drawings that assemble on scroll (thick walls, dimension chains, furniture detail, fading grid background). Pushed to GitHub, deploying to Vercel.
- **Where we left off:** Site complete and deployed. Part of demo site collection.

## Pending Items
- [ ] Optional: mobile hamburger menu
- [ ] Optional: rebuild remaining blueprints to match blueprint 1's full detail level

## Active Decisions & Context
- Part of a series of demo sites (naming: `demo-*`)
- Architecture theme — clean, minimal, warm stone palette (Bodoni Moda + Karla fonts)
- Mixed split directions (vertical + horizontal) with smooth dismantling/constructing feel
- SVG blueprints with line-drawing animation on scroll — bronze/stone colored lines on transparent background with fading grid
- User wants blueprints to look like real architectural drawings with thick walls, dimensions in meters, room labels, area calculations
- No blue/navy backgrounds — lines should match site's color palette

## Known Gotchas
- Lenis duration 1.8 with scrub: 2 for smoothness
- Dev server keeps dying in Claude's environment — user needs to run `npm run dev` in their own terminal
- Don't use filled rects for masking — they show as black squares on transparent backgrounds
