# Saint's Touch Mileage (PWA)

A fully offline-capable Progressive Web App for tracking photography business mileage with localStorage only.

## Free hosting options

### Option 1: GitHub Pages
1. Create a new GitHub repository and upload these files.
2. In GitHub, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` (or `master`) and folder `/ (root)`.
5. Save and wait for deployment URL.
6. Open the site over HTTPS on iPhone Safari.

### Option 2: Netlify Drop
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the project folder.
3. Netlify gives you a live HTTPS URL instantly.
4. Open that URL on iPhone Safari.

## Install on iPhone Home Screen
1. Open your hosted app in **Safari**.
2. Tap **Share** button.
3. Tap **Add to Home Screen**.
4. Keep name as **Saint's Mileage** (or customize), then tap **Add**.
5. Launch from Home Screen; it runs in standalone full-screen mode like a native app.

## Notes
- Data stored in `localStorage` on-device/browser profile.
- Use Settings tab to export JSON backup regularly.
- CSV export is available in Summaries.
