# C & N Prestige Cleaning Services LLC

Marketing website for **C & N Prestige Cleaning Services LLC**, premium residential and commercial cleaning serving **San Antonio and the Dallas-Fort Worth metroplex, Texas**.

## Overview

A fast, fully static, mobile-first website built with HTML + [Tailwind CSS](https://tailwindcss.com) (CDN). Clean white and lavender theme with the brand's deep purple and violet pulled from the logo.

## Pages

Each page lives in its own folder as an `index.html`, so it is served at a clean, extensionless URL on any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).

| Page | URL | File |
| --- | --- | --- |
| Home | `/` | `index.html` |
| Residential Cleaning | `/residential-cleaning/` | `residential-cleaning/index.html` |
| Deep Cleaning | `/deep-cleaning/` | `deep-cleaning/index.html` |
| Recurring Cleaning | `/recurring-cleaning/` | `recurring-cleaning/index.html` |
| Move-In / Move-Out Cleaning | `/move-in-out-cleaning/` | `move-in-out-cleaning/index.html` |
| Commercial Cleaning | `/commercial-cleaning/` | `commercial-cleaning/index.html` |
| Post-Construction Cleaning | `/post-construction-cleaning/` | `post-construction-cleaning/index.html` |
| Vacation Rental / Airbnb Cleaning | `/airbnb-cleaning/` | `airbnb-cleaning/index.html` |
| Add-On Services | `/add-on-services/` | `add-on-services/index.html` |

## Features

- Fully responsive, mobile-optimized layout with an accessible hamburger menu and a services dropdown that works on hover, keyboard focus and tap
- Brand colors matched to the logo: plum `#2d1b5e`, royal `#4a2a86`, violet `#7b4fc1`, lilac `#b79be3`, lavender `#f4f0fb`
- SEO: unique titles, meta descriptions, keywords, canonical URLs, Open Graph and Twitter cards, JSON-LD `LocalBusiness` / `CleaningService`, `Service`, `BreadcrumbList` and `FAQPage` schema
- Clean, extensionless URLs with no `.html` anywhere in the site
- `sitemap.xml`, `robots.txt` and `site.webmanifest`
- Favicon set: `favicon.ico` (16 to 64px), PNG icons (16, 32, 256px), Apple touch icon and 512px PWA icon, all cut from the logo emblem
- Local stock photography in `images/` plus curated Unsplash imagery matched to each service
- Scroll-reveal animations, FAQ accordions and a quote request form

## Things to update before launch

- **Domain**: all canonical URLs, Open Graph tags, `sitemap.xml` and `robots.txt` currently use `https://cnprestigecleaning.com`. Search and replace if the final domain differs.
- **Phone number**: no business phone is shown yet. Add it to the contact section and footer once confirmed.
- **Email**: `info@cnprestigecleaning.com` is a placeholder. Replace with the real inbox.
- **Quote form**: currently opens the visitor's email app with the request pre-filled (no backend). Wire it to a form service or booking embed when ready.
- **Service areas**: confirm the exact San Antonio and DFW cities served.
- **Reviews**: the testimonials are starter copy. Swap in real Google reviews when available.
- **Social links**: none are included yet. Add Facebook, Instagram or Google Business links to the footer as needed.

## Local preview

Serve the folder rather than opening the files directly, so the directory-based URLs resolve:

```bash
npx serve .
```
