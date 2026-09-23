# Verdant AI
Vite + React front end with Vercel serverless back end (`/api`). The API key stays on the server.

## Run locally
```bash
npm install
cp .env.example .env      # add ANTHROPIC_API_KEY
npx vercel dev            # serves front end and /api together
```
## Deploy
Push to GitHub, import in Vercel, add `ANTHROPIC_API_KEY` under Settings > Environment Variables, deploy.
