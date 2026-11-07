# Ringback releases

Installers for **Ringback**: a free desktop app that calls your phone when Claude Code (or Codex, Copilot CLI, Antigravity and other coding agents) stops for a permission, a question or its next task, and sends your answer straight back.

**[Download the latest version →](https://github.com/Thanatos9404/ringback-releases/releases/latest)**

| System | File |
| --- | --- |
| Windows 10/11 (64-bit) | `Ringback-Setup-<version>.exe` |
| macOS 12+ (Apple silicon and Intel) | `Ringback-<version>-mac.dmg` |
| Linux (64-bit) | `Ringback-<version>-linux-x86_64.AppImage` or `Ringback-<version>-linux-amd64.deb` |

Ringback keeps itself up to date from this page: it checks in the background and installs the new version when you restart it.

## First launch

The installers aren't code-signed yet, so your system may warn you once:

- **Windows:** SmartScreen says "Windows protected your PC". Choose **More info**, then **Run anyway**.
- **macOS:** right-click Ringback in Applications, choose **Open**, then **Open** again. (Until the app is signed, macOS can't install updates by itself; download the new version from here instead.)
- **Linux (AppImage):** make it executable (`chmod +x Ringback-*.AppImage`) and run it. Tokens are encrypted with GNOME Keyring or KWallet when one is installed.

## About this repo

This repository holds release files only. Each release is built by GitHub Actions from the Ringback source and published here once the Windows, macOS and Linux builds have all finished. Ringback is independent and not affiliated with Anthropic.
