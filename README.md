# srdsec.github.io

Personal InfoSec blog of Shane Daniels, built with [Jekyll](https://jekyllrb.com/)
and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, deployed
to GitHub Pages via GitHub Actions.

## Local development

```bash
bundle install
bundle exec jekyll s   # http://127.0.0.1:4000
```

## Writing posts

Add Markdown files to `_posts/` named `YYYY-MM-DD-title.md` with Chirpy front matter
(`title`, `date`, `categories`, `tags`). See the existing posts for examples.

## Deployment

Pushing to `master` triggers `.github/workflows/pages-deploy.yml`, which builds the
site and publishes it to GitHub Pages. The repo's **Settings → Pages → Source** must
be set to **GitHub Actions**.

