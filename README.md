# ABC Fun Time — Android Studio Project

This Android app wraps the live ABC Fun Time website in an Android WebView:
https://resplendent-phoenix-42aa97.netlify.app/

## Build APK

1. Install Android Studio.
2. Open this folder (`ABC_Fun_Time_Android_Studio`) in Android Studio.
3. Let Gradle sync and install any requested SDK components.
4. For a test APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK will be under:
   `app/build/outputs/apk/debug/app-debug.apk`

For a signed release APK use **Build > Generate Signed App Bundle / APK**.

## Requirements
- Android Studio with JDK 17 support
- Android SDK Platform 35
- Internet connection on the phone

## Website
The app loads the live Netlify website. Website updates therefore appear in the app without rebuilding the APK.
