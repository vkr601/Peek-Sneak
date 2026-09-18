# Lot Drawer

Static web app for the Sneak Peek event.

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and the `assets` folder to the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch → main → /(root)**.
5. Save and open the generated GitHub Pages URL.

## Deploy to Vercel

1. Import this repository into Vercel, or drag this folder into Vercel.
2. Framework preset: **Other** / no framework.
3. Build command: leave empty.
4. Output directory: `.`
5. Deploy.

## Google Sheets

The app reads `B2:D21` from the configured Google Sheet and maps the columns to:

- Column B → Subject
- Column C → Plot
- Column D → Twist

The spreadsheet must be accessible to the web. Changes are picked up when the app loads again.
