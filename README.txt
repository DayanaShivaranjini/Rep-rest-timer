REP & REST TIMER — ANDROID PWA

FILES
- index.html: the timer app
- manifest.webmanifest: installable app metadata
- service-worker.js: offline caching
- icon-192.png and icon-512.png: app icons

PUBLISH FREE WITH GITHUB PAGES
1. Sign in to https://github.com/ (create a free account if needed).
2. Create a new public repository, for example: rep-rest-timer.
3. Upload all five app files from this folder to the repository root.
4. In the repository, open Settings -> Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Choose the main branch and /(root), then Save.
7. Wait for GitHub Pages to publish. Open the Pages URL shown there on your Android phone in Chrome.
8. In Chrome, open the three-dot menu and choose Install app or Add to Home screen.
9. Launch Rep & Rest from your home screen. Open it once while online so its files are cached; it can then load offline.

NOTES
- PWA installation and service workers require HTTPS; GitHub Pages supplies HTTPS.
- Keep the screen awake and app in the foreground during workouts for the most reliable alarms. Android may throttle timers/audio in the background.
- The app stores workout settings in the browser's local storage on that device.
