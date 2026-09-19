# Doc Scanner (self-hosted copy)

This folder is the whole app. Host it anywhere that serves static files and it becomes an installable, offline-capable scanner with no login.

## Put it on GitHub Pages (free, about 10 minutes, no coding)

1. Go to github.com and create a free account (or sign in).
2. Click the "+" at the top right, then "New repository". Name it `doc-scanner`, keep it Public, click "Create repository".
3. On the new repository page click "uploading an existing file". Drag ALL the files from this folder into the box (index.html, jspdf.umd.min.js, manifest.webmanifest, sw.js, icon-180.png, icon-192.png, icon-512.png, README.md). Click "Commit changes".
4. Click "Settings" (top of the repository), then "Pages" in the left menu. Under "Build and deployment" set Source to "Deploy from a branch", Branch to `main` and folder to `/ (root)`, then click "Save".
5. Wait one or two minutes, then open `https://YOUR-USERNAME.github.io/doc-scanner/` on your phone.
6. iPhone: open that address in Safari, tap Share, tap "Add to Home Screen". Android: Chrome shows "Install app" in the menu.

The home-screen app opens full screen, works offline after the first visit, keeps your documents on the phone, and saves through the normal share sheet (Files, Photos, AirDrop, WhatsApp, Drive).

## Updating later

Upload a new `index.html` over the old one (same steps as 3). Phones pick up the new version the next time the app is opened with internet.
