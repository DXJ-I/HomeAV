# HomeAV GitHub Pages — static site

This is a plain HTML website. It does not need Jekyll, a theme, SCSS, or a `docs/` folder.

## Publish
1. Upload `index.html`, `privacy.html`, `support.html`, `.nojekyll`, and this README to the **repository root** (all at the same level).
2. GitHub repository → **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Select **main** and **/(root)**, then Save.
5. If needed, open **Actions** and rerun the Pages deployment.

Do not choose `/docs` unless you place the website files and `.nojekyll` inside `docs/` instead. Keep `.nojekyll` in the selected publishing directory. This static package has no `_config.yml` or Jekyll theme.

## App Store Connect URLs
Replace `YOUR-USERNAME` and `homeav-site`:
- Marketing: `https://YOUR-USERNAME.github.io/homeav-site/`
- Privacy: `https://YOUR-USERNAME.github.io/homeav-site/privacy.html`
- Support: `https://YOUR-USERNAME.github.io/homeav-site/support.html`

Replace the App Store placeholder links in `index.html` with the HomeAV listing URL once it exists.

## Release checklist
- Verify privacy wording against the final app, backend and SDKs.
- Complete App Store Connect App Privacy separately.
- Update the policy date when data practices change.
