# Project Lattice interface language packages v1

Public data-only download catalogue for Android Build75 and later. The app can
fetch this catalogue before authentication. English remains bundled in the app.
The existing German, French and Spanish interface translations are preserved.
These are interface text resources, not geographic/map data.

The `language-packs-v1` GitHub Release contains these exact four JSON files.
Verify pack sizes and SHA-256 values against `catalog-v1.json`. Downloads carry
no account token, location, H3 index or route. The app validates format, language,
revision, size, digest, plural forms and formatting arguments before using text.

New APK text does not authorize translating or publishing new language packs.
Updates are explicit owner-requested operations. Old compatible text remains;
missing/incompatible keys use English. No executable code is included.

Keep this static release and its assets when cleaning up obsolete APK releases.
Do not alter the existing `v1.0.0` map catalogue, map tags, packages or attribution.
