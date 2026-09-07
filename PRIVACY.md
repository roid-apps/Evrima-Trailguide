# Privacy statement — Evrima Trailguide

**Last updated: September 7, 2026 · Applies to: Evrima Trailguide v1.22.0 and the repository that hosts it**

Evrima Trailguide is a free desktop application for Windows, made by an independent developer (Roid). It is not a service, it has no accounts, and there is nothing to log into.

## The short version

**Evrima Trailguide collects nothing about you, sends nothing about you anywhere, and has no analytics, telemetry, advertising or tracking of any kind.** Everything it produces stays on your own computer.

## What the application reads

Only three things, all of them already on your machine:

1. **Pixels from screen regions you choose yourself.** Trailguide reads your own visible Status Report and growth meter using the Windows OCR engine built into your copy of Windows. The reading happens locally; no image ever leaves your computer.
2. **Steam's `appmanifest` file for The Isle**, to read the installed build number so it can tell you when its bundled reference data is older than your game.
3. **Its own settings file.**

## What the application will not do

By deliberate design, Trailguide does **not** open the game's process, read its memory, inject code, inspect network packets, detect other players, or automate keyboard or mouse input. This is a fixed boundary, not a current limitation.

## What is stored, and where

Two files, in `%LOCALAPPDATA%\Roid\Evrima Trailguide`:

| File | Contents |
| --- | --- |
| `settings.json` | Your preferences: scan regions, map layers, theme, interface scale, your own map waypoints. |
| `run-history.jsonl` | Your own runs: positions read from your Status Report, growth readings, and objective progress. |

These are ordinary files on your disk. They are never uploaded, and they are not read by anyone but you. You can export them, delete them, or inspect them in a text editor at any time. Uninstalling the application does not delete them, so that an upgrade does not lose your history; delete the folder yourself if you want them gone.

## Network activity

Trailguide makes **one** network request, and only if you switch it on.

The **update check** is off by default. When enabled, it makes a single unauthenticated `GET` to the public GitHub API asking which release is newest:

```text
https://api.github.com/repos/roid-apps/Evrima-Trailguide/releases/latest
```

It sends no run history, no settings, no identity and no telemetry — nothing but the `User-Agent` string GitHub requires of any caller. It never downloads or runs anything; it tells you a newer version exists and links you to the release page, where you download it yourself. GitHub will see the IP address that any web request reveals, exactly as it would if you opened the release page in a browser.

There is no other outbound connection. If you never enable the update check, Trailguide makes no network requests at all and works fully offline.

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
