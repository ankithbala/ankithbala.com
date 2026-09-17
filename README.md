# ankithbala.com Portfolio

This repository contains the portfolio website for Ankith Bala, synced from Firebase Hosting.

## Source of Truth

**Live site:** https://ankithbala.com (Firebase Hosting project: `ankithbala-dcc97`)

This repository was synced from the live Firebase Hosting deployment on **September 17, 2026**. The live site content (last modified ~July 1, 2024) is the authoritative source.

## Repository History

- **2022:** Initial static site with different structure (css/, css2/ directories)
- **2026-09-17:** Synced with live Firebase Hosting deployment
  - Migrated to Firebase Hosting structure (`public/` directory)
  - Added `firebase.json` and `.firebaserc` configuration
  - Removed old 2022 static files that don't match live site

## Deployment

See [DEPLOY.md](DEPLOY.md) for deployment instructions.

## Project Structure

```
.
├── public/              # Firebase Hosting public directory
│   ├── index.html      # Homepage
│   ├── static/         # CSS, JS, and image assets
│   ├── pages/          # Additional pages
│   └── ub-logo.png     # Site logo
├── firebase.json       # Firebase Hosting configuration
├── .firebaserc         # Firebase project settings
├── DEPLOY.md           # Deployment guide
└── README.md           # This file
```

## Future Products

The `public/astropanchanga/` path is reserved for a future product landing page.
