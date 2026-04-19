# Fleet Prestige OBD Pro — Android wrapper

Professional Android WebView wrapper for the uploaded Fleet Prestige HTML application.

## What is included
- Android app project (`app/`)
- WebView launcher activity
- Your uploaded HTML embedded as `app/src/main/assets/index.html`
- App icon and theme
- GitHub Actions workflow that builds a debug APK automatically

## Build on GitHub
1. Push all files from this repository to `main`.
2. Open **Actions**.
3. Run **Build APK** or push to `main`.
4. Download the artifact `FleetPrestige-v10.1-DEBUG`.

## Notes
- The APK is a WebView wrapper around your uploaded HTML.
- Your source HTML was taken from the uploaded file `fleet-prestige-pro (3).html`.
- If you update the HTML later, replace `app/src/main/assets/index.html` and rebuild.
