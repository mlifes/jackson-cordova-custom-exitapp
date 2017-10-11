# iOS & Android ExitApp
This plugin implements navigator.app.exitApp() on iOS and Android, to close your application programmatically. 
Please be aware that your application may be rejected by Apple when using this plugin.

# Installation
cordova plugin add jackson-cordova-custom-exitapp

# Usage
The usage is pretty simple. Call navigator.app.exitApp(); to exit the application immediately. Optional you can pass a parameter true || false to ask the user if the really wants to close the application.