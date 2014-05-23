notification-hub
================

A hub notification.

# Technology
This notification hub use [Polymer](http://www.polymer-project.org/) in order to use web components. There is no other dependency.

## Install

- Make sure you haven [nodejs](http://nodejs.org/) install in order to be able to play the demo and install dependencies.
- When node in installed, you need to install [bower](http://bower.io/), `npm install -g bower`
- Then install bower dependencies (you have to be in the project directory): `bower install`

## Launch the hub

In order to launch the hub you have to do : `npm run start` or `node server.js` and then go to the url: [localhost:8888](http://localhost:8888)

## Use the web component
Inside your html you just have to do: (you also can create the tag using JavaScript as in [index.html](https://github.com/pierr/notification-hub/blob/master/index.html))
```html
<!DOCTYPE html>
<html>
  <head>
    <script src="bower_components/platform/platform.js"></script>
    <link rel="import" href="notification-hub.html">
  </head>
  <body>
    <notification-hub></notification-hub>
    <!-- Then your standard application. -->
  </body>
</html>
```