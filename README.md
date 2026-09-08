# Evrima Trailguide

### Your next move, at a glance.

**Keep your bearings. Track your Prime progress. Plan the next stop.**

A Windows companion for **The Isle: Evrima**, made by **Roid**. Bring your own position, a Gateway map, personal waypoints and your run's checklist together—then keep the essentials within reach in a compact mini-map.

[![Download Windows installer](https://img.shields.io/badge/DOWNLOAD-v1.23.0_Windows_installer-2b8a57?style=for-the-badge)](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/EvrimaTrailguide-Setup-1.23.0.exe)
[![Installer downloads](https://img.shields.io/github/downloads/roid-apps/Evrima-Trailguide/v1.23.0/EvrimaTrailguide-Setup-1.23.0.exe?label=installer%20downloads&style=for-the-badge&color=2b8a57)](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.23.0)

**[What's new in v1.23.0 →](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.23.0)** · [Validation report](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/VALIDATION-1.23.0.txt) · [Checksums](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/SHA256SUMS.txt) · [Report a bug](https://github.com/roid-apps/Evrima-Trailguide/issues)

*Counter measures this installer's downloads, not unique people or completed installs; cached counts may take time to refresh.*

![Trailguide's Prime checklist, location controls and Gateway map](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/trailguide.png)

*Real v1.23.0 application screenshots with a separate demo profile and manually entered sample position/pins. Not live gameplay or another player's saved run.*

## Meet your mini-map field kit

Find the rendezvous without keeping the whole dashboard in view. **Follow accepted location updates**, pick a destination, and switch layouts to suit the moment.

| Expanded exploration | Compact navigation | Map-only |
| --- | --- | --- |
| ![Expanded mini-map](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/minimap-exploration.png) | ![Compact mini-map](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/minimap-compact.png) | ![Map-only view](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/minimap-map-only.png) |
| Explore, edit pins and choose layers. | Keep navigation small and readable. | Hide the window chrome; adjust map opacity separately. |

- **Your destination stays in view:** north-up direction, distance and an off-screen target indicator. Stale readings pause live bearings.
- **Your map, your marks:** nest, food, water, danger and meeting pins; rename/recolour them, share waypoint-only files, or clear all pins with confirmation.
- **Less distraction:** optional click-through, configurable recovery shortcuts, quiet arrival notices and a main-window Show/Hide button.
- **Readable at a glance:** Normal, Large and High contrast presets; a subtle stale badge; breadcrumbs with clear point-count feedback and an Off setting.
- **Flexible window behavior:** compact/expanded layouts, saved placement, follow/resume controls, and safeguards for off-screen recovery after display changes.

The overlay is intended for **borderless/windowed play**. It updates from your visible Status Report—not continuous hidden tracking. Guidance is map-relative, not your dinosaur's facing direction or a terrain-aware safe route. Transparency is shown here against the page background, not composited into game footage.

## More than a map

| Tool | What it helps you do |
| --- | --- |
| **Prime checklist & routes** | Organize requirements and evidence, then plan stops for the zones your run still needs. |
| **Gateway map & search** | Find places, pins and grid squares; explore zone, water, food and other reference layers. |
| **Combat & survival** | Compare attacks, growth, direct damage and bleed under explicit assumptions. |
| **Lineage & mutations** | Record selected mutations and completed Entombs without inventing unverified enhancement multipliers. |
| **Run history & replay** | Import/export runs and revisit recorded positions and events. |
| **Growth viewer & compass guide** | Explore build-stamped growth references and identify compass symbols. |
| **Setup & customization** | Check OCR/assets/storage, adjust scan regions, choose themes and scale the interface. |

![Combat and survival reference comparisons](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/combat.png)

*Reference estimates, not guaranteed fight outcomes. Data-build warnings and limitations remain visible in the app.*

## What's improved in 1.23.0?

Alongside the mini-map upgrades, the main location section has a cleaner toolbar and settings popups, with more map space and a clearer **Last known position** card. Screen-coordinate parsing is stricter; movement checks survive restarts and hold large jumps after blind intervals. Suspicious trail gaps are drawn as breaks instead of misleading “teleport” lines. Saved samples remain intact.

**[Read the complete release notes →](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.23.0)**

## Download and get started

1. Export your run history before upgrading as a backup.
2. **[Download EvrimaTrailguide-Setup-1.23.0.exe](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/EvrimaTrailguide-Setup-1.23.0.exe)** and run the installer. Use the EXE—not GitHub's Source code archives. No separate .NET download is needed.
3. Open **Setup check**, then open Evrima's **Status Report**. Choose **Scan setup → Auto setup areas** and verify the previews.
4. Start scanning and choose **Show mini-map**. Open the Status Report when you need to refresh your position.

**Requirements:** Windows x64, Windows 10 build 19041 or newer. English Windows OCR support may need installing separately. Normal upgrades reuse per-user settings and history.

**Default mini-map shortcuts:** `Ctrl+Shift+M` show/hide · `Ctrl+Shift+I` mouse interaction · `Ctrl+Shift+H` map-only. Change them in Overlay options.

[Watch the earlier walkthrough](https://www.youtube.com/watch?v=2N6UwlLMEbo) for the core workflow. It includes subtitles and chapters; the newer mini-map/UI features shown above are not all covered in that older video.

## Honest limits & security

Trailguide reads your own visible information. It does not reveal hidden players, read game memory, inject code or automate gameplay. OCR and local run history stay on your computer; update checks are optional. [Read the privacy statement](PRIVACY.md).

Prime, map visits, combat, bleed, growth and mutation outputs are estimates with source/build limits—not server-confirmed outcomes. Follow server rules for companion tools. After a real large move while coordinates were hidden, confirmation can take roughly 45 seconds. Every physical monitor/DPI/game-input combination has not been tested.

**The v1.23.0 installer is unsigned.** Its [dated validation report](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.23.0/VALIDATION-1.23.0.txt) records the checks actually performed on this build. Earlier Microsoft analyst reviews of v1.11.1 or v1.22.0 do **not** certify this new file. No scan guarantees safety or means Microsoft endorsement. Keep protection enabled and report any detection with the file's SHA-256 and exact detection name.

**September 8, 2026 checks:** 735 automated tests and 83 isolated mini-map checks passed; all 119 bundled assets verified. Microsoft Defender reported no threats in the exact release files with security intelligence **1.459.111.0**. No fresh-machine install or new Microsoft analyst review is claimed.

Previous releases remain available on the [releases page](https://github.com/roid-apps/Evrima-Trailguide/releases).

## Made by Roid

Found a rough edge or have an idea? [Open an issue](https://github.com/roid-apps/Evrima-Trailguide/issues) with your app version and screenshot, or contact **Discord: r_o_i_d** · **Email: b_greenspan@yahoo.com**.

Independent fan project. Not affiliated with or endorsed by The Isle's developers. Third-party artwork and data remain credited in the installer notices. This repository hosts public downloads and documentation; its automatic source archives are not the application installer.
