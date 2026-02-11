# Chill the Lion (ctli)

Static site: lion + fan interaction. Ready for Railway deploy.

## 1. Create repo on GitHub

- Go to [github.com/new](https://github.com/new)
- Repository name: **ctli**
- Public, leave "Add a README" unchecked
- Create repository

## 2. Push this project to GitHub

From the project folder:

```bash
cd "/Users/admin/Documents/chill the lion"
git remote add origin https://github.com/justerbaster/ctli.git   # if not already added
git push -u origin main
```

When asked for credentials: use your GitHub username and a [Personal Access Token](https://github.com/settings/tokens) (not your password).

## 3. Deploy on Railway

1. Go to [railway.app](https://railway.app) → **New Project** → **Deploy from GitHub repo**.
2. Choose **justerbaster/ctli**. Railway will detect Node.js and run `npm install` + `npm start`.
3. In the service → **Settings** → **Networking** → **Generate Domain**.
4. Open the generated URL to see the site.

## Local run

```bash
npm install
npm start
```

Then open http://localhost:3000 (or the port in the terminal). Railway sets `PORT` automatically in production.
