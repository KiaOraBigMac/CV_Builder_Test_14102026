# Big Mac CV Builder — upgraded web version

A static, local-first CV builder that runs in a modern browser.

## Features
- Live CV preview with A4 PDF printing/export
- Word (.docx) export
- Save and open `.fcv` project files
- Local autosave in the browser
- Single-column and two-column layouts, templates, fonts, colours and margins
- Drag CV sections in the preview to reorder them; the order is saved in the project
- Click a text block in the preview to independently adjust its font, size, colour, alignment, line spacing, bold, italic and underline
- Per-block formatting is saved locally and included in `.fcv` project files; PDF and Word export use the saved section order and block formatting where supported

## Run locally
Open `index.html` in a modern browser. Word export loads the `docx` library from a CDN and therefore requires an internet connection; PDF export uses the browser print dialog.

## Publish with GitHub Pages
Upload the contents of `FreeCVStudioWeb` (the files `index.html`, `styles.css`, `app.js`, and `README.md`) to the root of your GitHub Pages repository, then enable Pages from the `main` branch and `/(root)`. Do not upload only the ZIP file.

- Bilingual interface (English by default; switch to Chinese with the language button)
- A user guide appears on page load and can be reopened from the top bar
- Empty Skills sections are hidden; skills are displayed without automatic middle-dot separators
