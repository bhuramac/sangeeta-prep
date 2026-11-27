# Sangeeta Prep: setup (about 20 minutes, once)

You'll do three things: put the app online (GitHub Pages, free), connect it to your Google Drive, and add it to each device's home screen.

---

## 1. Put the app online (GitHub Pages, ~5 min)

1. Go to **github.com** and sign in, or create a free account.
2. Click **New repository**. Name it `sangeeta-prep`, choose **Public**, then click **Create repository**.
3. On the new repo page, click **uploading an existing file**. Drag in all 5 files from the `app` folder: `index.html`, `sw.js`, `manifest.json`, `icon-192.png`, `icon-512.png`. Click **Commit changes**.
4. Open **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then click **Save**.
5. Wait 1–2 minutes. Your app is at **`https://YOUR-USERNAME.github.io/sangeeta-prep/`**

> The code is public, but it holds **no personal data**. The Guru's name, progress and recordings live only in your Google Drive and on your devices.

You can open the link and start practising right away. Progress is saved on the device until Drive is connected, and then it's synced up.

---

## 2. Connect Google Drive (~10–15 min)

This creates a sign-in key that lets the app save to **your** Drive. The app uses Google's narrowest permission, so it can only see files it creates itself.

1. Go to **console.cloud.google.com**. Sign in with the Google account whose Drive should hold the data.
2. At the top, open the project picker, click **New project**, name it `Sangeeta Prep`, then click **Create** and select it.
3. Open **APIs & Services → Library**, search **Google Drive API**, and click **Enable**.
4. Open **Google Auth Platform** (it may be labelled *OAuth consent screen*) and click **Get started**:
   - App name: `Sangeeta Prep`. User support email: yours.
   - Audience: **External**.
   - Contact email: yours. Agree, then **Create**.
5. **Audience → Test users → Add users.** Add your Gmail address.
6. **Clients → Create client:**
   - Application type: **Web application**. Name: `Sangeeta Prep web`.
   - **Authorized JavaScript origins → Add URI:** `https://YOUR-USERNAME.github.io` (no `/sangeeta-prep`, no trailing slash).
   - Click **Create**, then **copy the Client ID** (it ends in `.apps.googleusercontent.com`).
7. Set the Client ID **once for all devices**: in your GitHub repo, open `index.html`, click the ✏️ pencil, and find this line near the bottom:
   ```js
   const CONFIG = { clientId: '' };
   ```
   Paste the ID between the quotes, then click **Commit changes**. *(Alternatively, paste it in the app under Parent → Settings on each device.)*
8. In the app, tap **Connect Drive** in the top bar and pick your Google account.
   - You'll see "Google hasn't verified this app". That's expected, because it's your own private app. Tap **Continue**.
   - Allow access.
9. Check: Google Drive now has a folder **Sangeeta Prep** containing `progress.json`.

**Day to day:** Google sign-ins from web apps last 1 hour. When the top-bar chip says **"Tap to sync"**, tap it once (no password needed). Nothing is lost in between, because everything is saved on the device first and synced on the next tap.

---

## 3. Phone and iPad

1. Open the app link in **Safari**. Tap **Share → Add to Home Screen**.
2. Open it from the home-screen icon and connect Drive once on that device (the step 8 tap).
3. The first time she records, tap **Allow** for the microphone.
4. **iPhone:** turn **off** the silent switch, or the tanpura won't play.
5. **Headphones** when recording with the app's tanpura give the most accurate shruti scores. (In the real exam she uses her own shruti box.)

---

## 4. First-time settings (Parent → Settings)

- **Guru's name:** `Smt. Deepa Bhatt`. Used in the reminders and in oral question 6.
- **Shruti:** G4 · 392 Hz (the default).
- **Save settings.** They sync to the other devices through Drive.

## Where your data lives

| What | Where |
|---|---|
| All progress, ratings, settings, your extra links | `My Drive / Sangeeta Prep / progress.json` |
| Daily safety copies | `My Drive / Sangeeta Prep / progress-YYYY-MM-DD.json` |
| Recordings (latest 2 per item) | `My Drive / Sangeeta Prep / recordings/` |
| Offline copy | Each device (synced on reconnect) |
| Manual backup | Parent → Settings → Download backup |

## Updating the app later
When I send an updated `index.html`, upload it to the same GitHub repo (**Add file → Upload files**, replacing the old one). Devices pick it up the next time the app opens online. Your data is untouched.
