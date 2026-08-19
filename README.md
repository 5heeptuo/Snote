# StickyNotes

## Download

[![Download Snote](https://img.shields.io/badge/Download-Snote%20v1.0.0-blue?style=for-the-badge&logo=github)](https://github.com/5heeptuo/Snote/releases/tag/v1.0.0)


| File | Platform | Size |
|---|---|---|
| `Snote-osx-arm64.dmg` | macOS (Apple Silicon / arm64) | ~54 MB |
| `StickyNotes-Setup-0.1.0-win-x64.exe` | Windows (x64) NSIS installer | ~50 MB |


## Install

- **macOS**: open the DMG, drag `Snote.app` into Applications.
- **Windows**: run the installer (UAC prompt; unsigned build — SmartScreen
  may ask to "Run anyway"), shortcuts are created on Desktop and Start Menu;
  uninstall via "Programs and Features".


## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl/Cmd + N` | Create a new note |
| `Ctrl/Cmd + F` | Focus search |
| `Ctrl/Cmd + ,` | Open Settings |
| `Ctrl/Cmd + W` | Close the current window |
| `Ctrl/Cmd + Q` | Quit Snotes |

> On macOS, use **Command (⌘)**. On Windows, use **Ctrl**.

## Notes

- Both builds are self-contained (no runtime install needed).
- macOS build is ad-hoc signed (not notarized): first launch requires
  right-click → Open, or System Settings → Privacy & Security → Open Anyway.
- Windows build is unsigned: SmartScreen shows "Unknown publisher".
