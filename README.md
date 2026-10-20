# Chalumna GitHub Pages website — V2

A responsive, single-page website for the Chalumna organisation. Version 2 brings the original colored-pencil coelacanth logo into the design and balances its sketchbook warmth with the deep-ocean palette.

## Publish on GitHub Pages

1. Create a **public** repository in the `Chalumna` GitHub organisation named exactly `Chalumna.github.io`.
2. Upload all files and folders from this package to the repository root. `index.html` must be at the root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for the deployment and open <https://chalumna.github.io/>.

## Included

- `index.html` — all website content and SEO metadata
- `assets/styles.css` — responsive visual design
- `assets/main.js` — mobile navigation and current footer year
- `assets/logo.png` — the supplied Chalumna colored-pencil logo
- `assets/favicon.svg` — site favicon
- `robots.txt` and `sitemap.xml` — basic crawler support

## Before publishing

- Check the contact email and repository links.
- Review all project status descriptions before publication.
- The site does not embed third-party coelacanth photographs; the hero uses the supplied Chalumna logo artwork.
- The logo is described in the organisation README as CC0 1.0. Code and any future dataset files remain under their own separate licence terms.
- Do not publish exact coelacanth observation locations or sensitive metadata.

## SEO

- `description`, Open Graph metadata and structured data are included in `index.html`.
- `robots.txt` and `sitemap.xml` are included.
- After the site is live, add `https://chalumna.github.io/` to Google Search Console and submit `https://chalumna.github.io/sitemap.xml`.
- Indexing is not guaranteed or immediate.

The site is plain HTML, CSS and JavaScript; no build step is required.
