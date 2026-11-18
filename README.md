# Pakaoo — SEO-Optimized Portfolio Demo (Type A)

A 5-page, SEO-first portfolio site built for the r/FreelanceIndia lead (u/VinayakSingh53), founder of Pakaoo — a Bengaluru food-tech startup seeking a Next.js developer with strong SEO.

## Live Demo
https://slavh.github.io/pakaoo-portfolio-demo/

## Pages
- `index.html` — Home (hero, value props, stats, CTA)
- `about.html` — Our story
- `menu.html` — Menu with structured data
- `partners.html` — Partner kitchens / brands
- `contact.html` — Contact form (demo, wires to API in production)

## SEO implementation (the lead's stated priority)
- ✅ Server-rendered/static HTML output (maps directly to Next.js SSG — every page is pre-rendered)
- ✅ Unique `<title>` + meta description on every page
- ✅ Open Graph tags (og:type, title, description, url, image) on every page
- ✅ Twitter Card tags
- ✅ JSON-LD structured data (`Organization`, `AboutPage`, `Menu`, `ContactPage`) per page
- ✅ Canonical URLs
- ✅ `sitemap.xml` + `robots.txt`
- ✅ Semantic HTML (`<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`), labelled nav/landmarks
- ✅ Responsive layout, optimized images (lightweight inline SVG for OG image), fast-loading CSS
- ✅ `<html lang>`, descriptive alt/labels, clean URL structure

## Production notes
This static demo mirrors what the production Next.js build will do. To hit Lighthouse 90+ in production: use `next/image` for optimization, `next/head` or the Metadata API for the tags above, `app/sitemap.ts` + `app/robots.ts`, and wire the contact form to a server action / API route. Figma-to-pixel conversion replaces the placeholder art.

## Price note
Quoted fairly in the outreach message; lead's budget was ₹10,000 (~$120), within the $40–$250 range.
