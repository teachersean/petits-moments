# Petits Moments

A gentle, browser-based companion for everyday French, with a small Korean practice corner.

## Run
Open `index.html` in a modern browser, or visit the GitHub Pages deployment. No build tools or account required. On iPhone, open the hosted app in Safari and use Share → Add to Home Screen. This prototype is not an offline-installed PWA.

## Privacy
Saved and custom phrases stay in the current browser's local storage. They do not sync to other devices and can be lost when browser data is cleared. Do not enter private family information. Optional speech uses device/browser voices; the operating system may use an online voice service. Nothing is recorded by this app.

## Development
The app is deliberately a single self-contained HTML file with embedded styles and JavaScript. Edit `index.html`, test the navigation, saved phrases, custom phrases, practice reveal/next, and speech fallback, then commit a focused change. Do not commit browser data, personal phrases, credentials, or hosting metadata.

## Status
Proof of concept. Desktop testing completed; real-device iPhone speech and persistence should be checked before relying on them. No external assets, analytics, or application network requests.
