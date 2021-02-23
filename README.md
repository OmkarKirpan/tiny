# @omkarkirpan/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@omkarkirpan/tiny)](https://github.com/OmkarKirpan/tiny)
[![npm bundle size (scoped version)](https://img.shields.io/bundlephobia/min/@omkarkirpan/tiny/1.0.0)](https://github.com/OmkarKirpan/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```