# Cadence - Music Learning Application

Cadence is a modern interactive music theory and ear training application for Android.

## Features

- **Learning Hub**: Guided modules covering fundamentals of music theory, notation, and harmony.
- **Keyboard & Notation**: Interactive piano keyboard synced with real-time sheet music notation.
- **Ear Training**: Practice interval, chord, and pitch recognition exercises.
- **Circle of Fifths**: Interactive wheel to visualize key signatures, scales, and relative minors/majors.

## Project Structure

- `cadence_app/`: The native Android application (Kotlin, Jetpack Compose, WebView bridge).
- `stitch_assets/`: Interactive module prototypes and UI assets.

## Getting Started

### Prerequisites
- Android Studio Ladybug | 2024.2+ or Android SDK (API 34/35)
- JDK 17+

### Running the App
1. Open the `cadence_app` directory in Android Studio.
2. Sync Gradle dependencies.
3. Run on an Android emulator or connected device:
   ```bash
   cd cadence_app
   ./gradlew installDebug
   ```
