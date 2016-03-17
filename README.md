# TrainingApp

A cross-platorm mobile application that allows humans to train robots that use the [Fido library](https://github.com/FidoProject/Fido). Robots that use this application are included in the [Hardware repo](https://github.com/FidoProject/Hardware). 

The app is written in [Ionic](http://ionicframework.com/) using AngularJS and HTML/CSS and uses sockets to connect to and train a robot. For this reason, your robot must be connected to the same network as your mobile device.

For the time being, this app is not available on the app store. It must be uploaded to your device using the Ionic framework's [command line interface](http://ionicframework.com/docs/cli/).

## Installation

First install node.js 4 (very important it is not node.js 5).
Then, install ionic and cordova using `sudo npm install --global ionic cordova`.
Next, navigate to the `/app` directory, and run `npm install`, `bower install`, and `ionic state reset`. This will install all the dependencies.

## Development

See the [ionic framework's instructions](http://ionicframework.com/docs/guide/testing.html) on running an application.
