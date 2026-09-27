[README.md](https://github.com/user-attachments/files/32708561/README.md)
# Foundations Bootcamp

A polished, zero-build static website for the Linux, networking, and scripting bootcamp.

## What is included

- `index.html` — the complete website
- `favicon.svg` — custom lightning-bolt favicon
- `README.md` — GitHub Pages deployment guide
- `original-source.html` — untouched copy of the original uploaded file

## Run locally

Double-click `index.html` or open it in any modern browser. No npm, Python server, framework, or build step is required.

## Free GitHub Pages deployment

### Option A: free personal URL

Create a repository named exactly:

`YOUR-GITHUB-USERNAME.github.io`

Upload `index.html` and `favicon.svg` to the repository root. GitHub Pages can publish a user site at:

`https://YOUR-GITHUB-USERNAME.github.io`

In the repository, go to **Settings → Pages**, choose the branch you want to publish from, and save. GitHub says changes can take several minutes to appear after publishing.

### Option B: free project URL

Create any public repository, for example:

`foundations-bootcamp`

Upload `index.html` and `favicon.svg`, then go to **Settings → Pages** and publish from the `main` branch. The site URL will be:

`https://YOUR-GITHUB-USERNAME.github.io/foundations-bootcamp/`

### True custom domain

GitHub Pages supports an outside custom domain, but the domain itself is separate from GitHub Pages. If you already own `example.com`:

1. Open **Repository → Settings → Pages**.
2. Under **Custom domain**, enter your domain and save.
3. At your DNS provider, point the domain at GitHub Pages using the records GitHub shows you.
4. Turn on **Enforce HTTPS** once GitHub makes it available.

For an apex domain (`example.com`), GitHub currently documents these A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

For `www.example.com`, GitHub documents a CNAME pointing to `YOUR-USERNAME.github.io`.

## Notes

Progress is saved in browser `localStorage`. It persists on the same browser/device but is not a shared account or cloud sync system.
