# My Apps

Turn any website into an app icon. Add a site, open it, and install the app (PWA).

## Features
- Add any website (name + URL)
- Opens it in an in-app viewer; if the site refuses to be embedded, it opens in your browser
- Real installable PWA (install from the browser menu)
- Your apps are saved locally; the app shell works offline

## Honest limitation
A website can only be shown *inside* the app if that site allows embedding. Sites like
YouTube block it, so for those the app opens the site in your browser. To make YouTube
itself an app, use Chrome -> m.youtube.com -> menu -> "Add to Home screen" (or the official app).

## Run
- Open `index.html` in Chrome, or use the GitHub Pages link.
- To install: open the link on your phone, then menu -> "Install app".

## Tested
9/9 checks passed in a real (headless Chromium) browser: seed, add, invalid URL, duplicate,
refresh persistence, in-app viewer open/close, service worker, no console errors.
