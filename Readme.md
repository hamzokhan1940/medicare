# MedTracker — Dr. Imran
**Personal Health Records Manager · Karachi, Pakistan**

## Files in this package
| File | Purpose |
|---|---|
| `index.html` | The complete app — all code in one file |
| `manifest.json` | Makes the app installable on phones (PWA) |
| `sw.js` | Allows the app to work offline |
| `icon.svg` | App icon |

---

## Option 1 — GitHub Pages (FREE, already set up)

Your app is already live at: **https://gigmasterent.github.io/medicare/**

**To update after changes:**
1. Go to github.com → your `medicare` repository
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Select all (Ctrl+A) → delete → paste new file content
5. Scroll down → click **Commit changes**
6. Wait 1-2 minutes → refresh your live URL

**To upload all files at once (better method):**
1. Go to github.com → `medicare` repository
2. Click **Add file → Upload files**
3. Drag all 4 files (index.html, manifest.json, sw.js, icon.svg) into the box
4. Click **Commit changes**

---

## Option 2 — Firebase Hosting (FREE, faster than GitHub Pages)

1. Go to console.firebase.google.com → your project `medicare-tracker-pk`
2. Left sidebar → **Hosting** → click **Get started**
3. Follow the 3-step wizard:
   - Install Firebase CLI: open Command Prompt → type `npm install -g firebase-tools`
   - Login: type `firebase login`
   - Init: type `firebase init hosting` → select your project → set `public` folder as `.` (just a dot)
4. Copy all 4 files into a folder on your computer
5. Type `firebase deploy`
6. Firebase gives you a free URL like `medicare-tracker-pk.web.app`

---

## Option 3 — Netlify (FREE, easiest drag-and-drop)

1. Go to **netlify.com** → sign up free
2. Click **Add new site → Deploy manually**
3. Drag the entire `medtracker-package` folder into the upload box
4. Netlify gives you a URL like `random-name.netlify.app` in 30 seconds
5. You can rename it to something like `medtracker-dr-imran.netlify.app`

---

## Android APK — FREE (no Google Play account needed)

### Method A — PWABuilder.com (Easiest — 5 minutes)
1. Go to **pwabuilder.com**
2. Paste your app URL: `https://gigmasterent.github.io/medicare/`
3. Click **Start** → wait for analysis
4. Click **Package for stores** → select **Android**
5. Click **Download** → you get an `.apk` file
6. Send the APK to any Android phone via WhatsApp/email
7. On the phone: Settings → Security → Allow unknown sources → install APK

### Method B — Install directly from browser (no APK needed!)
1. Open Chrome on Android phone
2. Go to `https://gigmasterent.github.io/medicare/`
3. Chrome shows a banner: **"Add to Home Screen"** — tap it
4. App appears on home screen exactly like a real app
5. Works offline, full screen, no browser bar

---

## Firebase Setup (already done)
- Project: `medicare-tracker-pk`
- Auth: Email/Password enabled ✅
- Firestore: enabled, rules published ✅
- All data syncs automatically across all devices

## Gemini AI Setup
- Get free key at: https://aistudio.google.com/app/apikey
- Paste in app → AI Advisor page
- Models: gemini-2.5-flash → gemini-2.5-flash-lite → gemini-1.5-flash-8b (auto-fallback)

---
*MedTracker © 2026 · Dr. Imran · Karachi · +92 348-2590727*
