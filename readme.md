# get-scroll [![module size](https://badge-size.herokuapp.com/bfred-it/get-scroll/master/dist/get-scroll.node.min.js) ![module gzipped size](https://badge-size.herokuapp.com/bfred-it/get-scroll/master/dist/get-scroll.node.min.js?compression=gzip)](https://github.com/bfred-it/get-scroll/blob/master/dist/get-scroll.min.js)

> Micro module to get the scroll position (top or left) in the browser

## Usage

```js
var currentScrollTop = getScroll.top();
var currentScrollLeft = getScroll.left();
```

## With browserify

```sh
npm install --save get-scroll
```

```js
var getScroll = require('get-scroll');
```

### Alternative usage in ES6

```js
import {getScrollLeft, getScrollTop} from 'get-scroll';

let currentScrollTop = getScrollTop()
let currentScrollLeft = getScrollLeft()
```

## API

### `getScroll.top()` _or `getScrollTop()`_

Returns the vertical scroll position of the document.

### `getScroll.left()` _or `getScrollLeft()`_

Returns the horizontal scroll position of the document.

## Files

Here's an explanation of the files included in this repo

* `index.js`: source file, in ES6
* `dist/get-scroll.js`: browser-ready file with AMD or a global variable called `getScroll`
* `dist/get-scroll.min.js`: same as above, minified
* `dist/get-scroll.node.js`: used by node/browserify with `require('get-scroll')`
* `dist/get-scroll.node.min.js`: same as above, but minified, for byte counting only

## Dependencies

No dependencies.

## License

MIT © [Federico Brigante](http://twitter.com/bfred_it)
