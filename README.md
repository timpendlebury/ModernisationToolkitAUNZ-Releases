# Modernisation Toolkit AUNZ — Releases

Windows installers and the stable update feed for Modernisation Toolkit AUNZ. Application source is maintained in a separate private repository.

The Toolkit helps building-automation engineers prepare, review and import legacy Apogee and Desigo Classic data into ABT Site for AUNZ modernisation projects.

> Modernisation Toolkit AUNZ is an independent, unofficial third-party tool developed in a personal capacity. It is not an official Siemens product and is not affiliated with, sponsored, endorsed or supported by Siemens AG or any other vendor or manufacturer. To the extent permitted by applicable law, the software is provided "as is", without warranty of any kind, express or implied. No ongoing support, updates or maintenance are promised. Use of the tool is at the user's own risk. Users should maintain appropriate project backups and independently review and validate all outputs and changes before applying them.

## Functionality

- **ABT project setup:** Find and open ABT projects, select an existing controller for gateway mapping, and preview controller contents before importing.
- **P1 gateway mapping:** Load Excel mapping workbooks, validate point addresses and object definitions, import mapped objects into ABT, and generate HPE gateway text files. Bundled P1 application templates help prepare workbook mappings.
- **Apogee controller migration:** Load Excel point-transfer files or `.dtxchg` exports and plan mappings to PXC4, PXC5 and PXC7 controllers. Review physical and virtual points, onboard/TXM I/O assignments, sensor scaling, names, alarms and trends before ABT import.
- **Desigo Classic migration:** Load Xworks DMU export packages with optional DPT data, then review controller and I/O mappings. Import supported physical points, virtual objects, BACnet references, alarms, trends, PID loops and schedules into ABT.
- **Review and reporting:** Use validation issues, review queues and import logs to check the migration. Export mapping CSVs and Excel import summaries, with Desigo CC mappings, PPCL review documents and Modbus/M-Bus `.ioopt` files available where applicable.

## Download and install

The current stable release is [Modernisation Toolkit AUNZ 0.1.2](https://github.com/timpendlebury/ModernisationToolkitAUNZ-Releases/releases/tag/v0.1.2).

Download the [signed Windows x64 installer](https://github.com/timpendlebury/ModernisationToolkitAUNZ-Releases/releases/latest/download/ModernisationToolkitAUNZDesktop-stable-Setup.exe) and run it on Windows x64. The installer includes the .NET runtime. The `.nupkg` and `releases.stable.json` assets support Velopack updates.

## Prerequisites

- Microsoft Excel for live workbook features.
- Siemens ABT Site/ABT Openness for ABT-connected workflows.
- Microsoft WebView2 Evergreen Runtime for embedded browser features.

These products are installed separately.

## Updates

From version 0.1.2, installed Toolkit builds check for updates each time the main window opens. Open **Settings → About and Updates** for the installed/latest version, **Check for updates**, **Download update**, **Restart and Update**, and **Open releases**. Downloads run while you work. Save or export your mappings and results, finish active operations, and close the ABT project before restarting. Updates apply only after the Toolkit has exited cleanly; an interrupted shutdown postpones the update. If the restart cannot be qualified, use **Open releases** to download Setup.exe, finish your work and close the Toolkit before installing it. Version 0.1.1 has a manual check under **Settings → Support** and needs the newer installer to gain these controls. Preserve project backups and review migration outputs before applying changes to an ABT project.

## Repository contents

This repository holds public distribution documentation, Windows installers and update feeds. It does not contain application source, customer project files, user settings or publication credentials.

## Signed installer verification

The Toolkit uses the existing T. Pendlebury code-signing identity. Read the [verification and optional trust instructions](CODE_SIGNING.md), download the [public certificate](T-Pendlebury-code-signing.cer), and check its [SHA-256 fingerprint](CERTIFICATE-SHA256SUMS).
