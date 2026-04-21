# IDM Freezer & Activation Tool v3.0
A modern, user-friendly tool to manage Internet Download Manager activation, trial freezing, and settings.

> **Developed by Enock46** | Fully Portable | No Installation Required

## ⭐ Features

✅ **Fully Self-Contained** - Single portable executable (.exe), no Python or dependencies needed  
✅ **Freeze Trial** - Freeze IDM's 30-day trial period indefinitely (recommended method)  
✅ **Activate IDM** - Traditional activation with license key generation  
✅ **Reset Settings** - Clear all activation and trial data  
✅ **Check Status** - View current IDM version and registration status  
✅ **Backup & Restore** - Backup IDM settings with history tracking  
✅ **Auto-Update Check** - Check for latest tool versions  
✅ **Smart Settings** - Configure logging, backups, and update checks  
✅ **Comprehensive Logging** - Detailed log files for troubleshooting  
✅ **Clean UI** - Colorful, user-friendly command-line interface  

## 🚀 Quick Start

### Option 1: Using the Portable Executable (Recommended)
1. Download `IDM.exe` from the [Releases](https://github.com/Enock46/IDM-Freezer/releases)
2. Right-click → **Run as administrator** (required for operations)
3. Select your desired option from the menu

### Option 2: Running from Source Code
```powershell
# Install dependencies
pip install -r requirements.txt

# Run the application
python IDM.py
```

## 📋 Menu Options

| Option | Description |
|--------|-------------|
| **[1] Activate IDM** | Apply traditional activation method |
| **[2] Freeze Trial** | ⭐ **Recommended** - Freeze 30-day trial permanently |
| **[3] Reset** | Remove all activation and trial data |
| **[4] Check IDM Status** | View installed IDM version and status |
| **[5] Backup/Restore** | Manage IDM settings backups |
| **[6] Download IDM** | Open IDM download page |
| **[7] Visit GitHub** | Open this repository |
| **[8] Check Updates** | Check for latest tool version |
| **[9] Settings** | Configure tool options |
| **[0] Exit** | Close the application |

## 📦 System Requirements

- **OS**: Windows 7, 8, 8.1, 10, or 11
- **Privileges**: Administrator rights required
- **Internet**: Required for freeze/activation operations
- **IDM**: Internet Download Manager must be installed

## ⚙️ Configuration

Settings are stored in: `%APPDATA%\IDM_Manager\config.json`

- **Auto Backup**: Automatically backup IDM settings
- **Logging**: Enable/disable detailed logging
- **Update Check**: Check for tool updates on startup

## 📝 Logs

Log files are saved to: `%APPDATA%\IDM_Manager\logs\`

## 🔧 Building from Source

```powershell
# Install PyInstaller
pip install pyinstaller

# Build the executable
pyinstaller IDM.spec
```

The executable will be created in `dist/IDM.exe`

## 📄 License

This project is provided as-is for educational purposes.

## ⚠️ Important Notes

- **Administrator privileges are required** for all operations
- The tool modifies Windows registry entries for IDM
- All changes are reversible using the Reset option
- Backups are automatically created before any modifications

## 🤝 Contributing

Feel free to fork, modify, and improve this tool!

## 📞 Support

For issues, questions, or suggestions, please open an issue on [GitHub](https://github.com/Enock46/IDM-Freezer/issues)

---

**Made with ❤️ by Enock46** | Last Updated: 4/2026

## Methods

### Freeze Trial (Recommended)
IDM provides a 30-day trial period. This option locks the trial period for lifetime so you won't have to reset the trial again and your trial won't expire.
IDM updates can be installed directly without having to freeze it again.

### Activation
Registers IDM with full functionality. Your activation remains permanent and undetected.

### Reset IDM Activation / Trial
Resets the IDM activation or trial period. Use this if you encounter any issues or want to start fresh.

### Check IDM Status
Checks the current status of your IDM installation (activated, in trial, or expired).

### Backup/Restore IDM Settings
Allows you to backup your current IDM settings and restore them later if needed.

## Requirements
- Windows 7/8/8.1/10/11 (64-bit)
- Internet Download Manager installed

## Troubleshooting

### Downloads Not Working After Activation
1. Run **Option 3 (Reset)** first
2. Then run **Option 1 (Freeze Trial)** again

### IDM Not Detected
- Make sure IDM is installed
- Download IDM from: https://www.internetdownloadmanager.com/download.html

### If "Fake Serial" Detection Occurs
1. **RESET**: Run **Option 3 (Reset)** to clear all current activation data.
2. **REINSTALL**: Reinstall IDM (optional but recommended for a clean state).
3. **FREEZE**: Run **Option 1 (Freeze Trial)**. This is the **most robust** method for current IDM versions.

## Disclaimer
I would like to make it clear that I am not the original creator of this script. 
When I first uploaded this script to GitHub, the main author had not yet established an official GitHub repository. 
Consequently, users had to go to the official forum to download and use the script until the GitHub repository was eventually created.
My primary goal in setting up this repository was to simplify the process for users. Additionally, 
I made sure to acknowledge the original creators of the script to show respect for their work.

### 💖 Donations
If you feel like showing your love and/or appreciation for this simple project, then how about buying me a coffee or milk? ☕🥛

[<img src="https://github.com/zinzied/Website-login-checker/assets/10098794/24f9935f-3637-4607-8980-06124c2d0225">](https://www.buymeacoffee.com/Zied)
