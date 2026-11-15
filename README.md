# Jianjun Zhao — Academic Homepage

Academic website based on the original [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (MIT license retained in `LICENSE`). The original layouts, CSS, and JavaScript are retained.

**Site:** https://jianjunzhao-home.github.io/  
**Existing repository:** `jianjunzhao-home/jianjunzhao-home.github.io`  
**Default branch:** `main`

## Publish to the existing repository

1. Clone the **existing repository** with GitHub Desktop. Do not rename or recreate it.
2. Copy the **contents of this project** (not the outer ZIP) into the cloned repository, including the hidden `.github` directory. Replace its initial `README.md`.
3. Commit to `main` and push the commit to GitHub.
4. In GitHub, open repository **Settings → Pages → Build and deployment → Source → GitHub Actions**.
5. Verify **Actions → Deploy Academic Pages template site to Pages** ends with a green check. Open the site URL above.

The supplied upstream GitHub Actions workflow was corrected from `master` to `main` to match this repository. All official demo publications, teaching records, talks, mock biographies and fake blog entries were removed. Its appearance is kept from the original Academic Pages theme, not a custom card design.

## Edit site content

- `_config.yml`: name, affiliation, contact, sidebar and domain.
- `_data/navigation.yml`: top-level navigation menu.
- `_pages/`: personal pages (about, research, service, teaching, CV, contact and publications listing).
- `_publications/`: **four selected papers only**, not a full bibliography.
- `images/avatar-placeholder.svg`: an `JZ` initials **placeholder**. Replace with your own photo by uploading `images/profile.jpg` and changing `author.avatar` in `_config.yml` to `profile.jpg`.
- Add a verified Google Scholar URL or ORCID URL in `_config.yml` when available.

The earlier PANGU Lab repository/site is separate and remains unchanged. No custom domain is required. Do not upload the ZIP as a single file to GitHub: extract it first.
