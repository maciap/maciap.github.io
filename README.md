# Martino Ciaperoni — personal website

This repository contains the source code for my personal academic website:

**https://maciap.github.io**

The website is built with [al-folio](https://github.com/alshedivat/al-folio), a Jekyll theme for academic websites, and hosted with GitHub Pages.

## Website contents

The website includes:

- a short academic profile, research areas, news and selected publications (home page)
- full publication list
- CV (web version and PDF)
- teaching and thesis supervision
- news
- selected code repositories

## Main files to update

Most website content can be edited from the following files:

```text
_pages/about.md              # homepage (bio, quick links, research areas)
_layouts/about.liquid        # homepage layout
_bibliography/papers.bib     # publication list (selected={true} shows on the homepage)
_news/                       # one Markdown file per news item
_data/cv.yml                 # CV page content
assets/pdf/Martino_Ciaperoni_CV.pdf  # downloadable CV
_pages/teaching.md           # teaching page
_data/repositories.yml       # repositories shown on the code page
_sass/_custom.scss           # site-specific styling
_config.yml                  # site-wide configuration
