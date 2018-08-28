cfssl
=========

[![Build Status](https://img.shields.io/travis/com/amylum/cfssl.svg)](https://travis-ci.com/amylum/cfssl)
[![GitHub release](https://img.shields.io/github/release/amylum/cfssl.svg)](https://github.com/amylum/cfssl/releases)
[![BSD-2 Licensed](https://img.shields.io/badge/license-BSD--2-green.svg)](https://tldrlegal.com/license/bsd-2-clause-license-(freebsd))

This is my package repo for [cfssl](https://github.com/cloudflare/cfssl)

The `upstream/` directory is taken directly from upstream. The rest of the repository is my packaging scripts for compiling a distributable build.

## Usage

To build a new package, update the submodule and run `make`. This launches the docker build container and builds the package.

To start a shell in the build environment for manual actions, run `make manual`.

## License

The cfssl upstream code is BSD 2-clause licensed. My packaging code is MIT licensed.

