# Cribb Tutoring — Cayman starter
- Push to a public GitHub repo.
- Settings → Pages → Deploy from a branch.
- Edit `_config.yml` email/area.
- To report the path for the cayman theme's files:

```bash
CAYMAN_PATH=`bundle info jekyll-theme-cayman --path`
```

- E.g., the location for the theme's `default.html` file would be `$CAYMAN_PATH/_layouts/default.html

- To build the site:
```bash
 cd cribb-tutoring/

 bundle config set --local path vendor/bundle
 bundle install
 bundle exec jekyll serve --livereload --host 0.0.0.0
```

