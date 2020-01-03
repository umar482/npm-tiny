# @umar.482/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@umar.482/tiny.svg)](https://www.npmjs.com/package/@umar.482/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@umar.482/tiny.svg)](https://www.npmjs.com/package/@umar.482/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @umar.482/tiny
```

## Usage

```js
const tiny = require("@umar.482/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```