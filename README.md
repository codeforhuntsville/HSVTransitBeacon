#HSV Transit Beacon 
originally 
# trolley-tracker-agent

Android app for reporting the current location of devise with this application installed.

Written by the Code for Greenville NC CfA Brigade, it has been adapted to track the Huntsville 
Trolley and Shuttle Buses by the Code for Huntsville CfA Brigade.

## Dependencies
- Development
 - Android Studio (IDE)
 - Android API Level 19 (4.4.x KitKat)
- Running the App
 - Android KitKat or newer
 - Functional GPS Hardware
 - Google Play Services (Google Location Services)

## Functionality
This app uses Google Location Services API to request high-precision location updates. When it receives a location update, the service will issue a HTTP POST to the trolley-tracker-api endpoint.
