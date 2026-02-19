# Wishes Board – With Anonymous Uploads + Emoji Reactions

This package adds:
- `upload.html`: Anonymous image upload using Uploadcare (no login for guests)
- Emoji Reactions block on the homepage (local-only counters)

## Configure
Open `config.js` and set:
- `eventName`, `eventDate` — already customized.
- `wishFormUrl` — paste your Microsoft/Google Form link (text-only; no file upload needed).
- `uploadcarePublicKey` — replace `demopublickey` with your own key from Uploadcare dashboard.

## How anonymous uploads work
We use the Uploadcare widget. Guests upload an image and get a shareable link. You can view/manage files in your Uploadcare dashboard.

## Publish
Upload these files to your GitHub repo root and ensure GitHub Pages is enabled (main branch, / root).

