MY KEYBOARD — COMPLETE ANDROID IME

This package contains:
- keyboard.html: the complete single-file keyboard UI
- MyKeyboardService.kt: Android InputMethodService bridge
- AndroidManifest.xml + IME metadata
- MainActivity for enabling/selecting the keyboard

BUILD:
1. Open the folder in Android Studio.
2. Sync Gradle.
3. Build > Build APK(s).
4. Install the APK.
5. Open the My Keyboard app.
6. Tap Enable My Keyboard.
7. Select My Keyboard as the default keyboard.
8. Test in Instagram, WhatsApp, Chrome, etc.

The HTML keyboard has a built-in live test area when opened in a browser, while inside the IME the Android bridge sends key text to the focused app.

Voice typing depends on the phone's installed speech/voice service and is intentionally not granted microphone permission by this keyboard.
