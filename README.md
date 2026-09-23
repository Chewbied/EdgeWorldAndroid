# EdgeWorld Android

Android launcher-style client for EdgeWorld. This is a first prototype and is intended for testing.

## Build in GitHub Actions (phone-friendly)

1. Create a GitHub repository and upload the **contents** of this folder (not the ZIP itself).
2. Keep the default branch named `main`.
3. Open the repository's **Actions** tab.
4. Select **Build EdgeWorld APK**.
5. Tap **Run workflow** if it is not already running.
6. When the workflow finishes, open the run and download the artifact named **EdgeWorld-Mobile-debug**.
7. Extract the downloaded artifact and install `app-debug.apk` on Android.

The workflow builds a debug APK with Java 17, Gradle 8.7, and Android Gradle Plugin 8.6.1.

## Important

This prototype attempts to reproduce launcher-style request characteristics, but it is not guaranteed to satisfy every server-side launcher check. If EdgeWorld still displays the launcher-only message, the next step is to identify the additional launcher behavior required by the current server.
