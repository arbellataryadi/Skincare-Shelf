# Skincare Shelf

A small phone app to track skincare: what's new, in use, expiring soon or finished, plus a morning/night routine checklist, skin tips and a private photo diary.

- **Your data stays on your phone.** Products, routine and photos are saved in the browser on the device you use. Nothing is uploaded anywhere.
- **Back up** from Settings (tap the round avatar at the top right) → Export backup. Restore it on a new phone the same way.
- **Import from Google Sheets:** Settings → paste your sheet link → Import. The sheet must be shared as "Anyone with the link → Viewer". Columns: Name, Category, Status, Expired Date, Notes.

## Install on your phone

1. Open the GitHub Pages link in **Safari** (iPhone) or **Chrome** (Android).
2. iPhone: Share → **Add to Home Screen**. Android: ⋮ → **Install app** / Add to Home screen.

It works offline after the first visit.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `sw.js` | Offline support |
| `manifest.webmanifest`, `icon*.png`, `icon.svg`, `apple-touch-icon.png` | Home-screen app name and icon |
