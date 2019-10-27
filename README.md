
<img src="app_logo.png" width="64" style="margin-right: 12px" />

# Smart Notes [![Build status](https://dev.azure.com/cross-solutions/eNotes-FlutterPH-Hackathon/_apis/build/status/eNotes-FlutterPH-Hackathon-CI)](https://dev.azure.com/cross-solutions/eNotes-FlutterPH-Hackathon/_build/latest?definitionId=3) [![Generic badge](https://img.shields.io/badge/App%20Center-Install%20Android-<COLOR>.svg)](https://install.appcenter.ms/orgs/cross-solutions/apps/smart-notes-android/distribution_groups/public) [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Flutter-1389FD.svg)](http://flutter.dev) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)]()

<img src="app_screenshot.png" />
<br />
<br />

A note-taking app powered by Google services such as Google Sign In, Google Drive, and Firebase ML Vision.

This is an official entry to FlutterPH's Online Hackathon 2019.


#### Notable Plugins/Technologies Used
- [google_sign_in](https://pub.dev/packages/google_sign_in), [googleapis](https://pub.dev/packages/googleapis), and [googleapis_auth](https://pub.dev/packages/googleapis_auth) for using Google Identity Platform and Google Drive Platform,
- [firebase_ml_vision](https://pub.dev/packages/firebase_ml_vision) for OCR (text recognition).
- [moor_flutter](https://pub.dev/packages/moor_flutter) for a reactive style of persisting data locally using SQLite.
- [scoped_model](https://pub.dev/packages/scoped_model) for state management using MVVM pattern.


#### Running the Project

Please send me an email at dustinboy619@gmail.com with your local Android debug certificate's SHA-1 fingerprint.
We will then give you the `google-services.json` config file needed in order to run the project. Place this in
`src/app/android/app` directory.

#### Installing

You can install the Android app by simply scanning the code below. This will redirect you to a page where you can download the latest APK.

![](data:image/png;base64,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)