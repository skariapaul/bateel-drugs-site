# Bateel Drug Store LLC — Website Revamp (Preview)

Revamped static site for [bateeldrugs.com](https://www.bateeldrugs.com/), parked on GitHub Pages for
review before any DNS/domain change. **The live domain is untouched.**

Live preview: https://skariapaul.github.io/bateel-drugs-site/

## Structure

| File | Page |
|---|---|
| `index.html` | Home — hero, about, brand portfolio, partnership, contact |
| `urgaid.html` | Urgaid Healthcare Solutions + Cool Patch |
| `tussolve.html` | Tussolve Syrup (dosage, composition, mode of action) |
| `reguard.html` | ReGuard first aid & hygiene (8 SKUs) |
| `clair.html` | Clair Oralcare (17 SKUs across 6 categories) |
| `fendoff.html` | FendOff Repellents (5 formulations) |
| `indeed.html` | Indeed Nutrition (8 supplements) |
| `assets/site.css` | Shared stylesheet for all pages |

No build step, no external dependencies — plain HTML/CSS.

## Assets

Brand logos, product photography, and the favicon were taken from the live site and stored under
`assets/`. Brand teal is `#09b89d` (sampled from the logo); a darker `#077a68` is used for body text
and buttons so contrast stays legible. Each brand page sets its own `--accent` to match its packaging.

- `assets/brands/` — the six brand logos
- `assets/p/` — product shots
- `assets/img/` — range/lifestyle banners

## Going live later

Add a `CNAME` file containing `www.bateeldrugs.com` and point DNS at GitHub Pages.

## Note on repo visibility

This repo is public because GitHub Pages is not available for private repos on the free plan.
Making it private again disables Pages; keeping the source private requires GitHub Pro.
