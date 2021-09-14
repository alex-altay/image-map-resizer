# Image Map Resize
[![npm version](https://badge.fury.io/js/image-map-resizer.svg)](http://badge.fury.io/js/image-map-resizer)
![license](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat) 
[![Blazing](https://img.shields.io/badge/speed-blazing%20%F0%9F%94%A5-brightgreen.svg?style=flat)](https://twitter.com/acdlite/status/974390255393505280)
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.me/davidjbradshaw)

*This is fork of David Bradshaw simple library that makes HTML Image Maps responsive, so that they automagically stay scaled to the size of the image they are attached to. It detects the window being resized and updates the co-ordinates of the image map accordingly.*

### Usage

Include the [imageMapResizer.min.js](https://raw.github.com/davidjbradshaw/imagemap-resizer/master/js/imageMapResizer.min.js) script then add the following call to the bottom of your page:

```js
imageMapResize();
```

Optionally you can pass a CSS selector that returns a collection of map tags, for example 'map.myMap'. Or a direct reference to a map object in the DOM. This function returns an array of map elements that it has been bound to.

### Differences from original library
- Removed Jquery support
- Used ES6 syntax
- Added a function to remove resize listeners to the global object:

```js
window.removeResizerListeners();
```

### Example
http://davidjbradshaw.com/imagemap-resizer/example/



### License
Copyright &copy; 2014-19 [David J. Bradshaw](https://github.com/davidjbradshaw) - Licensed under the [MIT license](http://opensource.org/licenses/MIT)

[![NPM](https://nodei.co/npm/image-map-resizer.png)](https://nodei.co/npm/image-map-resizer/)
