# ML Compass — GitHub Pages

English-first Data Science and Machine Learning study app, including Databricks ML certification prep.

## Publish on GitHub Pages (no build step)

1. Create a **public** repository on GitHub (for example `ml-compass`).
2. Select **Add file → Upload files** and upload **the contents of this folder**, keeping `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, and `icons/` at the repository root. Do **not** upload only the ZIP. GitHub's web uploader may ignore hidden files such as `.nojekyll`; this file is optional for this project.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** and select **Build and deployment → Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Your app will be available at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` after GitHub finishes deployment.

## Install on Android

1. Open the deployed HTTPS URL in Chrome on Android.
2. Open Chrome's three-dot menu and tap **Install app** (or **Add to Home screen**, depending on the browser).
3. Launch ML Compass from the home screen. Load it online at least once so the app shell is cached for offline use.

## What is saved?

Progress is saved in your browser's localStorage for that specific site. It is **not synchronized** automatically between devices or different URLs; use the app's Export/Import Progress features to move it. Clearing site data may erase progress.

## Files

- `index.html`: complete app, course content, quizzes and interface (self-contained).
- `manifest.webmanifest`: install metadata.
- `sw.js`: service worker that caches the app for offline access.
- `icons/`: Android home-screen icons.
- `.nojekyll`: tells GitHub Pages to serve the files without Jekyll processing.

No npm, Python, dependencies, tokens or custom domain needed. External resource searches (Kaggle, Databricks docs, GitHub) still require internet access.
