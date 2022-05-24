## Overview
## Requirements
The following minimum requirements need to be met for both the mobile application and DHIS2 metadata package;
* Android version 8 and above
* DHIS2 version 2.28 and above
## Installation
### Mobile Application
The android mobile application installer is distributed as an APK (Android Package Kit) available on the this git repository. In the future, we plan to distribute this APK through Google Play Store as it provides so many security measures. The instructions below work from Android version 8 and above.
1.  Download the APK version you want to install.
2.  Navigate to your Download folder using a file browser app or simply begin the install by clicking on the completed download in your mobile browser.
3.  Android will ask you to grant permission to either the file browser or your web browser to install the app. Grant the permission and it should redirect you back to the installation screen. If not, navigate back to your Download folder after granting the permission to try again.
4. The app should be safely installed.
### Metadata Package
A metadata package is a pre-configured template of DHIS2 metadata that can be installed on standalone instance or integrated into a country or organization's existing DHIS2. The process of installing a metadata package is well documented and can be found <a href="https://docs.dhis2.org/en/topics/metadata/immunization/immunization-aggregate/installation.html">here</a>
## Configuring the Mobile Application
The initial configuration of the MRDQA App requires a connection to the DHIS2 server with the installed metadata package. Once configuration has been imported into the App, data collection can proceed without a direct connection to the DHIS2 server.
To configure the app,
1.  point the mobile app to the DHIS2 server with the installed metadata package
2.  import data elements, indicators and facilities from the DHIS2 server into the app

__NB:__ Once the app has been configured and the DHIS2 server isn't reachable, the export functionalities (CSV & DHIS2 export) will be disabled.

