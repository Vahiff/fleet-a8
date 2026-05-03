# Fleet Prestige OBD Pro Android Wrapper

Professional Android WebView wrapper for the Fleet Prestige HTML application. The repository is prepared as an Android product shell that can be built, tested, and later upgraded into a signed release.

## Project Status

Status: Android wrapper MVP

Current focus:

- stable Android WebView shell
- embedded Fleet Prestige HTML app
- reproducible debug APK builds
- clear release path toward signed production builds

## What Is Included

- Android application project in `app/`
- WebView launcher activity
- embedded app asset at `app/src/main/assets/index.html`
- app icon and theme setup
- Gradle Android project configuration

## Tech Stack

- Android Gradle Plugin 8.2.2
- Java 17 target
- AndroidX AppCompat
- AndroidX WebKit
- AndroidX Activity

## Build Requirements

- Android Studio
- Java JDK 17
- Android SDK 34
- Gradle installed locally or Android Studio Gradle runner

## Local Build

```powershell
gradle assembleDebug
```

If using Android Studio, open the repository and run the `app` configuration.

## Updating The Embedded App

Replace:

```text
app/src/main/assets/index.html
```

Then rebuild the APK.

## Release Path

Before production release:

- add signed release configuration
- verify app permissions
- test WebView behavior on real Android devices
- prepare Google Play screenshots and privacy policy
- replace debug builds with signed `.aab` or release `.apk`

## Repository Standards

This repository uses professional project files for contribution, security, release hygiene, and issue tracking.

## License

All rights reserved unless a separate license is added by the owner.
