# Chalumna website

Source of [chalumna.github.io](https://chalumna.github.io/), the public website of the Chalumna organisation.

[Website](https://chalumna.github.io/) · [GitHub organisation](https://github.com/chalumna) · [Contact](mailto:maelig.pesco@gmail.com)

The website presents Chalumna, a small, independent, open-source project exploring whether modern computer vision can help identify individual coelacanths (*Latimeria*) from their white spot patterns, without tagging, touching, or otherwise disturbing the animals.

## Purpose

The site is a short public overview of the project. It describes:

- **Research**: the scientific motivation and planned research directions.
- **Projects**: the repositories in the organisation and their current status.
- **Principles**: open code, data used only with permission, protection of sensitive locations, and non-invasive methods.
- **References**: the published work the project builds on.

The site describes an early-stage project. Nothing on it should be read as a validated tool for scientific monitoring or as a claim of results.

## How the website was made

The website (HTML, CSS, JavaScript and SEO metadata) was **generated with ChatGPT**, based on a prompt and on content written and supplied by the project author. The author then reviewed and edited it before publication.

Scientific content, project descriptions and references come from the author and from the cited publications. The [organisation README](https://github.com/chalumna/.github) is the reference text. If the website and the README disagree, the README is authoritative.

## Repository contents

| File | Description |
| --- | --- |
| `index.html` | Page content, metadata (description, Open Graph, structured data) |
| `assets/styles.css` | Responsive layout and visual design |
| `assets/main.js` | Mobile navigation and footer year |
| `assets/logo.png` | Chalumna logo |
| `assets/favicon.png` | Site icon |
| `robots.txt` | Crawler rules |
| `sitemap.xml` | Sitemap submitted to search engines |
| `google*.html` | Google Search Console ownership verification. Do not delete. |

The site is plain HTML, CSS and JavaScript. There is no build step and no dependency.

## Local preview

```bash
git clone https://github.com/chalumna/chalumna.github.io.git
cd chalumna.github.io
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

The site is served by GitHub Pages from the root of the `main` branch (**Settings → Pages → Deploy from a branch**). Each push to `main` is published automatically, usually within a few minutes.

## Content rules

Changes to the website follow the organisation's principles:

- **No coelacanth images without permission.** The site does not embed third-party coelacanth photographs. Any image added later must be authorised by its rights holder, and its source and licence must be stated.
- **No sensitive locations.** Exact coelacanth observation locations and sensitive metadata are never published.
- **No overstated claims.** Project status must match the actual state of each repository. Results are described only once they exist and can be reproduced.
- **Citations.** Scientific statements are linked to their source in the References section.

## Contributing

Corrections and suggestions are welcome. Open an issue or a pull request in this repository, or get in touch by email.

## Independence

Chalumna is an independent personal project. It is not affiliated with, endorsed by, or officially connected to any research programme, institution, or company mentioned on the website unless explicitly stated otherwise.

## Licensing

- **Logo**: generated with ChatGPT and released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), as stated by the project.
- **Website code and text**: see the `LICENSE` file of this repository. Other repositories in the organisation are licensed separately.
- **Images and videos**: remain subject to the rights and conditions set by their creators, collectors and institutions.

## References

- Thornycroft, R. E. & Booth, A. J. (2012). Computer-aided identification of coelacanths, *Latimeria chalumnae*, using scale patterns. *Marine Biology Research*, 8, 300–306. <https://doi.org/10.1080/17451000.2011.628679>
- Nulens, R., Scott, L. & Herbin, M. (2011). An updated inventory of all known specimens of the coelacanth, *Latimeria* spp. *Smithiana Special Publication* 3. South African Institute for Aquatic Biodiversity.
