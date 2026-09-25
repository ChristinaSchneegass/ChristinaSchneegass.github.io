# Cognitive Futures Lab website

A clean, responsive static website for GitHub Pages. It uses plain HTML, CSS, and JavaScript; no build step or package installation is required.

## Publish with GitHub Pages

1. Copy every file and the complete `assets` folder into the root of the repository.
2. Commit and push the changes.
3. Open **Settings → Pages** in GitHub and deploy from the repository root on the intended branch.

The page files belong in the repository root. Images, logos, CSS, JavaScript, and the favicon belong in `assets`.

## Structure

```text
index.html
research.html
people.html
partners.html
symposium.html
notes.html
about.html
connect.html
privacy.html
assets/
  cfl-logo.svg
  4TUNIRICT.png
  TUDelft_logo_cmyk.svg
  Eindhoven_University_of_Technology_logo_new.svg.webp
  UT_Logo_2400_Sta_Black_EN.png
  css/styles.css
  icons/favicon.svg
  js/main.js
```

## Editing

- Site colours and layout are defined in `assets/css/styles.css`.
- Navigation and footer links are repeated in each HTML file so every page works independently on GitHub Pages.
- The mobile menu and automatic copyright year are handled by `assets/js/main.js`.
- Edit or expand content directly in the relevant HTML file.

The site uses system fonts and does not load external font services. It currently includes no cookies, analytics, forms, or newsletter integration.
