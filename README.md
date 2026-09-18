# yakshitasharma.github.io

Personal portfolio — security consultant (web, APIs, AI applications).
Single self-contained `index.html`: no build step, no dependencies, no server.

## Deploy — GitHub Pages

```bash
git add -A
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

Then: **Settings → Pages → Source: Deploy from a branch → `main` / `root`**.
Live at `https://<username>.github.io` within a couple of minutes.

## Deploy — anywhere else

Drag this folder onto [Netlify Drop](https://app.netlify.com/drop), or point
Cloudflare Pages at the repo. No build command, output directory `/`.

## Before going public

- [ ] Replace the `#` placeholders in the nav and footer with real LinkedIn / GitHub / X links
- [ ] Confirm or remove the stat figures in the hero strip
- [ ] Add a photo (the hero currently has no portrait)
