# Webpack-babel-cordova
Webpack-babel-cordova example
You must have node installed
create package.json using npm init command
install webpack npm install --save-dev webpack
install babel-core and loader installed npm install --save-dev babel-loader babel-core
install the babel presets npm install babel-preset-env --save-dev
include .babelrcfile or include in your webconfig file.I have added presets in my webconfig file.
More info on babel refer https://babeljs.io/docs/setup/#installation
you can add react plugin if you need it in your application.

Once set up is complete run npm webpack before running the app

Cordova app

In www folder I have a src folder which is going to be convert es6 to old javascript(dist) which would be used by application
