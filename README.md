# VMSG Importer (Android)

Imports SMS from a `.vmsg` file into the phone's normal messages, with duplicate protection.

## Build the APK
**Option A: Android Studio (easiest)**
1. Install Android Studio, choose File > Open, select this folder.
2. Wait for Gradle sync, then Build > Build APK(s).
3. APK: `app/build/outputs/apk/debug/app-debug.apk`

**Option B: GitHub (no install)**
1. Upload this folder to a new GitHub repository.
2. Open the Actions tab, run "Build APK", download `vmsg-importer-debug-apk`.

## Use on the Oppo phone
1. Copy the `.vmsg` file to the phone and install the APK (allow "install unknown apps").
2. Open the app, allow the SMS permissions.
3. Tap "Set this app as default SMS app" and accept.
4. Tap "Choose .vmsg file and import" and pick your file.
5. When finished, tap step 3 to make your normal Messages app the default again.

Android only allows the default SMS app to write messages, which is why steps 3 and 5 exist.
Imported messages then appear in your usual Messages app.
