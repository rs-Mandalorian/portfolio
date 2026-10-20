# Rob Schmelz portfolio

Personal portfolio, prepared October 20, 2026. Focus: digital platform and web strategy leadership.

GitHub owner: `rs-Mandalorian`.
Dedicated repository: `rs-Mandalorian/portfolio`.
Target project website: https://rs-mandalorian.github.io/portfolio/

The target address becomes available only after the repository and its Pages deployment are successfully configured.

## Preview

Open `dist/index.html` in a browser, or from this folder run:

```powershell
python -m http.server 8765 --bind 127.0.0.1 --directory dist
```

Visit http://127.0.0.1:8765. There is no dependency installation or build step.

## Edit

- `dist/index.html`: all public wording and page structure.
- `dist/styles.css`: responsive layout, colors, and print styles.
- `dist/app.js`: mobile navigation. Core content and project disclosures work without JavaScript.
- `dist/mark.svg`: original monogram/favicon.
- `REVIEW.md` in the local working copy: editorial decisions, evidence references, and questions. This private working note is excluded from the deployment ZIP and public site.

## GitHub Pages deployment

Use a **separate portfolio repository**. Do not make the career-center repository public or upload its evidence, applications, or other working files.

1. Review the content. The email and LinkedIn links are included as approved by Rob. Choose whether a public résumé should be included and prepare an approved version if so.
2. The local draft banner has been removed and the canonical URL is configured for the project website. Search indexing is allowed.
3. Copy the deployment ZIP contents into the `rs-Mandalorian/portfolio` repository's root. Its root should contain `index.html`, `styles.css`, `app.js`, `mark.svg`, `.nojekyll`, and this README. The ZIP excludes the private review note.
4. In GitHub repository Settings → Pages, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.

GitHub Pages publishes changes pushed to `main` automatically. Upload only the contents of the local `dist` folder when updating website files. Asset paths are relative so CSS, JavaScript, and icons resolve under `/portfolio/`. No custom workflow or build step is needed.

GitHub Pages provides public static hosting. This version has no server, form submission, analytics, cookies, external fonts, or external network dependencies.
