# MISRAF Expo Android Starter

Android-first Expo/React Native starter configured for Expo EAS cloud builds.

## Build profiles
- `preview` -> installable Android APK
- `production` -> Android App Bundle (AAB) for Google Play

## First-time Expo setup
1. Sign in to Expo/EAS and create/link an Expo project.
2. Add the generated EAS project ID to `app.json` under `expo.extra.eas.projectId`.
3. Create an Expo access token and save it in the GitHub repository as the Actions secret `EXPO_TOKEN`.

## GitHub Actions
Use the **EAS Android Build** workflow and choose `preview` for APK or `production` for AAB.
