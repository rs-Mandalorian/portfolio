# Rob Schmelz portfolio

Product & Digital Platform Leadership.

Website: https://rs-mandalorian.github.io/portfolio/
Repository: https://github.com/rs-Mandalorian/portfolio

## Pages

- `index.html`: overview, approach, career history, and independent projects.
- `product-leadership.html`: discovery, product decisions, experimentation, roadmaps, and delivery.
- `digital-platforms.html`: CMS modernization, structured content, search, self-service, and content operations.
- `ecommerce-customer-experience.html`: shopping experiences, analytics, checkout, and fulfillment.

Every page has navigation to the other areas and approved email and LinkedIn links.

## Files and editing

In the published repository and deployment ZIP, website files are at the root. In the local career-center workspace, editable website files live in `portfolio/dist/`.

- Edit the HTML files for wording and page structure.
- `styles.css` controls the responsive layout, colors, and typography.
- `app.js` controls the mobile menu. Core content and case-study disclosures work without JavaScript.
- Inter 4.1 regular and italic font files are hosted with the website. `Inter-LICENSE.txt` contains the font license, which applies to the supplied Inter font files.
- `mark.svg` is the portfolio icon.

There is no build step or dependency installation. Open `index.html` directly, or serve the website folder with a static HTTP server.

## Hosting and updates

GitHub Pages publishes from the `main` branch and `/ (root)` folder. Upload website files from the local `dist` folder to the repository root. Asset paths are relative and work under `/portfolio/`.

Change the stylesheet version in each HTML file when changing shared CSS so visitors receive the new styling promptly.

The deployment ZIP contains website files and this README. Private working notes, deployment tracking, career evidence, and application files remain outside this repository.

This is a static website with no form submission, analytics, cookies, or external network dependencies.
