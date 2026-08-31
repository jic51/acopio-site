# www.acopio.net

The public site for Acopio. **Generated — do not edit here.**

Every file in this repository is written by `tools/build-site.js` in the
private application repository, from a list that names each file and why it is
public. Editing a page here means the next build overwrites it.

## What must never appear in this repository

- `Code_v3_fixed.gs` or `Index_v3_fixed.html` — the application itself.
- Anything about pricing strategy, competitors or the roadmap.
- The installation runbook or the master-template notes.
- Any credential, stored-property name, spreadsheet address or deployment id.

The build is default-deny — a file is published only if it is named in
`build-site.js` — and `tools/test-site-privacy.js` re-derives the same set,
refuses anything outside it, and greps the built output for the strings above
before it can be pushed.
