# JARVIS AI APK

Hindi/English Android voice assistant starter project using Gemini AI and Android Text-to-Speech.

## Build APK
GitHub Actions automatically builds a debug APK when code is pushed to `main`.
Open **Actions → Build JARVIS Android APK → latest run → Artifacts** to download it.

## Gemini API key
Install the app, paste your own Gemini API key into the field at the bottom, and tap **SAVE API KEY**.
The key is stored locally on this device using app preferences. Do not share your key or commit it to GitHub.

## Notes
- Voice recognition uses the speech recognition service available on the Android device.
- This is a starter assistant. It does not silently control the phone or access private data.
