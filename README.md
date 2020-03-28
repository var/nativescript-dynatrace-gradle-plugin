# nativescript-dynatrace-gradle-plugin

### Installation 

`tns plugin add nativescript-dynatrace-gradle-plugin`

### Configuration

You must generate application ID and beacon URL and add them to your project's `gradle.properties` file so that your Android mobile app can send monitoring data to your Dynatrace monitoring environment.

Add the configuration to your `gradle.properties` in the following way:

`DTXApplicationID=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx`

`DTXBeaconURL=https://xxxxxxxxxx.bf.dynatrace.com/mbeacon`

### Similar Plugins

NativeScript Dynatrace Cocoapods Plugin for iOS: https://www.npmjs.com/package/nativescript-dynatrace-cocoapods-plugin
