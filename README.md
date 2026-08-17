# Daily Chinese — Android APK Project

This is a native Android wrapper for the Daily Chinese learning app.
The lessons are bundled inside the APK, so the core app does not require a website or network connection.
Chinese pronunciation uses Android's TextToSpeech engine.

## Build an APK in Android Studio
1. Install the current Android Studio.
2. Open this `DailyChineseAndroid` folder.
3. Let Android Studio install/sync the required SDK/Gradle components.
4. Choose **Build > Build App Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK will be under `app/build/outputs/apk/debug/app-debug.apk`.
6. Copy that APK to your Android phone and tap it to install.

## Package
- Application ID: `com.dailychinese.app`
- Minimum Android: Android 6.0 (API 23)
- Target SDK: 35
- Version: 1.0
