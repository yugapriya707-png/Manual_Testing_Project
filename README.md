# Manual Testing Project — ShopLite

## Run
Open `index.html` in Chrome, Edge or Firefox. No installation or server is required.

## Included
- `index.html`, `styles.css`, `app.js`: responsive QA dashboard with separate sections for plan, scenarios, cases, execution, bugs and summary.
- Editable test statuses and live execution metrics.
- Export detailed test cases to CSV.
- Import a website folder or multiple HTML pages to generate a page-by-page manual test suite for navigation, forms, images, keyboard access and responsive layout.
- `docs/`: editable templates for each QA deliverable.
- `data/`: sample test cases, scenarios and defect log.

## Test your own website
1. Use **Choose website folder** to select a folder containing the site's HTML pages, or choose multiple `.html` / `.htm` files.
2. Review the generated page scenarios and test cases, then open the live site and record each result with the status dropdown.
3. Export the generated cases to CSV when needed.

The dashboard reads HTML files locally and does not execute uploaded scripts, crawl a deployed URL, or submit forms. Include all pages you want covered in the upload; linked images, stylesheets and other assets are not scanned.

## Suggested workflow
1. Review the test plan and confirm scope, risks, environment and entry/exit criteria.
2. Convert requirements into test scenarios.
3. Write test cases with preconditions, steps, test data and expected results.
4. Execute each case and record actual result, status and evidence.
5. Log defects with reproducible steps, severity, priority and environment.
6. Re-test fixes, run regression, and publish the summary report.

All names, execution statuses and defects in this training project are sample data. Replace them with actual evidence before using the report for a real release.
