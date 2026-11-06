SMARTMATE PWA — FIRST WORKING STARTER

Included:
- Home dashboard
- Tasks with completion and search
- Reminders and agenda
- Quick notes
- Office work tracker
- Local document vault (up to 3 MB per file in this starter)
- Light/dark mode
- JSON export and restore
- PWA manifest and offline service worker

IMPORTANT LIMITATIONS:
1. This build stores data in the browser on the current device only.
2. Google sign-in, email/password accounts, cloud backup and multi-device sync are NOT connected yet.
3. Browser storage can be cleared by device/browser cleanup. Export JSON backups regularly.
4. For installability and offline service worker, host the folder on an HTTPS website (or localhost for testing). Opening index.html directly from Files will not enable PWA installation.
5. This is a starter implementation, not yet a hardened production app. Do not store highly sensitive documents until encryption, authentication, backend and security review are added.

QUICK TEST:
- Open index.html in a browser to test basic features.
- For PWA installation, deploy the folder contents to an HTTPS static host.
- Open the HTTPS address in Chrome on Android, then use browser menu > Install app / Add to Home screen.
