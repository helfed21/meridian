# MERIDIAN — website

Static site, no build step. Upload the whole folder to any static host (Netlify, Vercel, GitHub Pages) or open `index.html` locally.

## Pages
index.html · studio.html · projects.html · harbour-house.html · services.html · process.html · journal.html · contact.html

## Files
- `assets/css/style.css` — tokens, components, responsive layout (mobile below 900px), animations
- `assets/js/main.js` — mobile menu, scroll reveals, project filters and bottom sheet, chip groups, form validation
- `assets/img`, `assets/video` — optimised photos and loops
- `assets/og` — 1200×630 social preview image per page
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`, `robots.txt`, `sitemap.xml`

## Before deploy
1. Replace `https://www.meridian-ateliers.com` with the real domain: every page head (canonical, og:url, og:image, twitter:image), `robots.txt`, `sitemap.xml`. One find-and-replace across the folder.
2. Connect the two forms (contact.html, harbour-house.html) to Formspree / Netlify Forms: set the form `action`. Look for the `TODO: form handler` comment.
3. Paste GA4 and Meta Pixel snippets where the `<!-- GA4 -->` and `<!-- Meta Pixel -->` comments are, if you use them.

Studio details (addresses, clients, publications, awards) are invented for the portfolio. The phone number uses the UK range reserved for fiction (020 7946 0xxx).
