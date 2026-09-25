# Ranger Prep

A 12-month Ranger School fitness program and tracker that runs as an iPhone home-screen app. It works with no signal, and your data stays on your phone.

## Put it online (GitHub Pages, one time)

1. On github.com, create a new **public** repository named `ranger-prep`.
2. Click **Add file → Upload files**. Add all 7 files from this folder, then click **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, and folder to **/ (root)**. Save.
4. Wait about 1 minute. The app will be at `https://<your-username>.github.io/ranger-prep/`

## Install on iPhone

1. Open that link in **Safari**. It has to be Safari, not Chrome.
2. Tap **Share → Add to Home Screen → Add**.
3. Open it from the home-screen icon from now on. It launches full-screen and works offline.

## Your data

- Everything is saved on the phone as you type.
- Data from the home-screen app is separate from data in the Safari tab. Always use the icon.
- Deleting the icon deletes the data, so use **More → Export backup** every couple of weeks and save the file to Files or iCloud Drive. **Restore from backup** brings it back.

## Updating the app

Upload the changed files to the repo and change `CACHE = 'ranger-prep-v1'` in `sw.js` to the next number (`v2`, `v3`...). The phone picks up the new version the second time you open the app after the update.
