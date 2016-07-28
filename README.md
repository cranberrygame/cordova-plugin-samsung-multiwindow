Cordova Samsung MultiWindow plugin
====================

# Overview #
Show Samsung MultiWindow.
 
[android] [cordova cli] [xdk] [cocoon] [phonegap build service]

This is open source cordova plugin.

You can see Cordova Plugins in one page: http://cranberrygame.github.io?referrer=github

```c
```
# Change log #
```c
1.1.4 Updated MultiWindow SDK 1.3.2 (May 26, 2016)
```
# Install plugin #


## Cordova cli ##
https://cordova.apache.org/docs/en/edge/guide_cli_index.md.html#The%20Command-Line%20Interface - npm install -g cordova@6.0.0
```c
cordova plugin add cordova-plugin-samsung-multiwindow
```
## Xdk ##
https://software.intel.com/en-us/intel-xdk - Download XDK - XDK PORJECTS - [specific project] - CORDOVA HYBRID MOBILE APP SETTINGS - Plugin Management - Add Plugins to this Project - Third Party Plugins -
```c
Plugin Source: Cordova plugin registry
Plugin ID: cordova-plugin-samsung-multiwindow
```

## Cocoon ##
https://cocoon.io - Create project - [specific project] - Setting - Plugins - Custom - Git Url: https://github.com/cranberrygame/cordova-plugin-samsung-multiwindow.git - INSTALL - Save<br>

## Phonegap build service (config.xml) ##
https://build.phonegap.com/ - Apps - [specific project] - Update code - Zip file including config.xml
```c
<gap:plugin name="cordova-plugin-samsung-multiwindow" source="npm" />
```

## Construct2 ##
Download construct2 plugin: http://www.paywithapost.de/pay?id=4ef3f2be-26e8-4a04-b826-6680db13a8c8
<br>
Now all the native plugins are installed automatically: https://plus.google.com/102658703990850475314/posts/XS5jjEApJYV
# Server setting #
```c
```
# API #
```javascript

samsung.multiwindow.openMultiWindow('https://play.google.com/store/apps/developer?id=cranberrygame');

```
# Examples #
<a href="https://github.com/cranberrygame/cordova-plugin-samsung-multiwindow/blob/master/example/basic/index.html">example/index.html</a>

# Test #

<img src="https://raw.githubusercontent.com/cranberrygame/cordova-plugin-samsung-multiwindow/master/doc/screenshot.png"><br>

# Useful links #

Cordova Plugins<br>
http://cranberrygame.github.io?referrer=github

# Credits #

https://seap.samsung.com/sdk/cordova-plugins
http://developer.samsung.com/galaxy#multiwindow
