# Kiro & Nini — Wedding Invitation Website

A responsive, static wedding invitation website ready for GitHub Pages.

## Customize before publishing
1. Open `index.html` and change the displayed names if needed.
2. The date is currently set to **18 February 2027**. If the year differs, update the visible date in `index.html` and `const weddingDate` in `script.js`.
3. Add your real photos in `assets/` using exactly these filenames:
   - `cover.jpg` (wide/portrait cover image)
   - `photo-1.jpg`
   - `photo-2.jpg`
   - `photo-3.jpg`
4. Add a music file you own or have permission to use as `assets/music.mp3`.
   Browsers generally require a user tap before audio can start; the site includes a Play Music button.
5. In `index.html`, update church details, church map search, reception venue, time, and RSVP contact/link when confirmed.
6. Update names in the page title and footer if desired.

## Preview locally
Open `index.html` in a browser. For best results, use a local static server or GitHub Pages.

## Publish for free with GitHub Pages
1. Sign in or create a GitHub account at https://github.com.
2. Create a new **public** repository, for example `kiro-nini-wedding`.
3. Upload all files and folders in this project (keep `index.html` at the repository root).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then save.
7. Wait for GitHub Pages to deploy. The public URL will look like:
   `https://YOUR-USERNAME.github.io/kiro-nini-wedding/`

GitHub Pages documentation: https://docs.github.com/en/pages/quickstart

## Notes
- The venue is intentionally marked as “to be announced”.
- The Google Maps button currently searches for St. George Church, Heliopolis. Verify the exact church pin before sharing.
- This project does not upload or store RSVP responses. The WhatsApp button opens a pre-filled message; edit its link to your preferred contact if needed.
