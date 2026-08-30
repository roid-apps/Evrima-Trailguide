# Evrima Trailguide

> **Security update — August 30, 2026:** Microsoft reviewed the submitted v1.11.1 installer, determined that it did not meet the criteria for malware or potentially unwanted applications, and removed the previous Defender detection. Downloads are available again. Keep antivirus protection enabled; no exclusions are required. [Security details](#security--download-transparency)

### Track your Prime progress. Find your way. Explore combat matchups.

A Windows companion for **The Isle: Evrima**, made by **Roid**. Keep your run organized with a Prime checklist, your own location on the Gateway map, and damage and bleed comparisons.

[![Download Windows installer](https://img.shields.io/badge/Download-Windows%20installer-24734f?style=for-the-badge&labelColor=14251f)](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.11.1/EvrimaTrailguide-Setup-1.11.1.exe)
[![v1.11.1 installer downloads](https://img.shields.io/github/downloads/roid-apps/Evrima-Trailguide/v1.11.1/EvrimaTrailguide-Setup-1.11.1.exe?displayAssetName=false&label=v1.11.1%20downloads&color=24734f&labelColor=14251f&style=for-the-badge)](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.11.1)
[![Watch the walkthrough](https://img.shields.io/badge/Watch-Full%20walkthrough-b42335?style=for-the-badge&labelColor=14251f&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=2N6UwlLMEbo)

**Available now: v1.11.1 — Public Preview · Windows x64**  
[Release notes and downloads](https://github.com/roid-apps/Evrima-Trailguide/releases/tag/v1.11.1) · [Report a bug](https://github.com/roid-apps/Evrima-Trailguide/issues/new)

<sub>The counter tracks this version's installer downloads only, not unique people or installations. It excludes checksum downloads and may take time to refresh.</sub>

## See it in action

[![Watch Roid demonstrate Evrima Trailguide](https://i.ytimg.com/vi/2N6UwlLMEbo/hqdefault.jpg)](https://www.youtube.com/watch?v=2N6UwlLMEbo)

**[Watch the full walkthrough →](https://www.youtube.com/watch?v=2N6UwlLMEbo)** — setup, Prime tracking, map tools, combat comparisons, and run replay. Includes subtitles and chapters.

## What can it help with?

| Tool | What you can do |
| --- | --- |
| **Prime progress** | Organize requirements, recorded evidence, and your run's reported outcome. |
| **Your location and growth** | Read your own visible Status Report using OCR, with automatic region setup and manual adjustments. |
| **Interactive Gateway map** | Zoom, pan, expand the map, and explore zone, water, food, and location-name layers. |
| **Combat & survival** | Compare attacks, growth scenarios, direct damage, and bleed under different movement and wound-duration assumptions. |
| **Run history & replay** | Import/export runs and replay timestamped routes and events when the recording includes them. |
| **Compass guide** | Look up compass symbols and what they represent. |

## Download and get started

1. **[Download EvrimaTrailguide-Setup-1.11.1.exe](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.11.1/EvrimaTrailguide-Setup-1.11.1.exe).** Use the installer, **not** GitHub's automatic “Source code” ZIP or TAR.GZ files.
2. Run the installer. Choose whether to create a desktop shortcut and launch Trailguide afterward. No separate .NET download is required.
3. Start Evrima and open your **Status Report**. In Trailguide, use **Auto setup areas**, then check that the previews contain the correct information.
4. Start scanning. Open the Status Report to refresh your location; hover the growth meter for its percentage. Adjust the regions manually if your display or UI layout needs it.

> **Important:** Trailguide reads visible information about your own dinosaur. It does not reveal hidden players or guarantee Prime. Map visits and combat results are estimates, not server-confirmed outcomes; game updates can change their accuracy.

## Security & download transparency

### Microsoft review: detection removed

The v1.11.1 installer previously triggered `Program:Win32/Contebrew.A!ml`. Following the developer's submission on **August 30, 2026**, Microsoft's analyst response stated that the submitted files did not meet its criteria for malware or potentially unwanted applications and that the detection had been removed. The submitted installer shows **Final determination: Not malware**, with **No malware detected** for both cloud and client checks.

This resolves the reported false positive for the submitted installer. It is not a Microsoft endorsement, code-signing certificate, or guarantee covering future releases.

**If the previous detection still appears:** update Microsoft Defender's security intelligence through **Windows Security → Virus & threat protection → Protection updates → Check for updates**, then retry the same release download. Keep protection enabled. If a malware detection persists, stop and report the exact detection and definition version; do not add exclusions or choose “Allow” to bypass it. [Microsoft update guidance](https://learn.microsoft.com/en-us/defender-endpoint/microsoft-defender-security-center-antivirus)

### Unsigned installer and scan reports

The installer remains **unsigned**. Windows or Edge may still show **Unknown publisher** or **not commonly downloaded** warnings. These signing/reputation warnings are separate from the resolved Defender detection. [About SmartScreen reputation](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation)

- [Installer scan report on VirusTotal](https://www.virustotal.com/gui/file/0f806e579cb87e3bffda736e8098c75abc1aaf40f3b00fcdfe3bb12e9ebd0d23/detection)
- [Application scan report on VirusTotal](https://www.virustotal.com/gui/file/3a29e296a3e295dbaf4d7f446d224feb93bea739b1361d45f554f7a4baa3da72/detection)
- [Download the release checksum](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.11.1/SHA256SUMS.txt)

The reports are provided for transparency; their results can change over time. GitHub hosting, scan results, and matching checksums are not guarantees of safety. These links identify the v1.11.1 files, not future releases.

<details>
<summary>How to verify the installer checksum</summary>

In PowerShell, from the folder containing the downloaded installer, run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\EvrimaTrailguide-Setup-1.11.1.exe
```

Compare the result with `SHA256SUMS.txt`. A match verifies that the bytes match the published file; it is not a malware assessment.

</details>

## Feedback & support

Found a problem? **[Open an issue](https://github.com/roid-apps/Evrima-Trailguide/issues/new)** with your Trailguide version, what happened, steps to reproduce it, and a screenshot if useful. For security warnings, include the security product, exact detection name, and definition version. Avoid posting private information or run exports you do not want public.

- **Made by Roid**
- **Discord:** `r_o_i_d`
- **Email:** [b_greenspan@yahoo.com](mailto:b_greenspan@yahoo.com)
- **Alternate email:** [w2tvd9hf62b@gmail.com](mailto:w2tvd9hf62b@gmail.com)

---

Independent fan project. Not affiliated with or endorsed by The Isle's developers. Third-party assets belong to their respective owners; see the notices included with the application.

<!-- Release maintenance: update the installer URL, version-specific download badge, release notes, checksum, and scan links together when publishing a new version. Do not use /releases/latest for a pre-release-only repository. -->
