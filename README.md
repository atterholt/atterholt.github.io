# atterholt.github.io

Website for the Atterholt Group (Fiber Geophysics), Department of Geosciences, University of Arizona.

Built with Jekyll and published by GitHub Pages from the `main` branch.

## Editing content

Most content lives in plain data files, so you rarely need to touch HTML:

| What | File |
| --- | --- |
| Research themes (home cards and Research page) | `_data/themes.yml` |
| Group members and PI bio | `_data/people.yml` |
| Publications | `_data/publications.yml` |
| News and outreach (first three show on the home page) | `_data/news.yml` |
| Top navigation | `_data/navigation.yml` |
| Group name, tagline, email, address | `_config.yml` |
| Styles | `assets/css/style.scss` |

Web-sized images go in `assets/img/web/`; member photos in `assets/img/people/`.

## Previewing locally or in a Codespace

```
bundle install
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.
