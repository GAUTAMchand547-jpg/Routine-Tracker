# My Fitness Tracker (Android / Java)

A native Android project using Java, a local SQLite database, and a minimal monochrome UI.

## Build

Requirements: Android Studio with Android SDK 35 and JDK 17 or newer.

1. Open this folder (`MyFitnessTracker`) in Android Studio.
2. Allow Gradle sync and install the Android SDK platform/build tools requested by the IDE.
3. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
4. Android Studio writes the debug APK to `app/build/outputs/apk/debug/app-debug.apk`.

## Implemented
- Custom add/edit/delete habits with delete confirmation
- Daily or selected-weekday schedules and start dates
- Daily dashboard and completion check-ins stored in SQLite
- Monthly statistics based on scheduled check-ins, excluding future dates and respecting start dates
- Per-habit recent history and current/longest streak calculations
- Sunday rest mode
- Persistent local settings and completion history
- No account or internet permission required

## Limitations
- Reminder time is stored with each habit, but notification scheduling is not implemented yet.
- Backup/restore UI is not implemented.
- No automated device/emulator installation test has been run.
