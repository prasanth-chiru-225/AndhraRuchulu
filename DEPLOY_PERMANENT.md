# Permanent Hosting (GitHub Pages)

Your site is now configured for automatic permanent deployment using GitHub Pages.

## One-time steps (no Git command required)

1. Go to https://github.com/new
2. Create a repository (example: `andhra-ruchulu-site`) and make it **Public**.
3. Open that new repo in GitHub web.
4. Click **Add file → Upload files**.
5. Upload all files and folders from this `prasanth-food-hotel` folder (including `.github/workflows/deploy-pages.yml`).
6. Commit to the `main` branch.

## Enable Pages

1. In your repo: **Settings → Pages**
2. Under **Build and deployment**, set **Source = GitHub Actions**
3. Wait 1-3 minutes for the workflow to complete.

## Your permanent link format

`https://<your-github-username>.github.io/<your-repo-name>/`

## Future updates

Whenever you upload updated files to the `main` branch, your live website updates automatically.
