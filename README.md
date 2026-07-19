# CUE+ for Revit Updates

Public update distribution for CUE+ for Autodesk Revit 2022.

This repository contains update manifests and compiled installer releases only.
The application source code is maintained separately in a private repository.

## Channels

- `beta.json` — pilot releases for testing before team rollout.
- `stable.json` — production releases for general team use. This feed will be
  published with the first approved stable release.

Installers are attached to versioned GitHub Releases. CUE+ verifies every
download against the SHA-256 value in its channel manifest before scheduling an
installation.

## Current beta pilot

The current invited-pilot release is
[`0.9.0-beta.8`](https://github.com/SalahEldin14600/CueTools-Updates/releases/tag/v0.9.0-beta.8)
for Autodesk Revit 2022 on 64-bit Windows.

### First installation

1. Close every Revit session.
2. Download `CueTools-Setup-0.9.0-beta.8.exe` from the beta.8 release.
3. Run the installer. Administrator credentials are not required.
4. Open Revit 2022.
5. If Revit displays the unsigned add-in warning, choose **Always Load** once.
6. Use the tools from the **CUE+** ribbon tab.

After the first installation, CUE+ checks the beta feed automatically. Verified
updates are prepared silently and install after every Revit session closes
normally. CUE+ never forces Revit to close.

### Verification

The beta.8 installer SHA-256 is:

```text
5ffffd219bd1d28ce930ebde48b38b6d025bc3cd99b0443480defeee0d8405c8
```
