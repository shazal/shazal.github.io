# shazal.github.io

Personal academic website of Shazal Irshad, built with [al-folio](https://github.com/alshedivat/al-folio).

## Structure

- `_pages/about.md` — homepage
- `_pages/publications.md` — publications page
- `_bibliography/papers.bib` — all publications in BibTeX format
- `_news/` — news items shown on the homepage
- `assets/img/prof_pic.jpg` — profile photo
- `assets/pdf/shazal_cv.pdf` — CV (linked from about page)
- `_config.yml` — site configuration

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Adding a publication

Open `_bibliography/papers.bib` and add a new BibTeX entry. It will appear automatically on the publications page.

## Adding a news item

Create a new `.md` file in `_news/` following this format:

```markdown
---
layout: post
date: 2026-01-01
inline: true
---

Your news item text here.
```

## Deployment

Pushing to `master` triggers the GitHub Actions workflow which builds the site and deploys it to the `gh-pages` branch. The site is served at [https://shazal.github.io](https://shazal.github.io).