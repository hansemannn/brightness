# Brightness Module

## Description

Module to control the bright of Android device.


## Accessing the Brightness Module

To access this module from JavaScript, you would do the following:

```js
var bright = require("com.apaladini.brightness");
```

The bright variable is a reference to the Module object.	

## Functions

### getSystemBrightLevel

Return a float value (0.0 - 1.0) of current system bright level

### setSystemBrightLevel

Set a float value (0.0 - 1.0) to system bright level

### getWindowBrightLevel (Android only)

Return a float value (0.0 - 1.0) of current window bright level

### setWindowBrightLevel (Android only)

Set a float value (0.0 - 1.0) to window bright level

## Info

On Android, to use "setSystemBrightLevel", your app need permission to write on system settings. To do this, edit your tiapp.xml and insert this:

```xml
<android xmlns:android="http://schemas.android.com/apk/res/android">
    <manifest>
        <uses-permission android:name="android.permission.WRITE_SETTINGS"/>
    </manifest>
</android>
```

## Usage

See sample code

## Author

Adriano Paladini
