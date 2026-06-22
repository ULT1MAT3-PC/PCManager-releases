<div align="center">

# ULT1MAT3 PC Manager

### 80+ Windows system tools in one free Fluent app — for Windows 10 & 11

A Windows desktop Swiss-army knife: **clean, debloat, manage drivers and services, monitor hardware,
scan for viruses, fix your network and run AI diagnostics** — all from one window.
**No telemetry. No bloat. Free.**

[![Latest release](https://img.shields.io/github/v/release/ULT1MAT3-PC/PCManager-releases?label=download&sort=semver)](https://github.com/ULT1MAT3-PC/PCManager-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/ULT1MAT3-PC/PCManager-releases/total)](https://github.com/ULT1MAT3-PC/PCManager-releases/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20(x64)-0078D6)](#system-requirements)
[![License](https://img.shields.io/badge/license-MIT-green)](#license)

**[⬇ Download the latest release](https://github.com/ULT1MAT3-PC/PCManager-releases/releases/latest)** &nbsp;·&nbsp;
**[🌐 Website](https://ult1mat3-pc.github.io/)** &nbsp;·&nbsp;
**[🐞 Report a bug](https://github.com/ULT1MAT3-PC/PCManager-releases/issues)**

</div>

---

## What is ULT1MAT3 PC Manager?

**ULT1MAT3 PC Manager** is a free Windows system utility that replaces a folder full of separate
downloads with a single, fast, native app. Instead of juggling a cleaner, a debloater, a driver
updater, a hardware monitor and a network tool, you get **80+ tools in one Fluent window**, reachable
from the sidebar or the `Ctrl+K` command palette.

It's a more capable, privacy-respecting alternative to lightweight cleanup apps like Microsoft PC
Manager — local-first, with **no telemetry** and no upsells.

## Features

| Section | What you get |
| --- | --- |
| **Overview** | System dashboard with real-time sensors, charger telemetry and battery health |
| **Apps** | Install / update / remove software and **debloat** preinstalled Windows apps |
| **Storage** | Disk cleaner for caches, temp files and leftovers — with confirmation before deleting |
| **System** | Device **driver** manager (incl. OEM driver lookups) and Windows **service** manager |
| **Network** | Connectivity diagnostics, DNS flush, stack reset, adapter & connection inspector |
| **Security** | On-demand **virus scan** with quarantine and optional VirusTotal lookups |
| **Maintenance** | Multi-step **tune-up** passes and declarative "recipe" macros for repeatable fixes |
| **Diagnostics** | **AI analysis** via a local model (Ollama / llama.cpp) or hosted (OpenAI, Anthropic, GitHub Models) |

### Safe & private by design

- **No telemetry** — nothing about you or your PC is collected or sent anywhere.
- **System Restore snapshots** are created before risky operations, so you can roll back in one step.
- **Field Mode** — a fully offline mode for restricted or air-gapped environments.
- **SHA256 checksums** ship with every release so you can verify your download.

## Install

### Option 1 — Installer (recommended)
Download **`PCManager-Setup-1.3.0.exe`** from the [latest release](https://github.com/ULT1MAT3-PC/PCManager-releases/releases/latest) and run it.

### Option 2 — Portable (no install)
Download **`PCManager-1.3.0-win-x64-portable.zip`**, extract it, and run `PCManager.App.exe`. No admin rights needed.

### Option 3 — winget *(once published)*
```powershell
winget install ULT1MAT3.PCManager
```

### Option 4 — Scoop *(once published)*
```powershell
scoop bucket add ult1mat3 https://github.com/ULT1MAT3-PC/scoop-bucket
scoop install ult1mat3-pc-manager
```

> **SmartScreen note:** the installer is not yet code-signed, so Windows SmartScreen may warn on new
> downloads. Verify the SHA256 below, then choose **More info → Run anyway**.

### Verify your download (SHA256)

```text
PCManager-Setup-1.3.0.exe            8ac5f7479dccb62796a0ec075ee8b26465e4ef606b476d37c99369f11ec87ff4
PCManager-1.3.0-win-x64-portable.zip d657443289c64e1a45c39cd8e544f1ddd3dfa2e915ae402906426f58c17d3f4f
```

```powershell
Get-FileHash .\PCManager-Setup-1.3.0.exe -Algorithm SHA256
```

## System requirements

- **OS:** Windows 10 or Windows 11, 64-bit
- **Runtime:** none — the build is self-contained (no separate .NET install)
- Some tools need administrator rights and will offer to relaunch elevated when needed

## License

The downloads in this repository are distributed under the **MIT License**; third-party component
notices are included with the application. The application source is maintained separately.

---

<div align="center">
<sub>ULT1MAT3 PC Manager is an independent project and is not affiliated with or endorsed by Microsoft.
"Microsoft PC Manager" is a trademark of Microsoft Corporation.</sub>
</div>
