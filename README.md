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
