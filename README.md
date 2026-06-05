# 🛒 Bodega — Market Inventory App

A free, offline-capable Progressive Web App (PWA) for small market stall inventory management.

## Features
- ✅ Works 100% offline after first load
- ✅ Installable on Android/iPhone home screen (no app store needed)
- ✅ Inventory management with low-stock alerts
- ✅ Quick sale recording during the day
- ✅ End-of-day profit, trend, and restock report
- ✅ All data saved locally on the device
- ✅ Free to host and use forever

---

## How to Deploy (Free, No Coding Needed)

### Option A: GitHub Pages (Recommended — permanent free URL)

1. Create a free account at https://github.com
2. Click **New repository**, name it `bodega-app`, set it to **Public**, click Create
3. Click **uploading an existing file**
4. Drag and drop ALL these files:
   - `index.html`
   - `sw.js`
   - `manifest.json`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
5. Click **Commit changes**
6. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
7. Click **Save** — your app will be live at:
   `https://YOUR-USERNAME.github.io/bodega-app/`

Share that link with your friend. They open it once on their phone (needs internet just this first time), then it works offline forever.

---

### Option B: Netlify Drop (Easiest — drag and drop)

1. Go to https://app.netlify.com/drop
2. Drag the entire `bodega-app` folder onto the page
3. You get a free URL immediately (e.g. `https://random-name-123.netlify.app`)
4. (Optional) Go to Site settings → Change site name to something memorable

---

## How to Install on Phone (after deploying)

### Android (Chrome)
1. Open the app URL in Chrome
2. Tap the **3-dot menu → Add to Home Screen**
3. Or look for the "Install" banner inside the app

### iPhone (Safari)
1. Open the app URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (box with arrow)
3. Scroll down → tap **Add to Home Screen**
4. Tap **Add**

Once installed, the app icon appears on the home screen and opens like a regular app — no browser bar, works offline.

---

## Daily Usage

| Time | What to do |
|------|-----------|
| Morning | Open app → **Inventory** tab → update opening stock counts |
| During day | **Sales** tab → pick product → enter qty → tap "Record sale" |
| Evening | **Day Report** tab → see profit, trends, restock alerts → tap "Copy report" to share |

---

## Data & Privacy
- All data is stored **only on the device** using `localStorage`
- Nothing is sent to any server
- To back up: use the "Copy day report" button each evening and paste it into a notes app or group chat
