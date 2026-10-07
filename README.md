# Modernisation Toolkit AUNZ — Releases

Windows installers and the stable update feed for Modernisation Toolkit AUNZ. Application source is maintained in a separate private repository.

> Modernisation Toolkit AUNZ is an independent, unofficial third-party tool developed in a personal capacity. It is not an official Siemens product and is not affiliated with, sponsored, endorsed or supported by Siemens AG or any other vendor or manufacturer. To the extent permitted by applicable law, the software is provided "as is", without warranty of any kind, express or implied. No ongoing support, updates or maintenance are promised. Use of the tool is at the user's own risk. Users should maintain appropriate project backups and independently review and validate all outputs and changes before applying them.

## Download and install

The current stable release is [Modernisation Toolkit AUNZ 0.1.2](https://github.com/timpendlebury/ModernisationToolkitAUNZ-Releases/releases/tag/v0.1.2).

Download the [signed Windows x64 installer](https://github.com/timpendlebury/ModernisationToolkitAUNZ-Releases/releases/latest/download/ModernisationToolkitAUNZDesktop-stable-Setup.exe) and run it on Windows x64. The installer includes the .NET runtime. The `.nupkg` and `releases.stable.json` assets support Velopack updates.

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
