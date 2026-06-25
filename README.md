# jinyoo1021.github.io

A simple, readable personal portfolio built with Jekyll and hosted on GitHub Pages.

## Editing Content

Almost all site copy lives in [`_data/content.yml`](_data/content.yml).
Update your name, intro, projects, experience, and contact details there.

## Local Preview

```bash
bundle install      # Run once
bundle exec jekyll serve
```

→ http://localhost:4000

## Deployment

Push to `main` or the branch configured for GitHub Pages to build and deploy automatically.

## Structure

```
_config.yml            Site settings
_data/content.yml      Edit page content here
_layouts/default.html  Shared layout (head, theme control, theme script)
index.html             Section markup (Background/Education/Projects/Interested in)
assets/css/style.css   Design styles (light/dark variables)
assets/js/theme.js     Theme toggle
```
