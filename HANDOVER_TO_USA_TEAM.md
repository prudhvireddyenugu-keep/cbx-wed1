# Handover To USA Team

## Summary

This is the final Indian version of the CBX Temperature Controlled Solutions website. It is a standalone static HTML website prepared for USA team review, hosting, and maintenance.

The existing USA website should not merge this project into WordPress or Elementor. Instead, the USA website should link to this Indian website using the Indian flag in the USA site header.

Suggested URL:

```text
india.company.com
```

## Pages Included

- `index.html`
- `solutions.html`
- `industries.html`
- `faqs.html`

## Assets Included

- `images/` - all page and card images used by the site
- `logo.png` - main logo used in footer and supporting areas
- `images/nav-logo.png` - transparent logo used in the navbar

## Technical Setup

- Static HTML website
- Inline CSS inside each HTML file
- Inline JavaScript inside each HTML file
- No npm build step
- No backend dependency
- Google Fonts are the only external dependency

## Hosting Notes

Host as a static website. Keep these files at the hosting root:

- `index.html`
- `solutions.html`
- `industries.html`
- `faqs.html`
- `images/`
- `logo.png`

Suitable hosting options:

- GitHub Pages
- Netlify
- Vercel
- AWS S3 / CloudFront
- Any standard static web host

## USA Website Linking Note

The USA website should add or keep an Indian flag link in the header. That flag should link to the hosted Indian site, for example:

```text
https://india.company.com/
```

## Known Pending Items

- Final production domain must be confirmed by the USA team.
- USA team should decide where the static site will be hosted.
- Any future WordPress integration should be treated as a separate project and should preserve the current approved India website design.

## Maintenance Guidance

- Keep image paths relative and preserve the `images/` folder structure.
- Do not rename image files without updating references in all HTML pages.
- Keep monitoring positioned as a built-in feature, not a standalone product.
- Review contact details and compliance wording before public launch if company policy changes.
