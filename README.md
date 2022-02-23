# `npm-git-deps-testing`

_Testing of NPM's management of git dependencies._

## What is this?

This library has three tags:

- v1.0.0 which has a bunch of `devDependencies` that are slow to install but no NPM scripts
- v2.0.0 which has a bunch of `devDependencies` that are slow to install and a `prepare` script
- v3.0.0 which has a bunch of `devDependencies` that are slow to install and a `build` script

## Running the tests

- Set up a local `npm` package (e.g. using `npm init`)
- Install the different versions using, e.g. `npm -v install paulbrimicombe/npm-git-deps-testing#semver:1.0.0`
- If you're using `npm 6`, versions `1.0.0` and `3.0.0` will be fast to install but `2.0.0` will be slow
- If you're using `npm 8`, version `1.0.0` will be fast but `2.0.0` and `3.0.0` will be slow

