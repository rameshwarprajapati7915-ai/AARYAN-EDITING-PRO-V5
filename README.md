# AARYAN EDITING V5 — Android APK Project

This project packages the current AARYAN EDITING V5 web app inside a native Android WebView shell.

## What is included

- Current V5 `index.html`
- Android app module
- Android 16 / API 36 compile + target configuration
- Java 17
- WebView JavaScript + local storage
- Android file picker support for the V5 upload fields
- WhatsApp links can open the WhatsApp app
- Instagram links can open Instagram
- Back button navigation
- GitHub Actions workflow that builds a debug APK
- Portrait mobile layout

## Build free from a phone with GitHub

1. Create a GitHub repository named `AARYAN-EDITING-V5`.
2. Upload the complete contents of this folder, keeping the folder structure.
3. Open the repository's **Actions** tab.
4. Select **Build AARYAN EDITING APK**.
5. Tap **Run workflow**.
6. After the workflow finishes, open the run and download the artifact:
   `AARYAN-EDITING-V5-debug-apk`
7. Extract the ZIP and install `app-debug.apk` on your Android phone.

## Important

This produces a **debug APK for testing**. It is not the final signed Play Store release.

The current V5 browser code is packaged as-is. Its local/demo features remain local unless you connect the app to Firebase/backend services. A real production Google login, cloud database/storage, online payments, push notifications and courier tracking require their corresponding backend configuration.

## Android build settings

- compileSdk: 36
- targetSdk: 36
- minSdk: 24
- Java: 17
- Android Gradle Plugin: 8.13.2
- Gradle: 8.13

## Package

`com.aaryanediting.app`

## Version

5.0 / versionCode 5
