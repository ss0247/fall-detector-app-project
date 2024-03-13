# Experimental Fall Detector Android App

## INTRODUCTION

In short: When a fall is detected the app will send an SMS to the configured emergency phone number.

## USER GUIDE

* Make sure to configure the emergency phone number for the app to call automatically when a fall is detected.
* Calls from that number will be answered automatically.
* An SMS from that number with the word POSITION in the content will be replied to automatically with the geographical position (if available).
* If the SMS contains the word ALARM instead, it will play back an alarm sound.
* The app will start automatically when the phone is turned on.
* For optimal performance (to reduce the number of false alarms and the number of undetected falls) carry the device close to your waist (a trouser pocket, a belt clip, etc.).
* Keep your device charged at all times.

Install the app by side-loading the APK file available [here](https://github.com/altermarkive/experimental-fall-detector-android-app/releases)
(you can find more info about the process [here](https://www.howtogeek.com/313433/how-to-sideload-apps-on-android/)).

If you are familiar with F-Droid repositories you can also use the following link:

[<img alt="IzzyOnDroid" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" width="200px"/>](https://apt.izzysoft.de/fdroid/index/apk/altermarkive.guardian)

## SCREENSHOTS

 EULA screen (MIT license)     | About view (with instructions & emergency button) | Sensor & detection signals view (pausable & zoomable) | Settings view (to set emergency number & data collection) | Emergency number editor (with contact book lookup)
:-----------------------------:|:-------------------------------------------------:|:-----------------------------------------------------:|:---------------------------------------------------------:|:--------------------------------------------------:
 ![EULA](doc/screenshot.0.jpg) | ![About](doc/screenshot.1.jpg)                    | ![Signals](doc/screenshot.2.jpg)                      | ![Settings](doc/screenshot.3.jpg)                         | ![Contact](doc/screenshot.4.jpg)

## CREDITS

The fall detection is based upon the FallAllD: A Comprehensive Dataset of Human Falls and Activities of Daily Living by Majd Saleh, Université de Rennes 1, LTSI, Rennes, 35000, France, and INSERM, U1099, Rennes, 35000, France (search for the paper [here](https://ieee-dataport.org/open-access/fallalld-comprehensive-dataset-human-falls-and-activities-daily-living))

