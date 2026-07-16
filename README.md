# Ria Russo Portfolio

This is a deliberately simple static, multipage portfolio. Each link opens a separate HTML file; there is no framework, bundler, or client-side router.

## Run locally

Open `index.html` in a browser, or use a simple local server such as VS Code's Live Server extension. Test every navigation link after changing filenames or folders.

## Project structure

```text
index.html       # Homepage
about.html       # About page
projects.html    # Project work
contact.html     # Contact details
styles.css       # Shared styles for every page
```

## Development notes

- Keep files as **plain text**, never rich text (RTF). Save HTML as `.html` and CSS as `.css`, with no spaces at the end of filenames.
- The homepage intentionally follows the provided minimal reference: an off-white background, centered name, and stacked page links.
- Use the shared header and navigation on every inner page. Update all pages when adding or renaming a page.
- Add local images later under `assets/images/` and use useful `alt` text. Avoid relying on external placeholder images for final work.
- Build incrementally: add content and small CSS improvements first. Introduce JavaScript or a framework only when the site genuinely needs interactivity, repeated components, or a content system.
- Before publishing, check mobile sizing, keyboard navigation, page titles/descriptions, image alt text, and all links.
