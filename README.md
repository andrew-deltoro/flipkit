# Website Flip: Taquería El Sol

**A before/after demo of a rapid website redesign for a local business — from 2010 to 2026 in 48 hours.**

This repo shows what a "website flip" looks like: taking a dated, non-responsive small-business website and rebuilding it into a modern, mobile-first, order-driving site — fast. **Taquería El Sol is a fictional business** created for this demo, but the process is exactly what I deliver to real local businesses.

## Pages

| Path                 | What it is |
| -------------------- | ---------- |
| `/index.html`        | Case-study showcase page (the studio's own brand). Live scaled previews of both versions, what changed, results, process, CTA. |
| `/before/index.html` | Deliberately dated 2009-era site: fixed 900px layout, Times New Roman + Comic Sans, clashing colors, tiled background, marquee + blinking text, visitor counter, "Under Construction", phone-only ordering. |
| `/after/index.html`  | Modern redesign: terracotta/cream/charcoal palette, Zodiak + General Sans typography, custom sun SVG logo, AI-generated food photography, sticky nav, Order Online / Call Now CTAs, full menu with prices, hours + location, testimonials, bilingual copy. |

All three pages cross-link with relative paths, so the folder works as a static bundle from any root.

## The Problem

Most local businesses have websites that were built once, years ago, and never touched again:

- Not mobile-friendly — while most local searches happen on phones
- No clear call to action — customers can't order, book, or call in one tap
- Slow load times that hurt Google rankings
- Dated design that undermines trust before a customer ever walks in

## The Flip

The redesign addresses each of those in a ~48-hour turnaround:

- **Mobile-first responsive layout** — looks right on every screen
- **Conversion-focused CTAs** — "Order Online" and tap-to-call buttons above the fold
- **Modern branding** — custom SVG logo, cohesive palette, real food photography
- **SEO fundamentals** — semantic HTML, meta tags, fast static pages
- **Bilingual touches** — meeting the customer base where it is

## Stack

Plain static HTML + CSS. Fonts from [Fontshare](https://www.fontshare.com/) (Switzer + Satoshi on the case study; Zodiak + General Sans on the redesign). ~20 lines of JavaScript total. No frameworks, no build step, no dependencies — static sites are the right tool for most local businesses: fast, cheap to host, and hard to break.

AI tools were used to accelerate design, copywriting, and image generation — the workflow that makes a 48-hour turnaround possible.

## Assets

`/assets/*.jpg` — AI-generated food and context photography (hero al pastor, birria, aguas frescas, carne asada, kitchen, phone mockup), resized to 1600px and JPEG-compressed.

## QA

Screenshots captured with Playwright at 1440px desktop and 390px mobile for the case study and the redesign; the `before` page was verified to render as intended (it is deliberately non-responsive at a fixed 912px canvas).

## Notes on the numbers

The load-time, usability and page-weight figures on the case-study page are illustrative, measured against the `before` page in this repository. Conversion or revenue claims are deliberately omitted — a demo can't measure them.

## Want this for your business?

If your website looks like the "before," I can get you to the "after" — fast. Reach out on [LinkedIn](#). <!-- TODO: add your LinkedIn URL -->

---

*Taquería El Sol is a fictional business created for demonstration purposes. Any resemblance to real businesses is coincidental.*
