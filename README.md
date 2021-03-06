# Moneye

Cross-platform money management mobile application written in Flutter.\
This is a refined version of the original Moneye app that only contains relevant features. The Google Maps functionality has been removed, along with other irrelevant icons and features.\
The original Moneye source code is available here: https://github.com/itasevski/Moneye

- In order for the application to work, you need to create a Google API key that will be associated with a project in your Google Cloud account. For that, visit https://developers.google.com/maps/documentation/javascript/get-api-key.
- After you create your API key, make sure the Places, Maps Static, SDK for IOS & Android and Distances APIs are enabled in your Google Cloud project.
- After you ensure that the APIs are enabled, edit the Android manifest .xml file and replace "YOUR_API_KEY" with your Google API key.
- Also, in the lib folder, create a file called "moneye_secrets.dart" and add your Google API key in a static const String variable.

Original repository: https://github.com/Viktorija2Nikolovska/MoneyeApp


### Getting Started: Flutter

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
