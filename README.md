# @omkarkirpan/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@omkarkirpan/tiny)](https://github.com/OmkarKirpan/tiny)
[![install size](https://packagephobia.com/badge?p=@omkarkirpan/tiny)](https://packagephobia.com/result?p=@omkarkirpan/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@omkarkirpan/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```