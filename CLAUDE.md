# ATELIER — Architecture Studio Demo

A clean, minimal architecture firm website demo with full-screen vertical slide transitions.

## Tech Stack

| Layer | Technology | Notes |
|-------|-----------|-------|
| Framework | Astro | Static site generator |
| Scroll | GSAP ScrollTrigger + Lenis | Split-scroll animations, smooth scrolling |
| Animations | GSAP | Slide entrance micro-animations |
| Fonts | Bodoni Moda (display) + Karla (body) | Google Fonts |
| Hosting | Vercel | Auto-deploys from GitHub |
| Repo | github.com/AlejandroA02/demo-arch-studio | Public repo |

## Architecture

Single-page static site. One `index.astro` file with 6 full-screen Swiper slides. No components, no layouts.

## Project Structure

```
src/
  pages/
    index.astro    ← entire site
public/
  favicon.svg
```

## Sections (Swiper Slides)

- [x] Hero — "ATELIER" with CSS grid lines, fade on scroll
- [x] Philosophy (vertical split) — left up / right down
- [x] Meridian House (horizontal split) — top left / bottom right
- [x] Terra Office Tower (reversed vertical split) — right up / left down
- [x] Process (reversed horizontal split) — opposite horizontal movement
- [x] Awards (vertical split) — left up / right down
- [x] Contact — Dark section, full width

## Key Decisions

| Decision | Why | Date |
|----------|-----|------|
| Swiper.js for slides | User provided Swiper config, vertical full-screen slides | 2026-03-18 |
| Light/warm palette | Architecture firms favor clean, neutral aesthetics | 2026-03-18 |
| Bodoni Moda font | High-contrast serif = architectural, editorial feel | 2026-03-18 |
| No external images | Demo site uses CSS gradients and shapes only | 2026-03-18 |

## Known Issues

- Navigation links hidden on mobile (hamburger menu not implemented)
- Build shows a CSS import warning (cosmetic, doesn't affect output)

## Development Commands

| Command | What it does |
|---------|-------------|
| `npm run dev` | Start dev server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
