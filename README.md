phonegap-2-style-3
==================

PhoneGap 3.0 project that includes all of the plugins by default


##Getting Started##

Download and Install the latest version of [node](http://nodejs.org/). This will also install NPM.

Now open up your terminal and type `npm install -g cordova`. This will download the cordova-cli. We need this to do development with PhoneGap 3.0. Make sure to checkout the readme for the [cordova-cli](https://github.com/apache/cordova-cli).

You can copy over your own www assets into the www folder. 

You can now run commands like `cordova emulate ios` or `cordova run android`.

ERROR: Currently, the config.json file under the .cordova directory has fields for lib that point to my cordova-android and cordova-ios on my machine. Once cordova-CLI gets updated to 3.0, this won't be necessary. For now, you have to change those directories to your own version for cordova-android and cordova-ios that are on master (3.0 compatitable).
