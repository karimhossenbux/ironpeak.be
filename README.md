ironpeak.be
===========

This is the repository that builds the static website for [ironpeak.be](https://ironpeak.be/) using [hugo](https://gohugo.io/).

Current build status: [![Netlify Status](https://api.netlify.com/api/v1/badges/55df448b-0cad-4bc9-bf27-50b65531eea1/deploy-status)](https://app.netlify.com/sites/ironpeakbe/deploys)


CI / CD
-------
The pipeline runs on a free instance of [Netlify](https://www.netlify.com/), since this supports setting security headers compared to Github Pages.

Building
--------
`hugo server` to run locally, `hugo --minify` to build minified output to `generated/`.