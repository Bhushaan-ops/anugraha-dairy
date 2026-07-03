ANUGRAHA DAIRY — HOW TO GET A REAL INSTALLABLE APK
====================================================

This folder is a ready-to-host web app (PWA). To turn it into an actual
.apk file you install on an Android phone, follow these steps. No coding
needed — takes about 10-15 minutes.

--------------------------------------------------
STEP 1 — Put these files on the internet (free)
--------------------------------------------------
The files (index.html, manifest.json, sw.js, icon-192.png, icon-512.png,
icon-512-maskable.png) all need to be hosted at a public web address.
Easiest free option — GitHub Pages:

1. Go to github.com and create a free account (if you don't have one).
2. Create a new repository, e.g. "anugraha-dairy".
3. Upload ALL the files in this folder into that repository
   (drag and drop on the github.com website works fine).
4. Go to the repository's Settings tab -> Pages (left sidebar).
5. Under "Source", choose the "main" branch and save.
6. GitHub will give you a URL like:
   https://YOUR-USERNAME.github.io/anugraha-dairy/
   Wait 1-2 minutes for it to go live, then open it — you should see
   the Anugraha Dairy app.

(Alternative to GitHub Pages: netlify.com — just drag the folder onto
their "Deploy" page and it gives you a live URL instantly.)

--------------------------------------------------
STEP 2 — Convert it into an APK (free, no coding)
--------------------------------------------------
1. Go to https://www.pwabuilder.com
2. Paste your live URL from Step 1 into the box and click "Start".
3. It will scan your app and show a score/report — that's normal.
4. Click "Package for stores" (or "Publish").
5. Choose "Android" as the platform.
6. Keep the default settings (Package ID can be something like
   com.anugraha.dairy) and click "Generate".
7. It downloads a .zip — inside it you'll find the .apk file
   (and an .aab file, which is for the Play Store specifically).

--------------------------------------------------
STEP 3 — Install the APK on your father's phone
--------------------------------------------------
1. Send the .apk file to the phone (WhatsApp, email, USB, Google Drive).
2. On the phone, tap the file to install.
3. Android may show "blocked for your protection" — this is just
   because it's not from the Play Store yet. Tap "Install anyway" /
   allow "install from this source" when prompted.
4. The Anugraha Dairy icon will appear on the home screen like any
   normal app.

--------------------------------------------------
STEP 4 (OPTIONAL) — Publish properly to the Play Store
--------------------------------------------------
1. Create a Google Play Developer account at play.google.com/console
   (one-time $25 fee, needs your ID for verification).
2. Create a new app listing, upload the .aab file from Step 2.
3. Fill in the store listing (description, screenshots, privacy policy
   — PWABuilder's site has a free privacy policy generator if needed).
4. Submit for review. Google usually takes a few days to approve.

--------------------------------------------------
NOTE ON YOUR DATA
--------------------------------------------------
This app stores all customers and entries directly on the phone
(nothing is sent to any server). That means:
- Data stays private on that device.
- If you uninstall the app or clear its storage, the data is lost —
  so it's worth periodically noting down totals elsewhere, or asking
  Claude to add an export/backup feature down the line if you'd like.
