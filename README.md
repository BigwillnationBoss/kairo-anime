# Kairo Anime — iPhone PWA

A free-to-start, mobile-first anime discovery and tracking web app. It is not a video host and does not bypass paywalls or copyright controls.

## Features
- Responsive dark premium interface
- Search by title and genre
- English dub / sub filters
- Local watchlist and episode tracking using browser localStorage
- Links to legal streaming discovery sources
- PWA manifest and service-worker offline caching

## Run locally
Open `index.html` for a quick preview. PWA installation and service-worker caching require HTTPS or localhost.

## Publish free
1. Create a GitHub account and a new public repository.
2. Upload all files in this folder to the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. When GitHub Pages publishes the site, open its HTTPS URL in Safari on your iPhone.
6. Tap **Share → Add to Home Screen**. If offered, enable **Open as Web App**, then tap Add.

GitHub Pages availability/terms may change. No paid domain is required; the free `github.io` URL works.

## Notes
- Catalogue is a starter sample, not every anime ever made.
- Streaming availability varies by region and licensing; provider links are discovery links, not guarantees of free access.
- Watchlist and progress stay in the browser on this device. Clearing site data or switching browsers can erase them.
- For production, add a maintained metadata API, source licensing verification, privacy policy, accessibility testing, and stronger offline behavior.
