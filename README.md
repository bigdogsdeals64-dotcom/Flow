[README.md](https://github.com/user-attachments/files/22312065/README.md)
# UPS Live Flow (GitHub Pages)

This folder contains a single-file dashboard (`index.html`) you can host on GitHub Pages. It pulls the latest count from your Apps Script `/exec` URL and computes live **PPH** from your chosen start time and break minutes.

## Quick deploy (GitHub Pages)
1. Create a new public repo on GitHub, e.g. `ups-live-flow`.
2. Upload **index.html** to the **root** of the repo and commit.
3. Go to **Settings → Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` and **/(root)**
   - Save
4. Open your site: `https://<your-username>.github.io/<repo>/`

## Using the app
- In the **Endpoint** field, paste your Apps Script Web App URL (ends with `/exec`).
- Tap **Set Now** to populate the start time, or set any HH:MM.
- Adjust **Break (min)** as needed.
- The page refreshes data every 10 seconds. Preferences are saved in your browser.

## Optional
- Add the page to your phone’s Home Screen for a full-screen PWA-like experience.
