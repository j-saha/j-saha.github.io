# j-saha.github.io

Source for [Joy Saha's personal academic website](https://j-saha.github.io), built with [Jekyll](https://jekyllrb.com/) using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)).

## Structure

- `_pages/` — top-level pages (About, Publications, Work and Education, Honors & Awards)
- `_publications/` — one Markdown file per publication
- `_data/navigation.yml` — site navigation
- `_config.yml` — site-wide configuration (name, bio, social links, etc.)
- `files/` — downloadable files (CV PDF, papers, etc.)
- `images/` — site images, including the sidebar avatar

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## License

MIT, see [LICENSE](LICENSE). Theme by [Academic Pages](https://github.com/academicpages/academicpages.github.io) / [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/).
