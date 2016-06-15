# heka-fire

`<heka-fire>` is a cloned replacement for firebase-app that provides access to Firebase storage

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/heka-fire)

[Source](http://github.com/hekahouse/heka-fire/)

## Install

    bower install --save HekaHouse/heka-fire

## Example

    <heka-fire
      id="app"
      name="heka-house"
      api-key="API-KEY"
      auth-domain="heka-house-polymer-demos.firebaseapp.com"
      storage-bucket="heka-house-polymer-demos.appspot.com"
      database-url="https://heka-house-polymer-demos.firebaseio.com"
      app="{{app}}">
    </heka-fire>

The Firebase document is initiaized once the user and app properties are provided.

These come from associated heka-fire and firebase-auth elements


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

heka-fire is based on the pre-release [polymerfire](https://github.com/firebase/polymerfire)

until polymerfire supports Firebase storage all heka-fire elements utilize heka-fire.html in place of firebase-app
