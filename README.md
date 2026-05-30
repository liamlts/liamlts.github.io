# liamlts.github.io

Personal academic website of **Liam T. Schmidt** — PhD candidate in condensed
matter physics at Northeastern University (DeLTA Lab, Quantum Matter and Sensing
Institute).

Live at **https://liamlts.github.io/**.

## What this is

A hand-built static site — plain HTML, CSS, and vanilla JavaScript, no framework
or build step. The only external dependencies are loaded from CDNs at runtime
(Google Fonts, [Leaflet](https://leafletjs.com/) for the facilities map, and
CARTO basemap tiles).

## Structure

```
site/                  # everything that gets published
├── index.html         # single-page bio, research, publications, talks, teaching
├── experience.html    # CV / experience page
├── projects/          # research-area detail pages
├── css/style.css      # all styling
├── images/            # photos, project/publication/event thumbnails
├── media/             # avatar
├── uploads/resume.pdf
├── robots.txt
└── 404.html
.github/workflows/deploy.yml   # GitHub Pages deployment
```

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which uploads the
`site/` directory as the GitHub Pages artifact and deploys it. There is no build
step — `site/` is served as-is.

To preview locally:

```bash
cd site && python3 -m http.server 8000
# open http://localhost:8000
```

## License

[MIT](LICENSE.md) © Liam T. Schmidt
