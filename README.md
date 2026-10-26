# Луна — Android APK

This repository uses GitHub Actions to build a debug APK from the bundled web app.

## Build
1. Push the repository to GitHub.
2. Open the repository's **Actions** tab.
3. Choose **Build Luna APK** and click **Run workflow** (or push to `main`).
4. When the run completes, open it and download the `Luna-Android-APK` artifact.
5. Extract the downloaded artifact ZIP; install `app-debug.apk` on your Android phone.

The debug APK is for personal testing, not a Play Store release. The app stores data locally in the browser/WebView; no cloud sync is configured.
