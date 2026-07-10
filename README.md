![ProFilio](ProFilio%20Banner.png)

---

## Overview

ProFilio (*For My Son*) began as a personal project to create a Minecraft experience I wanted to share with my son.

The goal wasn't to reinvent Minecraft or overwhelm with new content. Instead, the additions were selected to preserve the core vanilla experience while refining nearly every aspect of the game.

With breathtaking landscapes, expanded cave systems, and enhanced versions of the structures you already know, enjoy a refreshed representation of the game you love, with new mysteries and adventures waiting to be discovered. Quality-of-life improvements, performance optimizations, higher-resolution textures, and the selected shader come together to create an experience that feels both familiar and entirely new.

Whether you're starting your very first world or returning for your next Minecraft adventure, I hope ProFilio lets you rediscover the sense of wonder that made Minecraft special in the first place.

---

## Credits

[Credit Where Credit is Due](CREDITS.md)

ProFilio would not exist without the incredible work of the Minecraft modding community. Please take a moment to visit and support the mod authors whose work made this project possible.

---

## First Launch

> **Recommended:** Before beginning your Survival world, take the time to pre-generate your world with Chunky. This allows Voxy to build its distant terrain, letting you experience the breathtaking long-distance views ProFilio was designed to deliver. Skipping this step significantly reduces the visual impact of the pack and is **not recommended**.
>
> **Note:** Large-radius world generation can take several hours depending on your hardware.

1. Start your new world in **Creative** mode.
2. Disable any shader pack before starting world generation (recommended).
3. Freeze time:
   ```
   /gamerule doDaylightCycle false
   ```
4. Freeze weather:
   ```
   /gamerule doWeatherCycle false
   ```
5. Run Chunky:
   ```
   /chunky radius 512c
   /chunky start
   ```

   > Replace **512c** with your preferred pre-generation radius if desired.

6. Allow Chunky to complete world generation before importing the terrain into Voxy.
7. Import the pre-generated terrain into Voxy:
   ```
   /voxy import current
   ```
8. Re-enable:
   ```
   /gamerule doDaylightCycle true
   /gamerule doWeatherCycle true
   ```
9. Switch to **Survival** mode.
10. Re-enable your preferred shader pack and begin your adventure.

> **Note:** Voxy will continue building distant terrain in the background as you explore. If you later discover a location you'd like to call home, you can repeat these steps to pre-generate and import a new area centered on your new location.

---

## Requirements

- **Minecraft:** 26.1.2
- **Mod Loader:** Fabric
- **Primary Launcher:** CurseForge (recommended)
- **Java:** Java 25 (Default CurseForge Runtime)
- **Memory Allocation:** 4–8 GB RAM (8 GB recommended)

> **Note:** ProFilio was developed and tested using the default Java runtime included with the CurseForge App (Java 25) and **8 GB RAM** allocated.

---

## Support

Questions, suggestions, and bug reports are always welcome.

- 💬 **Questions, suggestions, and general feedback:** https://github.com/Fathom-2/ProFilio/discussions
- 🐞 **Bug reports and confirmed issues:** https://github.com/Fathom-2/ProFilio/issues
- 📦 **Mod Support:** Please use the links provided in the **Credits** page for support related to individual mods.
