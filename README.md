# FamLink APK

Capacitor wrapper for the FamLink app. GitHub Actions builds the Android APK automatically.

## How to get the APK (no Android Studio needed)
1. Create a new GitHub repository (e.g. `famlink-app`).
2. Upload ALL these files/folders to it (keep the structure), on the `main` branch.
3. GitHub -> **Actions** tab -> the "Build FamLink APK" workflow runs automatically.
4. When it finishes (green tick), open the run -> **Artifacts** -> download **FamLink-APK**.
5. Unzip -> `app-debug.apk` -> install on Android phones (allow "install from unknown sources").

## Rebuild after changes
- Edit files in `www/` (the app's web code) and push -> a new APK builds automatically.
- Or go to Actions -> Run workflow.

## Config
- App id: `in.nutriblitz.famlink`
- App name: FamLink
- Backend: Supabase (famlink_ tables)
