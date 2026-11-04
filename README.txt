MP2 Monitor V2 — GitHub Pages PWA installation repair

Upload index.html, manifest.webmanifest, sw.js, and icons/ to the ROOT of the myMP2tracker GitHub repository (replace existing files).

Website: https://raynorcsuruelos.github.io/myMP2tracker/

The fix moves manifest and other page metadata into the HTML head, uses stable GitHub Pages manifest scope/start URL, and refreshes the service worker cache.

After deployment, close and reopen Chrome, refresh the website, then use Chrome menu > Add to Home screen > Install. If Chrome still reports that installation is unavailable, check Chrome/Android app installation restrictions and any existing installed copy.

MP2 data remains in browser IndexedDB, not in this ZIP. Export JSON before clearing site data or uninstalling an existing app.
