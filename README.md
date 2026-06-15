# ZoneMusic 1.0

A complete audio overhaul for Final Fantasy XI. Over 350 tracks — covers, remixes, and original compositions — spanning Vanilla, Rise of the Zilart, and Chains of Promathia. Day/night themes, battle music, boss themes, and more, all playing seamlessly as you explore Vana'diel.

By **MoonRise (Eldorin)**

---

## Requirements

- **Ashita v4**
- **XIPivot**

---

## Installation

1. Place the `ZoneMusic` folder into your Ashita `addons` folder.
2. Place the `sounds` folder into your XIPivot overlay folder.
3. In game, type `/zm load`.
4. Get the sounds from https://www.nexusmods.com/finalfantasy11/mods/34 or https://drive.google.com/file/d/1fw-bMa9PIomk_9YyMWjOeLiLngmtXTVg/view?usp=drive_link

That's it.

Features:
• 350+ tracks
• Toggle individual music events on/off
• Dynamic combat music that resumes where it left off
• Day/Night zone themes
• Low HP themes
• Chocobo music
• Fishing music
• Cutscene support
• Custom soundtrack support
---

## Commands

| Command | What it does |
|---------|--------------|
| `/zm` | Open the settings window |
| `/zm on` / `/zm off` | Start / stop the music |
| `/zm solo` / `/zm party` / `/zm auto` | Battle music mode |
| `/zm random` | Toggle random battle tracks |
| `/zm dynamic` | Toggle dynamic battle mode (resumes where it left off) |
| `/zm fade` | Toggle fade in/out |
| `/zm help` | List all commands |

Everything else lives in the settings window (`/zm`).

---

## Use Your Own Music

Every track is just a `.wav` file in the `sounds` folder. Replace any file with your own and ZoneMusic plays it instead.

Naming:

- `day_{zoneID}.wav` — daytime zone music
- `night_{zoneID}.wav` — nighttime (optional; falls back to day)
- `battle_{zoneID}_solo.wav` — solo battle music
- `battle_{zoneID}_party.wav` — party battle music

Encoding: 16-bit PCM WAV, 44100 Hz, stereo.

---

## Features

- Day and night themes per zone
- Separate solo and party battle music
- Unique boss themes (Bahamut, Omega, Ultima, Diabolos, and more)
- Low HP music
- Chocobo riding music
- Fishing music
- Mog House music
- Seamless zone-to-zone transitions — no restarting between districts
- Cutscenes play their intended music

---

## Notes

- ZoneMusic covers Vanilla, RoTZ, and CoP zones. Later expansions play the game's native music until those packs ship.
- This is a passion project built on a 22-year-old game engine. A few rough edges (like a long NPC conversation occasionally swapping music after ~10 seconds) are engine limitations, not bugs.

---

Enjoy Vana'diel.
