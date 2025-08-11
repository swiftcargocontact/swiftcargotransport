# SwiftCargo – static site
No build tools. Just open `index.html` in a browser or upload the folder to Netlify / Vercel / GitHub Pages / any host.

## Replace these before going live
- **Payment buttons:** In the Pricing section, change the `href` of each “Buy Now” button to your Payment Link.
- **Contact form:** Replace the `form action="#"` with a Formspree or Netlify Forms endpoint.
- **Fleet images:** Drop your photos into `/images` and keep the file names or update the `<img src>` paths.

## Deploy
- **Netlify:** Drag-and-drop the folder into the Netlify dashboard, or use the CLI.
- **Vercel:** `vercel` and choose this folder.
- **GitHub Pages:** Push to a repo, enable Pages for the `main` branch root.

## Structure
- `index.html` — single-page site with all styles inline.
- `images/` — put your vehicle photos here.
