# Notice preview (test only)

Public test pages, separate from the app's production `/notices/` endpoint.
Use sample content only. `noindex` discourages search indexing; it does not make this site private.

- Entry: `index.html`; localized lists: `ko.html`, `en.html`, `ja.html`.
- Each detail page has matching-language links. All pages share their own `style.css`, including light/dark styles.
- `latest.json` uses a `preview-` ID. The released app does not request this file, so preview edits cannot change its production N badge.
- The app already selects the production localized list from `Bundle.main.preferredLocalizations`; Korean maps to ko, Japanese to ja, and English/other fallback to en.
- Test edits here first. Publish approved content by explicitly updating production `/notices/` localized pages and its manifest together. Do not copy preview banners, noindex metadata, or preview IDs to production.
- Do not add production links to this folder or make a production-page redirect to preview.
- Deploy only this directory when updating previews. Never bulk-copy the website root over the support repository.
