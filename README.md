# EuRuKo 2024 website

Placeholder website for EuRuKo 2024.

## Development

Start a local webserver to preview the site.

```sh
$ bundle install
# build the site, watch for changes
$ bundle exec jekyll build --watch
# run webserver, open http://localhost:8000
$ cd _site && ruby -run -e httpd . -p 8000
```

## Deploy

The site is deployed using GitHub actions. For the moment the `dist` folder is deployed as a static website but in the future the repo can be updated to use Bridgetown, Jekyll, or whatever frontend stack works best.

Workflows templates can be found here: <https://github.com/actions/starter-workflows/tree/main/pages>
