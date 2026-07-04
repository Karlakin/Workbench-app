# workbench; — app repo

Single-page mobile workbench. Reads and writes markdown notes in a **separate private repo** through the GitHub API. See LANDING-CHECKLIST.md in the kit for full setup.

Quick version: make this repo **public**, enable **Settings → Pages → Deploy from branch → main → / (root)**, open the Pages URL on your iPad, Share → **Add to Home Screen**, then connect it to your notes repo with a fine-grained token (Contents: read & write, notes repo only).

Files: `index.html` (the whole app) · `manifest.json` + icons (home-screen install). No build step, no dependencies, no server — your token and notes never touch anything but github.com.
