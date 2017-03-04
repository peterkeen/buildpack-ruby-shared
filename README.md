# Shared Ruby Buildpack

This is a buildpack for [capistrano-buildpack](https://github.com/peterkeen/capistrano-buildpack) that
will share a common Ruby installation.

## Caveats:

* requires `capistrano-buildpack` >= 0.0.14
* relies on `.ruby-version` instead of asking Bundler
* does not automatically munge your `PATH`

## License

Copyright (c) Cora Street Press LLC.

See `LICENSE` file for details.

