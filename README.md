# F&B Construction Group — Website

A complete, ready-to-publish website for F&B Construction Group.

## What's inside
```
index.html        the whole site (all sections)
styles.css        all styling
script.js         mobile menu, scroll reveal, project filter, lightbox, contact form
assets/
  logo-original.jpg      logo on white background (used for SEO/social previews)
  logo-transparent.png   logo with transparent background (used in header & footer)
  favicon.svg            browser-tab icon
  hero-bridge.jpg        homepage hero background photo
  director-blair.jpg     director's photo
  projects/              9 real project photos shown in the gallery
```

## How to put this on the internet

This is a **static site** — plain HTML/CSS/JS with no server or database required.
Google Sites does not accept custom code uploads like this, so use one of these instead (all free):

### Option A — GitHub Pages (free, easiest for a permanent URL)
1. Create a free account at github.com if you don't have one.
2. Create a new repository (e.g. `fb-construction`).
3. Upload all the files in this folder (keep the `assets` folder structure).
4. Go to the repo's **Settings → Pages**, set source to the `main` branch, root folder.
5. Your site goes live at `https://yourusername.github.io/fb-construction/`.

### Option B — Netlify (free, fastest)
1. Go to netlify.com and sign up.
2. Drag and drop this whole folder onto the "Deploy" area on your dashboard.
3. Netlify gives you a live URL immediately; you can add a custom domain later (e.g. fbconstruction.com).

### Option C — Your own hosting / cPanel
Upload all files via FTP or the File Manager into your site's `public_html` folder, keeping the `assets` folder intact.

## Getting found on Google
- Once live, submit your URL at **Google Search Console** (search.google.com/search-console) — add your domain, verify ownership, and submit the homepage for indexing.
- The site already includes SEO basics: a descriptive title, meta description, and structured business data (name, hours, contact, director) that helps Google show rich results.
- Consider creating a **Google Business Profile** (business.google.com) for F&B Construction Group too — it's separate from this website but is usually what makes a business show up on Google Maps and in local search.

## Editing content later
- Text: open `index.html` in any text editor and edit between the tags.
- Colors/fonts: open `styles.css` — the main brand colors are defined at the top under `:root`.
- Photos: real project photos now live in `assets/projects/`. To add more, drop a new `.jpg` into that folder and copy one `<article class="project-card">` block in `index.html`, updating the `data-category`, `data-full`, `data-caption`, image `src`/`alt`, and the text underneath.
- Director photo: `assets/director-blair.jpg`, shown in the About section.
- Logo: `assets/logo-original.jpg` (white background, used for previews/SEO) and `assets/logo-transparent.png` (transparent background, used in the header and footer).

## Contact details currently on the site
- Email: fbconstructiongroup34@gmail.com
- WhatsApp: +254 758 583 185
- Director: Blair Wright Benard
- Hours: Mon–Sat 8:00–18:00, Sunday closed
