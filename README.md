# @vineshdev/tinytest

[![npm (scoped)](https://img.shields.io/badge/npm-v1.0.0-green.svg)](https://github.com/vineshkumar87/tinytest)

tiniest npm test module

## Install

```
$ npm install @vineshdev/tinytest
```

## Usage

```java
const tiny = require("@vineshdev/tinytest");

tiny("Have Lot Of Space");
//=> "HaveLotOfSpace"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
