# Pocket Ledger: put it on your Android phone

Pocket Ledger is a small web app for tracking monthly income and expenses. Once installed it works
without internet, and your transactions are saved only on your phone. Nothing is ever sent to a server.

You need a free GitHub account to host the app files once. The files contain no personal data.

## 1. Put the files on GitHub (about 5 minutes, on a computer)

1. Unzip this package. You should see: `index.html`, `sw.js`, `manifest.webmanifest`,
   `icon-192.png`, `icon-512.png` and this README.
2. Sign in at https://github.com (or create a free account).
3. Click **+** (top right) then **New repository**.
   - Repository name: `pocket-ledger` (any name works).
   - Choose **Public**. GitHub Pages is free for public repositories only.
   - Click **Create repository**.
4. On the new repository page click **uploading an existing file**. Drag in all the unzipped files
   (the files themselves, not the folder). Click **Commit changes**.
5. Open **Settings** then **Pages** (left menu).
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**.
   - Set **Branch** to `main` and the folder to `/ (root)`, then click **Save**.
6. Wait a minute or two and refresh the Pages settings. The address appears at the top:
   `https://YOUR-USERNAME.github.io/pocket-ledger/`

## 2. Install it on your phone

1. Open that address in **Chrome** on your Android phone. This first visit needs internet.
2. Tap the **three dots** menu, then **Install app** (or **Add to Home screen**).
3. Open **Ledger** from your home screen. From now on it works offline.

## Your data and privacy

- The repository and the web address are public, but they only hold the empty app. Your transactions
  are stored in your phone's browser storage and never uploaded anywhere.
- Use **Settings, then Export all to CSV** regularly as a backup. Clearing Chrome's site data
  or uninstalling Chrome erases your entries.
- To move data to another phone, export on one and use **Import from CSV** on the other.
- Do not put any financial data in the GitHub repository.

## Updating the app later

Replace the files in the repository. If you change `index.html`, also change the `CACHE` name at the
top of `sw.js` (for example to `pocket-ledger-v2`) so phones pick up the new version.
