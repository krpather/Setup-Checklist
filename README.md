# Setup History Upgrade

Manual Setup Lead URL:

`https://krpather.github.io/Setup-Checklist/history.html`

## Install
1. In Apps Script, replace current `Code.gs` with this package's `Code.gs`.
2. Deploy > Manage deployments > Edit > New version > Deploy.
3. Keep Execute as: Me and Who has access: Anyone.
4. In GitHub repo `krpather/Setup-Checklist`, add `history.html` and `history.js`.
5. Append `style-additions.css` to the bottom of the existing `style.css`.
6. Wait for GitHub Pages to redeploy, then open `/history.html`.

The history page groups submissions by month and setup date, shows people/roles/completion/issues, expands each saved raw checklist, and lets Keanan verify the full setup date with lead notes.

The Apps Script automatically extends `Web Submissions` with `Verified By` and `Lead Notes` columns while preserving existing data.
