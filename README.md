# 🇺🇸 WMC IPTV – US Version

![WMC IPTV US Version](combined.jpg)

## Modern IPTV for Windows Media Center

**WMC IPTV** brings modern IPTV and live-TV sources directly into the native Windows Media Center Live TV experience using virtual HDHomeRun tuners.

Created and developed by **Boxcar32**.

---

## 📥 Download WMC IPTV – US Version

The **WMC IPTV – US Version 1.1** installer is now available.

**157 Channels | Channels 100–256 | 8 Virtual Tuners | EPG123 | YouTube TV Sign-In**

### ⬇️ Download

[**Download WMC IPTV – US Version 1.1**](https://github.com/boxcar32/WMC-IPTV/releases/tag/v1.1.0)

The release includes **WMC IPTV Setup.exe**, the **v1.1 source package**, and release notes.

---

## 🆕 Version 1.1

Version 1.1 includes major installation, portability, and YouTube TV improvements.

- Portable CC4C Chrome extension support
- First-time YouTube TV sign-in support
- Persistent CC4C Chrome profile for YouTube TV authentication
- Improved fresh Windows 11 installation
- Automatic unique virtual HDHomeRun Device ID selection
- Device ID preservation during reinstall
- Improved HDHRProxyIPTV startup and configuration
- 8 virtual HDHomeRun tuners
- Improved EPG123 guide matching
- Modern `epg123.mxf` support
- Improved reinstall handling for running/locked components
- Universal IPTV bridge improvements
- System tray status/control support

Version 1.1 has been tested on fresh Windows installations, including first-time YouTube TV authentication and playback through Windows Media Center.

---

## 🇺🇸 US Version

The current US configuration has been designed and tested with a **157-channel Windows Media Center lineup**.

### Current Configuration

- 📺 **157 IPTV channels**
- 🔢 WMC channel range: **100–256**
- 📡 **8 virtual HDHomeRun tuners**
- 📖 **EPG123 guide integration**
- 🎮 Windows Media Center remote-control support
- ⏺ Native WMC Live TV and recording
- 📋 Channels appear directly in the WMC Guide

From Windows Media Center's perspective, IPTV channels are presented as television channels through the virtual tuner system.

---

## ✨ Features

WMC IPTV is built to preserve the native Windows Media Center television experience while adding support for modern IPTV sources.

- 📺 **Native WMC Live TV** — IPTV channels appear and operate like normal television channels inside Windows Media Center.
- 📋 **Native WMC Guide** — Browse channels and program listings using the familiar Windows Media Center Guide.
- ⏺ **WMC Recording** — Use Windows Media Center's normal recording and scheduled-recording features.
- 🎮 **Remote Control Support** — Change channels, browse the Guide, and control Live TV with a standard WMC remote.
- 📡 **8 Virtual Tuners** — Multiple virtual HDHomeRun tuners allow WMC to manage simultaneous television sessions.
- 📖 **EPG123 Integration** — Match IPTV channels with program-guide listings for the native WMC Guide.
- 🌐 **Multiple IPTV Sources** — Combine compatible YouTube TV, Frndly TV, Pluto TV, HTTP/HLS, local streams, webcams, and other M3U sources into one WMC lineup.
- 🔢 **Unified Channel Lineup** — The current US Version provides 157 channels numbered 100–256.
- 🔐 **YouTube TV Sign-In** — Version 1.1 provides first-time authentication using the persistent CC4C Chrome profile.
- 🧩 **Portable CC4C Extension** — The required puppeteer-stream Chrome extension is included with the installation instead of depending on a developer-machine path.
- 🖥️ **Windows 11 Tested** — Developed and tested with GaRyan2 Windows Media Center on Windows 11.
- 🛠️ **Automated Installer** — WMC IPTV Setup automates the components and configuration needed to build the IPTV-to-WMC bridge.

### One Interface. Multiple Sources.

Instead of switching between separate streaming applications, WMC IPTV brings compatible live-TV sources together inside the classic Windows Media Center interface:

**Live TV • Guide • Recording • Remote Control • Multiple Tuners**

---

## 🚀 Quick Start

### 1. Prerequisites

Before installing WMC IPTV, install and configure:

- **Windows Media Center**
- **EPG123**
- **SiliconDust HDHomeRun software/drivers**
- **Google Chrome**

Subscription services such as YouTube TV require your own valid account and subscription.

### 2. Download

Download **WMC IPTV – US Version 1.1** from the Releases section.

### 3. Install

Run:

**WMC IPTV Setup.exe**

Follow the installer prompts.

The installer configures the WMC IPTV components, virtual HDHomeRun tuner system, CC4C, and universal IPTV bridge.

### 4. Provide Your M3U

Select your compatible M3U playlist when requested.

The playlist contains the live-TV sources you are authorized to access.

WMC IPTV builds the channel mappings and presents the channels through the virtual tuner system.

### 5. YouTube TV Sign-In

If your lineup contains YouTube TV channels, sign in when the YouTube TV authentication window is presented.

Use your own Google/YouTube TV account.

CC4C uses a persistent Chrome profile so the authenticated session can remain available after reboot.

You normally do not need to sign in again every time Windows starts. A new sign-in may be required if Google or YouTube TV expires the session or otherwise requests authentication again.

### 6. Configure Windows Media Center with EPG123

**Use EPG123 Client Setup as the WMC television setup method.**

Do not perform a separate standalone WMC TV Signal Setup before this process.

EPG123 Client Setup configures Windows Media Center for the virtual HDHomeRun/ClearQAM tuner environment.

WMC IPTV provides:

**8 virtual HDHomeRun tuners**

Complete the EPG123 Client Setup process and the required Windows Media Center television configuration.

If a ClearQAM channel scan begins during setup, stop/cancel the scan at the beginning when the setup process allows it, then complete the remaining setup.

### 7. Install the IPTV Channels

After the WMC/EPG123 television environment is configured, allow WMC IPTV to add the IPTV channels to Windows Media Center.

The current US configuration uses:

**Channels 100–256**

for a total of:

**157 channels**

### 8. Configure the Program Guide

Complete the EPG123 guide configuration.

WMC IPTV matches compatible IPTV channels with EPG123 services and links those listings with the Windows Media Center Guide.

### 9. Watch TV

Open:

**Windows Media Center → TV → Live TV**

Your IPTV channels can now use the normal WMC television interface, including:

- Live TV
- Program Guide
- Channel changing
- Remote control
- Recording
- Scheduled recordings

For additional instructions, see the installation/setup guide included with the release.

---

## 🌐 Supported Sources

WMC IPTV can integrate user-supplied live-TV sources including:

- **YouTube TV**
- **Frndly TV**
- **Pluto TV**
- Local HDHomeRun/live streams
- HTTP/HLS streams
- Live webcams
- Other compatible M3U sources

> **WMC IPTV does not provide television subscriptions, accounts, credentials, or unauthorized streams. Users must supply and have permission to access their own sources.**

---

## 📺 YouTube TV

YouTube TV integration uses **CC4C** and a Chrome browser session.

Version 1.1 includes the portable puppeteer-stream extension required by CC4C.

On a new installation:

1. WMC IPTV starts the YouTube TV sign-in process.
2. Sign in using your own Google/YouTube TV account.
3. Confirm that YouTube TV can play in the CC4C Chrome profile.
4. Close the authentication browser when setup is complete.
5. WMC IPTV can then use that persistent authenticated profile for YouTube TV channels.

The authentication session is stored in the CC4C Chrome profile rather than inside WMC IPTV.

WMC IPTV does **not** store your Google username or password.

---

## ⚙️ How It Works

```text
IPTV / Live-TV Sources
         │
         ▼
   Universal IPTV Bridge
         │
         ├── YouTube TV → CC4C → Chrome
         ├── Frndly TV
         ├── Pluto TV
         ├── Local Streams
         ├── HTTP/HLS
         └── Webcams
         │
         ▼
    HDHRProxyIPTV
         │
         ▼
8 Virtual HDHomeRun Tuners
         │
         ▼
 Windows Media Center
         │
         ├── Live TV
         ├── WMC Guide
         ├── Recording
         └── Remote Control
