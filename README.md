# NAWA Creative Media website

A static, responsive website split into separate HTML, CSS, and JavaScript files.

## Files

- `index.html` — page structure and SEO metadata
- `style.css` — all page styling and responsive layouts
- `script.js` — language toggle, navigation, FAQ, and interactive background behavior
- `logo.svg` — standalone NAWA wordmark
- `README.md` — this guide

## Run locally

1. Keep all five files in the same folder.
2. Open `index.html` in a modern browser.

No build step or package installation is required. Google Fonts are loaded from Google Fonts, so an internet connection is needed for those fonts.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload all five files to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

## Customize

- Update text and page sections in `index.html`.
- Change colors, spacing, and typography in `style.css`.
- Change interactions and translations in `script.js`.
- Replace `logo.svg` with your own SVG while keeping the same filename, or update the image path in `index.html`.

## Important

The contact buttons and social links use the contact details and URLs present in the supplied source page. Verify those details before publishing. The contact form, if added later, will need a form service or backend to receive submissions.
