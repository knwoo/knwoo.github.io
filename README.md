# Keonwoo Kim — Academic Homepage

Ready-to-deploy, static academic homepage inspired by the visual design of [siruizou2005/academic-homepage](https://github.com/siruizou2005/academic-homepage). **This is a standalone HTML implementation, not a clone of the original Astro source.**

## Deploy

1. Create a public GitHub repository named `knwoo.github.io`.
2. Upload **the contents** of this folder (including `.github/workflows/deploy.yml`) to the repository root, commit to `main`.
3. GitHub repository **Settings → Pages → Source: GitHub Actions**.
4. The workflow deploys to https://knwoo.github.io/ automatically.

For a project repository rather than `knwoo.github.io`, links are relative so the site works under a subpath.

## Edit

- `index.html`: all website text and layout.
- `assets/profile.jpg`: profile photo.
- `Keonwoo_Kim_CV.pdf`: downloadable CV.

## Important items to verify

- **Notion About Me:** Notion page could not be retrieved. The current paragraph is a CV-derived placeholder; replace with the original Notion intro.
- **Email:** The user typed `knwoo.snu.ac.kr` without `@`. This package uses `knwoo@snu.ac.kr`, which is printed in the CV.
- **Publication status:** CV includes planned/submitted works and inconsistent years (SeDoNa appears under 2027 with RA-L 2025). These were retained and flagged; confirm before public deployment.

No Node.js or dependencies are required. Open `index.html` directly for a local preview.
