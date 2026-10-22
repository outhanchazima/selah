# Selah modules

Static module hosting for the Selah Bible app (GitHub Pages).
`catalogue.json` lists each Bible module; the app downloads the
`.sqlite.gz` files and verifies them against the SHA-256 of the
decompressed module. Texts are public-domain, sourced from eBible.org
and converted with `tools/module_pipeline` in the app repository.
