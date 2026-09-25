# Privacy statement — Evrima Trailguide

**Last updated: September 25, 2026 · Updated for: Evrima Trailguide v1.25.0-dev.5 and the repository that hosts it**

Evrima Trailguide is a free desktop application for Windows, made by an independent developer (Roid). It is not a service, it has no accounts, and there is nothing to log into.

## The short version

**Trailguide has no analytics, telemetry or advertising SDK. It does not upload your profile, screenshots, routes or notes.** OCR and profile processing happen locally. You choose whether to export/share files or contact GitHub for an update check.

## What the application reads

Its inputs are local:

1. **Pixels from screen regions you choose yourself.** Trailguide reads your own visible Status Report and growth meter using the Windows OCR engine built into your copy of Windows. The reading happens locally; no image ever leaves your computer.
2. **Steam's `appmanifest` file for The Isle**, to read the installed build number so it can tell you when its bundled reference data is older than your game.
3. **Its own settings, history, bundled reference data and recovery files.**
4. **Files you explicitly choose to import, restore or compare**, such as waypoint/run exports, profile backups and reference JSON snapshots. Choosing an external website link opens your browser; that site has its own privacy policy.

## What the application will not do

By deliberate design, Trailguide does **not** open the game's process, read its memory, inject code, inspect network packets, detect other players, or automate keyboard or mouse input. This is a fixed boundary, not a current limitation.

## What is stored, and where

The profile is stored in `%LOCALAPPDATA%\Roid\Evrima Trailguide`:

| File | Contents |
| --- | --- |
| `settings.json` | Preferences, capture regions, current run, lineage, waypoints/routes, expedition plans and personal notes. |
| `run-history.jsonl` | Your own runs: positions read from your Status Report, growth readings, and objective progress. |
| `recovery/` and backup/restore files | Seven rolling daily profile snapshots, retained manual/pre-restore backups and pending restore data. |

Isolated demo profiles use a separate temporary folder. Manually exported profiles, route cards, run files and waypoint files go where you choose; they can contain locations and private notes. Diagnostic files may be created locally. Review files before sharing them. Backups are ordinary local files, not encrypted cloud storage.

These are ordinary files on your disk, accessible to software or people with the necessary local permissions. Trailguide does not upload them. You can export them, delete them or inspect them. Uninstalling does not delete your profile; remove the profile and any separately exported copies yourself if you want them gone.

## Network activity

The built-in network feature is the optional update check, triggered manually or on launch if enabled.

The **update check** is off by default. When enabled, it makes a single unauthenticated `GET` to the public GitHub API asking which release is newest:

```text
https://api.github.com/repos/roid-apps/Evrima-Trailguide/releases/latest
```

It sends no run history, no settings, no identity and no telemetry — nothing but the `User-Agent` string GitHub requires of any caller. It never downloads or runs anything; it tells you a newer version exists and links you to the release page, where you download it yourself. GitHub will see the IP address that any web request reveals, exactly as it would if you opened the release page in a browser.

The update check follows stable GitHub releases, not development prereleases. There is no hosted live-location service or profile sync. With update checking off, the application works offline; external links you choose to open are handled by your browser.

## The repository and downloads

This project is hosted on GitHub. Downloading the installer, opening an issue or viewing a page is handled entirely by GitHub under [their privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement); the developer receives no personal information from it beyond the public download counts and whatever you choose to write in an issue you open yourself.

If you email the address below, the developer will have your email address and whatever you send. Please do not include run exports or screenshots containing information you would rather not share.

## Children

Trailguide is a tool for a video game and is not directed at children. It collects no information from anyone, of any age.

## Changes

If this statement changes, the date at the top changes with it and the previous version stays in this repository's history.

## Contact

- **Made by Roid**
- **Discord:** `r_o_i_d`
- **Email:** [b_greenspan@yahoo.com](mailto:b_greenspan@yahoo.com)

---

Independent fan project. Not affiliated with or endorsed by The Isle's developers.
