# Deployment Guide

This repository is configured for Firebase Hosting deployment to project `ankithbala-dcc97`.

## Prerequisites

- Firebase CLI installed: `npm install -g firebase-tools`
- Authenticated Firebase account with access to project `ankithbala-dcc97`

## Deployment Steps

1. **Login to Firebase**
   ```bash
   firebase login
   ```

2. **Select the project**
   ```bash
   firebase use ankithbala-dcc97
   ```

3. **Deploy to Firebase Hosting**
   ```bash
   firebase deploy --only hosting
   ```

## Site URLs

After deployment, the site will be available at:
- Primary: https://ankithbala.com
- Firebase: https://ankithbala-dcc97.web.app/
- Firebase: https://ankithbala-dcc97.firebaseapp.com/

## Project Structure

- `public/` - Static files served by Firebase Hosting
  - `index.html` - Homepage
  - `static/` - CSS, JS, and image assets
  - `pages/` - Additional HTML pages
  - `ub-logo.png` - Site logo
- `firebase.json` - Firebase Hosting configuration
- `.firebaserc` - Firebase project settings

## Future Products

The `public/astropanchanga/` path is reserved for a future product landing page.
