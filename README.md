KyuPlay — Setup & System Requirements

KyuPlay is a desktop venue-management application built for managing courts, players, Open Play sessions, matchmaking, tournaments, schedules, statistics, Live View, and venue records from one place.

KyuPlay is available for Windows and Apple Silicon Macs.

Windows
System Requirements
Operating System: Windows 10 or Windows 11, 64-bit
Recommended RAM: 8 GB or more
Recommended Display: 1366×768 or higher
Storage: Keep at least 500 MB of free space for KyuPlay, application data, backups, and exports
Microsoft Edge WebView2 Runtime: Required
Internet connection recommended for downloading, updates, and any online services used by KyuPlay

KyuPlay uses Microsoft Edge WebView2 to render its desktop interface. WebView2 is normally already installed on modern Windows 10 and Windows 11 systems. Tauri's Windows installer can also install WebView2 when it is missing, depending on how the installer is packaged.

Installing on Windows
Download the official KyuPlay Windows installer.
Open the installer.
Allow Windows to complete the installation.
If WebView2 is required, allow its installation to finish.
Launch KyuPlay from the Start menu or desktop shortcut.
You do NOT need to install

Normal KyuPlay users do not need:

Node.js
npm
Rust
Cargo
Tauri CLI
Visual Studio
Microsoft C++ Build Tools

Those tools are only needed by developers who build KyuPlay from source. Microsoft C++ Build Tools, for example, are a Tauri development requirement, not something ordinary users need after KyuPlay has been packaged.

macOS
Important — Apple Silicon Only

KyuPlay for macOS only supports Apple Silicon / M-series Macs.

Supported processor family:

Apple M1 or newer Apple Silicon

Intel-based Macs are not supported by the KyuPlay macOS release.

You can check your Mac by opening:

Apple menu → About This Mac

Under Chip, it should show an Apple M-series processor.

System Requirements
Processor: Apple Silicon / M-series only
Operating System: macOS 12 Monterey or newer recommended for KyuPlay
Recommended RAM: 8 GB or more
Recommended Display: 1280×800 or higher
Storage: Keep at least 500 MB of free space for KyuPlay, venue data, backups, and exports
Internet connection recommended for downloading, updates, and any online services used by KyuPlay

Tauri supports Apple Silicon-specific builds, and its documentation provides macOS 12.0 as the minimum system version configuration for Apple Silicon-only distribution.

Installing on macOS
Download the official KyuPlay for macOS package.
Open the downloaded .dmg or installer package.
Move KyuPlay to Applications if instructed.
Open Applications → KyuPlay.
Complete any macOS security confirmation shown during the first launch.

Official macOS applications distributed outside the App Store are normally code-signed and notarized for distribution.

You do NOT need to install

Normal Mac users do not need:

Xcode
Xcode Command Line Tools
Node.js
npm
Rust
Cargo
Tauri CLI

Those are development tools used to build KyuPlay, not runtime requirements for the finished app.

Recommended Setup

For the smoothest KyuPlay experience:

Keep Windows or macOS updated.
Use 8 GB RAM or more where possible.
Keep sufficient free disk space for venue records, backups, and Excel exports.
On Windows, keep Microsoft Edge WebView2 updated.
Avoid manually modifying KyuPlay's application-data files.
Create regular KyuPlay backups, especially before replacing or transferring venue data.
Keep important .kyuplay backups in a separate safe location.
Use the built-in Excel statistics export when you need reporting data outside KyuPlay.

For venue use, a larger display such as 1920×1080 is recommended, especially when managing several courts or using KyuPlay's Live View.

Platform Compatibility
	Windows	macOS
KyuPlay supported	✅	✅
Architecture	64-bit Windows	Apple Silicon only
Intel Mac	—	❌ Not supported
M-series Mac	—	✅ Supported
WebView runtime	Microsoft Edge WebView2	Built into macOS
Node.js required	❌	❌
Rust required	❌	❌
Tauri required separately	❌	❌
Development tools required	❌	❌
Need Help?

If KyuPlay does not start:

Windows: make sure Microsoft Edge WebView2 Runtime is installed and Windows is up to date.

Mac: confirm that the computer uses an Apple M-series chip and is running a supported version of macOS.

For other installation, licensing, or KyuPlay issues, contact KyuPlay support with your operating-system version and a short description of what happened.
