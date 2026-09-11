# Internal Page Creepster Font Design

## Goal

Display all text in `internal.html` using the Creepster font linked by the user, without changing the typography of other pages.

## Design

- Add Google Fonts preconnect hints and the Creepster CSS stylesheet link to the document `<head>`.
- Add a page-scoped body rule in `internal.html` that uses `"Creepster", cursive`.
- Keep the existing shared `styles.css` link intact and make no changes to `index.html`.

## Verification

- Confirm the Google Fonts URL is the CSS endpoint for Creepster rather than the specimen webpage.
- Confirm `internal.html` assigns Creepster to the body and remains valid HTML.
- Confirm no other project page is modified.
