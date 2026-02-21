# Number Plate Creator – Releases

This repository is used **exclusively** to host release files for **Number Plate Creator (NPC)**.

It exists to support:

* Automatic updates via Electron (`electron-updater`)
* Manual downloads for beta testers and public users

> 🔒 **Source code is NOT included in this repository.**
> NPC is a closed-source application. This repo contains **release binaries only**.

---

## 📦 What’s in this repository?

Each GitHub Release contains the files required for updates:

* `NumberPlateCreator.exe`  ← versioned installer
* `latest.yml`
* `NumberPlateCreator.exe.blockmap`

These files are generated automatically during the build process and are used by the app to:

* Detect updates
* Download new versions
* Apply updates safely

---

## 🔄 Automatic Updates

Number Plate Creator uses **Electron Auto Updater**.

When a new version is released:

1. The app checks this repository
2. Downloads the update in the background
3. Prompts the user to install when ready

No manual action is required from the user.

---

## 🧪 Beta vs Public Releases

Some releases may be marked as:

* **Pre-release (Beta)** – for testing and feedback
* **Stable Release** – for public use

Beta builds may contain unfinished features or experimental changes.

---

## 🚫 What’s NOT included

This repository does **not** contain:

* Application source code
* Website files
* Creator logic
* Assets, scripts, or configuration files

Those are intentionally excluded.

---

## 📥 Downloading NPC

If you’re here to download NPC:

1. Go to **Releases**
2. Download the installer for your version (e.g., `NumberPlateCreator.exe`)
3. Run the installer

> First-time installation uses the same installer as updates. Updates are also handled automatically via `latest.yml`.

---

## 🧾 License & Usage

Number Plate Creator is proprietary software.
Redistribution, modification, or reverse engineering is **not permitted**.

---

## 💬 Support & Community

* 🌐 Website: [https://codemaster.ltd](https://codemaster.ltd)
* 💬 Discord: [https://discord.gg/ZDCGZCguBW](https://discord.gg/ZDCGZCguBW)

---

**© CodeMaster Ltd – All rights reserved**
