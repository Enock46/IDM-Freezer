# IDM Freezer & Activation Tool

A simple tool to manage Internet Download Manager - freeze trial, activate, and reset settings.

---

## Quick Start

### Option 1: Download Portable EXE

1. Download IDM.exe from [Releases](https://github.com/Enock46/IDM-Freezer/releases)
2. Right-click → Run as administrator
3. Choose your option

### Option 2: Run from Source

`powershell
pip install -r requirements.txt
python IDM.py
`

---

## Features

- Freeze IDM Trial (Recommended)
- Activate IDM
- Reset Settings
- Check IDM Status
- Backup/Restore Settings
- Auto-Update Check

---

## Menu Options

| # | Action |
|---|--------|
| 1 | Activate IDM |
| 2 | Freeze Trial |
| 3 | Reset |
| 4 | Check Status |
| 5 | Backup/Restore |
| 6 | Download IDM |
| 7 | GitHub |
| 8 | Check Updates |
| 9 | Settings |
| 0 | Exit |

---

## Requirements

- Windows 7, 8, 10, 11
- Administrator privileges
- Internet connection
- IDM installed

---

## Build from Source

`powershell
pip install pyinstaller
pyinstaller IDM.spec
`

Executable output: dist/IDM.exe

---

## License

MIT License

---

## Support

Open a GitHub issue for help.

Made by Enock46 | v0.1
