# Frontend Deployment

This folder is ready for Vercel deployment.

## Before deploy

Edit `config.js` and set the live Render backend URL:

`backendUrl: "https://your-render-backend-url.onrender.com"`

## Deploy

1. Upload this `frontend` folder to Vercel.
2. Keep the backend running separately on Render.
3. The Vercel frontend will load the live backend workspace in the embedded frame.
4. If you change the Render URL later, update `config.js` and redeploy the frontend.

## What this frontend does

- provides a clean hosted entry page
- embeds the live Render workspace
- gives you a simple public demo URL for client presentation
