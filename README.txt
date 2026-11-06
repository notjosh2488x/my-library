MY LIBRARY — iPad PWA package

CONTENTS
- index.html: the app
- manifest.webmanifest: installable app metadata
- sw.js: app-shell offline cache
- icon-192.png and icon-512.png: app icons

PUBLISHING
1. Extract this ZIP on a computer, or use a hosting service that accepts a folder/ZIP.
2. Upload the contents of this folder to a static HTTPS host such as Netlify Drop (https://app.netlify.com/drop).
3. Open the published HTTPS address in Safari on your iPad.
4. Tap Share > Add to Home Screen > Add.
5. Launch My Library from the Home Screen.

IMPORTANT
- EPUB files and library metadata are stored locally in the browser on that iPad.
- This package does not include cloud sync or a server-side backup.
- The EPUB reader uses epub.js and JSZip from jsDelivr when opening books; an internet connection is needed to load those libraries initially.
- For best results, keep the app installed and do not clear Safari website data.
- The app requires HTTPS for service-worker installation.
