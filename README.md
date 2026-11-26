# Jiyuan Yang's Academic Homepage

This repository hosts my personal academic homepage at <https://yang-era.github.io/>.

The site is based on the Academic Pages Jekyll template and is maintained as a concise research profile.

## Main Content

* `_pages/about.md`: homepage, research interests, education, experience, honors, and news.
* `_pages/publications.html`: publication list rendered from `_publications/`.
* `_pages/cv.md`: short academic CV.
* `_publications/`: publication metadata and links.
* `_pages/zh/`: Simplified Chinese pages. Each page's `english_url` pairs it with its English counterpart. Translated paper pages reuse the metadata and images from `_publications/`.
* `_config.yml`: site metadata, author profile, and collection settings.

## Local Preview

Install dependencies and start a local Jekyll server:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000/>.
