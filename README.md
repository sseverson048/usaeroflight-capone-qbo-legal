# USAeroFlight Capital One–QuickBooks Online Integration: legal documents

This repository contains **only** the public legal documents for the USAeroFlight Capital One–QuickBooks Online Integration. That integration is an internal
accounting application used by USAeroFlight LLC to account for Capital One business credit-card purchases in its
QuickBooks Online company.

The site exists because Intuit requires a registered app to provide public HTTPS URLs for its
End-User License Agreement and Privacy Policy.

| Page | Path |
|---|---|
| Home | `/` (`index.html`) |
| End-User License Agreement | `/eula/` |
| Privacy Policy | `/privacy/` |

## What is *not* here

- No application source code.
- No API keys, OAuth credentials, secrets, tokens, receipts, statements or transaction data.
- No connection to Capital One, QuickBooks Online or any API.
- No analytics, cookies, tracking, forms or external JavaScript.

It is plain static HTML and CSS served by GitHub Pages. `.nojekyll` tells Pages to serve the files as-is.

## Updating a document

Edit the HTML file, change its "Effective Date", commit and push. GitHub Pages republishes automatically.
