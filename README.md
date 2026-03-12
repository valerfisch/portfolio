# Portfolio

My personal portfolio site, built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages.

**Live at** https://valerfisch.github.io/portfolio

## Project Structure

```
content/              Markdown content for each page/section
  _index.md           Homepage
  about.md            About page
  awards/             Awards section (ordered by filename prefix)
  cv/                 CV/experience entries (ordered by filename prefix)
layouts/              Hugo HTML templates
  _default/           Base layout (baseof, list, single)
  partials/           Shared components (header, footer, nav, meta)
  awards/             Award-specific list/single templates
  cv/                 CV-specific list/single templates
assets/
  sass/main.scss      Styles
  images/             Image assets
hugo.toml             Site configuration
```

## Getting Started

You need [Hugo](https://gohugo.io/installation/) installed.

Run the dev server:

```sh
hugo server -D
```

Site is then available at `http://localhost:1313/portfolio/` with live reload.

To build the static site into `public/`:

```sh
hugo
```

## Content

All content is in `content/` as Markdown with YAML front matter. Sections like `awards/` and `cv/` use numeric filename prefixes for ordering (e.g. `01_bmw.md`, `02_straightlabs.md`). Each section has its own `_index.md` for the list page and corresponding layout templates in `layouts/`.

## Deployment

Deployed to GitHub Pages from the `public/` directory.