# Tondlift – Privacy Policy

Static website hosting the Privacy Policy of **Tondlift: Gym Workout Tracker**
(Android: `com.tondlift.gym.workout.tracker`, and iOS), served with GitHub Pages.

This repository contains only this website. The app source code lives in a separate, private repository.

## Live URLs

| Page | URL |
|---|---|
| Landing page | https://botondsulyok.github.io/tondlift-privacy-policy/ |
| Privacy Policy (English) – **use this in the stores and in the app** | https://botondsulyok.github.io/tondlift-privacy-policy/privacy/ |
| Adatvédelmi tájékoztató (magyar) | https://botondsulyok.github.io/tondlift-privacy-policy/privacy/hu.html |

## Files

```
index.html          Landing page (app name, short description, links, contact)
privacy/index.html  Privacy Policy – English
privacy/hu.html     Privacy Policy – Hungarian
.nojekyll           Tells GitHub Pages to serve the files as-is (no Jekyll)
```

Plain HTML5 with inline CSS. No JavaScript, no framework, no build step, no external fonts/CDNs, no cookies.

## How to update

1. Edit **both** `privacy/index.html` and `privacy/hu.html` so the two languages stay in sync.
2. Update the "Last updated" / "Utolsó frissítés" date on both pages
   (the visible text and the `datetime` attribute of the `<time>` element).
3. If the app's data handling changed (new SDK, analytics, server, permissions, etc.), also update
   the Google Play Console **Data safety** form and the App Store Connect **App Privacy** answers.
4. Commit and push to `main`. GitHub Pages redeploys automatically within a minute or two.

Do not rename or move `privacy/index.html` – its URL is registered in Google Play Console,
App Store Connect and inside the app.

## GitHub Pages setup (one-time)

Repository → **Settings** → **Pages** → **Build and deployment** →
Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**.

