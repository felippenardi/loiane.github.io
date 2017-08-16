# loiane.github.io

[![Build Status][travis-image]][travis-url] [![Dependency Status][dependencyci-image]][dependencyci-url]

> source for loiane.com

## Prerequisites

To install this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll -v 3.5.1`
2. [NodeJS](http://nodejs.org) - use the installer.

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**Development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc.

```shell
$ npm run start
```

**Deploy mode**

You can easily deploy your site build with the command
```shell
$ npm run deploy
```

## Tests

If you want to run the tests on your local machine please install `gem install html-proofer`. And then run the tests using
```shell
$ htmlproofer ./_site
```

[license-image]: https://img.shields.io/badge/license-ISC-blue.svg
[license-url]: https://github.com/loiane/loiane.github.io/blob/master/LICENSE
[travis-image]: https://travis-ci.org/loiane/loiane.github.io.svg?branch=master
[travis-url]: https://travis-ci.org/loiane/loiane.github.io
[dependencyci-image]: https://dependencyci.com/github/loiane/loiane.github.io/badge
[dependencyci-url]: https://dependencyci.com/github/loiane/loiane.github.io

### Notes

This work is licensed under a Creative Commons Attribution 4.0 International License. In other words, share but provide attribution/credits.

### Theme

Theme adapted from [Hyde](https://github.com/poole/hyde).

Design inspired by [Todd Motto](https://toddmotto.com) and [Wes Bos](http://wesbos.com).
