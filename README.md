# CBX India Website

Final static Indian website for CBX Temperature Controlled Solutions.

## Project Overview

This project is a standalone static HTML website for the India business. It is not a WordPress, Elementor, React, or npm project. The USA website can link to this India website separately, for example from an Indian flag in the USA site header.

## Pages Included

- `index.html` - Home page
- `solutions.html` - Reefer Transport, Climate Crates, Passive Packaging, and monitoring feature content
- `industries.html` - Industry pages for Pharmaceuticals, Biotech & Life Sciences, Food & Frozen, and Electronics & Semiconductors
- `faqs.html` - Frequently asked questions

## Assets

- Main image folder: `images/`
- Main logo file: `logo.png`
- Navbar logo file: `images/nav-logo.png`

CSS and JavaScript are embedded inside each HTML file. Google Fonts are the only external dependency.

## How To Open Locally

Open `index.html` directly in a browser.

Optional local server:

```bash
python -m http.server 8765
```

Then open:

```text
http://127.0.0.1:8765/index.html
```

## How To Host

This site can be hosted on any static hosting provider:

- GitHub Pages
- Netlify
- Vercel
- AWS S3 / CloudFront
- Any standard static web server

Upload the project folder contents with `index.html` at the hosting root.

## Future Maintenance Notes

- Keep `index.html` at the root level.
- Keep the `images/` folder next to the HTML files.
- Do not move or rename images unless all HTML references are updated.
- Monitoring is positioned as a built-in feature across solutions, not a separate product.
- The USA WordPress/Elementor website should link to this India website instead of merging the files into WordPress.
