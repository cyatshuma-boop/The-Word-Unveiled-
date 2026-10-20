# The Word Unveiled — public web/PWA deployment bundle

This folder is prepared for HTTPS static hosting (for example GitHub Pages). HTTPS is required for service workers and reliable Add to Home Screen installation.

## Publish with GitHub Pages
1. Create or sign in to a GitHub account and create a new **public** repository, for example `the-word-unveiled`.
2. Upload the contents of this folder to the repository root (not the folder itself): `index.html`, `manifest.json`, `service-worker.js`, `icon.svg`, `icon-512.png`.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. The public URL will be shown in Settings → Pages.
6. Open that HTTPS URL on Android Chrome. Use the browser menu → **Install app** or **Add to Home screen**. On iPhone Safari, use Share → **Add to Home Screen**.

## Current limitations
- This is a prototype; the full KJV text loads from an external JSON source on first use.
- English word studies include a curated starter set. Live lexicon results depend on the third-party service and network availability.
- This is not a signed Android APK/AAB or iOS App Store build. Store release requires further testing, data/licensing review, and developer accounts.
