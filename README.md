## Little Website with Personal Introduction and a Projects Showcase

Powered by [Jekyll](https://jekyllrb.com/) and [Github Pages](https://pages.github.com/), built upon the [Alembic](https://github.com/daviddarnes/alembic) theme.

The website is hosted [here](https://sayarghoshroy.github.io/).

---

My design features a landing page, a projects showcase page and a tab to hold your resume.

The style can be easily tweaked by editting the files:
- `_sass/_settings.scss` 
- `_sass/_theme.scss`

#### To Build

```bash
bundle update
bundle install
```

#### To Run Locally

1. Open `Gemfile` in a text editor
2. Uncomment line 17 i.e add `gemspec`
3. In line 4, modify `github-pages` to `jekyll-remote-theme`
4. Run the commands above to build with `bundle`
5. Fire up the terminal and run: `bundle exec jekyll serve`

---
