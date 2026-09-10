# KyuPlay — Setup & System Requirements

KyuPlay is a desktop venue-management application for managing **courts, players, Open Play sessions, matchmaking, tournaments, schedules, statistics, Live View, and venue records** in one place.

KyuPlay is available for:

- **Windows**
- **macOS on Apple Silicon / M-series Macs only**

---

# Windows

## System Requirements

- **Operating System:** Windows 10 or Windows 11, 64-bit
- **Recommended RAM:** 8 GB or more
- **Recommended Display:** 1366×768 or higher
- **Recommended Free Storage:** At least 500 MB
- **Required Runtime:** Microsoft Edge WebView2 Runtime
- **Internet Connection:** Recommended for downloads, updates, licensing, and online services used by KyuPlay

KyuPlay uses **Microsoft Edge WebView2** to display its desktop interface. On most modern Windows 10 and Windows 11 computers, WebView2 is already installed.

## Windows Installation

1. Download the official **KyuPlay Windows installer**.
2. Open the installer.
3. Follow the installation instructions.
4. If WebView2 is required, allow it to install.
5. Launch **KyuPlay** from the Start menu or desktop shortcut.

## You Do Not Need to Install

Normal KyuPlay users do **not** need:

- Node.js
- npm
- Rust
- Cargo
- Tauri CLI
- Visual Studio
- Microsoft C++ Build Tools

These are only needed by developers who build KyuPlay from source.

---

# macOS

## Important — Apple Silicon Only

**KyuPlay for macOS only supports Apple Silicon / M-series Macs.**

Supported examples include:

- Apple M1
- Apple M2
- Apple M3
- Apple M4
- Newer Apple Silicon Macs

**Intel-based Macs are not supported.**

To check your Mac:

**Apple menu → About This Mac → Chip**

Your Mac should show an **Apple M-series processor**.

## macOS System Requirements

- **Processor:** Apple Silicon / M-series only
- **Operating System:** macOS 12 Monterey or newer recommended
- **Recommended RAM:** 8 GB or more
- **Recommended Display:** 1280×800 or higher
- **Recommended Free Storage:** At least 500 MB
- **Internet Connection:** Recommended for downloads, updates, licensing, and online services used by KyuPlay

## macOS Installation

1. Download the official **KyuPlay macOS package**.
2. Open the downloaded `.dmg` or installer.
3. Move KyuPlay to **Applications** if instructed.
4. Open **Applications → KyuPlay**.
5. Complete any macOS security confirmation shown during first launch.

## You Do Not Need to Install

Normal Mac users do **not** need:

- Xcode
- Xcode Command Line Tools
- Node.js
- npm
- Rust
- Cargo
- Tauri CLI

These are development tools only.

---

# Recommended Setup

For the smoothest KyuPlay experience:

- Keep **Windows or macOS updated**.
- Use **8 GB RAM or more** when possible.
- Keep enough free storage for venue records, backups, and Excel exports.
- On Windows, keep **Microsoft Edge WebView2** updated.
- Avoid manually editing KyuPlay application-data files.
- Create regular KyuPlay backups.
- Keep important `.kyuplay` backup files in a separate safe location.
- Use KyuPlay's built-in Excel statistics export for reporting.
- For venue use, a **1920×1080 display** is recommended, especially when managing multiple courts or using **Live View**.

---

# Platform Compatibility

## Windows

- **Supported:** Yes
- **Architecture:** 64-bit Windows
- **Web Runtime:** Microsoft Edge WebView2
- **Node.js Required:** No
- **Rust Required:** No
- **Tauri Required Separately:** No
- **Development Tools Required:** No

## macOS

- **Supported:** Yes
- **Architecture:** Apple Silicon / M-series only
- **Intel Mac Support:** No
- **M-series Mac Support:** Yes
- **Web Runtime:** Built into macOS
- **Node.js Required:** No
- **Rust Required:** No
- **Tauri Required Separately:** No
- **Development Tools Required:** No

---

# Troubleshooting

## If KyuPlay Does Not Start on Windows

- Make sure Windows is up to date.
- Make sure **Microsoft Edge WebView2 Runtime** is installed.
- Restart the computer and try opening KyuPlay again.

## If KyuPlay Does Not Start on macOS

- Confirm that the Mac uses an **Apple M-series processor**.
- Confirm that macOS is up to date.
- Check any macOS security prompts shown during first launch.

---

# Need Help?

For installation, licensing, or KyuPlay-related issues, contact **KyuPlay Support** and include:

- your operating system,
- your Windows or macOS version,
- your device model if relevant,
- and a short description of the issue.
