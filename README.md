# Pylauncher

A tiny static site with tabs, descriptions and image galleries (with optional blurred "hidden" images).

## Run locally
Open `index.html` in a browser, or serve the folder:

    python3 -m http.server 8000

## Deploy with GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Your site will be live at `https://<username>.github.io/<repo>/`.

## Editing content
Edit the `tabs` array in the `<script>` section of `index.html`. Each tab has a `name`, `description` and `images` list. Set `hidden: true` on an image to blur it until clicked.
