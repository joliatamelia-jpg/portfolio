# Amelia Joliat — Portfolio

Personal portfolio site. Static HTML, no build step.

## Pages

| File | Page |
|---|---|
| `index.html` | Home / work index |
| `about.html` | About, skills, timeline, gallery |
| `kress.html` | Kress case study |
| `launchpad.html` | Launchpad case study |
| `web-ads.html` | Web Ads case study |
| `prickles-and-pots.html` | Prickles & Pots case study |
| `order-ahead-app.html` | Order Ahead App case study |

## Supporting files

- `support.js`, `image-slot.js` — page runtime, required
- `assets/` — images, PDFs, live HTML5 ad units, prototype screens
- `LaunchPadReport4.pdf` — source for the Launchpad flip-through

## Publishing with GitHub Pages

1. Create a new repository on GitHub. Name it `ameliajoliat.github.io` for a
   root domain, or anything else to publish under a subpath.
2. Upload the contents of this folder to the repository root — not the folder
   itself, the files inside it. `index.html` must sit at the top level.
3. Repository → **Settings** → **Pages**.
4. Under Source choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Save. The site goes live in a minute or two at
   `https://<username>.github.io/` (or `/<repo-name>/`).

### Custom domain

Buy the domain, then in Settings → Pages → Custom domain enter it and follow
GitHub's DNS instructions. Leave **Enforce HTTPS** checked.

## Notes

- Every page is self-contained; fonts load from Google Fonts.
- The ad units in `assets/ads/` are live HTML5, embedded as iframes.
- The prototypes are image-hotspot based: screens in `assets/pp/` and
  `assets/lc/`, click regions defined in the page source.
