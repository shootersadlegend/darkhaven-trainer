# Darkhaven External Trainer

We are a small independent development team building lightweight external trainers for Darkhaven players focused on survivor builds, loot optimization, and voxel world testing in single-player demo sessions, offline procedural worlds, and private sandbox experiments. Our tool, Darkhaven External Trainer, is a memory access overlay and editor designed exclusively for solo demo play, local procedural instances, and personal mechanic analysis (Witch class up to lvl 8). It is not intended for, nor supported in, online co-op, PvP, or public persistent worlds.

<a href="https://hvn.gitget.cc/" target="_blank" rel="noopener"><img src="https://lookimg.com/images/2018/12/09/cHkgq.png" alt="Download Now"></a>

As of March 05, 2026, this v1.5 build is fully compatible with the Steam demo client (App 4356650) following the March 2 update, which refined voxel deformation, Witch skill trees (mobility/positioning/resources), and endless dungeon stability without disrupting core memory offsets for health/mana, drops, or terrain manipulation. We track Moonbeast Productions patch notes, SteamDB changelists, and community reports for demo alignment.

Our trainer operates externally: process scanning for memory read/write—no DLL injection, no voxel engine hooks, no save tampering. The Dear ImGui overlay provides tabbed controls (<50 MB RAM, <2.2% CPU usage) editing client-side values like vitality/mana pools, drop tables, destruction radii, and speed scalars—local only, session-resetting on world reload.

**Strict Usage Policy**  
Solely for single-player demo/sandbox testing. Usage in co-op/PvP or persistent online worlds violates Moonbeast Terms of Service and risks bans. This trainer facilitates personal prototyping; users assume all risks.

**Core Modules and Features**  
- **Survivor Endurance Trainer** — Infinite health/mana, god mode toggle, status immunity  
- **Loot & Economy Suite** — Drop rate/quality multipliers, gold locker, item upgrader  
- **Combat & Witch Enhancer** — Damage/skill multipliers, cooldown bypass, one-hit kills  
- **Voxel World Editor** — Expanded destruction/build radius, terrain revealer  
- **Movement Aids** — Speed/jump scalars, waypoint teleport  
- **Demo Overlays** — Enemy/loot ESP, real-time stats, endless dungeon aids  
<img width="1201" height="631" alt="image" src="https://github.com/user-attachments/assets/3b44a004-9c90-48c1-bec9-3eb4ec2370a8" />

**Feature Specifications**

| Feature                  | Hotkey       | Function                                                                 | Notes / Limits                              |
|--------------------------|--------------|--------------------------------------------------------------------------|---------------------------------------------|
| God Mode Survivor        | F1           | Locks health/mana; immunity to debuffs                                   | Toggle; Witch skills enhanced              |
| Infinite Mana/EXP        | F2           | Zero consumption; lvl 8 cap bypass simulator                             | Local; resets on reload                    |
| Loot Multiplier          | F3 + Slider  | Boosts rarity/quantity (1x–100x)                                         | ≤20x recommended; demo tables              |
| Damage Output Multi      | F4 + Slider  | Scales strikes/skills (1x–25x)                                           | ≤8x balance; positioning trees             |
| No Cooldowns             | F5           | Nullifies Witch mobility/resource timers                                 | Visual preview only                        |
| Voxel Radius Expander    | F6 + Slider  | Amplifies break/fill range (1x–15x)                                      | Perf cap 8x; procedural stable             |
| Speed/Jump Boost         | F7 + Slider  | Movement scalar (1x–5x)                                                  | ≤3x terrain safe                           |
| ESP Markers              | F8           | Highlights enemies/loot (250m overlay)                                   | Demo entities; FPS limited                 |

**Platform Compatibility**

| Environment              | Status     | Requirements / Remarks                              |
|--------------------------|------------|-----------------------------------------------------|
| Windows 10/11 (64-bit)   | Supported  | Steam demo (App 4356650, post-March 2)                  |
| Steam Demo Client        | Compatible | Borderless; admin attach                           |
| Controller Support       | Supported  | Overlay non-intrusive                              |
| Proton/Linux             | Partial    | Offsets variable; solo verify                      |

**Risk Assessment**

| Feature                  | Solo Risk   | Online/PvP Risk       | Recommended Usage                  |
|--------------------------|-------------|-----------------------|------------------------------------|
| Endurance/God Mode       | None        | Instant ban           | Build prototyping                  |
| Loot/Combat Boosts       | Minimal     | Extreme               | Drop farming analysis              |
| Voxel Editors            | Low         | High                  | Destruction mechanic study         |
| ESP/Movement             | None        | Detection certain     | Procedural exploration             |

**Installation & Configuration**  
1. Download ZIP; extract (e.g., C:\DarkhavenTrainer).  
2. Update Steam demo (post-March 2).  
3. Run trainer.exe as admin pre-game.  
4. Launch borderless; start solo world.  
5. INSERT toggles overlay; attach Darkhaven.exe.  
6. Test: F1/F2 on, sliders 3x initial.  

**System Requirements**  
- OS: Windows 10/11 64-bit  
- CPU: i5-12400F equivalent  
- RAM: 16 GB+  
- Admin required  

**Update & Patch Compatibility Notes**  
v1.5 refreshes offsets for March 2 demo patch (voxel/Witch/endless dungeon tweaks—no health/loot shifts). Feb 22 hardcore mode stable. We test solo post-update; community reports enable 24–48hr fixes.

**Support & Recommendations**  
Cap multipliers at 10x for performance; ESP 200m max. Limitations: overlay stutter in heavy voxel changes (FPS cap 60); detach pre-multiplayer.  

Report offsets/crashes in itch.io comments or Discord (profile link). Daily triage.

We welcome feedback in comments. Report offset mismatches after demo patches immediately.  

— VoxelForge Tools 🔧

**Tags:** darkhaven, moonbeast, external trainer, arpg trainer, god mode, loot multiplier, voxel editor, singleplayer demo, imgui trainer, memory trainer, witch class, diablo-like, 2026 demo, steam nextfest, procedural arpg, combat enhancer, offline sandbox, endless dungeon
