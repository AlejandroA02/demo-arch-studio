# MEMORY

## Last Session
- **Date:** 2026-03-18
- **Accomplished:** Built architecture studio demo. Iterated from Swiper slides → split-scroll with mixed vertical and horizontal splits. Pushed to GitHub (AlejandroA02/demo-arch-studio). Pending Vercel deploy.
- **Where we left off:** Site is polished and pushed. Ready for Vercel import.

## Pending Items
- [ ] Import repo on Vercel for auto-deploy
- [ ] Optional: mobile hamburger menu

## Active Decisions & Context
- Part of a series of demo sites (naming: `demo-*`)
- Architecture theme — clean, minimal, warm stone palette
- User specifically wanted mixed split directions (vertical + horizontal) with smooth dismantling/constructing feel
- Swiper was dropped in favor of GSAP ScrollTrigger for more flexible split-scroll behavior

## Known Gotchas
- Lenis duration set to 1.8 with scrub: 2 for extra smoothness — user confirmed this feels right
