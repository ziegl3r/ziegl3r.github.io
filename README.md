# cory@buildlog

Build-in-public blog + portfolio, built with Jekyll for GitHub Pages.
Documents the Claude Certified Architect – Foundations (CCA-F) study
journey and the CarTechTutor build log.

## Structure

```
_config.yml       site settings — set `url` once your repo is live
_posts/           blog posts (index at /blog/)
_projects/        portfolio entries (index at /portfolio/)
_layouts/         page templates (default, home, post, project)
_includes/        shared partials (nav, footer, head)
assets/           css
index.md          homepage intro copy
about.md          about page
```

## Writing a new post

Add a file to `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```yaml
---
title: "Post Title"
hash: a1b2c3d   # any 7-char string, cosmetic only
tags: [tag-one, tag-two]
---
Intro paragraph shown as the excerpt.
<!--more-->
Rest of the post.
```

## Adding a project

Copy `_projects/template-project.md`, rename it, fill in the front matter, and set `published: true` (or delete that line).

## Local preview (optional)

GitHub builds the site automatically on push — you don't need Ruby installed to publish. To preview locally before pushing:

```bash
bundle install
bundle exec jekyll serve
# → http://localhost:4000
```

## Deploying

GitHub repo → **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)`**.
