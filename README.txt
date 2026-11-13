QUICK BILLING — OFFLINE ANDROID APP (INSTALLABLE PWA)

This package is an installable web app, not an APK. It becomes an app icon on Android and works offline after the first successful online visit and installation because the service worker caches the app shell. Product and bill data are stored locally in the browser/app origin.

ONE-TIME SETUP (FREE)
1. Extract this ZIP on a computer or phone.
2. Upload the CONTENTS of this folder (index.html, manifest.webmanifest, sw.js, icons folder) to a free HTTPS static host such as GitHub Pages.
3. Open the published HTTPS address in Chrome on your Android phone while online.
4. Wait for the page to finish loading and the offline service worker to register.
5. In Chrome, tap the three-dot menu > Install app (or Add to Home screen) > Install.
6. Open Quick Billing from the new home-screen icon. After the first successful setup, core app screens load offline.

IMPORTANT DATA NOTE
Browser file:// data and hosted-app data are separate. Before moving from an older version, export your product CSV from the old app. After installing this PWA, import that CSV in the app. Bills/history stored in the old browser origin do not automatically transfer. Use the app's export/backup features regularly.

OFFLINE LIMITATION
A service worker cannot be installed from a local file:// ZIP. The app needs one initial HTTPS visit to install/cache it. After that, it can run offline. A native APK would require a separate Android build/signing process; this ZIP is the free installable PWA package.
