# Privacy statement — Evrima Trailguide

**Last updated: November 17, 2026 · Updated for: Evrima Trailguide v1.27.1 and the repository that hosts it**

Evrima Trailguide is a free desktop application for Windows, made by an independent developer (Roid). It is not a service, it has no accounts, and there is nothing to log into.

## The short version

**Trailguide has no analytics, telemetry or advertising SDK. It does not upload your profile, screenshots, routes or notes.** OCR and profile processing happen locally. You choose whether to export/share files or contact GitHub for an update check.

## What the application reads

Its inputs are local:

1. **Pixels from screen regions you choose yourself.** Trailguide reads your own visible Status Report and growth meter using the Windows OCR engine built into your copy of Windows. The reading happens locally; no image ever leaves your computer.
2. **Steam's `appmanifest` file for The Isle**, to read the installed build number so it can tell you when its bundled reference data is older than your game.
3. **Its own settings, history, bundled reference data and recovery files.**
4. **Files you explicitly choose to import, restore or compare**, such as waypoint/run exports, profile backups and reference JSON snapshots. Choosing an external website link opens your browser; that site has its own privacy policy.
5. **Windows foreground-window information and configured mini-map shortcuts.** These let the overlay respond during gameplay and lock mouse interaction appropriately. Keyboard handling is local; typed text is not recorded or uploaded.

## What the application will not do

By deliberate design, Trailguide does **not** read game memory, inject code, inspect network packets, detect other players, or automate keyboard or mouse input. This is a fixed boundary, not a current limitation.

## What is stored, and where

The profile is stored in `%LOCALAPPDATA%\Roid\Evrima Trailguide`:

| File | Contents |
| --- | --- |
| `settings.json` | Preferences, capture regions, current run, lineage, waypoints/routes, expedition plans and personal notes. |
| `run-history.jsonl` | Your own runs: positions read from your Status Report, growth readings, and objective progress. |
| `recovery/` and backup/restore files | Seven rolling daily profile snapshots, retained manual/pre-restore backups, raw original files for restore rollback, restore journals and retained failed restore requests. |

Isolated demo profiles use a separate temporary folder. Manually exported profiles, route cards, run files and waypoint files go where you choose; they can contain locations and private notes. Diagnostic files may be created locally. Review files before sharing them. Backups are ordinary local files, not encrypted cloud storage.

These are ordinary files on your disk, accessible to software or people with the necessary local permissions. Trailguide does not upload them. You can export them, delete them or inspect them. Uninstalling does not delete your profile; remove the profile and any separately exported copies yourself if you want them gone.

## Network activity

Update checking and automatic updates are optional and off by default. A manual check contacts GitHub once; launch checks and automatic updates run only when enabled. Automatic updating checks at launch and periodically while the app is open. Stable releases are the default, with a separate preview-release opt-in. The application asks the public GitHub API for releases from this project:

```text
https://api.github.com/repos/roid-apps/Evrima-Trailguide/releases/latest
```

Preview checks use the same repository's release list. With automatic updates enabled, Trailguide also downloads release checksums and a newer Windows installer from GitHub's release-asset servers. It verifies the installer before staging it locally and runs the update after you normally close Trailguide. It does not force-close the application or the game. Turning automatic updates off cancels pending automatic work.

These requests send no run history, settings, screenshots, identity or telemetry. GitHub and its download infrastructure receive the IP address and ordinary HTTP request information, including the required application `User-Agent`, as with other downloads. Downloaded update packages and installation logs are stored locally.

There is no hosted live-location service or profile sync. With update checking and automatic updates off, the application works offline; external links you choose to open are handled by your browser.

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
