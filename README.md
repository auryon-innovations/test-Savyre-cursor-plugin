# Savyre Cursor team marketplace

Marketplace wrapper for importing `savyre-cursor-plugin` into Cursor without changing the public single-plugin repo.

## Layout

```text
teamCursorPlugin/
  .cursor-plugin/marketplace.json
  savyre-cursor-plugin/   # plugin package (from ui-ux)
```

## Import in Cursor

1. Push this repo to GitHub.
2. Open Cursor → Customize → Browse Marketplace → **+ Add Marketplace**.
3. Paste this repository URL.
4. Import, then install **savyre-cursor-plugin**.
5. Developer: Reload Window.

Keep the public `savyre-cursor-plugin` repo as a single plugin (`plugin.json` only on `main`).
