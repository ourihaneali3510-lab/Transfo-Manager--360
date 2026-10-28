# TRANSFO-MANAGER 360 — Android v1

## Included
- Native Android starter project (Kotlin).
- French, Arabic, and English interface labels.
- Wilaya list codes 01–69.
- Local app-private JSON storage (no internet required).
- Add/delete substations and transformers.
- Test-result history with common test presets: water content, breakdown voltage, bushing tan delta, DGA, TTR, winding/insulation resistance and thermography.
- JSON backup export and restore through Android's document picker.
- GitHub Actions workflow to build a debug APK artifact.

## Build
Open this folder in Android Studio. Use JDK 17 and Android SDK 35, then Build > Build APK(s).
Project versions: Android Gradle Plugin 8.7.3, Kotlin 2.0.21, min SDK 23.

## Phone-only option
Upload the project files to a GitHub repository and run the Actions workflow. The APK is uploaded as an artifact when the workflow completes.

## Important
This is an MVP starter, not a validated electrical engineering system. It does not automatically judge tests as pass/fail. Confirm the correct Algerian wilaya list for your organizational use and validate on a device before operational deployment.
