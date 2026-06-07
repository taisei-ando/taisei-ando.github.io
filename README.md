# taisei-ando.github.io

Personal academic website for Taisei Ando, hosted with GitHub Pages.

The site is built with Jekyll and is based on the Jekyll Now theme, with custom pages and styling for an academic profile.

## Site Structure

- `index.html`: top page with profile, affiliation, contact links, and research interests
- `publications.html`: publications page
- `cv.html`: biography, honors, and miscellaneous CV entries
- `_config.yml`: site-wide settings such as name, description, avatar, and footer links
- `style.scss` and `_sass/`: site styles
- `_layouts/` and `_includes/`: Jekyll templates and shared partials
- `404.md`: custom 404 page

## Local Development

Install GitHub Pages' Jekyll dependencies:

```sh
gem install github-pages
```

Serve the site locally:

```sh
jekyll serve
```

Then open:

```text
http://127.0.0.1:4000/
```

If Bundler is used in the future, prefer:

```sh
bundle exec jekyll serve
```

## Updating Content

- Edit profile metadata in `_config.yml`.
- Edit the homepage content in `index.html`.
- Edit publication entries in `publications.html`.
- Edit CV entries in `cv.html`.
- Update styles in `style.scss` or the partials under `_sass/`.

Changes pushed to the GitHub Pages branch are built and published automatically by GitHub Pages.

## Credits

This site was originally based on [Jekyll Now](https://github.com/barryclark/jekyll-now).
