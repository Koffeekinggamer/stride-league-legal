# Add an app

This folder is a template. It is not published. Jekyll skips folders whose names start with an underscore.

1. Copy this folder to a new folder at the site root. Use lowercase letters, for example `walkie`.
2. The new folder name must not start with an underscore, or Jekyll will skip it.
3. In each page, set `app_name`, `app_base`, `accent`, and `icon`.
4. Set `permalink` to `/{folder}/privacy/`, `/{folder}/support/`, `/{folder}/delete-account/`, and `/{folder}/security/`.
5. Replace every bracketed placeholder. Delete a line if you do not have that fact yet.
6. Put the app icon in `assets/` and point `icon` at it. SVG is enough for the header and the favicon.
7. Add one section to `index.md`, with the icon and links to the four pages. Give the section a class so its links can use the app color.
8. Pick a link color that passes WCAG AA on the background `#F4F2EE` (at least 4.5 to 1 for normal text). A bright brand color can stay in the icon. Darken it for text if the bright color fails.
9. Write in plain English, in short sentences. Do not use an em dash or an en dash. Kramdown turns two hyphens in a row into an en dash, so do not type those either.
10. Do not move the Stride League files at the site root (`privacy.md`, `terms.md`, `delete-account.md`). Those URLs are already public. Stride League uses `_layouts/default.html`. New apps use `_layouts/app.html`.

A terms page is optional. Stride League already has one at `/terms/`. To add terms for a new app, add `show_terms: true` and `terms_path` in that app's front matter, and write the page.
