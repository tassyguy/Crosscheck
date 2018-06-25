# Crosscheck
An app for checking cross-interactions with medications. This is intended to be the Flutter port of Crosscheck to deliver a responsive native mobile app experience (plus Google Fuchsia when that's eventually released), with the React-Native part of the app being eventually depreciated for an Electron-based desktop app since Flutter does not currently support desktop OSs and web (as of writing).

## Planned features:

* Android Go support
* Consistent Material Design 2.0 look for both iOS and Android
* Support for substances/chemicals outside of the FDA database/regulations such as grapefruit, medical marijuania (if allowed by Google/Apple), red dye #5, etc. that are considered legal in some capacity

## Potential Features (later on)

* Cupertino-style design for iOS version if deemed necessary
* Multiple country/language support
* Integration with HealthKit (iOS) and the Google Fit SDK (Android)
* Digital assistant integration(Siri/Google Assistant/Alexa/Cortana) when allowed and deemed appropriate
* Select your medical database (i.e. source info from India's health database instead of United State's FDA if desired)
* Support for interactions with illicit substances (amphetamines, lysergic acid diethylamide, heroin, etc.) so people whom intend on using said substances can be informed of the potential side effects and potentially damaging results of mixing drugs/medications before making a decision on whether to partake in an activity that involves them and lower the risk of accidentally oversodage.
