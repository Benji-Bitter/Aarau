# Aarau website

A standalone static website. No npm, build step, backend or secrets needed.

## Deploy on GitHub Pages

1. Create a GitHub repository for your site.
2. Copy **the contents of this folder** into the repository root, including `assets/`, `downloads/`, `LICENSE.txt` and `.nojekyll`. `index.html` must be at the root.
3. Commit and push to your default branch (usually `main`).
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select your default branch and **/ (root)**, then Save.
5. GitHub will display your live URL after deployment. Paths are relative, so both `username.github.io` and `username.github.io/repository/` work.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

The download ZIP contains the nine Roman weights and variable fonts. Contact links use the supplied email and Australian phone number. No form service or tracking is included.

## Edit

Edit `index.html` for layout, text and contact details. `license.html` displays the supplied licence; retain `LICENSE.txt` with distributed fonts. Keep font URLs relative. The complete font project refreshes the font assets and download ZIP with `.venv/bin/python scripts/website.py` after rebuilding the fonts. The HTML pages remain authoritative and are preserved by that command.
