# SketchNotch Releases & Installation Guide 🎨

Welcome to the official download and release repository for **SketchNotch**—the Hand-Drawn Dynamic Island application for Windows 11 & 10 (with macOS migration path).

[![Official Showcase & Website](https://img.shields.io/badge/Official%20Site-sketchnotch.pages.dev-f38020?logo=cloudflare)](https://sketchnotch.pages.dev)
[![Release Version](https://img.shields.io/badge/Release-v1.0.0-24C8DB)](https://github.com/smokedogcodes/SketchNotch-Releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-11%20%2F%2010-0078D6?logo=windows)](https://github.com/smokedogcodes/SketchNotch-Releases)

---

## 📥 Downloads (Latest Release v1.0.0)

| Package | Format | Size | Description | Download |
| :--- | :---: | :---: | :--- | :---: |
| **SketchNotch Standalone** *(Recommended)* | `.exe` | **5.7 MB** | **Single standalone `.exe` file**. Zero installation, no extra DLLs needed, double-click & run anywhere! | [**Download SketchNotch.exe**](https://github.com/smokedogcodes/SketchNotch-Releases/releases/download/v1.0.0/SketchNotch.exe) |
| **SketchNotch Portable Archive** | `.zip` | **5.3 MB** | Complete folder archive with core executable, `WebView2Loader.dll`, and quick-start docs | [Download Portable .zip](https://github.com/smokedogcodes/SketchNotch-Releases/releases/download/v1.0.0/SketchNotch-v1.0.0-Windows-x64.zip) |

---

## ⚡ System Requirements
- **Operating System**: Windows 11 (22H2, 23H2, 24H2) or Windows 10 (21H2, 22H2) 64-bit.
- **Runtime**: Microsoft Edge WebView2 Evergreen Runtime (pre-installed on Windows 11 and modern Windows 10).
- **Memory**: ~50 MB RAM footprint.
- **Permissions**: Standard user permissions (no administrator elevation required).

---

## 🚀 Installation & Quick Start Guide

### Option 1: Standalone Single Executable (Recommended)
1. Download **`SketchNotch.exe`** (5.7 MB).
2. Double-click to launch directly from Downloads, Desktop, or a USB drive.
3. No installation, unzipping, or external DLL files required!

### Option 2: Portable Folder Archive
1. Download `SketchNotch-v1.0.0-Windows-x64.zip`.
2. Extract the archive into any folder (e.g. `C:\Tools\SketchNotch`).
3. Double-click `sketchnotch.exe`. Both `sketchnotch.exe` and `WebView2Loader.dll` are included together.

---

## 🔑 Activating Your License

When you first open SketchNotch, it runs in **Trial / Activation Mode**.

### 1. Free 7-Day Trial
- You can activate an instant 7-day trial using the trial key generated on [sketchnotch.pages.dev](https://sketchnotch.pages.dev) or use default demo key:
  ```
  SKNOTCH-TR-DEMO-0007
  ```
- Or generate a fresh trial key instantly from the website.

### 2. Buying a Permanent Lifetime License via WhatsApp
1. Copy your unique **Hardware ID (HWID)** shown inside the SketchNotch activation prompt.
2. Click **"Buy via WhatsApp"** or visit [sketchnotch.pages.dev/#pricing](https://sketchnotch.pages.dev/#pricing).
3. Choose your plan:
   - **Personal Lifetime**: $14.99 (1 PC, lifetime updates)
   - **Pro Multi-PC**: $24.99 (3 PCs, priority features)
   - **Studio / Team**: $69.99 (10 PCs, centralized keys)
4. Receive your official activation key (`SKNOTCH-PD-XXXX-XXXX`) directly in WhatsApp chat.
5. Paste into SketchNotch and click **"Unlock & Activate"**.

---

## 🕹️ Desktop Shortcuts & Hotkeys
- `Win + Space`: Expand or collapse the Dynamic Island drawer.
- `Ctrl + Alt + M`: Global Hardware Microphone Kill Switch.
- `Ctrl + Shift + S`: Take Region Screenshot & Auto-Stage to File Shelf.
- `Win + Alt + C`: Toggle Caffeine Mode (Keep screen awake).
- `Win + Alt + S`: Open Settings Studio.

---

## 📋 Release Notes v1.0.0
- **Native Win32 Frameless Overlay**: Transparent, always-on-top window using `WS_EX_TOPMOST`, `WS_EX_TOOLWINDOW`, and `WS_EX_LAYERED`.
- **4 Adaptive Presentation Modes**: Idle 40px Pill, Compact Notch, Minimal Attached Pill + Bubbles, and Expanded Interactive Drawer.
- **All 16 Native Modules**:
  1. Media Controller (GSMTC)
  2. Audio Loopback FFT Spectrum Visualizer (WASAPI)
  3. Calls & Communication (Zoom, Teams, Discord, FaceTime)
  4. Global Mic Kill Switch
  5. File Shelf & Drop Staging
  6. On-Device File Format Converter (PNG, JPEG, PDF)
  7. Archive Zipping Engine
  8. Pomodoro Focus Timer with 7-Day Streak
  9. Region Screenshot Snipping Tool
  10. Voice Memo & Screen Recorder
  11. Laptop Charge Alert (80% Battery Health Guard)
  12. Bluetooth Peripherals Battery Monitor (AirPods / Mice / Keyboards)
  13. USB Drive Quick Mount & Safe Eject
  14. Webcam & Mic Privacy Guard Alerts
  15. Volume & Brightness HUD OSD Replacement
  16. Live Calendar Meetings Countdown & Clipboard OCR Search
- **Hand-Drawn Design System**: Warm Paper (`#fdfbf7`), Soft Pencil (`#2d2d2d`), Correction Marker (`#E34234`), Chartreuse (`#D4FF3F`), Kalam & Patrick Hand typography, wobbly irregular borders and hard offset shadows.

---

## 🔄 Automatic Update Push & "What's New" Modal

SketchNotch includes a built-in auto-update notification engine and release changelog viewer:
1. **GitHub Releases Tracking**: On startup (and periodically in background), SketchNotch queries the latest release from `smokedogcodes/SketchNotch-Releases/releases/latest`.
2. **Instant Dynamic Island Indicator**: When a new version is detected, a hand-drawn chartreuse update pill (`★ Update v1.0.1 Ready`) animates directly inside the Dynamic Island notch.
3. **First-Run "What's New" Modal**: Whenever a new update is launched for the first time, SketchNotch displays an authentic paper-styled "What's New" modal outlining new modules, bug fixes, and feature improvements.
4. **Settings Studio Updates Tab**: A dedicated tab in Settings Studio (`Updates & What's New`) allows users to check for updates manually, view the latest release notes, and download the new `.exe` with a single click.

---

## 🔒 Verification & Checksums
- `SketchNotch.exe`: `SHA-256: A1BC7935984BF53C8217177FBFD5CDF9C7C79AAAFC7708CC88086032B66B2C85` (5.8 MB)
- `SketchNotch-v1.0.0-Windows-x64.zip`: `SHA-256: A4823259EA4868371C5BB10D17F94E17092043B0422F8F02BF7D58C69F8FC195` (5.5 MB)

---

## 💬 Community & Support
- Web: [https://sketchnotch.pages.dev](https://sketchnotch.pages.dev)
- WhatsApp Support: [Contact via WhatsApp](https://wa.me/?text=Hi%20SketchNotch%20Support!)
- Source Code: Private Repository (`smokedogcodes/SketchNotch`)
