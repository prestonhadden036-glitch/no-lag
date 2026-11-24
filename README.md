# NoLag

Measure first, then tune. NoLag finds where your lag comes from and fixes what can be fixed on Windows 10/11:
Ping boost through NoLag relay nodes with Smart Route, Loss Shield (and Starlink Shield for Starlink users), a network
analyzer, game server detection, and PC/FPS tweaks that can each be undone.

## Download

**[⬇ Download NoLag for Windows](https://github.com/prestonhadden036-glitch/no-lag/releases/latest/download/NoLag-Setup.exe)** (always the newest version)

| File | What it is |
|---|---|
| `NoLag-Setup.exe` | Installer (recommended): Start menu entry, optional desktop icon, uninstaller |
| `NoLag-<version>-portable.zip` | No install: unzip anywhere and run `NoLag.exe` |
| `SHA256SUMS.txt` | Checksums of the files above |

All versions: [Releases](https://github.com/prestonhadden036-glitch/no-lag/releases)

## "Windows protected your PC"

NoLag isn't code-signed yet, so Windows SmartScreen shows a blue warning for a new download. Click **More info → Run
anyway**. You can check the file against `SHA256SUMS.txt` (PowerShell: `Get-FileHash .\NoLag-Setup.exe`).

## Requirements

- Windows 10 or 11, 64-bit
- Administrator rights for tweaks and Ping boost (NoLag asks when it needs them; diagnostics work without)

## Plans

NoLag works for free. Standard and Exclusive unlock more: see the [website](https://statuesque-chebakia-14fd20.netlify.app/). Paste your license key in
**Account & plans** inside the app.

## Uninstall

Settings → Apps → NoLag → Uninstall. The uninstaller offers to undo every Windows tweak NoLag applied, from the exact
backups it made. Your settings stay in `%APPDATA%\NoLag` unless you delete that folder.
