# TV Shows Android

A basic Android application for browsing TV shows.

## Project Structure

This is a standard Android project using Kotlin and Gradle.

```
TV-Shows-Android/
├── app/                          # Main application module
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/tvshows/    # Kotlin source files
│   │       │   └── MainActivity.kt           # Main activity
│   │       ├── res/                          # Resources
│   │       │   ├── layout/                   # Layout XML files
│   │       │   ├── values/                   # Values (strings, colors, themes)
│   │       │   └── mipmap-*/                 # App icons
│   │       └── AndroidManifest.xml           # App manifest
│   ├── build.gradle                          # App module build configuration
│   └── proguard-rules.pro                    # ProGuard rules
├── build.gradle                              # Root build configuration
├── settings.gradle                           # Project settings
└── gradle.properties                         # Gradle properties
```

## Requirements

- Android Studio Arctic Fox or newer
- JDK 8 or higher
- Android SDK (API level 21+)
- Gradle 7.4.2 or compatible

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/stylianoslavdas/TV-Shows-Android.git
   ```

2. Open the project in Android Studio

3. Sync the Gradle files (Android Studio should prompt you automatically)

4. Build and run the app on an emulator or physical device

## Building the Project

To build the project from the command line:

```bash
./gradlew build
```

## Running Tests

To run unit tests:

```bash
./gradlew test
```

To run instrumented tests:

```bash
./gradlew connectedAndroidTest
```

## Features

- Basic Android application structure
- Material Design components
- Kotlin support
- AndroidX libraries

## Technologies Used

- **Language:** Kotlin
- **UI Framework:** Android SDK with Material Components
- **Build System:** Gradle
- **Minimum SDK:** API 21 (Android 5.0 Lollipop)
- **Target SDK:** API 33 (Android 13)

## License

This is a test project for Android development.
