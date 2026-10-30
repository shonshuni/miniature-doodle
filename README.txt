DAILYKIT — VERSION 1.1 STARTER

This is a responsive web-app/PWA prototype, not an Android APK yet.

To test: open index.html in a modern browser. Notes are stored in that browser on that device.
To install as a PWA: upload the folder to an HTTPS host, then use the browser's Install app / Add to Home Screen option. Service-worker offline caching requires HTTPS (or localhost).

QR generator: loads qrcode.js from cdnjs on first use, so QR creation needs an internet connection until the library is bundled locally. Other tools are designed to work locally in the browser.

Before public release: test on multiple devices, bundle the QR library for full offline use, add a real support contact and complete privacy policy, check accessibility, and perform security/reliability testing. This project has no advertising integration yet.
