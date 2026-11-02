# Under the Tree

Our family Christmas list: wishes, gifts and who's getting what.

- **Open the app:** https://zachdavies11.github.io/under-the-tree/
- Enter the family code once, then pick your name.
- On a phone, use **Add to Home Screen** to install it like an app.

## How it's built
- `index.html` – the whole app (no build step).
- `firebase-config.js` – which Firebase project the app talks to. These values identify the project; they are not secrets.
- `firestore.rules` – the database security rules (paste into Firebase → Firestore → Rules).
- `manifest.webmanifest` and `icons/` – the home-screen name and icon.

Lists are stored in Google Firebase (free Spark plan) under `families/<family code>/`.
