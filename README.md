# Audiobook Sync — Deploy-Ready Full Repo

This repo contains a full-featured single-file React app (AppFull.jsx) that implements:
- Folder-based project loading via the File System Access API
- EPUB (epub.js) and PDF (pdfjs) rendering
- Audio player with sync, manual mapping, bookmarks, notes
- PWA manifest + simple service worker

## How to run locally

1. Install Node.js 16+
2. Extract the ZIP
3. In project folder run:
   npm install
   npm run dev

Open in Chrome/Edge for full folder picker and File System Access support.

## Deploy to Netlify / Vercel
- Push to GitHub and import in Netlify or Vercel (auto-detect Vite).
- Build command: npm run build
- Publish directory: dist

