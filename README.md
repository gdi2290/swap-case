# Swap Case

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Gittip][gittip-image]][gittip-url]

Swap the case of a string with non-ASCII character support. Also handles non-string entities, such as objects with a `toString` property, numbers and booleans. Empty values (`null` and `undefined`) will come out as an empty string.

## Installation

```bash
npm install swap-case --save
```

## Usage

```javascript
var swapCase = require('swap-case');

swapCase(null);                   //=> ""
swapCase('string');               //=> "STRING"
swapCase('PascalCase');           //=> "pASCALcASE"
swapCase('Iñtërnâtiônàlizætiøn'); //=> "iÑTËRNÂTIÔNÀLIZÆTIØN"
```

## License

MIT

[npm-image]: https://img.shields.io/npm/v/swap-case.svg?style=flat
[npm-url]: https://npmjs.org/package/swap-case
[travis-image]: https://img.shields.io/travis/blakeembrey/swap-case.svg?style=flat
[travis-url]: https://travis-ci.org/blakeembrey/swap-case
[coveralls-image]: https://img.shields.io/coveralls/blakeembrey/swap-case.svg?style=flat
[coveralls-url]: https://coveralls.io/r/blakeembrey/swap-case?branch=master
[gittip-image]: https://img.shields.io/gittip/blakeembrey.svg?style=flat
[gittip-url]: https://www.gittip.com/blakeembrey
