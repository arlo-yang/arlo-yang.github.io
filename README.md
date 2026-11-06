# arlo-yang.github.io

Personal website for Yi (Arlo) Yang.

The site is built with Jekyll, based on the al-folio academic theme, and publishes to GitHub Pages from the `gh-pages` branch.

## Update Content

- Edit the homepage bio in `_pages/about.md`.
- Edit publications in `_bibliography/papers.bib`.
- Edit site metadata and social links in `_config.yml`.

## Deploy

Push changes to `main`; the `Deploy site` GitHub Action builds the site and publishes `_site` to `gh-pages`.

GitHub Pages should be configured as:

- Source: `Deploy from a branch`
- Branch: `gh-pages`
- Folder: `/`
