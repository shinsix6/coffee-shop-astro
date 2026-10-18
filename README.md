# Coffee Shop Landing Page

A single-page landing site for a fictional neighbourhood coffee shop. Built as a design and front-end showcase, not a production site for a real business.

## Stack

- [Astro](https://docs.astro.build) 7
- [Tailwind CSS](https://tailwindcss.com) 4 via `@tailwindcss/vite`
- No client-side JavaScript

## The landing page

One scrolling page, six sections:

- **Navbar** — sticky header, logo and navigation
- **Hero** — headline, subheadline and a View Menu call to action
- **About** — the shop's story and sourcing, paired with a photo
- **Menu** — item cards with photography, linking out to a full menu
- **Gallery** — a photo grid of the shop and its people
- **Contact** — address, opening hours and email

Styling follows `DESIGN.md`, an Art Nouveau brief: ornamental borders, whiplash curve dividers, a stained glass motif, asymmetric grids, and a palette of deep teal, old gold, burgundy and ivory set in Quattrocento. The brand colours live as tokens in `src/styles/global.css`. Sections fade and rise into place on load, and the animation is disabled for visitors who prefer reduced motion.

## Running it

Requires Node 22.22 or newer.

```sh
npm install
npm run dev
```

## Showcase only

This is a portfolio piece. The shop name, address, email, opening hours, prices and photography are all invented, and every menu and call-to-action link is a placeholder pointing nowhere. Swap all of it before the page goes anywhere near a real audience.