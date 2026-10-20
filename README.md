# SketchNotch Releases & Installation Guide 🎨

Welcome to the official download and release repository for **SketchNotch**—the Hand-Drawn Dynamic Island application for Windows 11 & 10 (with macOS migration path).

[![Official Showcase & Website](https://img.shields.io/badge/Official%20Site-sketchnotch.pages.dev-f38020?logo=cloudflare)](https://sketchnotch.pages.dev)
[![Release Version](https://img.shields.io/badge/Release-v1.0.0-24C8DB)](https://github.com/smokedogcodes/SketchNotch-Releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-11%20%2F%2010-0078D6?logo=windows)](https://github.com/smokedogcodes/SketchNotch-Releases)

---

## 📥 Downloads (Latest Release v1.0.0)

| Package | Format | Architecture | Description | Download |
| :--- | :---: | :---: | :--- | :---: |
| **SketchNotch Installer** | `.msi` / `.exe` | x64 / ARM64 | Full installer with auto-updates & start menu shortcuts | [Download Installer](https://github.com/smokedogcodes/SketchNotch-Releases/releases/download/v1.0.0/SketchNotch-Setup-1.0.0.exe) |
| **SketchNotch Portable** | `.zip` | x64 | Zero-installation standalone portable archive | [Download Portable .zip](https://github.com/smokedogcodes/SketchNotch-Releases/releases/download/v1.0.0/SketchNotch-v1.0.0-Windows-x64.zip) |

---

## ⚡ System Requirements
- **Operating System**: Windows 11 (22H2, 23H2, 24H2) or Windows 10 (21H2, 22H2) 64-bit.
- **Runtime**: Microsoft Edge WebView2 Evergreen Runtime (pre-installed on Windows 11 and modern Windows 10).
- **Memory**: ~120 MB RAM footprint.
- **Permissions**: Standard user permissions (no administrator elevation required).

---

## 🚀 Installation & Quick Start Guide

### Option 1: Standard Windows Installer (Recommended)
1. Download `SketchNotch-Setup-1.0.0.exe` above.
2. Double-click the installer and follow the prompt.
3. SketchNotch will launch automatically and anchor itself to the top-center camera notch of your display.

### Option 2: Portable Zero-Install Archive
1. Download `SketchNotch-v1.0.0-Windows-x64.zip`.
2. Extract the archive into any folder (e.g. `C:\Tools\SketchNotch` or `Desktop\SketchNotch`).
3. Double-click `sketchnotch.exe`.
4. **Note**: Make sure `WebView2Loader.dll` remains in the same folder as `sketchnotch.exe` (both are included together in the zip).

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

## 🔒 Verification & Checksums
- `SketchNotch-v1.0.0-Windows-x64.zip`: `SHA-256: 3085CDC1B1EF7B0596173935037980B3B81B4590CA4ABB687EC4EC83769B45C7`
- Bundle contents: `sketchnotch.exe` (Optimized Release 17.6MB) + `WebView2Loader.dll` (160KB) + `README.txt`

---

## 💬 Community & Support
- Web: [https://sketchnotch.pages.dev](https://sketchnotch.pages.dev)
- WhatsApp Support: [Contact via WhatsApp](https://wa.me/?text=Hi%20SketchNotch%20Support!)
- Source Code: Private Repository (`smokedogcodes/SketchNotch`)
