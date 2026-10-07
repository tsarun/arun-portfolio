# Arun TS — Portfolio

Personal portfolio of **Arun TS**, Senior AI Product Manager & Product Leader (16+ years across AI, telecom, fintech, and banking).

A fully static site — no build step, no dependencies, no backend. Open `index.html` or deploy the folder as-is.

## Deploy to GitHub Pages

1. Push this folder to your repository (e.g. `tsarun/tsarun.github.io` or any repo).
2. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
3. For a custom domain (e.g. `tsarun.com`): add a `CNAME` file containing `tsarun.com`, then point your DNS at GitHub Pages (`A` records to `185.199.108.153`–`111`, or a `CNAME` to `<user>.github.io`).

Any static host (Netlify, Vercel, Cloudflare Pages, S3) works the same way — drop the folder in.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire site — markup, styles, and a small script for the theme toggle and recruiter mode |
| `assets/arun-ts-hero.webp` | Hero portrait (light background) |
| `assets/arun-ts-hero-dark.webp` | Hero portrait (dark background, shown automatically in dark mode) |
| `assets/arun-ts-profile-photo.png` | Profile photo used in the recruiter brief |
| `assets/Arun_TS_Senior_Product_Manager.pdf` | Resume, linked from all download buttons |
| `assets/og-image.png` | Social share image (referenced by the Open Graph / Twitter meta tags) |

## Features

- Light/dark theme toggle — keyboard accessible, screen-reader announced, remembers the visitor's choice, respects reduced-motion settings
- Recruiter mode — a 60-second one-view brief of the same content
- Responsive hero with theme-aware portrait crossfade
- Sections: impact metrics, selected work, experience, toolkit, independent AI builds with case studies, mentoring, LinkedIn recommendations, contact
- SEO + social meta tags and schema.org Person markup

## Notes

- The `og:image` and canonical URLs point to `https://tsarun.com/` — update them in `index.html` if you deploy under a different domain.
- Everything runs client-side; there is no tracking, no cookies, and nothing is sent to a server.
