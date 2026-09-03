# SEVERPRINT

3D printing on demand — a Tilda landing page.

**Live:** https://pafuluofu-dev.github.io/tilda-severprint/

## About

Landing page for a made-to-order 3D printing service — prototyping, one-off parts and small production runs. Long-scroll layout built in Tilda's Zero Block with a sticky nav, anchor navigation between sections, a materials and use-case breakdown, and a quote request form.

Interface language is Russian.

## Stack

- **Tilda** — Zero Block layout, built from the platform's page builder
- **Static site** — plain HTML, CSS and JavaScript, no build step and no server
- Tilda's runtime bundle: grid, lazy-loading, forms, menu and animation modules

## Running locally

Any static file server works. From the repository root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

Opening `index.html` straight off the filesystem mostly works too, but a
server is closer to how it is actually deployed.

## Layout

```
index.html   the page itself
assets/      74 files — styles, scripts, images and fonts
```

## Notes

- The site credit in the footer (*Разработка сайта*) links to my Telegram.
