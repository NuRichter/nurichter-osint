# NuRichter OSINT Recon Framework

A comprehensive open-source intelligence tool directory with **1167+ tools** across **33 categories**.

## Deploy

Static site. Push to Vercel, Netlify, or any static host. No build step required.

```bash
vercel --prod
```

## Structure

```
index.html    -- markup
style.css     -- design system (Signal Dark theme)
app.js        -- application logic + embedded tool data
vercel.json   -- deployment config + caching headers
```

## Features

- Collapsible tree navigation (33 categories, nested sub-categories)
- Real-time full-text search across names, descriptions, and metadata
- Filter by pricing (free / freemium / paid), OPSEC posture (passive / active), tool type (CLI, API, deprecated)
- Detail drawer with full tool metadata, flags, and direct links
- Responsive layout (sidebar drawer on mobile)
- Keyboard shortcuts: `Ctrl+K` focus search, `Esc` close panels

## Credits

Data source: OSINT Framework (`arf.json`)
Design and build: NuRichter Workspace
