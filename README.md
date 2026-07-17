# Tianyu Xiang — Academic Website

Source for [garyxty.github.io](https://garyxty.github.io), the academic website of Tianyu Xiang.

The site is built with Jekyll and adapted from
[sbryngelson/academic-website-template](https://github.com/sbryngelson/academic-website-template).

## Content

- `/_pages/home.md` — landing page and short biography
- `/_pages/about.md` — detailed biography, education, awards, and mentoring
- `/_pages/research.md` — research overview
- `/_includes/publications-list.md` — publication list
- `/_pages/awards.md` — awards and scholarships
- `/_pages/cv.md` — education, experience, and mentoring
- `/_data/news.yml` — news displayed on the home page

## Local preview

```bash
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

The site is deployed to GitHub Pages by `.github/workflows/deploy.yml` whenever
the `master` branch is updated.

## License

The template code is available under the MIT License. Personal text, images,
and publication metadata remain the property of their respective owners.
