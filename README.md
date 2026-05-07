# Hushly Policy Site

Static GitHub Pages site hosting the Hushly privacy policy.

## Setup steps (one-time)

1. Go to https://github.com/new and create a new **public** repository named **`hushly-policy`** (Description: "Privacy policy for the Hushly Android app", no README/license needed).
2. From this directory:

   ```bash
   cd policy-site
   git init -b main
   git add index.html README.md
   git commit -m "Initial privacy policy"
   git remote add origin https://github.com/blood8879/hushly-policy.git
   git push -u origin main
   ```

3. On the new repo's GitHub page → **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `(root)` → **Save**
4. Wait 1–2 minutes for deployment. The site URL will be:

   **https://blood8879.github.io/hushly-policy/**

   Use this URL in Play Console → App content → Privacy policy.

## Updating later

Edit `index.html`, commit, push. Pages rebuilds automatically.
