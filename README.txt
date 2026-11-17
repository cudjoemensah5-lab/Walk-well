# WalkWell PWA

This folder is the complete Progressive Web App package.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload **all files and folders in this package** (not just index.html).
3. In the repository, open Settings → Pages.
4. Choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish your site.
6. Open the HTTPS website in Chrome on Android.
7. Open Chrome's menu (⋮) and choose **Install app** or **Add to Home screen**.

## Important
- Keep `index.html`, `manifest.webmanifest`, `service-worker.js`, `splash-wallpaper.png` and the icon files together.
- GPS tracking requires HTTPS and location permission.
- The splash screen welcomes Bless Mensah. Edit the text in `splash-wallpaper.png` if you want a different name.
- The map and place search use internet services; the app shell can be cached, but live maps/GPS/place search still need internet and location permission.
- Keep the app open during a walk; background GPS tracking is not guaranteed.
