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

# 🚀 Quick Start

## 1. Prerequisites

Before installing WMC IPTV, install and configure:

- **Windows Media Center**
- **EPG123**
- **SiliconDust HDHomeRun software/drivers**
- **Google Chrome**

Subscription services such as YouTube TV require your own valid account and subscription.

---

## 2. Download

Download **WMC IPTV – US Version 1.1** from the Releases section.

[**Download WMC IPTV – US Version 1.1**](https://github.com/boxcar32/WMC-IPTV/releases/tag/v1.1.0)

---

## 3. Install WMC IPTV

Run:

**WMC IPTV Setup.exe**

Follow the installer prompts.

WMC IPTV installs and configures the components required for the IPTV-to-Windows Media Center system, including:

- HDHRProxyIPTV
- Virtual HDHomeRun tuners
- Universal IPTV bridge
- CC4C components
- WMC channel utilities
- EPG123 guide-matching components
- WMC IPTV system tray components

During the installation process, WMC IPTV will guide you through the remaining setup.

---

## 4. Configure Windows Media Center with EPG123

After installing WMC IPTV, run **EPG123 Client Setup** when instructed.

**Use EPG123 Client Setup as the Windows Media Center television setup method.**

Do **not** perform a separate standalone Windows Media Center TV Signal Setup before this process.

EPG123 Client Setup configures Windows Media Center for the virtual HDHomeRun/ClearQAM tuner environment.

WMC IPTV provides:

**8 virtual HDHomeRun tuners**

During the EPG123/WMC television setup:

- Select **Cable**
- Use the **ClearQAM** tuner configuration
- Allow Windows Media Center to detect the virtual HDHomeRun tuners
- When the channel scan begins, stop/cancel the scan at the beginning when the setup process allows it
- Complete the remaining Windows Media Center setup
- Complete EPG123 Client Setup

After EPG123 Client Setup is complete, return to the WMC IPTV installation window and continue.

---

## 5. YouTube TV Sign-In

If you use **YouTube TV**, WMC IPTV provides a first-time sign-in process for CC4C.

A Chrome window will be available for the CC4C YouTube TV profile.

Sign in using your own Google/YouTube TV account.

Verify that YouTube TV opens correctly using that profile.

CC4C uses a persistent Chrome profile so the authenticated session can remain available after Windows restarts.

You normally do **not** need to sign in again every time Windows starts.

A new sign-in may be required if Google or YouTube TV:

- Expires the session
- Signs the account out
- Requires account verification
- Requires authentication again

The authentication session is maintained by the Chrome profile.

**WMC IPTV does not store your Google username or password.**

---

## 6. Provide Your M3U

Select your compatible M3U playlist when requested.

The playlist contains the live-TV sources you are authorized to access.

WMC IPTV processes the playlist and builds the channel/source configuration used by the IPTV bridge and virtual tuner system.

The playlist can contain supported sources such as:

- YouTube TV
- Frndly TV
- Pluto TV
- Local HDHomeRun streams
- HTTP/HLS streams
- Webcams
- Other compatible live-TV sources

---

## 7. Install the IPTV Channels

After the M3U is processed, WMC IPTV adds the IPTV channels to Windows Media Center.

The current tested US configuration uses:

**Channels 100–256**

for a total of:

**157 channels**

The channels are presented to Windows Media Center through the virtual HDHomeRun/ClearQAM tuner system.

---

## 8. Run Stage 2 – Configure the Program Guide

After the IPTV channels have been installed in Windows Media Center, run:

**WMC IPTV – Stage 2 Guide Setup**

Stage 2 automatically matches the installed WMC IPTV channels with the corresponding EPG123 guide services and links them to the Windows Media Center Guide.

Version 1.1 supports the modern:

`epg123.mxf`

guide data format.

Stage 2 will:

- Read the installed WMC IPTV channels
- Read the EPG123 guide services
- Match compatible channels with their EPG123 listings
- Link the matched channels to the Windows Media Center Guide
- Safely leave channels unchanged when no suitable match is found

When Stage 2 reports:

**STAGE 2 COMPLETE**

the automatic WMC guide mapping has finished.

Open Windows Media Center and check the Guide. Your matched IPTV channels should now display their EPG123 program listings.

---

## 9. Watch TV

Open:

**Windows Media Center → TV → Live TV**

Your IPTV channels can now use the normal Windows Media Center television interface, including:

- Live TV
- Program Guide
- Channel changing
- MCE remote control
- Recording
- Scheduled recordings

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

YouTube TV integration uses **CC4C** and a persistent Chrome browser profile.

Version 1.1 includes the portable puppeteer-stream extension required by CC4C.

This fixes the previous dependency on a developer-machine extension path and allows CC4C to operate on newly installed computers.

### First-Time Setup

On a new installation:

1. Complete the WMC/EPG123 television setup.
2. Open the CC4C YouTube TV sign-in session when instructed.
3. Sign in using your own Google/YouTube TV account.
4. Verify that YouTube TV can play using the CC4C Chrome profile.
5. Complete the sign-in process.
6. Continue WMC IPTV setup and select your M3U.

After authentication, CC4C can use the persistent Chrome profile for YouTube TV playback.

The authentication session is stored in the Chrome profile rather than inside WMC IPTV.

**WMC IPTV does not store your Google username or password.**

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
```

---

## 📖 EPG123 Guide Integration

EPG123 provides program-guide data for Windows Media Center.

WMC IPTV can match IPTV channels against EPG123 services and link compatible channels with their guide listings.

Version 1.1 supports the modern:

`epg123.mxf`

format as well as the WMC IPTV guide-matching workflow.

### WMC Setup

EPG123 Client Setup is also used to establish the Windows Media Center television environment required by WMC IPTV.

This is the supported setup path for the WMC IPTV ClearQAM virtual tuners.

A separate standalone WMC TV Signal Setup should not be performed before the EPG123 Client Setup workflow.

---

## 🔢 Channel Numbering

The current US Version uses a sequential Windows Media Center channel lineup beginning at:

**100**

and ending at:

**256**

for the tested 157-channel configuration.

The M3U playlist identifies the channels and source types.

WMC IPTV then builds the corresponding virtual tuner/ClearQAM mappings.

---

## 📡 Virtual Tuners

WMC IPTV currently provides:

**8 virtual HDHomeRun tuners**

through HDHRProxyIPTV.

This allows Windows Media Center to treat the IPTV system similarly to a television tuner device.

### Device IDs

Each WMC IPTV computer should use a unique valid virtual HDHomeRun Device ID when multiple HDHomeRun or WMC IPTV systems are present on the same network.

Version 1.1 improves automatic Device ID selection.

The selected Device ID is also preserved during a WMC IPTV reinstall.

This helps prevent Windows Media Center on one computer from accidentally connecting to another WMC IPTV proxy on the network.

---

## 🔄 Automatic Startup

WMC IPTV automatically starts its required background components when Windows starts.

These include:

- CC4C when required
- Universal IPTV bridge
- Chrome window management
- WMC IPTV system-tray status component

The WMC IPTV system tray provides status and control for the IPTV environment.

---

## 🖥️ Windows 11

WMC IPTV Version 1.1 has been tested on fresh Windows 11 installations.

Testing has included:

- Fresh WMC IPTV installation
- Virtual tuner detection
- EPG123 Client Setup
- Automatic Device ID selection
- CC4C portable extension loading
- First-time YouTube TV authentication
- Persistent YouTube TV login after reboot
- YouTube TV playback through Windows Media Center
- Reinstallation over an existing WMC IPTV installation

---

## 🛡️ Windows Smart App Control

The WMC IPTV installer may be blocked by **Windows 11 Smart App Control** because the current installer is not digitally code-signed.

A production distribution would normally use a trusted code-signing certificate.

Users should make their own security decisions before running unsigned software.

---

## 🔧 Reinstalling WMC IPTV

Version 1.1 includes improvements for reinstalling WMC IPTV over an existing installation.

The installer handles running WMC IPTV components before replacing files.

The existing virtual HDHomeRun Device ID can also be preserved during reinstall.

This prevents a normal reinstall from unnecessarily changing the virtual tuner identity already configured on that computer.

---

## 🎮 Windows Media Center Remote Control

Once the IPTV channels are installed as Windows Media Center television channels, normal WMC/MCE remote controls can be used.

Typical controls include:

- Channel Up / Down
- Number buttons
- Guide
- Arrow keys
- OK
- Back
- Play / Pause
- Stop
- Record
- Skip / Replay
- Volume
- Mute
- Green Button

No special IPTV-specific remote-control software is required for normal Windows Media Center navigation.

---

## ⚠️ Important

WMC IPTV is intended for use with television services and streams that the user is legally authorized to access.

WMC IPTV does not:

- Provide a YouTube TV subscription
- Provide a Frndly TV subscription
- Provide paid-TV credentials
- Supply unauthorized television streams
- Circumvent subscription requirements

You are responsible for the services, playlists, streams, and accounts you configure.

---

## 📦 Current Version

**WMC IPTV – US Version 1.1.0**

Release tag:

**v1.1.0**

### Download

[**WMC IPTV v1.1.0 Release**](https://github.com/boxcar32/WMC-IPTV/releases/tag/v1.1.0)

Release assets include:

- **WMC IPTV Setup.exe**
- **WMC-IPTV-Source-v1.1.zip**

---

## 🙏 Credits & Acknowledgements

WMC IPTV builds on ideas, tools, and work from the Windows Media Center and home-theater community.

Special thanks and acknowledgement to:

- **GaRyan2** — creator of EPG123 and the WMC utilities used for Windows Media Center guide integration. WMC IPTV uses GaRyan2 WMC utility libraries for portions of its WMC/EPG integration.

- **Kévin Chalet** — for his work and documentation involving HDHRProxyIPTV and integrating network/virtual tuners with Windows Media Center.

- **Channels DVR** — acknowledgement for its work in modern live-TV streaming and DVR integration. Channels DVR is an independent project and is not affiliated with WMC IPTV.

- **ADBTuner** — acknowledgement for its work bringing streaming television services into tuner/DVR environments using automated playback and virtual tuner concepts. ADBTuner is an independent project and is not affiliated with WMC IPTV.

WMC IPTV also acknowledges the Windows Media Center, EPG123, HDHomeRun, IPTV, and home-theater communities whose work and documentation have helped keep Windows Media Center useful with modern television sources.

### Independent Project

WMC IPTV is an independent community project.

It is not affiliated with, endorsed by, or sponsored by Microsoft, Google/YouTube TV, Frndly TV, Pluto TV, Channels DVR, ADBTuner, SiliconDust, or the other services and projects referenced in this documentation.

All product names, trademarks, and registered trademarks are the property of their respective owners.

---

## 👤 Developer

**Boxcar32**

WMC IPTV was created to bring modern live-TV sources into the classic Windows Media Center television experience while preserving WMC's Guide, recording, tuner, and remote-control functionality.

See the included documentation and **COPYRIGHT.txt** for copyright information and third-party acknowledgements.


---

## Digitally Signed Installer

Official WMC IPTV releases are digitally signed using Microsoft Azure Artifact Signing.

**Publisher:** Marvin Williams

To verify an official installer in Windows:

1. Right-click `WMC IPTV Setup.exe`
2. Select **Properties**
3. Open the **Digital Signatures** tab
4. Select **Marvin Williams**
5. Click **Details**

Windows should report:

**This digital signature is OK.**

This helps verify that the installer came from the published source and has not been modified after signing.

---

## Disclaimer

WMC IPTV is an independent third-party project and is not affiliated with, endorsed by, or sponsored by Microsoft.

Windows, Windows Media Center, and related Microsoft product names are trademarks of Microsoft Corporation.
