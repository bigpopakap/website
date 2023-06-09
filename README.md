# Kapil Easwar's website
========================

Source repo for [kapileaswar.com][website-url]

| Circle CI | Github Pages |
|----------|--------------|
| [![CircleCI](https://dl.circleci.com/status-badge/img/gh/bigpopakap/website/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/bigpopakap/website/tree/main) | [![pages-build-deployment](https://github.com/bigpopakap/website/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/bigpopakap/website/actions/workflows/pages/pages-build-deployment) |

## Running locally

```
# Install dependencies
bundle install

# Run the local server
bundle exec jekyll serve -l --source docs/

# Visit localhost:4000, or whatever the build output says
```

## Common use cases

* [Publishing a post]()
* [Writing a draft post](https://jekyllrb.com/docs/posts/#drafts)

## Notable dependencies

### Jekyll theme

The site uses [`beautiful-jekyll`][plugin-theme-website] as a `remote_theme`.

[//]: # (References)

[website-url]: https://http://kapileaswar.com/

[plugin-theme-website]: https://beautifuljekyll.com/
[plugin-theme-github]: https://github.com/daattali/beautiful-jekyll
