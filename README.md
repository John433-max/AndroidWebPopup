
# AndroidWebPopup

An Android app that pops up a website every hour.

## Features

- Displays a website in a WebView every hour
- Uses AlarmManager for scheduling
- Simple and easy to use

## Setup

1. Clone the repository
2. Open the project in Android Studio
3. Build and run the app on your Android device or emulator

## Usage

Once the app is installed and running, it will automatically schedule a popup to appear every hour, displaying the configured website.

## Building a Signed APK

To build a signed APK:

1. Update the signing configuration in `app/build.gradle` with your keystore information
2. Run `./gradlew assembleRelease`
3. The signed APK will be generated at `app/build/outputs/apk/release/app-release.apk`

## License

This project is open source and available under the [MIT License](LICENSE).
