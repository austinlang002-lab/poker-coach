# Hold'em Coach

A 6-max No-Limit Hold'em trainer (5/10 blinds, 600-chip stacks) against 5 computer opponents. Every hand is recorded and each of your decisions is graded Good / Questionable / Mistake with a short explanation and the best play.

**Play:** https://austinlang002-lab.github.io/poker-coach/

## Install on iPhone
1. Open the link above in **Safari**.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Open it from the home-screen icon. It runs full screen and works offline.

## Hand history and backups
- History (last 1,000 hands) is saved on the phone, inside the home-screen app.
- **⋯ menu → Back up history** saves a `.json` file (choose *Save to Files* → iCloud Drive).
- **⋯ menu → Restore from backup** loads a backup file. Hands already on the phone are not duplicated.
- Back up now and then: deleting the home-screen app, or clearing Safari website data, erases the on-phone history.

## Files
- `index.html` — the whole app (game engine, opponents, coaching, UI)
- `manifest.webmanifest`, `icons/` — home-screen name, icon, full-screen mode
- `sw.js` — offline support

## Updating
Edit `index.html` and push to `main`. GitHub Pages republishes in about a minute; the app picks up the change the next time it is opened with a connection.
