# LEVEL UP — Android-ready starter app

This is a mobile-friendly Progressive Web App (PWA) starter.

## Included
- Daily routine from 7:00 AM to 10:30 PM
- Editable daily checklist and custom tasks
- Water tracker and daily reflection
- Weekly movement plan and workout log
- Balanced meal inspiration
- Guitar practice plan and history
- Career / digital-marketing priority tracker
- Daily completion dashboard and weekly reflection
- Local data storage and JSON export
- PWA manifest and service worker for install/offline support

## Run it
For PWA installation and offline caching, host these files on an HTTPS static host (for example, GitHub Pages or another static hosting provider). Open the hosted URL in Chrome on Android, then use Chrome menu → Add to Home screen / Install app.

You can also open `index.html` locally for a basic preview, but service-worker installation and reliable notifications require a secure hosted origin.

## Important limitations
- Data is stored in the browser on that device. It is not synced between devices.
- The notification button only requests browser permission and sends a test notification. It does not schedule reliable background reminders.
- This is a PWA, not a signed native APK. A native Android build would require an Android wrapper/build process and testing.
