# AthleteTrack — Mood & Medication Tracker

A Progressive Web App (PWA) for athletes to track daily mood, medication effectiveness, sleep, and training load.

---

## What's in this folder

```
athlete-tracker/
├── index.html       ← The entire app (all code in one file)
├── manifest.json    ← Tells the browser "this is an installable app"
├── sw.js            ← Service worker — makes the app work offline
├── icons/
│   ├── icon-192.png ← App icon (home screen)
│   └── icon-512.png ← App icon (splash screen)
└── README.md        ← This file
```

---

## How to deploy to GitHub Pages (step by step)

### Step 1 — Create a GitHub account (if you don't have one)
Go to https://github.com and sign up. It's free.

### Step 2 — Create a new repository
1. Click the **+** button in the top right → **New repository**
2. Name it: `athlete-tracker` (or anything you like)
3. Set it to **Public** (required for free GitHub Pages)
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3 — Upload the files
1. In your new repository, click **"uploading an existing file"** (or drag-and-drop)
2. Upload everything in this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The `icons/` folder (upload both icon files)
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. In your repository, click **Settings** (top menu)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes, then refresh the page
7. GitHub will show you a URL like: `https://yourusername.github.io/athlete-tracker/`

That's it. The app is live. ✅

---

## How to install it on his phone (iPhone)

1. Open Safari on his iPhone
2. Go to the URL GitHub gave you
3. Tap the **Share** button (the box with an arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Tap **Add** in the top right
6. The app appears on his home screen like any other app

**On Android:**
1. Open Chrome
2. Go to the URL
3. Tap the three-dot menu → **"Add to Home Screen"** or **"Install App"**

---

## Sharing the link with your son

Just text him the URL: `https://yourusername.github.io/athlete-tracker/`

He installs it once. After that it works offline — no internet needed to log a check-in.

---

## How to update the app later

1. Go to your GitHub repository
2. Click on `index.html`
3. Click the pencil ✏️ icon to edit
4. Paste the new version
5. Click **Commit changes**

The app updates automatically within minutes. His data is safe — it lives on his phone, not on GitHub.

---

## Privacy note

All data is stored locally on the device using browser localStorage. Nothing is sent to any server. The share link encodes data in the URL itself — no database involved.

---

Built with: HTML, CSS, JavaScript, Chart.js, jsPDF — no frameworks, no build step, no dependencies to install.
