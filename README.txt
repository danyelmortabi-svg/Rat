Android Lab Demo APK source

This is a visible, consent-based WebView demo client. It does not provide covert access or remote device-control functions.

To obtain the APK without Android SDK on your phone:
1. Upload the contents of this folder to a GitHub repository (keep the .github folder).
2. Open the repository's Actions tab.
3. Run "Build demo APK" (or push to main).
4. Open the successful workflow run and download artifact "android-lab-demo-apk".
5. Extract app-debug.apk and install it on your Android device.

Default address is http://127.0.0.1:3000, for the lab panel running on the same phone. For a server on another device, enter its LAN address, e.g. http://192.168.1.10:3000.
