<div align="center">

# 🖥️ PC Manager — Downloads

**A Windows desktop Swiss-army knife — 80+ system tools in one Fluent window.**

[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)](#download)
[![Self-contained](https://img.shields.io/badge/runtime-self--contained-512BD4)](#download)
[![Telemetry: none](https://img.shields.io/badge/telemetry-none-2ea043)](#privacy)

</div>

This repository hosts the **released builds** of PC Manager. The application source code is maintained
privately; this page exists so you can download and run the app.

## Download

Grab the latest from the [**Releases**](../../releases/latest) page — pick whichever you prefer:

- 📥 **Installer** — `PCManager-Setup-x.y.z.exe`. Start-menu shortcuts, an uninstaller, and an optional
  run-at-startup task.
- 🎒 **Portable ZIP** — `PCManager-x.y.z-win-x64-portable.zip`. Unzip anywhere and run
  `PCManager\PCManager.App.exe`; nothing is installed and nothing is written to Program Files.

Both are **self-contained (win-x64)** — you don't need the .NET runtime installed.
**Requirements: Windows 10 / 11 (x64).**

> [!NOTE]
> The build is **not code-signed yet**, so Windows SmartScreen may warn "unknown publisher" on first
> run. Click **More info → Run anyway**. Every release also ships a `.sha256` checksum next to each
> file if you want to verify the download.

## What's inside

80+ tools across eight groups — Overview, Apps, Storage, System, Network, Security, Maintenance, and
Diagnostics: hardware sensors, a disk cleaner, a debloater, driver/service managers, a real on-demand
virus scanner with quarantine, network diagnostics, a local-LLM "AI analyst", crash/boot diagnostics,
and much more — all reachable from the sidebar or a **`Ctrl+K` command palette**.

> [!IMPORTANT]
> PC Manager runs **as the invoking user** (not elevated). Privileged tools detect when they need
> administrator rights and offer a one-click restart-as-admin path. Many tools make **real changes**
> to your system — review actions before applying them.

## Privacy

**Local-first, no telemetry.** Settings and logs stay under `%LocalAppData%\PCManager`; nothing is sent
anywhere. A **Field Mode** toggle blocks *every* feature that would reach the internet (update checks,
VirusTotal lookups, the AI analyst, etc.) for use on locked-down or client machines.

## 🐛 Found a bug?

Open it on the [**issue tracker**](../../issues). A good report gets fixed faster — please include:

- **What happened vs. what you expected**, and the exact **tool / page** involved.
- Whether you were running **as administrator**.
- Your **Windows edition & build** (the **PC Info** page has a copy button).
- The relevant tail of the log at **`%LocalAppData%\PCManager\logs`**.
- A **screenshot or GIF** if it's a UI glitch.

> ⚠️ **Security issue?** Please don't open a *public* issue for anything exploitable — report it
> privately first.

## License

PC Manager is released under the **MIT License** — a copy ships inside every download, alongside the
third-party component notices.
