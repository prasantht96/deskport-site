# DeskPort site

Static site for the DeskPort Android app (`com.deskport.app`). Plain HTML plus one CSS file (`assets/style.css`). No build step, no scripts, no trackers, no external fonts.

Live URL: https://prasantht96.github.io/deskport-site/

## Pages

index.html, privacy.html, terms.html, refunds.html, support.html, delete-data.html, 404.html, plus robots.txt, sitemap.xml and .nojekyll.

## Publish (GitHub Pages)

1. Create the repo `prasantht96/deskport-site` on GitHub (public).
2. Push this folder to the `main` branch.
3. In the repo go to Settings, Pages, set Source to "Deploy from a branch", Branch `main`, folder `/ (root)`.
4. Wait a minute, then open the live URL above.

## Assets to replace

The files in `assets/` are generated placeholders in the brand gradient. Replace them with the real art, keeping the same filenames and sizes:

| File | Size | Used for |
|---|---|---|
| assets/hero.jpg | 1024 x 500 | Hero image on the home page |
| assets/feature-1024x500.jpg | 1024 x 500 | Feature image on the home page (also fits the Play feature graphic) |
| assets/og-1200x675.jpg | 1200 x 675 | Social share image (Open Graph and Twitter) |
| assets/icon-192.png | 192 x 192 | Header logo and apple-touch-icon |
| assets/favicon-32.png | 32 x 32 | Browser tab icon |

## Editing notes

- No em dashes or en dashes anywhere (use commas, colons or hyphens).
- Contact email: tprasanth696@gmail.com. Effective date on the legal pages: 2026-10-14. Update the date when you change a policy.
- Keep the app's `PolicyLinks.kt` URLs in sync with the page names.
