# Shazal Irshad — al-folio Site Files

These are the custom content files for your al-folio site. Here's how to use them.

## Files included

| File | Purpose |
|------|---------|
| `_config.yml` | Main site config — replaces the one in your repo |
| `_pages/about.md` | Homepage / about section |
| `_pages/publications.md` | Publications page |
| `_pages/cv.md` | CV page |
| `_pages/contact.md` | Contact page |
| `_bibliography/papers.bib` | All your publications in BibTeX format |
| `_news/*.md` | News/announcement items |
| `assets/json/resume.json` | Structured CV data used by the CV page layout |

## Setup steps

### 1. Copy files into your repo
Copy each file into the matching location in your `shazal.github.io` repo (after renaming it).

### 2. Add your photo
Place your profile photo at:
```
assets/img/prof_pic.jpg
```

### 3. Add your CV PDF
Place your CV PDF at:
```
assets/pdf/shazal_cv.pdf
```
The CV page will automatically show a download link for it.

### 4. Update social links in `_config.yml`
Fill in any missing fields:
- `scholar_userid` — your Google Scholar profile ID (from the URL: `scholar.google.com/citations?user=XXXXXXXX`)
- `linkedin_username` — update if different from `shazal-irshad`
- `github_username` — update if different from `shazal`

### 5. Rename your repo
If not done already, rename the repo from `shazal-irshad.github.io` to `shazal.github.io` in GitHub Settings.

### 6. Push and deploy
Commit everything and push to `master`. The GitHub Actions workflow will build and deploy to `gh-pages` automatically.

## Optional: add more news items
Add `.md` files to `_news/` following the existing format. They'll appear in the news table on the homepage.
