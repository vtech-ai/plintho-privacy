# Plintho Privacy Policy

Source of the privacy policy hosted at <https://vtech-ai.github.io/plintho-privacy/>.

## How it's served

- `index.html` is a self-contained, dependency-free static page — readable for years without any toolchain.
- Served via GitHub Pages from the `main` branch.

## To enable / verify Pages

GitHub repo → Settings → Pages → Source: **Deploy from a branch** → Branch: **main** / **/ (root)** → Save.

The page goes live within a minute or so at:

    https://vtech-ai.github.io/plintho-privacy/

## Custom domain (optional)

If pointing `plintho.app/privacy` here:

1. Add a `CNAME` file in this repo containing `plintho.app`.
2. In your DNS provider, add a `CNAME` record from `plintho.app` (or `privacy.plintho.app`) to `vtech-ai.github.io`.
3. Repo Settings → Pages → Custom domain → enter `plintho.app` (or your subdomain) → Save → wait for HTTPS.

## Updating

1. Edit `index.html`.
2. Bump the **Last updated** date inside the page.
3. Commit and push to `main`. Live within a minute.

The App Store Connect → App Information → Privacy Policy URL field should point at whichever public URL ends up serving this page.
