# Bāla Saṃskṛtam

A single-page web app for children: Sanskrit prayers and Gītā verses read aloud line by line in an Indian male voice (with a soft tanpura), plus letters, vowel signs, words and six small grammar lessons. Works offline once opened, installs to the home screen on Android and iPhone, and needs no server.

## Publish on GitHub Pages

1. Create a new public repository (for example `bala-sanskritam`) and upload every file in this folder to its root.
2. In the repository, open Settings → Pages, set Source to "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, and save.
3. After a minute the app is live at `https://<your-username>.github.io/bala-sanskritam/`. Share that link; on a phone, "Add to Home Screen" installs it like an app.

## Files

- `index.html` – the whole app, with all audio built in (about 4 MB)
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png` – home-screen install
- `sw.js` – caches the app so it opens offline

## Credits

Voice made with Indic-TTS by AI4Bharat, IIT Madras. Prayer and Gītā texts are traditional and in the public domain.
