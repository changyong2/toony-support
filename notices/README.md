# toony notices

Public, read-only announcements for the toony app.

Only the repository owner should be granted write access. App users do not sign in or receive repository credentials. There is no posting, editing or comment endpoint.

To publish an announcement, edit the localized HTML pages in this folder and update ko.html, en.html and ja.html in newest-first order. Keep links relative and do not add scripts, forms or third-party assets. GitHub Pages publishes the main branch.

For a new announcement, also change `latestID` in `latest.json` to a new stable ID (for example `2026-11-01-26.1.2`). Use the same ID for all languages and publish the localized pages and manifest together. The app compares this ID with the last successfully opened notice list to display a red N. Editing an existing announcement without changing its ID does not reset the badge.
