# Text Tracker — PWA → APK Ready

A polished, installable Progressive Web App that tracks the time since your last received and last sent text messages.

**Separate from the main SOLATX budget transparency site.**

## What's included
- `index.html` — full app with live timers, color states, toast notifications, haptic feedback
- `manifest.json` — PWA install config
- `sw.js` — offline caching service worker
- `icon.svg` / `icon-192.png` / `icon-512.png` — app icons

## Live URL (once Pages + domain set)
Will be available at a subdomain of solatx.org (e.g. tracker.solatx.org)

## Quick test (browser)
1. Open a local server in this folder:
   ```
   npx serve .
   # or python3 -m http.server 8080
   ```
2. Open the URL on your phone or Chrome desktop.
3. Chrome will offer “Install” / “Add to Home Screen”.

## Features
- Live second-by-second timers
- Color shifts (cyan → yellow → red) based on how long you’ve been waiting
- Sent counter that auto-sets timestamp
- One-tap “Now” buttons
- Reset + Copy Status
- Offline capable
- Installable as standalone app on Android & iOS
