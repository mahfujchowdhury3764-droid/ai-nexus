AI NEXUS — PWA starter

FILES
- index.html: website/app interface
- manifest.webmanifest: installable app metadata
- service-worker.js: basic offline caching
- icon.svg: app icon

TEST LOCALLY
Opening index.html directly (file://) shows the website, but PWA install and offline features need HTTPS or localhost.

PUBLISH
Upload the contents of this folder to an HTTPS static host. A free static host can be used for a starter site. After publishing:
- Android/Chrome: open the site and choose Install app / Add to Home screen.
- iPhone/Safari: open the site, tap Share, then Add to Home Screen.

IMPORTANT
This is an installable web app (PWA), not yet a native Android APK or iOS App Store package.
Some tools are local demo utilities and do not connect to an AI model. Real AI features need a secure backend and an AI provider API. Never put a private API key in browser JavaScript.
