# StickyNotes v0.1.0 — Release Assets

Upload these files to the GitHub release:

| File | Platform | Size |
|---|---|---|
| `Snote-osx-arm64.dmg` | macOS (Apple Silicon / arm64) | ~54 MB |
| `StickyNotes-Setup-0.1.0-win-x64.exe` | Windows (x64) NSIS installer | ~50 MB |
| `SHA256SUMS` | checksums for the two installers | — |

## Install

- **macOS**: open the DMG, drag `Snote.app` into Applications.
- **Windows**: run the installer (UAC prompt; unsigned build — SmartScreen
  may ask to "Run anyway"), shortcuts are created on Desktop and Start Menu;
  uninstall via "Programs and Features".

## Notes

- Both builds are self-contained (no runtime install needed).
- macOS build is ad-hoc signed (not notarized): first launch requires
  right-click → Open, or System Settings → Privacy & Security → Open Anyway.
- Windows build is unsigned: SmartScreen shows "Unknown publisher".
