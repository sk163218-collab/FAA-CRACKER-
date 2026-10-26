# FAA CRACKER — Android starter project

A native Kotlin + Jetpack Compose offline-first MCQ practice app.

## Included
- Subject-wise practice: Financial Accounting, Finance, Taxation, Indian Geography, Environment, General Studies and English
- Mixed mock test
- Immediate answer feedback and explanations
- Wrong-answer revision saved locally
- Last result saved locally
- No internet permission or account required

## Important content note
This starter contains 21 sample MCQs with answer keys and explanations. They have been checked for internal consistency and standard textbook-level accuracy, but this is not yet a comprehensive or officially endorsed FAA question bank. Tax rules, schemes, and exam syllabus can change; verify time-sensitive details against official current sources before exam use.

## Build APK in Android Studio
1. Install Android Studio (a recent stable version) on a computer.
2. Open this project folder (`FAA_CRACKER_Android`) in Android Studio.
3. Let Gradle sync. A working internet connection may be needed the first time to download Android build dependencies.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK is normally created at:
   `app/build/outputs/apk/debug/app-debug.apk`
6. Transfer the APK to your Android phone and install it. You may need to allow installation from that file source.

## Requirements
- Android Studio with a compatible JDK (Android Studio's bundled JDK is recommended)
- Android SDK platform 35
- Minimum Android version: Android 7.0 (API 24)

## Next improvements
- Expand the question bank chapter by chapter with reviewed answer keys
- Add optional negative marking and configurable mock-test timer
- Add detailed score history and chapter analytics
- Add import/export backup of progress

## Build using only an Android phone (GitHub Actions)
1. On your phone, create a repository on GitHub and upload the contents of this project, including the hidden `.github/workflows/build-apk.yml` file. Ensure the repository is named `FAA-CRACKER`.
2. Open the repository's **Actions** tab. If prompted, enable Actions.
3. Select **Build FAA CRACKER APK**, tap **Run workflow**, and wait for the run to finish successfully.
4. Open the completed workflow run, find **Artifacts**, and download `FAA-CRACKER-debug-APK`.
5. Extract the downloaded artifact ZIP; it contains `app-debug.apk`. Tap the APK to install.
Note: GitHub's mobile website layout may vary. Repository upload of multiple files/folders can be awkward on a phone; if upload is difficult, use GitHub's browser interface or a trusted Git client app. Do not upload passwords or secrets.
