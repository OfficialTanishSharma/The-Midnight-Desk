# The Midnight Desk — Vercel deployment

Static browser detective game deployed from this repository to Vercel.

## Included SEO files

- `index.html` — game, metadata, structured data, visible case manual, responsive layout, and local progress saving
- `social-preview.png` — Open Graph and X/Twitter preview image
- `favicon.ico`, PNG, SVG, and manifest assets — Google Search and browser icons
- `sitemap.xml` — search-engine sitemap
- `robots.txt` — crawler permissions
- `llms.txt` — concise AI-readable project description
- `google5ccb1f93b49d09fe.html` — Google Search Console verification
- `vercel.json` — static deployment headers

## Post-deploy checks

Confirm these URLs return successfully:

- https://the-midnight-desk.vercel.app/
- https://the-midnight-desk.vercel.app/social-preview.png
- https://the-midnight-desk.vercel.app/google5ccb1f93b49d09fe.html
- https://the-midnight-desk.vercel.app/sitemap.xml
- https://the-midnight-desk.vercel.app/robots.txt
- https://the-midnight-desk.vercel.app/llms.txt

The game stores only local case progress in the player's browser using `localStorage`.
