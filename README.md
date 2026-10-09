# tester_pages

Fictional test pages for the Docs2Wallet app, published with GitHub Pages.

- Home list: https://n05124.github.io/tester_pages/
- Each test lives in its own folder with an `index.html`, e.g. `url-pass-test/`.

## Current tests

| Folder | Test | Flow |
|---|---|---|
| `url-pass-test/` | URL pass test creation (Docs2Wallet Test Night, Sat Nov 21 2026) | Paste link → Confirm → Add to Apple Wallet |

## Adding a test

1. Create a new folder, e.g. `pdf-pass-test/`, with an `index.html` (plus any images or files).
2. Start the page with `<a href="../">← All test pages</a>` and a visible "TEST EVENT — NOT REAL" label.
3. For link-import tests, include schema.org `Event` JSON-LD with a **future** `startDate`.
4. In the home `index.html`, copy one `<article class="card">` block and update its folder, title, tags, details and expected result.
5. Commit; GitHub Pages republishes in a minute or two.

Everything here is fictional and exists only for testing.
