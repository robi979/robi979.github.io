# Robin Nowak — academic website

Plain HTML/CSS. There's no build step and no external requests; the site uses the visitor's system font.

## Editing content
- **About page:** `index.html`.
- **Research page:** `research.html`. Copy an `<article class="paper">` block for each paper.
- **Photo:** `assets/portrait.jpg` (about 800px wide). The crop is set by `object-position` in `assets/style.css`.
- **CV and papers:** PDFs in `pdfs/`. Replace the CV but keep the filename `cv_nowak.pdf`.
- **Colors and fonts:** change the variables at the top of `assets/style.css`.

Preview by double-clicking `index.html`.

## Deploying to GitHub Pages
1. Create a public repo named `<your-github-username>.github.io`.
2. Upload `index.html`, `research.html`, `README.md`, the `pdfs/` folder and the `assets/` folder. Don't upload `assets/photo.JPG` (the 4 MB original, not used by the site).
3. In the repo, go to **Settings → Pages**. Set Source to "Deploy from a branch" and choose `main` / root.
4. The site goes live at `https://<your-github-username>.github.io` within a minute or two.

**Custom domain (optional):** under Settings → Pages → Custom domain, enter e.g. `robinnowak.com`. Then add the DNS records GitHub shows you at your domain registrar.
