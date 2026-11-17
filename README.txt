LOCAL FILE TAG EDITOR - hosting guide

1. Upload everything in this folder (index.html, sw.js, manifest.webmanifest
   and both icons) to any static host, for example:
   - Netlify: drag and drop the folder at app.netlify.com/drop
   - GitHub Pages: put the files in a repo and turn on Pages in Settings
2. Open the https:// link in Chrome on Android, then menu > "Install app"
   (or "Add to Home screen"). It then runs full screen.
3. Share the link with anyone. Nothing is uploaded: all editing happens on
   each person's own phone.

Note: the page loads two small script libraries (tag writer and MP3 encoder)
from the jsDelivr CDN. After the first visit they are cached for offline use.

Optional, Google Play: PWABuilder (pwabuilder.com) can package the hosted
link as an Android app bundle. A Play developer account costs a one-time
$25 fee.
