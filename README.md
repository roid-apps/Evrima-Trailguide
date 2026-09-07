# Evrima Trailguide

> **Current release — v1.22.0 (September 7, 2026):** Six versions of work in one release. Your Prime route is now **drawn on the map** as a numbered path that re-measures as you walk and re-plans when you arrive; the **whole interface can be recoloured** with ten themes and sliders, with the current look as the untouched default; map labels no longer overlap and you can **search for a place, waypoint or grid square**; **four map layers** that were already in your installer are drawn for the first time; waypoints can be renamed, recoloured and lettered; and there are **colour-blind-safe map palettes** and an **interface size slider**. Carries everything from v1.17.0 onward. Local Defender scans reported no threats. This version is unsigned and has **not** received Microsoft analyst review — the earlier Microsoft review applies only to v1.11.1. Keep antivirus protection enabled. [Security details](#security--download-transparency)

### Track your Prime progress. Find your way. Explore combat matchups.

A Windows companion for **The Isle: Evrima**, made by **Roid**. Keep your run organized with a Prime checklist, your own location on the Gateway map, and damage and bleed comparisons.

[![Download Windows installer](https://img.shields.io/badge/Download-Windows%20installer-24734f?style=for-the-badge&labelColor=14251f)](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.22.0/EvrimaTrailguide-Setup-1.22.0.exe)
[![v1.22.0 installer downloads](https://img.shields.io/github/downloads/roid-apps/Evrima-Trailguide/v1.22.0/EvrimaTrailguide-Setup-1.22.0.exe?displayAssetName=false&label=v1.22.0%20downloads&color=24734f&labelColor=14251f&style=for-the-badge)](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.22.0)
[![Watch the walkthrough](https://img.shields.io/badge/Watch-Full%20walkthrough-b42335?style=for-the-badge&labelColor=14251f&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=2N6UwlLMEbo)

**Current recommended download: v1.22.0 · Windows x64**  
[Release notes and downloads](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.22.0) · [Previous v1.16.2 release](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.16.2) · [Report a bug](https://github.com/roid-apps/Evrima-Trailguide/issues/new)

<sub>The counter tracks this version's installer downloads only, not unique people or installations. It excludes checksum downloads and may take time to refresh.</sub>

The older `v1.11.2-testing.1` tag is retained so existing links and download counts keep working.

## See it in action

[![Watch Roid demonstrate Evrima Trailguide](https://i.ytimg.com/vi/2N6UwlLMEbo/hqdefault.jpg)](https://www.youtube.com/watch?v=2N6UwlLMEbo)

**[Watch the full walkthrough →](https://www.youtube.com/watch?v=2N6UwlLMEbo)** — setup, Prime tracking, map tools, combat comparisons, and run replay. Includes subtitles and chapters.

## What can it help with?

| Tool | What you can do |
| --- | --- |
| **Prime progress** | Organize requirements, recorded evidence, and your run's reported outcome. |
| **Your location and growth** | Read your own visible Status Report using OCR, with automatic region setup and manual adjustments. |
| **Interactive Gateway map** | Zoom, pan, expand the map, and explore zone, water, food, salt lick, wallow, cave, air-current and location-name layers. Names no longer print on top of each other. |
| **Search the map** | Jump to a place, one of your own waypoints, or a grid square such as H18, with the distance and direction from your last read position. |
| **Prime route, drawn** | Order the zones your run still needs and see them on the map as a numbered path — with a live distance and bearing to the next one that updates as you walk, and a re-plan when you arrive. |
| **Your own waypoints** | Right-click to drop a mark, then rename, recolour and letter it. Saved between sessions and not tied to one dinosaur. |
| **Combat & survival** | Compare attacks, growth scenarios, direct damage, and bleed under different movement and wound-duration assumptions. |
| **Run history & replay** | Import/export runs and replay timestamped routes and events when the recording includes them. |
| **Trail you can trust** | Positions come from your own visible Status Report, and a reading that could not have come from where you actually are is refused rather than drawn. |
| **Mini-map 2.0** | Keep a small, movable self-location HUD on screen for borderless or windowed play, with optional click-through so it does not intercept your game controls. |
| **Compass guide** | Look up compass symbols and what they represent. |
| **Make it readable** | Recolour the whole interface with ten themes or your own sliders, scale it from 85% to 160%, and choose a map palette that does not rely on colour alone. The default is exactly what it has always looked like. |
| **Reading health** | See when each field was last actually read and how many readings the guards refused, so a scan that has quietly stopped working does not look the same as one that is fine. |
| **Growth timing** | An estimate of how long until your next milestone, measured from your own readings rather than looked up — so it already reflects your species, diet and server multiplier. |
| **First-launch readiness** | Check Windows OCR, bundled assets, local storage and scan-area setup before use; reopen Setup check when troubleshooting. |
| **Stated provenance** | Every growth number names the game version and build it came from, and how closely it reproduces the live readings collected for this project. |

## Download and get started

1. **Export your run history before upgrading.** Normal installation can replace your previous version and uses the same user settings.
2. **[Download EvrimaTrailguide-Setup-1.22.0.exe](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.22.0/EvrimaTrailguide-Setup-1.22.0.exe).** Use the installer, **not** GitHub's automatic “Source code” ZIP or TAR.GZ files.
3. Run the installer. Choose whether to create a desktop shortcut and launch Trailguide afterward. No separate .NET download is required.
4. Review the **first-launch readiness check**. Windows x64, Windows 10 build 19041 or newer is required; English Windows OCR support may need to be installed separately.
5. Start Evrima and open your **Status Report**. In Trailguide, use **Auto setup areas**, then check that the previews contain the correct information.
6. Start scanning. Open the Status Report to refresh your location; hover the growth meter for its percentage. Adjust the regions manually if your display or UI layout needs it.

> **Important:** Trailguide reads visible information about your own dinosaur. It does not reveal hidden players or guarantee Prime. Map visits and combat results are estimates, not server-confirmed outcomes; game updates can change their accuracy.

## Security & download transparency

### v1.22.0: local checks, not Microsoft analyst approval

On **September 7, 2026**, the release build passed **653 automated tests**, zero failed or skipped. Microsoft Defender custom scans with security intelligence **1.459.90.0** and real-time protection enabled — covering the exact installer and the complete published payload — completed with **no detection**. All **119 bundled assets** are present, and no personal settings or run history are bundled in the payload. The actual installer was run to the per-user location, its uninstall registration verified as *Evrima Trailguide 1.22.0*, and the installed binary confirmed byte-identical to the published application. A functional sweep of **55 checks passed with none failed** against that installed copy. `settings.json`, `settings.json.bak` and `run-history.jsonl` were compared by SHA-256 before and after installation and were unchanged.

The application is built from commit `7f7a8d5` on a clean tree and embeds `1.22.0+7f7a8d5d2560ee5baa35f2a13ccae8eb08dcd4a5`, so the binary can be traced to the exact source that produced it.

These are bounded checks on one PC, not an independent security audit, a clean-VM test, or proof of every in-game behavior, and no uninstall was performed. **v1.22.0 has not received a Microsoft analyst review**, and no VirusTotal report is provided for this build. The Microsoft review that cleared v1.11.1 does not cover this file.

- [v1.22.0 validation report](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.22.0/VALIDATION-1.22.0.txt)
- [v1.22.0 installer checksum](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.22.0/SHA256SUMS.txt)

**Installer SHA-256:**

```text
89DDC8706C80CF6BEF1E5C5CD2B5C42495792C5B562C5293CFAB69A7F4A73FE0
```

### Previous v1.11.1: Microsoft removed the detection

The v1.11.1 installer previously triggered `Program:Win32/Contebrew.A!ml`. Following the developer's submission on **August 30, 2026**, Microsoft's analyst response stated that the submitted files did not meet its criteria for malware or potentially unwanted applications and that the detection had been removed. The submitted installer shows **Final determination: Not malware**, with **No malware detected** for both cloud and client checks.

This resolves the reported false positive for the submitted installer. It is not a Microsoft endorsement, code-signing certificate, or guarantee covering future releases.

**If the previous detection still appears:** update Microsoft Defender's security intelligence through **Windows Security → Virus & threat protection → Protection updates → Check for updates**, then retry the same release download. Keep protection enabled. If a malware detection persists, stop and report the exact detection and definition version; do not add exclusions or choose “Allow” to bypass it. [Microsoft update guidance](https://learn.microsoft.com/en-us/defender-endpoint/microsoft-defender-security-center-antivirus)

### Unsigned installer and historical scan reports

The installer remains **unsigned**. Windows or Edge may still show **Unknown publisher** or **not commonly downloaded** warnings. These signing/reputation warnings are separate from the resolved Defender detection. [About SmartScreen reputation](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation)

- [Previous v1.11.1 installer report on VirusTotal](https://www.virustotal.com/gui/file/0f806e579cb87e3bffda736e8098c75abc1aaf40f3b00fcdfe3bb12e9ebd0d23/detection)
- [Previous v1.11.1 application report on VirusTotal](https://www.virustotal.com/gui/file/3a29e296a3e295dbaf4d7f446d224feb93bea739b1361d45f554f7a4baa3da72/detection)
- [Previous v1.11.1 checksum](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.11.1/SHA256SUMS.txt)

The reports are provided for transparency; their results can change over time. GitHub hosting, scan results, and matching checksums are not guarantees of safety. These links identify the v1.11.1 files, not future releases.

<details>
<summary>How to verify the installer checksum</summary>

In PowerShell, from the folder containing the downloaded installer, run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\EvrimaTrailguide-Setup-1.22.0.exe
```

Compare the result with the **v1.22.0** `SHA256SUMS.txt`. A match verifies that the bytes match the published file; it is not a malware assessment.

</details>

## Feedback & support

Found a problem? **[Open an issue](https://github.com/roid-apps/Evrima-Trailguide/issues/new)** with your Trailguide version, what happened, steps to reproduce it, and a screenshot if useful. For security warnings, include the security product, exact detection name, and definition version. Avoid posting private information or run exports you do not want public.

- **Made by Roid**
- **Discord:** `r_o_i_d`
- **Email:** [b_greenspan@yahoo.com](mailto:b_greenspan@yahoo.com)
- **Alternate email:** [w2tvd9hf62b@gmail.com](mailto:w2tvd9hf62b@gmail.com)

---

Independent fan project. Not affiliated with or endorsed by The Isle's developers. Third-party assets belong to their respective owners; see the notices included with the application.

<!-- Release maintenance: update the installer URL, version-specific download badge, release notes, checksum, and version-specific security evidence together.
     Do NOT blanket-replace the version string across this file: the "Previous ... release" link and the whole v1.11.1 security history must keep pointing at their own older tags.
     v1.11.2 retains the v1.11.2-testing.1 tag to preserve links and counters; v1.11.3 and v1.16.1 use plain tags.
     v1.12.0 through v1.16.0 were never published to GitHub, so v1.16.1 was the first release after v1.11.3.
     v1.17.0 through v1.21.0 were likewise never published, so v1.22.0 is the first release after v1.16.2 and its
     notes cover all six of them. -->
