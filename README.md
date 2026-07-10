# Number Plate Creator V5 - Releases

This repository hosts **Windows installers and auto-update files** for [Number Plate Creator](https://cripdevelopments.co.uk) (NPC) by **Smurfy @ Crip Developments**.

It is used for:

- Automatic updates in the installed app (`electron-updater`)
- Manual downloads for new users and testers

**Source code is not included.** NPC is closed-source. This repo contains release binaries only.

---

## What is Number Plate Creator?

A Windows desktop app for designing UK-style number plates for games and mods - GTA V, FiveM, BeamNG, ETS, Roblox, and more.

You need a **licence key** (Free or Pro) from Payhip to use the app after install.

---

## Download & install (first time)

1. Open **[Releases](https://github.com/CripDevelopments/NumberPlateCreatorV5/releases/latest)**
2. Download the installer, e.g. `NumberPlateCreator-Setup-5.0.0.exe`
3. Run the installer and follow the prompts
4. Get a licence key (see below), then open the app and **activate** it

**Requirements:** Windows 10/11 (64-bit), internet connection for activation and updates.

> Windows may warn that the app is unsigned. Choose **More info → Run anyway** if prompted. The project is not code-signed yet.

---

## Licence (required)

The installer is the **app only**. You still need a key:

| Tier | What you get | Get key |
|------|----------------|---------|
| **Free** | Core creator, diffuse PNG exports (limited), core themes | [Payhip Free (£0)](https://cripdevelopments.co.uk/b/number-plate-creator-free) |
| **Pro** | Unlimited exports, Pro maps/themes, vehicle tools, gallery upload, and more | [Payhip Pro](https://cripdevelopments.co.uk/b/number-plate-creator-pro) |

**After you have a key:**

1. Open Number Plate Creator  
2. Go to **License** (or the activation screen on first launch)  
3. Paste your Payhip key and activate  

Guides:

- [Main licence / download readme](https://cripguard.cripdevelopments.co.uk/npc-license/readme.html)
- [Free licence readme](https://cripguard.cripdevelopments.co.uk/npc-license/NPC-FREE-LICENSE.html)
- [Pro licence readme](https://cripguard.cripdevelopments.co.uk/npc-license/NPC-PRO-LICENSE.html)
- [Features & Free vs Pro table](https://cripguard.cripdevelopments.co.uk/npc-license/NPC-FEATURES-GUIDE.html)

---

## Automatic updates

Once installed, NPC can update itself from this repository.

When a new **stable** release is published:

1. The app checks GitHub for a newer version  
2. Downloads the update in the background  
3. Asks you to **Restart** to finish installing  

You can also use **Settings → Check for updates** in the app.

Each release typically includes:

- `NumberPlateCreator-Setup-x.y.z.exe` - installer  
- `latest.yml` - update metadata (required for auto-update)  
- `*.blockmap` - used for efficient downloads  

---

## Beta / pre-release builds

Some releases may be marked **Pre-release** (beta).

- Stable releases - recommended for everyone  
- Pre-releases - testing only; may be unfinished  

In the app, turn on **Include beta / pre-release builds** in Settings if you want those.

---

## What’s not in this repo

- Application source code  
- Website / VPS licence portal  
- Creator logic, assets, or configs  

Readmes, licence help, and the features guide live on the Crip Developments licence site (links above).

---

## Support

- Website: [cripdevelopments.co.uk](https://cripdevelopments.co.uk)  
- Discord: [discord.cripdevelopments.co.uk](https://discord.cripdevelopments.co.uk)  
- Email: [info@cripdevelopments.co.uk](mailto:info@cripdevelopments.co.uk)

---

© Crip Developments - All rights reserved.  
Number Plate Creator is proprietary software. Redistribution, modification, or reverse engineering is not permitted.
