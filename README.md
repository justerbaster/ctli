# Chill the Lion

Static site: lion + fan interaction. Prepared for Railway deploy.

## Deploy on Railway

1. Push the project to GitHub (if not already).
2. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub repo.
3. Select this repo. Railway will detect Node.js and use `npm start` (serve on `$PORT`).
4. In the service → Settings → Networking: generate a public domain.
5. Open the generated URL to see the site.

## Local run

```bash
npm install
npm start
```

Then open http://localhost:3000 (or the port shown in the terminal).
