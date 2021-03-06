# unexpected-immutable

[![Build Status](https://travis-ci.org/albertfdp/unexpected-immutable.svg?branch=master)](https://travis-ci.org/albertfdp/unexpected-immutable)

This plugin provides a set of  [unexpected](https://unexpected.js.org) types and assertions for [immutable-js](http://facebook.github.io/immutable-js/) library for JavaScript collections.

![unexpected-immutable-watermelons](http://i.giphy.com/fQa7ew7maOC5y.gif)
> An unexpected immutable watermelon

## Installation

Install via [npm](http://npmjs.org/):

```bash
$ npm install unexpected unexpected-immutable
```

You can use this plugin as any other unexpected plugins:

```javascript
const unexpected = require('unexpected')
const unexpectedImmutable = require('unexpected-immutable')

const expect = unexpected.clone().use(unexpectedImmutable)

```

## License

MIT
