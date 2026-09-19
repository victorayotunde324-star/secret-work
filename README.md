# Secret Work Landing Page

A responsive, Vercel-ready static landing page for the Secret Work basketball training app.

## Run locally

No build tools are required.

1. Open this folder in VS Code.
2. Install the "Live Server" VS Code extension (optional).
3. Open `index.html` with Live Server, or simply open the file in your browser.

## Deploy to Vercel

### Option A — GitHub
1. Create a GitHub repository.
2. Upload all files in this folder.
3. In Vercel, click **Add New → Project**.
4. Import the repository.
5. Framework preset: **Other**.
6. Build command: leave empty.
7. Output directory: leave empty / root.
8. Deploy.

### Option B — Vercel CLI
Install the Vercel CLI, log in, then run:

```bash
vercel
```

For production:

```bash
vercel --prod
```

## Before launch

Replace the `#` App Store and Google Play links in `index.html` with the real store URLs.

Replace the placeholder subscription prices (`$—`) with the real monthly/yearly prices.

Update the Privacy Policy and Terms & Conditions with your actual legal entity, contact details, governing law, refund rules, and service-specific terms.

The logo is stored at `assets/secret-work-logo.jpeg`.


## Updated visual assets

The hero now uses the supplied Secret Work app screen. The App Store and Google Play buttons use the supplied badge images. The supplied visual assets were enlarged 2× and lightly sharpened for cleaner web rendering.

The store links intentionally remain `#` until the app is published.
