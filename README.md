# Nightreign Co-op Mod

A co-op test mod for ELDEN RING NIGHTREIGN, loaded with me3 and played together through Seamless Co-op.

**Downloads are on the [Releases](../../releases/latest) page.** Always get both part zips of the newest build.

**Download both zips** (part 1 and part 2) and extract both into the same place. Everyone in the group needs this exact build and the same Seamless Co-op version.

## How to install (do this on every PC)

1. **You need:** ELDEN RING NIGHTREIGN on Steam (fully updated), [me3](https://github.com/garyttierney/me3/releases) 0.11.0 or newer (the Windows `.msi` installer), and [Seamless Co-op for Nightreign](https://www.nexusmods.com/eldenringnightreign/mods/3) (tested with 1.1.3; everyone must use the same version).
2. **Unpack:** put both zips in the same place (e.g. the Desktop). Right-click each zip > Properties > tick **Unblock** if it is there. Extract part 1, then part 2 to the **same** place (say yes to merging). You get one `NightreignCoopMod` folder with `mod\`, `natives\`, `SeamlessCoop\`, `play-coop.me3`, `play-solo.me3` and the text files. Don't copy anything into the game folder.
3. **Install me3:** run its `.msi` installer.
4. **Add Seamless Co-op:** copy everything from the Seamless download's `SeamlessCoop` folder into `NightreignCoopMod\SeamlessCoop\`, so you have `NightreignCoopMod\SeamlessCoop\nrsc.dll` and `nrsc_settings.ini`. (`nrsc_launcher.exe` is not needed.)
5. **Start:** double-click `play-coop.me3` (pick me3 if Windows asks). If nothing happens, open PowerShell in the folder and run `me3 launch --profile play-coop.me3`.
6. **Play together:** everyone starts with `play-coop.me3` and groups up through Seamless Co-op's Steam party invite. `play-solo.me3` plays the mod alone.

**Important:** never start the game the normal way (with Easy Anti-Cheat) while using the mod, and never use it on official matchmaking — that can get your account banned. If your antivirus removes `nrstatver.dll` or `nrsc.dll`, restore it and allow the folder.

**Updating to a new build:** keep a copy of your `SeamlessCoop` files, delete the old `NightreignCoopMod` folder, unpack the new zips, put the Seamless files back.

**Problems:** crash at start or missing models → part 2 is missing or was extracted somewhere else. The mod's stats box missing in Character Selection → send `natives\nrstatver.log`. The full guide is `HOW TO INSTALL (every PC).txt` inside the zips (also attached to each release).

