# MTA CheatSheet
[![Deploy](https://github.com/ssebs/MTG-CheatSheet/actions/workflows/deploy.yml/badge.svg)](https://github.com/ssebs/MTG-CheatSheet/actions/workflows/deploy.yml)

A single-page, searchable cheat sheet of Magic: The Gathering keywords, rules terms, and the fine distinctions that come up at the Commander table. It's one self-contained `index.html` — no build step, no dependencies.

Check it out now at: https://ssebs.github.io/MTG-CheatSheet

## Features
- **Instant search** — filter every entry as you type, with matches highlighted.
- **Sections that collapse** — expand/collapse any category, or all at once.
- **Table of contents** — jump to any section, with scroll-spy highlighting where you are.
- **Fully responsive** — the TOC becomes a drawer on mobile.
- **Zero dependencies** — one HTML file, no build, no framework.

## Usage
Just open `index.html` in a browser, or visit the [live site](https://ssebs.github.io/MTG-CheatSheet/). Type in the search box to filter, or click a section header to collapse it.

Keyboard shortcuts:
- `/` — focus the search box
- `Esc` — clear the search (or close the mobile TOC)

## Running locally
No tooling required — just open the file:
```sh
git clone https://github.com/ssebs/MTG-CheatSheet.git
cd MTG-CheatSheet
# open index.html in your browser, or serve it:
python -m http.server
```

## Deploying to GitHub Pages
Pushing to `main` deploys automatically via the [`deploy.yml`](./.github/workflows/deploy.yml) workflow. One-time setup:
- Go to **Settings** > **Pages** in the repo.
- Under **Build and deployment** > **Source**, pick **GitHub Actions**.

The site publishes to `https://<username>.github.io/MTG-CheatSheet/`.

## LICENSE
Licensed under the [Apache 2 License](./LICENSE).
