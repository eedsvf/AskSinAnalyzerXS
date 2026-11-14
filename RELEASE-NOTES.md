# AskSinAnalyzerXS 1.8.0 for macOS (Apple Silicon)

First Apple Silicon release of AskSinAnalyzerXS for macOS.

### Features
- Native Apple Silicon (ARM64) application
- Ready-to-use macOS application
- Serial communication using the native macOS serial port interface
- No separate Node.js or Electron installation required

### Installation
1. Download `asksin-analyzer-xs-1.8.0-mac.dmg`.
2. Open the DMG file.
3. Drag `AskSinAnalyzerXS.app` into the Applications folder.
4. Launch the application.

**macOS Security Notice:** This application is ad-hoc signed but not notarized by Apple. macOS Gatekeeper may prevent it from opening.

If macOS blocks the application, first try **System Settings → Privacy & Security → Open Anyway**.

If macOS reports that the application is damaged, and you trust the download from this GitHub release, you can remove its quarantine attribute using Terminal:

```bash
xattr -dr com.apple.quarantine /Applications/AskSinAnalyzerXS.app
```

This command affects only AskSinAnalyzerXS and does not disable Gatekeeper globally.

### Architecture
Apple Silicon (ARM64) – M1, M2, M3, M4 and newer.
