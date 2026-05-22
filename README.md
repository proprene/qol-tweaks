# QoL-Tweaks (arcdps_qol_tweaks.dll)

An ArcDPS addon for Guild Wars 2 with cinematic/dialogue skip, confirmation overrides, clone hiding, and bank performance fixes.

## Features

- **Cinematic Skip** — Auto-skip in-game cinematics after a configurable timeout (default 150ms). Uses game tick hook + vtable dispatch matching fastload's approach.
- **Dialogue Skip** — Automatically skip NPC dialogue by signaling the event/progression system on the first dialogue line. Voice lines keep playing while the game advances immediately.
- **Skip Delete Confirm** — Bypass the item deletion confirmation dialog (direct delete).
- **Skip Drag-Drop Confirm** — Bypass the confirmation dialog when drag-dropping items to delete.
- **Skip Salvage Confirm** — Bypass the item salvage confirmation dialog (direct salvage).
- **Fix Bank Opening Lag** — Eliminating the stutter when opening the bank panel.
- **INI persistence** — Settings saved to `addons/arcdps/arcdps_qol_tweaks.ini`
- **Wine/macOS compatible** — Tested via CrossOver/Wine

## Installation

1. Download `arcdps_qol_tweaks.dll` from the [Releases](../../releases) page
2. Place it in your Guild Wars 2 installation directory (same folder as `Gw2-64.exe`)
3. Requires [ArcDPS](https://www.deltaconnected.com/arcdps/) to be installed
4. Launch GW2 — the addon will be loaded by ArcDPS automatically

## Usage

Open the settings window via the ArcDPS options panel ("QoL-Tweaks" entry). The in-game status panel shows green "Status: OK" when all hooks are active, or per-hook error messages if any scan failed.

Settings are saved automatically when changed.

## Downloads
![GitHub Downloads](https://img.shields.io/github/downloads/proprene/qol-tweaks/total)
