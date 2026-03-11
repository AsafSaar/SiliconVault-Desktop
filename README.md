<p align="center">
  <img src="https://siliconvault.app/icon.svg" width="80" alt="SiliconVault" />
</p>

<h1 align="center">SiliconVault Desktop</h1>

<p align="center">
  <strong>Offline retro computing inventory manager</strong><br>
  Your collection. Your machine. No cloud required.
</p>

<p align="center">
  <a href="https://siliconvault.app">Website</a> &middot;
  <a href="https://github.com/AsafSaar/SiliconVault-Desktop/releases/latest">Download</a>
</p>

---

SiliconVault Desktop: The local, offline counterpart to the SiliconVault web app. Designed for retro computing collectors who prioritize privacy and ownership, SiliconVault Desktop brings our powerful inventory tools directly to your machine. Catalog your entire collection: computers, consoles, software, and peripherals, locally, with zero cloud dependency and no internet required.

Already using the web version at siliconvault.app? SiliconVault Desktop offers the same precision for your vintage hardware, but in a secure, permanent, and fully offline environment.

**$29.99 — one-time purchase, yours forever.** 12 months of updates included.

## Download

| Platform | Requirements | Download |
|----------|-------------|----------|
| **macOS** | macOS 11+ (Apple Silicon & Intel) | [Download .dmg](https://github.com/AsafSaar/SiliconVault-Desktop/releases/latest) |
| **Windows** | Windows 10/11, x64 | [Download .exe](https://github.com/AsafSaar/SiliconVault-Desktop/releases/latest) |
| **Linux** | x64 (Ubuntu 20.04+, Fedora 38+, Debian 11+) | coming soon (.AppImage / .deb) |

## Features

- **Fully offline** — no internet connection required after installation
- **Local SQLite database** — your entire collection in a single file, stored on your device
- **No telemetry** — zero analytics, zero tracking, zero phone-home
- **AI hardware identification** — use your own OpenAI or Azure API key to identify items from photos
- **CSV & JSON export** — export your full collection anytime
- **Image management** — store photos locally alongside your inventory
- **Health tracking** — monitor component condition, capacitor status, and maintenance schedules
- **Document library** — attach manuals, schematics, and reference docs to your items
- **Collection sets** — track completeness against known sets
- **9 retro themes** — Green Phosphor, Amber Phosphor, Commodore 64, Atari 800XL, ZX Spectrum, Amstrad CPC, Amiga Workbench, Modern Dark, Modern Light
- **English & Hebrew** — full i18n with RTL support

## Getting Started

1. Download the installer for your platform from the [Releases](https://github.com/AsafSaar/SiliconVault-Desktop/releases/latest) page
2. Install and launch SiliconVault Desktop
3. Enter your license key (received via email after purchase)
4. Start cataloging — fully offline

## License Key

A license key is required to use SiliconVault Desktop. To purchase:

- Visit [siliconvault.app/download](https://siliconvault.app/download)
- Or email [info@corgimind.com](mailto:info@corgimind.com?subject=SiliconVault%20Desktop%20License)

One license = one activation. Your license includes 12 months of software updates from the date of activation.

## Data Storage

Your data is stored locally in the app's data directory:

| Platform | Path |
|----------|------|
| macOS | `~/Library/Application Support/app.siliconvault/` |
| Windows | `%APPDATA%\app.siliconvault\` |
| Linux | `~/.local/share/app.siliconvault/` |

- **Database:** `siliconvault.db` (SQLite with WAL mode)
- **Images:** `uploads/` subfolder

Back up this directory to preserve your collection.

## Desktop vs Web

SiliconVault Desktop is the offline counterpart to [siliconvault.app](https://siliconvault.app). Both share the same interface, but serve different needs:

| | Desktop | Web |
|---|---------|-----|
| Storage | Local SQLite | Cloud (PostgreSQL) |
| Users | Single-user | Multi-user with roles |
| AI | Your own API key (Optional) | Admin-configured |
| Images | Local filesystem | Cloud (Vercel Blob) |
| Community | — | Showroom, trading, profiles |
| Offline | Yes | No |
| Price | $29.99 one-time | Free |

## Tech Stack

Built with [Tauri v2](https://tauri.app) — a Rust-based framework for lightweight, secure desktop apps.

- **Backend:** Rust + Axum + SQLite (via SQLx)
- **Frontend:** React 18 + Vite + TypeScript + Tailwind
- **Auth:** Local JWT + bcrypt
- **License:** Ed25519 offline signature verification
- **AI:** OpenAI / Azure OpenAI integration (optional, user-configured)

## Support

SiliconVault is built and maintained by [Asaf Saar](https://www.linkedin.com/in/asafsaar/).

- Report issues: [GitHub Issues](https://github.com/AsafSaar/SiliconVault-Desktop/issues)
- Email: [info@corgimind.com](mailto:info@corgimind.com)
- Support the project: [Ko-fi](https://ko-fi.com/asafsaar)

---

<p align="center">
  <sub>&copy; 2026 Asaf Saar. All rights reserved. SiliconVault is proprietary software.</sub>
</p>
