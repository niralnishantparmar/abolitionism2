# Abolitionism Static Site

This is a GitHub Pages-ready static version of the site.

## Run locally

```bash
npm install
npm run dev
```

## Publish on GitHub Pages

1. Create a new GitHub repo.
2. Upload all files from this project.
3. In GitHub: **Settings → Pages → Source = GitHub Actions**.
4. Push to `main`.
5. GitHub will build and publish the site automatically.

Because the app uses `HashRouter`, page routes work on GitHub Pages without 404 refresh problems.
