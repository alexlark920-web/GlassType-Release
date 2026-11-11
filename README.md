# GlassType distribution

GlassType is an offline iOS keyboard with English, Russian and Ukrainian layouts. The private development repository is not included here; this public repository contains release artifacts, SideStore metadata and the app icon only.

## Add a source in SideStore

- [Stable source](sidestore://source?url=https%3A%2F%2Fraw.githubusercontent.com%2Falexlark920-web%2FGlassType-Release%2Fmain%2Fsources%2Fstable.json)
- [Beta source](sidestore://source?url=https%3A%2F%2Fraw.githubusercontent.com%2Falexlark920-web%2FGlassType-Release%2Fmain%2Fsources%2Fbeta.json)

If the link does not open in your installed SideStore version, copy the corresponding raw JSON URL into Sources → Add Source. Install GlassType from the selected source; use Refresh All in My Apps to check for updates. A beta and a stable listing share the same app bundle identifier, so installing both side by side is not supported.

## Notes

The keyboard requires SideStore to re-sign the unsigned IPA. Installation and refresh still depend on SideStore, the paired device, and Apple free provisioning limits. The IPA being downloadable does not prove that it installs on every iOS version; please report device and iOS details with reproducible issues.
