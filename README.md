# kemisto17.github.io

This user site owns Android App Link verification for Varta and redirects the
domain root to the Varta project website.

The current `assetlinks.json` publishes two SHA-256 certificate fingerprints.
Before each Android release, verify that one exactly matches the Play App
Signing certificate for `com.kemisto17.varta`. Keep only fingerprints whose
origin is known and still needs App Link verification.
