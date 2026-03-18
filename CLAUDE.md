# ATELIER — Architecture Studio Demo

A clean, minimal architecture firm website demo with full-screen vertical slide transitions.

## Tech Stack

| Layer | Technology | Notes |
|-------|-----------|-------|
| Framework | Astro | Static site generator |
| Slides | Swiper.js | Vertical slides, parallax, mousewheel nav |
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

- [x] Hero — "ATELIER" with CSS architectural line drawing, parallax
- [x] Philosophy — Quote + geometric composition, two-column layout
- [x] Projects — 4 project cards with gradient thumbnails, hover states
- [x] Process — CONCEPT → DESIGN → BUILD with CSS icons and connectors
- [x] Awards — Editorial-style award list, 7 entries
- [x] Contact — Studio info, address, clean footer

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
