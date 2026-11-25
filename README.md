# Dan's Dough Balls V3 PWA foundation

Upload all files and folders in this package to the root of the GitHub Pages repository.

## Included
- Installable web app manifest
- App icons, Apple touch icon and maskable icon
- Service worker app-shell caching
- Offline launch and navigation fallback
- PWA install prompt where supported
- iPhone Add to Home Screen guidance
- Online/offline status indicator
- Automatic cache version cleanup
- Home-screen shortcuts for Dough, Timer and Journal

## Deploying an update
Change the `VERSION` value near the top of `sw.js` whenever cached files change. This forces the old cache to be cleaned up after the new service worker activates.

## GitHub Pages
Keep relative paths unchanged. The PWA is configured to run from either a custom domain or a GitHub project subpath.
