# LJT-Homepage

Personal homepage of **Junteng Liu**, a first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology. The site is built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and published with GitHub Pages.

## Pages

- **About** (`/`) — introduction, education, research experience, research skills, publications and contact information.
- **Publications** (`/publications/`) — the same publication records, listed from newest to oldest.

## Content

| Path | Purpose |
| --- | --- |
| `_pages/about.md` | About page and its sections |
| `_pages/publications.html` | Publications subpage |
| `_publications/` | Publication records (title, authors, venue, year) |
| `_includes/publication-list.html` | Renders the publication records on both pages |
| `_config.yml` | Site title, author profile, contact links and Jekyll settings |
| `_data/navigation.yml` | Header navigation |
| `_data/authors.yml` | Author profile data |

## Building locally

```bash
bundle install
npm run build
bundle exec jekyll serve -l -H localhost
```

## Publishing

Pushing to `master` runs `.github/workflows/jekyll.yml`, which builds the site with Jekyll and deploys it toGitHub Pages at:

https://spanellisnikolaos564-sketch.github.io/LJT-Homepage/