# Learning Tracker – Android app

## Get the APK (no Android Studio needed)
1. Create a free account at github.com and make a new repository (any name, private is fine).
2. Upload ALL files from this folder (including the hidden `.github` folder) to the repository.
   If the "Actions" tab shows no workflow, click Add file > Create new file, name it
   `.github/workflows/build-apk.yml` and paste in the contents of that file from this zip.
3. Open the Actions tab > "Build APK" > Run workflow. Wait about 5 minutes.
4. Open the finished run, download "learning-tracker-apk" (a zip), unzip it to get app-debug.apk.
5. Copy the APK to your phone, tap it, and allow "Install unknown apps" when asked.

## Or build with Android Studio
Open the `android` folder in Android Studio, then Build > Build Bundle(s)/APK(s) > Build APK(s).

## Changing the app later
Edit `www/index.html`, then run the workflow again (or `npx cap sync android` before building).
