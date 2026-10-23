# Selah modules

Module hosting for the Selah Bible app.

- `catalogue.json` (served by GitHub Pages) lists every Bible, commentary
  and dictionary module.
- The `.sqlite.gz` module files are assets of a GitHub Release
  (`modules-YYYY-MM-DD`); each catalogue `url` points there. The app
  downloads them and verifies the SHA-256 of the decompressed module.

Texts are public domain or Creative Commons BY / BY-SA, harvested from
eBible.org and the CrossWire SWORD repositories with
`tools/module_pipeline` in the app repository
(`sword_build.py`, then `merge_catalogue.py`). Copyrighted translations
are not hosted here.
