# Lift Log

A gym workout log that runs in your phone's browser and works offline.
Log sets / reps / kg, rest timer, workout history with PRs, and progress charts.

Your data is stored **on the phone only**. Use **History → Backup & restore** regularly
and save the backup file to iCloud Drive via the Files app.

## Put it online (GitHub Pages)
1. Create a new public repository on github.com (e.g. `lift-log`).
2. Upload everything in this folder (keep the `icons` folder).
3. Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
4. After a minute your app is at `https://<your-username>.github.io/lift-log/`.

## Add to iPhone home screen
Open that link in **Safari** → Share → **Add to Home Screen**.
Always open the app from the home-screen icon — on iPhone it keeps its own storage, separate from Safari.

## Updating the app later
Upload the new `index.html`, then change `VERSION` in `sw.js` (e.g. `lift-log-v2`) and upload that too.
Close and reopen the app twice to see the update. Your workouts are not affected.
