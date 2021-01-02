# Flash Chat ⚡️

## Overview
*This app is based on a course project from [The Complete 2020 Flutter Development Bootcamp with Dart](https://www.udemy.com/course/flutter-bootcamp-with-dart) on [Udemy](https://www.udemy.com). Refactors the original code, adds some new features and fixes some bugs.*

Flash Chat is a light-weight group chat app for both iOS and Android. It is developed using Flutter. It uses Firebase Cloud Firestore, a cloud-based NoSQL database, and Firebase Authentication for secure authentication.

## Demo

<img src="https://i.loli.net/2021/01/03/Qiq6tDCWJBTAK4g.png"></img>

<img src="https://i.loli.net/2021/01/03/nPhYRfbNlBkLp53.png"></img>



## Usage

- Download this repository by `git clone https://github.com/wq-yang/Flash-App.git`
- Add you own Firestore Credentials:
  - Create a Google Firebase project.
  - Follow Firebase docs to enable Authentication and Cloud Firestore.
  - (If needed) Add Android app for your Firebase project, download `google-services.json`, and move it to `/PATH_TO_YOUR_APP/android/app/`
  - (If needed) Add iOS app for your Firebase project, download `GoogleService-Info.plist`, and move it to `/PATH_TO_YOUR_APP/ios/Runner/`
- Build iOS and (or) Android version of Flash Chat.



## Updates

- Refactored the code based on DRY (Don't Repeat Yourself) rule.
- Reduced time to load message bubble style. From about 0.5 second to not noticeable.
- Improved input experience — switch focus, submit form, and send message using only keyboard.
- Disable navigating back to chat screen after the user has signed out.
- Fixed the bug of possibly not showing messages chronological.
- Fixed the bug of sending repetitive messages when hitting send button even if the input box is empty

## TODO

- Continue refactoring the code.
- Allow creating and joining chatrooms with a generated room ID.
- Prompt user when failing to log in or register.
- Allow using customized username (by default using the log in email id).
- Improve user experience when new message is sent.
- More animations for loading etc.