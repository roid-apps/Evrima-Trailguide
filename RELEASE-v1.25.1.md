# Evrima Trailguide 1.25.1 — Your Map, Your Way

**The Mini-map & Tracking Update is now stable.** Build a HUD that fits the way you play, follow your next stop, and keep the full Trailguide workspace one click away.

[Download the Windows installer](https://github.com/roid-apps/Evrima-Trailguide/releases/download/v1.25.1/EvrimaTrailguide-Setup-1.25.1.exe) · [Full walkthrough](https://youtu.be/U__SdPqlwzQ)

## A mini-map that feels like yours

| Compact navigation | Map-only HUD |
| --- | --- |
| ![Actual compact mini-map](https://raw.githubusercontent.com/roid-apps/Evrima-Trailguide/main/images/v1.25.1/mini-map-compact.png) | ![Actual transparent-chrome map-only mode](https://raw.githubusercontent.com/roid-apps/Evrima-Trailguide/main/images/v1.25.1/mini-map-only.png) |

- **Customize without losing the map.** A separate live-preview editor replaces the settings panel that crowded out the map on short screens.
- **Tune the essentials.** Independent map-image opacity, player-marker size/color, trail color/width/point limit, place-label size/density, zone-fill strength and individual migration/patrol/sanctuary layers.
- **Keep critical information legible.** Opacity affects the map image—not your position, target, controls or warnings. Map-only removes the frame and controls; the image itself has a 10% visibility floor.
- **Switch setups quickly.** Navigation, Exploration and transparent game-HUD presets; save, load, update or delete up to eight personal layouts.
- **Safer game input.** Map-only remains click-through and non-activating. Optional auto-lock switches interaction off when the game regains foreground. Recovery hotkeys and the main Show/Hide mini-map button remain available.
- **Follow your itinerary.** Previous/next saved-route controls, visible progress and resume after reopening. Manual target changes end the active itinerary rather than leaving conflicting route controls.
- **Less clutter.** Small-window label limits and no empty destination banner covering the map.

## Tracking fixes that matter

- Sustained plausible movement can now confirm a genuine relocation after approximately 45 seconds; you no longer have to remain within a tiny fixed radius.
- Widely separated outliers cannot confirm each other. Parse failures, pauses and context changes interrupt pending evidence.
- Suspicious missing-digit readings near world origin stay held. Confirmed relocations start separate trail segments, including after saving/reopening.
- Scanner stop/restart no longer lets an older loop change the replacement loop's running state. Cancelled or context-invalid OCR results cannot apply as current evidence.
- Capture timestamps reflect when the image was captured, not when OCR finished. Future timestamps show a clock warning; old/future growth samples no longer create a supposedly current growth estimate.
- Closing no longer blocks the UI waiting for its own scanner continuation.

## A cleaner everyday workspace

![Actual visual combat comparison](https://raw.githubusercontent.com/roid-apps/Evrima-Trailguide/main/images/v1.25.1/combat-visual.png)

- Short/scaled windows can scroll to their controls and map. The header wraps, with version/run metadata tucked away.
- Growth Viewer inputs now come before the artwork.
- Mutation selection has a clear prompt and the empty ledger explains how to start. Hover descriptions remain available before selection.
- Empty run replay asks you to select/import a run—not open a live Status Report.
- Player-facing reference copy replaces technical extraction language in the main workflow; genuine estimate limitations remain available.
- The update checker correctly recognizes stable versions after previews with the same numeric base. This release uses **1.25.1** so the existing dev.5 checker can find it too.

Upgrading from stable 1.23.0? This also includes the preview series' visual dinosaur comparison, independent combat-side mutation scenarios, Expedition planner, named waypoint routes, measured recovery/supply scenarios, field and family journals, profile recovery tools, mutation hover descriptions and aligned compass guide.

## Install and recover

1. Export a complete profile backup and close Trailguide.
2. Run **EvrimaTrailguide-Setup-1.25.1.exe**. The ZIP is this installer plus notices/checksum, not a portable app. GitHub's automatic source archives are not the application.
3. Open **Setup check**, then verify your scan areas against Evrima's visible Status Report.
4. Open the mini-map and choose its **gear button / Overlay options**.

Default shortcuts: **Ctrl+Shift+M** show/hide · **Ctrl+Shift+I** restore interactive controls · **Ctrl+Shift+H** map-only. Returning to the game may re-lock interaction when auto-lock is enabled. Personal layouts do not silently replace registered recovery shortcuts.

Windows x64, Windows 10 build 19041+; .NET runtime included. English Windows OCR support may need enabling separately. Normal upgrades reuse your per-user profile. Back up before downgrading: older versions cannot preserve all newer settings.

## Validation and honest limits

**824 unit tests passed, zero failed/skipped**, plus 92 native/functional mini-map checks and the main-layout, combat, reference-UI, Expedition, feature, readiness and new regression-probe suites. The attached dated validation report identifies the exact package, installation checks and limits; checksums are attached separately.

This is an independent **self-location companion**, not hidden-player tracking. Coordinates must be visible for OCR updates. Navigation is north-up/map-relative, not dinosaur-facing heading or terrain-safe pathfinding. Combat and Prime outputs remain reference estimates—not guaranteed outcomes.

Native overlay/recovery checks are automated. Live-game input across every display/fullscreen configuration, physical mixed-DPI changes, clean-machine installation and extended-session performance qualification were **not** completed for this build. Borderless/windowed play is intended; universal compatibility is not promised.

The installer is unsigned. SmartScreen reputation warnings are not themselves malware detections; keep protection enabled. No Microsoft endorsement or new analyst certification is claimed.

Screenshots are actual app renders using isolated demo/test profiles and sample coordinates—not live gameplay. Your saved runs and private research are not published.

Made by **Roid** · [Report an issue](https://github.com/roid-apps/Evrima-Trailguide/issues) · Discord **r_o_i_d**
