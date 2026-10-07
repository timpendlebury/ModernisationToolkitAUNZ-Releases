# Modernisation Toolkit AUNZ — Releases

Windows installers and the stable update feed for Modernisation Toolkit AUNZ. Application source is maintained in a separate private repository.

## Download and install

The first release is being prepared. Published installers will be available on the [Releases page](https://github.com/timpendlebury/ModernisationToolkitAUNZ-Releases/releases).

Download `ModernisationToolkitAUNZ-stable-Setup.exe` from a published release and run it on Windows x64. The installer includes the .NET runtime. The `.nupkg` and `releases.stable.json` assets support Velopack updates.

## Prerequisites

- Microsoft Excel for live workbook features.
- Siemens ABT Site/ABT Openness for ABT-connected workflows.
- Microsoft WebView2 Evergreen Runtime for embedded browser features.

These products are installed separately.

## Updates

Open **Settings → Support → Check for updates** in the installed Toolkit. Finish your work and close the Toolkit before running a newer installer. Preserve project backups and review migration outputs before applying changes to an ABT project.

## Repository contents

This repository holds public distribution documentation, Windows installers and update feeds. It does not contain application source, customer project files, user settings or publication credentials.

## Signed installer verification

The Toolkit uses the existing T. Pendlebury code-signing identity. Read the [verification and optional trust instructions](CODE_SIGNING.md), download the [public certificate](T-Pendlebury-code-signing.cer), and check its [SHA-256 fingerprint](CERTIFICATE-SHA256SUMS).
