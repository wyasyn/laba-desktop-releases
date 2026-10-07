# Laba Desktop

Live TV and radio from Uganda and beyond, for Windows, macOS and Linux.

**[Download the latest version](https://github.com/wyasyn/laba-desktop-releases/releases/latest)**

| System | File |
| --- | --- |
| Windows 10 and 11 | `Laba_x.y.z_x64-setup.exe` |
| macOS 12 or newer, Apple silicon | `Laba_x.y.z_aarch64.dmg` |
| macOS 12 or newer, Intel | `Laba_x.y.z_x64.dmg` |
| Linux (any) | `Laba_x.y.z_amd64.AppImage` |
| Debian, Ubuntu | `Laba_x.y.z_amd64.deb` |
| Fedora, openSUSE | `Laba-x.y.z-1.x86_64.rpm` |

Laba updates itself on Windows, macOS and the AppImage. With the `.deb` or `.rpm`, install the new version's package when the app tells you one is available.

## First launch

The installers are not code signed yet, so your system asks once before opening Laba:

- **Windows:** SmartScreen says "Windows protected your PC". Choose **More info**, then **Run anyway**.
- **macOS:** the first open is blocked. Open **System Settings → Privacy & Security** and choose **Open Anyway** for Laba.
- **Linux AppImage:** make it executable first: `chmod +x Laba_*.AppImage`.

## Linux media playback

Laba plays through GStreamer. The `.deb` and `.rpm` pull in what they need; on other systems install the GStreamer "good", "bad" and "libav" plugins if TV or radio does not play.

## Support

Website: [laba.yasinwalum.com](https://laba.yasinwalum.com) · Email: ywalum@gmail.com

This repository only holds releases.
