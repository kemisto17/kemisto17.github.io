# kemisto17.github.io

This user site owns Android App Link verification for Varta and redirects the
domain root to the Varta project website.

The current `assetlinks.json` contains the Android Studio debug certificate so
locally installed development builds can be verified. Before distributing
Varta through Google Play, add the Play App Signing SHA-256 fingerprint to the
same `sha256_cert_fingerprints` array.
