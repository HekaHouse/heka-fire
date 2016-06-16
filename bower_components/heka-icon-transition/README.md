# heka-icon-transition

`<heka-icon-transition>` an element allowing line-based SVG icons to seamlessly change from one to the other. It provides an implementation of Material Design's [delightful details](http://www.google.com/design/spec/animation/delightful-details.html) transitions.

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/heka-icon-transition)

[Source](http://github.com/hekahouse/heka-icon-transition/)

## Install

    bower install --save HekaHouse/heka-icon-transition

## Example

    <icon-transition color="#fff" id="hero" shape="check"></icon-transition>

Available shapes:
    plus, check, more, more-vert, menu, up, down, left, right, left-arrow, right-arrow, cancel

Transition is triggered by changing the shape value.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install
