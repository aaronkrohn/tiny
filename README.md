# @akrohn/tiny

(https://www.npmjs.com/package/@akrohn/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @akrohn/tiny
```

## Usage

```js
const tiny = require("@akrohn/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
