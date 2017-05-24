# Sunshine

This app is coursework from the Udacity 'Android Fundamentals' personal development training course.

Sunshine app provides 7-day forecast in the main screen. If you select on any particular day forecast, it opens up the detail activity. The detail activity shows more details like Humidity, Wind and Pressure. App is allowed to send broadcast notifications.

Setting activity has options to change the location, change the temperature metrics and on/off option to allow notifications.

### Installation

To install the app on your device, there are three possible ways:

1.) Download the .apk file from the build directory and copy it on to your Android device and Install it.

2.) Import the project into the Android Studio IDE and hit the play button to install the app via ADB.

3.) Follow the commands to install the app via ADB using Command Prompt.

### Usage

In order for the Sunshine app to function properly an API key for openweathermap.org must be included with the build.

Include the unique key for the build by adding the following line to [USER_HOME]/.gradle/gradle.properties

MyOpenWeatherMapApiKey="<UNIQUE_API_KEY>"
