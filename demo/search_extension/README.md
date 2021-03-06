Search Box Extension
====================

An example extension showing how to use the SDK from a background page.

The extension showcases the following SDK features:
* Search

The extension also showcases the following Chrome features:
* Omnibox

Using the extension
-------------------

###Configuring

The extension requires an API client ID and client secret to function. Uncomment the lines and replace them with your ID and secret.
```javascript
angular.module('box.conf')
    //.constant('clientSecret', 'uII-----------------------------')
    //.constant('clientId', 'i3p-----------------------------');
```

###Building

Building the extension requires Grunt.
*If you are new to Grunt, you will find a lot of answers to your questions in their [getting started guide](http://gruntjs.com/getting-started).

From the same directory as Gruntfile.js, type
```
npm install
bower install
grunt
```

###Installing

To install, enable developer mode and select this folder from the 'Load Unpacked Extension' dialog.  For more information, see the [Chrome Developer Guide](https://developer.chrome.com/extensions/getstarted#unpacked).