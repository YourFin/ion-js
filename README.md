<p align="center">
 <a title="" href="https://api.travis-ci.org/amzn/ion-js.svg?branch=master">
 <img src="https://api.travis-ci.org/amzn/ion-js.svg?branch=master"/>
 </a>
</p>


Build prerequisites: Node.js and npm (the JavaScript package manager)

First, install the Grunt CLI:

 sudo npm install -g grunt-cli

Next, use npm to install all the package's dependencies:

 npm install

Finally, run grunt to execute the build:

 grunt

To debug the unit tests, use the following command:

 node debug node_modules/intern/client config=tests/intern ionVersion=es6

To run Ion in a browser, see the example in the "browser" folder. You'll need to copy require.js and the Ion JavaScript files (Ion.js etc.) into the "scripts" folder.