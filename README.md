# tiny

![npm](https://img.shields.io/npm/v/@tarisa/tiny?color=red&logo=npm)

(test create npm package)

Removes all spaces from a string.

## Install

```
$ npm install @tarisa/tiny
```

## Usage

```js
const tiny = require("@tarisa/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
