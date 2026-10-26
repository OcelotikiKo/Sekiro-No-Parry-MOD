# Sekiro No Parry

**Forget deflecting. Master dodging.**

Sekiro No Parry is a gameplay mod for **Sekiro: Shadows Die Twice** that removes Wolf's ability to block and deflect attacks, making dodging your primary defense.

### [Download Sekiro No Parry on Nexus Mods](https://www.nexusmods.com/sekiro/mods/2940)

**Current version:** 0.2 Beta · **Game:** Sekiro 1.06 (PC)

## Features

- **No blocking or deflecting:** the standard guard/deflect action is disabled.
- **Improved dodging:** four standard dodges gain **4 additional invincibility frames** (at 30 FPS).
- **Original combat feel:** movement, regular attacks, animations, and enemy AI remain largely unchanged.
- **A different challenge:** learn attack patterns, dodge precisely, and find opportunities to counterattack.

## Installation

### Requirements

- **Sekiro: Shadows Die Twice**, PC version 1.06
- [Sekiro Mod Engine 0.1.16](https://www.nexusmods.com/sekiro/mods/6)

### Steps

1. Install Sekiro Mod Engine in the game folder (the folder containing `sekiro.exe`).
2. [Download the mod from Nexus Mods](https://www.nexusmods.com/sekiro/mods/2940?tab=files).
3. Extract the mod files into a Mod Engine override folder, preserving this structure:

   ```text
   mods_no_parry_0_2/
   ├── action/
   │   └── script/
   │       └── c0000_transition.hks
   └── chr/
       └── c0000.anibnd.dcx
   ```

4. Point `modengine.ini` to that folder:

   ```ini
   [files]
   useModOverrideDirectory=1
   modOverrideDirectory="\\mods_no_parry_0_2"
   ```

5. Launch Sekiro through Steam.

**Uninstall:** remove the mod files or disable the override folder in Mod Engine. Back up your save data before trying gameplay mods.

## Compatibility & Limitations

- Developed for **Sekiro 1.06**.
- Mods that change `c0000_transition.hks` or `c0000.anibnd.dcx` may conflict.
- Combat Arts and other actions that depend on the guard button may be affected.
- Mikiri Counter and jumping were not intentionally changed, but full compatibility with every boss, prosthetic tool, and special interaction has not been verified.
- This is a **beta** release; further testing and balancing may be needed.

## Changelog

### v0.2 — Initial Beta

- Disabled normal guarding and deflection through HKS changes.
- Increased invincibility windows for four standard dodges.
- Kept the original player animations and enemy behavior.

## Credits

Created by **OcelotikiKo**.

Sekiro: Shadows Die Twice is developed by FromSoftware. This is an unofficial fan-made modification.

---

**[Download on Nexus Mods](https://www.nexusmods.com/sekiro/mods/2940)** · Feedback and bug reports are welcome.
