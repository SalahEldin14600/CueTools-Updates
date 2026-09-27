# CUE+ for Revit Updates

Public installers and update feeds for CUE+ for Revit. Application source is maintained in the private N1-Tools repository.

## Current full CUE+ installer: 0.9.0-beta.36

Supports Autodesk Revit **2022, 2023, 2024 and 2025** on 64-bit Windows.

**[Download the full CUE+ beta.36 installer](https://github.com/SalahEldin14600/CueTools-Updates/releases/download/v0.9.0-beta.36/CueTools-Setup-0.9.0-beta.36.exe)**

[Release notes and assets](https://github.com/SalahEldin14600/CueTools-Updates/releases/tag/v0.9.0-beta.36)

The combined installer includes the CUE+ tools, Family Renamer and the bundled Arch package. Close every Revit session before running setup. Administrator rights and a GitHub login are not required. Select the Revit versions you want to update.

CUE+ beta releases are marked **Pre-release**. GitHub's generic **Latest** link currently points to the separately versioned **Arch package**, not the full CUE+ installer. Use the full-installer link above.

## Updating an existing installation

1. In Revit, open **CUE+ > Manage > Update CUE+ > Check Now**.
2. Allow the update to download and verify.
3. Save your work and close all Revit sessions normally.
4. Reopen Revit after installation finishes.

CUE+ also checks the configured feed automatically. It never forces Revit to close.

## Update channels

- [beta.json](https://raw.githubusercontent.com/SalahEldin14600/CueTools-Updates/main/beta.json) is the authoritative current beta update feed.
- A stable feed will be published when a stable release is approved.

## Installer verification

SHA-256 for `CueTools-Setup-0.9.0-beta.36.exe`:

```text
c415e697bec142f3ffc9f4fc0b2785a7870aae7bffb0f5dcde4b724b306f6698
```

CUE+ verifies the installer checksum before scheduling installation. Module builds for all four supported Revit versions, 91 Family Renamer/navigation checks and installer compilation passed; live feature acceptance remains pending.
