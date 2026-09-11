# Internal Page Creepster Font Design

## Goal

Display all text in `internal.html` using the Creepster font linked by the user, without changing the typography of other pages.

## Design

- Load Creepster through a valid Google Fonts `@import` in the existing external `styles.css`.
- Add an `internal-page` class to the body in `internal.html`.
- Scope the `"Creepster", cursive` declaration to `.internal-page` in `styles.css`.
- Use no embedded CSS and no second local stylesheet.
- Keep the existing shared `styles.css` link intact and make no changes to `index.html`.

## Verification

- Confirm the Google Fonts import uses the CSS endpoint for Creepster rather than the specimen webpage.
- Confirm `internal.html` contains the `internal-page` body class, links only `styles.css`, and contains no embedded CSS.
- Confirm `styles.css` scopes Creepster to `.internal-page`.
- Confirm no other project page is modified.
