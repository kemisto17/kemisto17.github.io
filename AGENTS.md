# Varta App Links Repository Instructions

This repository is an independent checkout. Do not assume `C:\socnet\AGENTS.md` is loaded.

Varta is a production, privacy-conscious campus application for verified students. Preserve the shared product rule that students may follow organizations but not other students.

## Scope

- This static GitHub Pages repository owns Android App Link verification for `com.kemisto17.varta` and redirects the domain root to the Varta project site.
- Keep `.well-known/assetlinks.json`, the Expo Android intent filter, the application package name, and deployed signing fingerprints aligned.
- Treat signing fingerprints as deployment-critical configuration. Verify values from the relevant Android debug or Google Play App Signing certificate before changing them.
- Keep the site static and minimal. Do not add dependencies or application services for simple redirects or verification files.

## Safety

- Do not add secrets, private keys, keystores, service credentials, or personal data.
- Do not change the production domain, redirect destination, package name, or signing fingerprints without explicit authorization. Cross-check the mobile repository's `app.json`; if that repository is unavailable, require a verified package and intent-filter configuration.
- Validate JSON and inspect the final static files after changes.
- Do not publish or deploy without explicit authorization.
