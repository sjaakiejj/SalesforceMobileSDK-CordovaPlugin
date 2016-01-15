Steps to use the Cordova plugin for the Salesforce Mobile SDK
------------------------

<pre>
npm install cordova -g
npm install shelljs

cordova create TestApp
cd TestApp
cordova plugin add https://github.com/sjaakiejj/SalesforceMobileSDK-CordovaPlugin
cordova platform add android@5.0.0
cordova build android
</pre>

For more information, check out [Salesforce Mobile SDK Development Guide](https://github.com/forcedotcom/SalesforceMobileSDK-Shared/blob/master/doc/mobile_sdk.pdf?raw=true)
