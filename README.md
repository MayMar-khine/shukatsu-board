# 就活 Board

A job hunting kanban board in one file (`index.html`). No server, no account, no Claude needed.
Your data is saved in the browser you use (localStorage). The file on GitHub holds no personal data.

## Put it on GitHub Pages (about 5 minutes)

1. On github.com, click **New repository**. Name it e.g. `shukatsu-board`.
   - Free accounts: Pages only works on **Public** repos. That's OK, because `index.html` has no data in it.
2. Click **uploading an existing file**, drag in `index.html` (and this README), then **Commit changes**.
   - Do **not** upload `shukatsu-board-backup.json` to a public repo. That file has your companies and notes.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**, then **Save**.
4. Wait 1–2 minutes. Your board is live at `https://<your-username>.github.io/shukatsu-board/`.
5. Open it, click **Import**, and choose `shukatsu-board-backup.json` to load your 7 companies.

## How saving works

- Every change saves automatically, but **only in that browser on that device**.
- To move to another device (Mac → iPhone): click **Export** on the first device, send yourself the `.json` file, and click **Import** on the other one. Import replaces what's on that device.
- Clearing browser data, or using a private window, wipes the board. Click **Export** now and then as a backup.
- Anyone who opens your Pages link sees an empty board, not yours.

## Updating the design later

Edit `index.html` on GitHub (pencil icon) and commit. Your saved data is not affected.
