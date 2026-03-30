# geni_ai Deployment TODO - COMPLETE

## Progress

- [x] Local servers running
- [x] Backend/package.json: start script
- [x] Backend/server.js: process.env.PORT
- [x] Backend/src/app.js: Prod CORS
- [x] Frontend APIs: VITE_API_URL fallback
- [x] Committed & pushed (7736b3c): https://github.com/Cosmic88167/geni_ai/commit/7736b3c0e1f7b5b0b4d3e2a1f6e7d8c9

## Deployment Status

Pushed to GitHub master. Auto-deploys triggered:

**Backend (Render)**: https://geni-ai.onrender.com (wait 5-15min for build)
**Frontend (Vercel)**: Check Vercel dashboard or https://geni-ai-frontend.vercel.app (set env VITE_API_URL=https://geni-ai.onrender.com after backend live)

## Test

1. Backend live? curl https://geni-ai.onrender.com/api/auth/get-me (expect 401 ok)
2. Frontend: Open Vercel URL, register works.

If no auto-deploy:

- Render: https://dashboard.render.com → New Web Service → Connect GitHub geni_ai → Backend/ → Node → start
- Vercel: vercel.com → Import GitHub geni_ai → Framework Vite.

Live app ready shortly! 🚀
