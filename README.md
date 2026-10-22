# Doubles Tournament (offline Android app)

Option A, no installs: push this folder to a new GitHub repo. Open the Actions tab, run "Build APK" (it also runs on push), then download `DoublesTournament-apk` from the finished run and unzip it to get app-debug.apk.

Option B, Android Studio: File > Open this folder, wait for sync, then Build > Build Bundle(s) / APK(s) > Build APK(s). The APK appears in app/build/outputs/apk/debug/.

Home screen > Backup and transfer: export all data to one .json file, and import it on another phone.

Requires Android 10 or newer. Exported CSV, Excel, PDF and image files are saved to your Downloads folder.

Install: copy the APK to your phone, open it, and allow "Install unknown apps" if asked. The app has no internet permission and stores data on the phone.

The whole app is one file: app/src/main/assets/index.html
