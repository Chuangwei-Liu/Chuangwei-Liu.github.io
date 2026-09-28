# Chuangwei Liu — Personal Academic Homepage

This repository contains the source code for [Chuangwei Liu's personal homepage](https://chuangwei-liu.github.io/).

The site is built with Jekyll and GitHub Pages, using the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template as its starting point. It is intended to be a broad academic profile rather than a page dedicated to a single research topic.

## Where to edit the site

- `_config.yml` — site title, description, profile, and links;
- `_pages/about.md` — the main homepage content;
- `_data/navigation.yml` — navigation items;
- `images/` — profile and project images;
- `_posts/` — optional Markdown research notes and blog posts.

## Local preview

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open `http://localhost:4000`.

GitHub Pages publishes the site automatically from the repository's default branch.
