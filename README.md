wb
=======

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Gittip][gittip-image]][gittip-url]
[![David deps][david-image]][david-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/wb.svg?style=flat-square
[npm-url]: https://npmjs.org/package/wb
[travis-image]: https://img.shields.io/travis/node-modules/wb.svg?style=flat-square
[travis-url]: https://travis-ci.org/node-modules/wb
[coveralls-image]: https://img.shields.io/coveralls/node-modules/wb.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/node-modules/wb?branch=master
[gittip-image]: https://img.shields.io/gittip/fengmk2.svg?style=flat-square
[gittip-url]: https://www.gittip.com/fengmk2/
[david-image]: https://img.shields.io/david/node-modules/wb.svg?style=flat-square
[david-url]: https://david-dm.org/node-modules/wb
[node-image]: https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/wb.svg?style=flat-square
[download-url]: https://npmjs.org/package/wb

Another [weibo](http://weibo.com) API Node.js client.

## Install

```bash
$ npm install wb --save
```

## Usage

```js
var Weibo = require('wb');
var client = new Weibo(options);

var tweets = yield* client.homeTimeline(opts);

console.log(tweets);
```

## Test

```bash
$ npm install
$ npm test
```

### Coverage

```bash
$ npm test-cov
```

## License

(The MIT License)

Copyright (c) 2014 fengmk2 &lt;fengmk2@gmail.com&gt; and other contributors

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
