KAKA ACADEMY LEAGUE — ANDROID INSTALLABLE APP STARTER

Files in this package:
- index.html (updated website with app install support)
- manifest.json (app name, display settings and KAL logo reference)
- sw.js (service worker for installation and app-shell caching)

BEFORE UPLOADING:
Your existing official logo file must remain named exactly:
kal-logo.png

Upload all four files into the ROOT of your GitHub repository:
- index.html
- manifest.json
- sw.js
- kal-logo.png

IMPORTANT:
1. This package preserves the Google Search Console verification meta tag you supplied.
2. It keeps the Google Sheets spreadsheet ID and the existing tab/column assumptions.
3. It uses your existing kal-logo.png as the website logo and Android app icon.
4. Do not upload the ZIP file itself into the repository. Extract it first.
5. Commit all changes to the same branch/folder used by GitHub Pages.
6. Wait for GitHub Pages to publish, then open the website in Chrome on Android.
7. Use the visible “Install KAL App” button if Chrome offers it. Otherwise open Chrome menu (⋮) and choose “Install app” or “Add to Home screen”.

This creates an installable web app (PWA) first. It is not yet a standalone APK file. The live league table and match results need internet to update from Google Sheets. The app shell may open from cache when offline.
