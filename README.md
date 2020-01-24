# @wizwiz/tiny
npm basic package

### Install
$ npm install @wizwiz/tiny

### Usage
const tiny = require("@wizwiz/tiny");

const newstr = tiny("So much space!");
//=> "Somuchspace!"
console.log(`${newstr}`);

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
