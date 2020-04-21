# Google Lighthouse CI

[![google.com](https://github.com/jonathanong/google-lighthouse-ci/workflows/google.com/badge.svg?event=schedule)](https://github.com/jonathanong/google-lighthouse-ci/actions?query=workflow%3Agoogle.com+branch%3Amaster)

Runs Google Lighthouse CI using GitHub Workflows. Setup to run on push as well as nightly. Does not use existing GitHub Actions for better configurability. 

## Running locally

Run `npx lighthouse` on the relevant URL:

```zsh
npx lighthouse https://www.google.com/products/bookcases
```

Note that this library does not use `lighthouse`, so do not commit the package changes.
