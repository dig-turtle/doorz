# This is the Doorz multi-platform game!

The rules are simple, keep opening doors until you get to the end! When you win, there's a special prize!

# For Contributors:
 This is an Apache Cordova application, which means it runs on nodejs.  To set it up locally, first install cordova: 
 ```cmd
 npm install -g cordova
 ```
 
 From there, the application is manipulated with cordova commands.
 Currently, this app is targeting browser (website), android, and ios.
 
 To check if you have the proper requirements to build the project, run:
 
```cmd
cordova requirements
```
 
 To build all platforms (won't work on Windows): 
 ```cmd
 cordova build
 ```
 
 To build a specific platform, just specify the platform after the command:
 ```cmd
 cordova build browser | android | ios
 ```
 
 For a complete list of helpful commands to get up and running with this project, please visit the [cli documentation](https://cordova.apache.org/docs/en/latest/guide/cli/)