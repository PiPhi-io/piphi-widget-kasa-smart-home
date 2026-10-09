# Kasa Smart Home widgets

Independent PiPhi Widget SDK package for `tp-link-kasa-local-api`.

It provides device control, energy monitoring, smart-plug, and environmental cards. The package is versioned and released independently; the PiPhi registry links it to compatible Kasa integrations and Core installs it as an automatic companion.

## Validate

```bash
npm ci
npm run validate
```

Release tags use `v<package-version>`. GitHub Actions signs the immutable archive with PiPhi's first-party widget publisher key and attaches the archive, signed manifest, and checksums to the release.
