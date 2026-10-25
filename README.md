# Macro Lab by LOKI FX (PWA)

The original calculator is preserved in `index.html`; PWA manifest, icons and service worker are added.

## Publish with GitHub Pages
1. Upload all files from this folder to the repository root (not the enclosing folder).
2. In GitHub open Settings → Pages.
3. Under Build and deployment select Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
4. Wait until Pages gives the live URL. Open that URL in Chrome on Android and use Install.

The install banner appears only in browsers that support `beforeinstallprompt`; iOS Safari uses Share → Add to Home Screen. First visit needs internet; after successful service-worker caching the app shell can load offline.
