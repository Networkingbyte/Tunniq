<p align="center">
  <img src="https://img.shields.io/badge/version-2.0.2-00f0ff?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/platform-Windows_|_Linux_|_macOS_|_Android-00f0ff?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/license-Free_to_use-10b981?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/free_forever-yes-10b981?style=for-the-badge" alt="Free Forever">
</p>

<h1 align="center">⚡ Tunniq</h1>

<p align="center">
  <b>SSH & SFTP Client, Password Manager and AI Terminal Assistant</b><br>
  <sub>Fast. Secure. Local. No bloat.</sub>
</p>

---

## What is Tunniq?

Tunniq is a free application that combines an **SSH terminal**, **SFTP file manager**, **password vault** and an **AI assistant** into one lightweight tool. Built for developers, sysadmins, and anyone who works with remote servers.

No subscriptions. No cloud lock-in. No telemetry. Just a fast, local tool that does its job.

---
<img width="1565" height="972" alt="Screenshot 2026-06-24 064906" src="https://github.com/user-attachments/assets/253a3bd5-5a5d-40e4-a8ee-79e886afba94" />

<img width="1567" height="978" alt="Screenshot 2026-06-24 064656" src="https://github.com/user-attachments/assets/89170905-2f87-45d3-93e3-bb427a56d570" />

<img width="1572" height="977" alt="Screenshot 2026-06-24 064816" src="https://github.com/user-attachments/assets/1acadf83-4696-472b-9e79-3f8a29b74dc8" />

---

## Why Tunniq?

| | Tunniq |
|---|---|
| **Price** | Free forever |
| **Privacy** | 100% local — nothing leaves your machine |
| **Security** | AES-256 encryption at rest |
| **Tracking** | Zero telemetry, zero analytics |
| **AI** | Optional, uses your own API key, talks only to the provider you pick |
| **Code** | Closed source — free to use, not to modify |

---

## What's new in 2.0.2

- **AI side chat** — Ask about errors, commands or config without leaving the terminal. Bring your own key for **Claude**, **Gemini**, or any **OpenAI-compatible** service (OpenAI, OpenRouter, a local Ollama). Share the last 100 lines of terminal output only when you tick the box.
- **AI Read Files mode** — Allow a server folder, tick the files the AI may read, and review its proposed edits as a diff. Nothing is written until you click **Replace all**, the originals are backed up, and **Undo** puts them back.
- **Drag-and-drop uploads** — Drop files or whole folders onto the SFTP panel. A **Transfers** tray shows progress, speed and time left, and uploads keep running in the background when you close the panel.
- **Two-pane Files view** — Your computer on one side, the server on the other. Drag between them to upload or download, with owner and permission columns on the server side.
- **Clear server identity** — The Files view shows which user you are (with a **ROOT** badge when you are root), whether you can use sudo, and whether you can write in the folder you are looking at, before you try.
- **Android** — The AI chat, plus **Upload many**: pick several files and upload them in the background with a progress list.

---

## Features

- **SSH Terminal** — Multiple tabs, split panes, copy/paste, search, themes, broadcast mode
- **SFTP File Manager** — Browse, upload, download, drag-and-drop, background transfers with progress
- **Two-pane Files view** — Local and server side by side, like a classic SFTP commander
- **AI Assistant** — Bring-your-own-key chat with optional, permission-based file reading and reviewed edits
- **Password Vault** — Encrypted local storage with master passcode
- **Host Manager** — Save servers with labels, colors, and groups
- **Keychain** — Manage SSH keys separately from hosts
- **Snippets** — Save and run frequently used commands instantly
- **Hotkeys** — 30+ fully customizable keyboard shortcuts
- **GitHub Backup** — Push encrypted data to your own private repo
- **Command Palette** — Quick-access search for hosts, snippets, and actions

---

## Download

### Windows (10+)
| Type | Link | Description |
|------|------|-------------|
| **Installer** | [Tunniq-Setup.exe](https://github.com/NetworkingByte/Tunniq/releases/latest/download/Tunniq-Setup.exe) | Run the setup wizard, takes 30 seconds |
| **Portable** | [Tunniq-Portable.exe](https://github.com/NetworkingByte/Tunniq/releases/latest/download/Tunniq-Portable.exe) | No install, just run it |

### Linux (Debian/Ubuntu)
| Type | Link | Description |
|------|------|-------------|
| **.deb Package** | [Tunniq.deb](https://github.com/NetworkingByte/Tunniq/releases/latest/download/Tunniq.deb) | Native package for Debian-based distros |

```bash
# .deb installation
sudo dpkg -i Tunniq.deb
sudo apt-get install -f
```

### macOS (11+)
| Type | Link | Description |
|------|------|-------------|
| **Apple Silicon** (M1–M4) | [Tunniq-arm64.dmg](https://github.com/NetworkingByte/Tunniq/releases/latest/download/Tunniq-arm64.dmg) | Open the disk image and drag to Applications |
| **Intel** | [Tunniq-x64.dmg](https://github.com/NetworkingByte/Tunniq/releases/latest/download/Tunniq-x64.dmg) | Open the disk image and drag to Applications |

Not sure which Mac you have? Apple menu → **About This Mac**: "Chip: Apple M…" means Apple Silicon, "Processor: Intel" means Intel.

```bash
# .dmg installation
open Tunniq-arm64.dmg   # or Tunniq-x64.dmg
# Drag Tunniq to Applications folder

## MUST DO - the app is not signed with an Apple certificate
xattr -cr /Applications/Tunniq.app
```

### Android (8.0+)
| Type | Link | Description |
|------|------|-------------|
| **.apk** | [Tunniq.apk](https://github.com/NetworkingByte/Tunniq/releases/latest/download/Tunniq.apk) | Direct install, no Play Store needed |

```bash
# .apk installation
# Enable "Install from unknown sources" in Settings
# Open the .apk file and install
```

### iOS
iOS builds are not part of this release.

---

## Quick Start

```
1. Open Tunniq
2. Click "+ Add Host"
3. Enter your server IP, username, and password
4. Click "Connect"
5. You're in.
```

That's it. No configuration needed.

### Using the AI assistant (optional)

```
1. In a terminal tab, click "AI" in the toolbar (✨ on Android)
2. Open ⚙ settings, pick Claude, Gemini or an OpenAI-compatible service
3. Paste your own API key and click "Save and test"
4. Ask away. Tick "include terminal output" to share what's on screen
5. Turn on "Read files" to let it read files you pick and propose edits
```

---

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| New Connection | `Ctrl+N` |
| Close Tab | `Ctrl+W` |
| Next / Previous Tab | `Ctrl+Tab` / `Ctrl+Shift+Tab` |
| Switch to Tab 1-9 | `Ctrl+1` – `Ctrl+9` |
| Command Palette | `Ctrl+Shift+P` |
| Terminal Search | `Ctrl+Shift+F` |
| Copy from Terminal | `Ctrl+Shift+C` |
| Paste to Terminal | `Ctrl+Shift+V` |
| Snippets Panel | `Ctrl+Shift+S` |
| SFTP Panel | `Ctrl+Shift+D` |
| Toggle Sidebar | `Ctrl+B` |

All shortcuts are fully customizable in **Settings → Hotkeys**.

---

## Platform Comparison

| Feature | Windows | Linux | macOS | Android |
|---------|---------|-------|-------|---------|
| SSH Terminal | ✅ | ✅ | ✅ | ✅ |
| SFTP Manager | ✅ | ✅ | ✅ | ✅ |
| Drag-and-drop upload | ✅ | ✅ | ✅ | — |
| Background uploads with progress | ✅ | ✅ | ✅ | ✅ |
| Two-pane Files view | ✅ | ✅ | ✅ | — |
| AI Assistant (own API key) | ✅ | ✅ | ✅ | ✅ |
| Password Vault | ✅ | ✅ | ✅ | ✅ |
| Host Manager | ✅ | ✅ | ✅ | ✅ |
| Keychain | ✅ | ✅ | ✅ | ✅ |
| Snippets | ✅ | ✅ | ✅ | ✅ |
| GitHub Backup | ✅ | ✅ | ✅ | ✅ |
| Command Palette | ✅ | ✅ | ✅ | ✅ |
| Touch Optimized | — | — | — | ✅ |

---

## Support the Project

Tunniq is built and maintained by a solo developer. If you find it useful, consider buying me a coffee — it keeps the project alive.

<p align="center">
  <a href="https://ko-fi.com/shubhambhanot">
    <img src="https://img.shields.io/badge/buy_me_a_coffee-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi" alt="Ko-fi">
  </a>
</p>

<p align="center">
  <sub>Every donation helps me build better tools and keep them free.</sub><br>
  <sub>No amount is too small — even a ⭐ star helps.</sub>
</p>

---

## License

Tunniq is **free to use**. It is **not open source**. You may install and use it on any number of devices without restriction.

**You cannot:**
- Modify, reverse engineer, or create derivative works
- Redistribute the software or claim it as your own
- Remove or alter any copyright or branding notices

All rights reserved by **NetworkingByte Solutions**.

---

## Privacy

- All data is stored **locally** on your device
- **No analytics**, **no tracking**, **no phone-home**
- Backups go only where **you** choose (local file or your GitHub repo)
- Your vault is encrypted with **AES-256** — even we can't read it
- The AI assistant is **off until you add your own key**. Requests go straight from your device to the provider you choose (Anthropic, Google, or your own endpoint), never through us. Your key is stored encrypted on your device.
- The AI only sees terminal output when you tick the box, and only files in folders you allow and files you select

---

## Made by

**NetworkingByte Solutions** — building practical, privacy-first tools.

- 🌐 [networkingbyte.com](https://networkingbyte.com)
- 🐛 [Report a Bug](https://tunniq.com/bugs)
- 📖 [How to Use](https://tunniq.com/howtouse)

---

<p align="center">
  <b>Free. Local. Private. Safe.</b><br>
  <sub>If Tunniq saves you time, consider supporting the project. It means a lot.</sub>
</p>
