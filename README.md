# MangoAtlas: Using IndoorAtlas

# Description:
The project is suppose to be like an indoor Google Maps where users can see directions to their destination inside a building. There is also the feature where the map shows other users on the map and the primary user can see and use that information to their own benefit.

# Example Applications:
1. See how many people are in a restaurant at the current time and receive a notification (Use twilio API) once it reaches below a certain number
2. Cruise navigation: importing the different floor plan of a cruise and seeing where areas of high traffic are to either avoid or attend them.
3. Add a rewards system to where if you enter within 10 feet of a specific location, you can get awarded to encourage customer participation
----------------------------------------------------------------------------------------------------------------------------
# Setup:
Clone the repository at this link: https://github.com/IndoorAtlas/sdk-cordova-examples
And then download and replace the index.js and APIkeys file from here

# Cordova Instructions: http://docs.indooratlas.com/develop/cordova/
Do the following in a terminal: (Command Line, bash, powershell)
1. git clone https://github.com/IndoorAtlas/sdk-cordova-examples    //Downloading the repository
2. cd sdk-cordova-examples/CordovaExamples                          //opening folder in terminal
3. cordova platform add https://github.com/apache/cordova-ios.git#4.4.0-ios-sim
    cordova platform add android                                    //Choose IOS or Android development
4. cordova plugin add cordova-plugin-spinner                        //Add indoor atlas plugin
    cordova plugin add https://github.com/IndoorAtlas/cordova-plugin.git
5.  cordova build
    cordova run
    
# Other instructions:
Make sure to download the following:
  Java
  Android Studio
  
# Enabling GPS on Android Emulator:
  1. Open up terminal within Android Studio
  2. Type in: telnet localhost 5554
  3. Type in: geo fix (longitude) (latitude)
        Example: geo fix -80.2345 25.3214
        
        
  
