# STARWOLF LABS // RX-14

Amber-phosphor world-band field receiver interface for an old iPhone.

## Put RX-14 on GitHub Pages

1. Create a new GitHub repository, for example `rx14`.
2. Upload **all files in this folder** to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. GitHub will show the HTTPS address when the site is ready. Open that address in Safari on the iPhone.
7. In Safari tap **Share → Add to Home Screen**.

## Editing stations

All station memories live in `stations.js`. The current Radio Garden entries are provisional search/city links and can be replaced with exact verified station links later.

## Files

- `index.html` — RX-14 interface and behavior
- `stations.js` — editable memory banks and station links
- `manifest.webmanifest` — Home Screen / standalone app metadata
- `icon.svg` — temporary STARWOLF RX-14 app icon

## Next upgrade

RX-14 v0.3 can replace external links with compatible direct audio streams and drive the spectrum display from real audio. iOS will require a user interaction before starting audio, so `OPEN SIGNAL` is a natural playback control.
