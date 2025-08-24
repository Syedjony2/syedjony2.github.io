# SRSOFTWARES Website

Static site for SRSOFTWARES. Free hosting with GitHub Pages.

## Structure
- `index.html` – Home
- `products.html` – All products grid
- `products/` – Product detail pages
- `assets/css/style.css` – Styles
- `assets/js/main.js` – Small JS (copyright year)

## How to host on GitHub Pages (free)
1. Create a new public repository named `srsoftwares.github.io` (replace with your GitHub username if different). If your username is `yourname`, repo must be `yourname.github.io`.
2. Copy all files from this folder into the repo and commit.
3. GitHub Pages will auto-deploy from the `main` branch.
4. Your site will be live at `https://yourname.github.io/`.

If you use a normal repo name (not `username.github.io`), enable Pages in Repo Settings → Pages → Build and deployment: Source = `Deploy from a branch`, Branch = `main` and folder `/root`.

## Add downloads
- Upload your installer/binaries to GitHub Releases (Repo → Releases → Draft a new release → Upload files → Publish).
- Open each product page in `products/*.html` and replace the `href="#"` on the Download button with your release asset URL.

## Update prices/text
- Edit texts directly in HTML files.

## Custom domain (optional, not required)
- You can add a domain later in Settings → Pages → Custom domain. This may have a cost at the registrar. To keep $0, stay with the default `.github.io` URL.
