# PDF Studio

A private, browser-only PDF merge, split and page organizer built with React, Vite, pdf-lib and PDF.js.

## Run locally

```bash
npm install
npm run dev
```

## Deploy to Vercel

1. Push this folder's contents to a GitHub repository.
2. In Vercel, choose **Add New → Project**, then import the repository.
3. Vercel detects **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Click **Deploy**. No environment variables or backend are needed.

## Features

- Merge multiple PDFs with visual page-level ordering
- Split one PDF into multiple files by comma-separated ranges
- Rotate and remove pages
- Browser-only processing; no file uploads to a server

## Notes

- Large PDFs can consume significant browser memory.
- Password-protected/encrypted PDFs are not supported.
- Splitting into several ranges triggers several downloads; browsers may request permission for multiple downloads.
- Fonts are loaded from Google Fonts; PDF processing itself works without a server.
