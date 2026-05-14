# Production Ready NJ

**Get found when productions come to town.**

> *Production Ready NJ helps local New Jersey businesses, locations, crew, and on-screen talent get properly listed on the state's official film-industry directories.*

A one-page site plus a `/productions` reference page covering productions filmed in Monmouth County and the Jersey Shore. Built around the NJ-411 directory ecosystem and the production boom New Jersey is currently in.

## Pillar
Independent venture — not part of any other pillar in the ecosystem. Sober, industry-credible voice; no cosmic register.

## Status
- **Public repo, noindex stealth** — github.io subdomain only; custom domain pending
- **Domain:** productionreadynj.com
- **Demo:** `index.html` at repo root
- **Subpage:** `productions.html`
- **Stylesheet:** `styles.css` (shared)
- **Live URL:** https://productionreadynj.com

## File Structure
```
production-ready-nj/
├── index.html        # main landing page
├── productions.html  # productions filmed locally — reference page
├── styles.css        # shared stylesheet (brand colors, typography, responsive)
├── README.md         # this file
└── CNAME             # auto-created by GitHub Pages
```

## What's still TODO before launch
- Add real phone number (`tel:` link in `#contact` and footer)
- Add Calendly link (`#contact` schedule line)
- Optionally swap "Get started" button on Packages section for direct Stripe Payment Links per tier (commented in the HTML)
- Confirm Plus-tier description (Deal Sheet contents) once first paid client validates the format
- Add favicon and Open Graph image
- Optional: Formspree or similar form solution for inbound leads, if not relying on direct email

## Brand
- **Navy:** `#0a2540`
- **Cream:** `#f5efe6`
- **Yellow:** `#f4c536`
- **Yellow-dark (eyebrows/accents):** `#8a6a1f`
- **Type:** system-ui sans stack

## Source of truth
- **Drive archive:** keep this same set of files mirrored at the repo path used in the BRET deploy workflow
- **Repo deployment:** these are the deployment copies
- Keep both aligned when HTML/CSS is updated

---
*Founder: Bret Warshawsky — bret@productionreadynj.com*
*Independent service. Not affiliated with the New Jersey Motion Picture & Television Commission.*
