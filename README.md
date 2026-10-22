# QuickCal (web)

An iOS-style calendar you can host on GitHub Pages and add to your iPhone home screen.

## Put it on GitHub Pages
1. Create a new repository on github.com (e.g. `quickcal`).
2. Upload all files from this folder (index.html, manifest.webmanifest, sw.js, the two icons).
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. After a minute it's live at `https://<your-username>.github.io/quickcal/`.

## Add it to your iPhone
- Open the link in Safari → Share → **Add to Home Screen**. It opens full-screen like an app and works offline.
- Fast-add icon: open `https://<your-username>.github.io/quickcal/#add` and add *that* to your home screen too. Tapping it opens straight into "New Event" with the keyboard up.

Events are saved on your phone (in the browser's storage), not online.
