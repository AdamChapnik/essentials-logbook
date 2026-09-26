# Essentials Logbook

A mobile-first workout logbook app for [Jeff Nippard's Essentials Program](https://www.jeffnippard.com/). Track your exercises, log sets and reps, calculate warm-up weights, and stay on top of your training—all in one place.

## Features

- 📋 **Complete 12-week program** with 67 unique exercises
- 📸 **Exercise photos** for quick reference when choosing alternatives
- 💪 **Warm-up calculator** based on your working weight
- ⏱️ **Rest timer** with audio/vibration feedback
- 📊 **Set logging** with load, reps, and RPE tracking
- 💾 **Offline support** via service worker caching
- 📱 **PWA installable** on your home screen
- 🔄 **Backup/restore** via JSON export and import
- 📈 **Equipment tracker** to manage your gym setup

## Getting Started

### Online
Open the app directly: [Essentials Logbook](https://adamchapnik.github.io/essentials-logbook)

### Install on Phone
1. Open the app in your phone's browser
2. Tap **Share** (or menu icon)
3. Select **Add to Home Screen**
4. The app will install as a standalone app

### Offline
Once installed, the app works offline thanks to service worker caching. Your logged data syncs automatically.

## Data

- All data stored locally on your device
- No data is sent to external servers
- Use **Backup** to export your logs as JSON
- Use **Restore** to import a previous backup

## Technical Stack

- Vanilla HTML5, CSS3, JavaScript
- Service Worker for offline support
- Web App Manifest for PWA installation
- LocalStorage for data persistence
- Responsive design for mobile and tablet

## Files

- `index.html` - Complete app (includes all code, images, and data)
- `sw.js` - Service worker for offline caching
- `manifest.webmanifest` - PWA metadata
- `icon-*.png` - App icons for various contexts

## Development

This is a standalone static web app with no build process or dependencies. To modify:

1. Edit `index.html` directly
2. Test locally by opening in your browser
3. Deploy by pushing to this repository (GitHub Pages automatically serves the updated version)

## License

Created for personal use with Jeff Nippard's Essentials Program.
