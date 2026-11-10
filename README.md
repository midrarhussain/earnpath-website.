# EarnPath website

A responsive static website that explains practical online income methods. Built with plain HTML, CSS and JavaScript, so it can be deployed to Vercel or GitHub Pages without a build step.

## Run locally
Open `index.html` in a browser, or use VS Code Live Server.

## Deploy to Vercel
1. Create a GitHub repository, for example `earnpath-website`.
2. Upload all files in this folder to the repository root.
3. Sign in to Vercel and choose **Add New → Project**.
4. Import the GitHub repository.
5. Framework Preset: **Other**.
6. Build Command: leave blank.
7. Output Directory: `.` (or leave default if Vercel detects the static site).
8. Click **Deploy**.

## Deploy to GitHub Pages
1. Open repository Settings → Pages.
2. Choose Deploy from a branch.
3. Select `main` and `/ (root)`, then Save.
4. Wait for the Pages URL to appear.

## Before public launch
- Replace the temporary brand name and logo if desired.
- Add a real contact email and complete privacy policy for your jurisdiction.
- Check current advertising-network policies before adding ads.
- Add original, researched articles; do not publish copied or AI-generated claims without fact-checking.
- Test mobile layout, links and page speed.

## Notes
- No backend, database, login or paid API is required.
- Search and category filters work in the browser.
- Method details are stored in `script.js`; edit the `methods` array to add or update entries.
- Income claims are intentionally avoided. The site is educational and does not promise earnings.
