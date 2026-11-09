Version 1.2.0

NEW
- Map tab (interactive world map): your own markers with in-world pins, teleport to a marker, "explored" trail, collectibles and quest items found around you
  (wide scan 60-600 m, "taken" state read from the game), game locations (safe zones, safe spots, convoys, hives, dark zones, shops, substations, landmarks),
  your own locations (right click > Add Location), category filters, search, found items shown in grey (optional hide).
  The map backdrop is drawn from the game's own data: terrain, rivers, roads, buildings. Rotated like the in-game map.
- 7 interface languages: English, Russian, Polish, Spanish, French, German, Simplified Chinese (Interface > Menu Theme > Language).
  Long texts shrink / trim to fit; menu search works in both English and the chosen language.
- New menu design "Cyber" (angled corners, neon line, bracket frame).
- Wallhack tab: separate ESP for Zombies and Humans, each with its own settings.
  Box (plain / corners / 3D), fill, glow, skeleton, head dot, health bar, name, distance, snaplines, offscreen arrows, live preview.
- Skeleton ESP follows the real game bones. Dead enemies lose their ESP at the moment of death; stunned enemies (UV flashlight) keep it.
- Humans are detected correctly (before, every enemy was treated as a zombie).
- Radar (now in Wallhack): zombies red, humans orange, with height hints.
- Pet tab: Clawd (pixel crab) walks along the panels, hops, blinks and watches the cursor. Grab it and throw it. Optional Santa hat.
- Session Stats: kills, streak, best streak, hits, damage, kills per minute, timer. Bind List. Media Player (current song, cover art, play/pause/skip).
- Draggable HUD: move watermark, speedometer, keystrokes, bind list, media player, radar and stats while the menu is open. "Reset All Positions" puts them back.
- Camera & Trail: parkour trail, custom default FOV, smooth zoom.
- Bind popups with keyboard icons for Long Jump, Unlimited Jumps, Float In Air, Teleport.
- Rapid Fire option: "Pistols & Revolvers Only".
- New Year theme: snow on and inside the menu, garland, mini trees, Santa hats, snow on hit and kill effects (Interface > New Year, FX > New Year).

UPDATED MODS
- Item Extravaganza 1.1.3 (4077 items) and NIGHTVEIN r195 (game build 26402545), both by Atom (Atom0420), included with the author's permission.
- Instant Search / Pickup now also works on containers, wardrobes, lying items and collectibles without the pickup animation, with pickup sounds.
- If the game is already running with an older DLTB.RIP runtime loaded, restart the game once.

CHANGED
- Menu header reworked: search on the left, animated section title on the right.
- Rapid Fire rewritten: no more stuck button.
- Overlay FPS limit (default 100) to reduce load on the game.
- Interface > Layout & Performance: "Hide HUD On Pause / Map" and "Overlay FPS Limit".
- HUD and mod overlay are hidden while the game menu is open (pause, map, inventory). The mod menu still opens with Insert.
- Sub-tabs size themselves to their label text.
- Enemies > Objects sub-tab removed. Debug lines removed from the menu.

FIXED
- Item Extravaganza items being blocked by the game-code self-check while trainer patches were active.
- Background darkening in the menu when "No Background" is on; menu flicker; HUD box shimmer.
- Two checkboxes on one row overlapping; overlapping sub-tab labels.
- Wallhack skeleton drawing on corpses and on dead enemies.
- Map labels jittering when the camera turns or the map scrolls.

WHAT'S NEW IN 1.1.0

NEW
- Wallhack tab: separate ESP for Zombies and Humans, each with its own settings.
  Box (plain / corners / 3D), fill, glow, skeleton, head dot, health bar, name, distance, snaplines, offscreen arrows, live preview.
- Skeleton ESP now follows the real game bones (the game's own bone table), so arms and legs line up with the body.
  Dead enemies lose their ESP at the moment of death; stunned enemies (UV flashlight) keep it.
- Humans are now detected correctly (before, every enemy was treated as a zombie).
- Pet tab: Clawd (pixel crab) walks along the tops of panels, hops, blinks and watches your cursor. Grab it with the mouse and throw it.
- Santa hat option for the pet (off by default).
- Radar: enemies around you (zombies red, humans orange), with height hints.
- Session Stats: kills, streak, best streak, hits, damage, kills per minute, session timer.
- Bind List: shows active binds on screen.
- Media Player: shows the current song from Windows media controls, with cover art and play/pause/skip.
- Draggable HUD: move the watermark, speedometer, keystrokes, bind list, media player, radar and stats with the mouse while the menu is open. "Reset All Positions" puts them back.
- Camera & Trail: parkour trail behind the character, custom default FOV, smooth zoom.
- Bind popups with keyboard icons for Long Jump, Unlimited Jumps, Float In Air and Teleport.
- Rapid Fire option: "Pistols & Revolvers Only".
- New Year theme: snow on the menu and inside it, garland, mini trees (watermark and menu header), Santa hats (menu icon and watermark),
  snow on hit and New Year kill effects. Toggle in Interface > New Year and FX > New Year.

CHANGED
- Menu header reworked: search on the left, animated section title on the right.
- Rapid Fire rewritten: no more stuck button.
- Overlay FPS limit (default 100) to reduce load on the game.
- Interface > Layout & Performance: "Hide HUD On Pause / Map" and "Overlay FPS Limit".
- HUD and mod overlay are hidden while the game menu is open (pause, map, inventory). The mod menu still opens with Insert.
- Sub-tabs in Interface and other sections size themselves to their label text (long names no longer overlap).

FIXED
- Background darkening in the menu when "No Background" is on.
- Menu flicker while sitting in the menu.
- HUD box shimmer.
- Two checkboxes on one row overlapping.
- Wallhack skeleton drawing on corpses and on dead enemies.
- Sub-tab labels overlapping ("Watermark & Text" / "Crosshair & Keys").
- Instant Reload: firearm reloads and bow arrow insertion are near-instant (replaces No Reload).
- Instant Search / Pickup: take everything from a corpse without the search animation.
- Loot My Kills: loot from your melee and firearm kills is collected automatically, with a delay slider.
- NIGHTVEIN updated to r178. Its game layer loads by itself once the game is found; no "Load runtime" button.
- Third person: switches immediately, even with the menu open. Bind your own key (Toggle or Hold). The status line shows what it is waiting for.
- Hide HUD: the F8 key can be changed or set to Hold.
- NIGHTVEIN panels moved to the top of their tabs.

FEATURES
Player: God Mode, unlimited stamina, unlimited UV and flashlight, freeze hunger, no fall damage, no knockdown. Endless Beast Mode, faster meter charge. Night and open-world XP multipliers, no death XP penalty.
Combat: always perfect block or parry, auto block, freeze weapon durability, one-hit kill, damage multiplier, instant and easy finishers, ragdoll more often. Firearms: infinite ammo and arrows, unlimited throwables, Instant Reload, no recoil, rapid fire, mega accuracy, silenced firearms. Aim assist and triggerbot with visibility checks.
Items: catalog powered by Item Extravaganza. Free crafting, blueprint upgrades, multiplied resources, money editor, free purchases, price multipliers.
World: pause time, exact hour or day phase, world speed, slow motion, remove fog of war, discover map locations, open locked doors, easy lockpick, weather control.
Vehicles: god car, no fuel use, unlimited UV, challenge-mode vehicle. NIGHTVEIN vehicle spawning, skins, unlimited fuel and boost, repair, driving tuning, speed boost.
Loot: Instant Search / Pickup, Loot My Kills.
QoL: Hide HUD, thrown weapons return, no head bob, instant dismantle, right-hand pickup.
AI: AI scale, invisibility, no zombie grab, no chase, stomp anywhere, freeze, kill or burn nearby AI, disable AI spawn, spawn enemies.
Movement and camera: movement speed, jump height, unlimited air jumps, auto bunny hop, long jump, vault kick, grappling hook tweaks, slide boost, float in air, fly (noclip), speedometer, custom FOV, smooth zoom, parkour trail, native third-person camera (bindable), teleport to waypoint or nearest respawn, unlimited hook cable, swim speed, no water physics.
Visuals: boxes and skeletons for zombies and humans, health, names, distance, off-screen arrows, radar. Hitmarkers, damage numbers, blood, hit and kill sounds, 20+ kill effects, kill streak announcer, New Year effects.
Interface: Classic, Modern and Liquid Glass menu designs, theme colors, fonts, UI scale, search. Watermark, crosshair, keystrokes, keybind list, media player, session stats, pet. Configs: create, save, load.

REQUIREMENTS
Dying Light: The Beast (Steam), Windows 10 or 11 x64. Nothing else to install. No Visual C++ Redistributable.

INSTALLATION
1. Extract the whole archive into its own folder (for example C:\Games\DLTB.RIP), not Program Files. Keep DLTB.RIP.exe, Start DLTB.RIP.bat and the items and nightvein folders together.
2. Start the game with Start DLTB.RIP.bat, or run DLTB.RIP.exe while you are already playing.
3. Allow administrator rights. They are needed to work with the game's memory.
4. In game: INSERT opens and closes the menu. END unloads the trainer (changeable in Configs).

Updating from 1.0: replace the old files. Your configs keep working.

NOTES
Single-player only. Use at your own risk and back up your saves. Item, money and loot changes can be autosaved.
Do not run the original Item Extravaganza or NIGHTVEIN in the same game session.
Antivirus programs may flag the trainer, because it edits game memory and loads a DLL into the game. Download it only from this page.
A game update can disable some features until the mod is updated.

CREDITS
Atom (Atom0420): Item Extravaganza (https://www.nexusmods.com/dyinglightthebeast/mods/1026) for the Items tab, and NIGHTVEIN (https://www.nexusmods.com/dyinglightthebeast/mods/1069) for Instant Reload, Instant Search, Loot My Kills, vehicles and third person. Both are included with the author's permission. Please endorse their mods too.
Dear ImGui by Omar Cornut (MIT). Manrope font and Font Awesome 5 Free icons (SIL OFL 1.1).
"Rust Headshot" hit sound from Rust by Facepunch Studios. All rights belong to its owner.
Source code: https://github.com/VeryHardys/DLTB.RIP

Not affiliated with Techland, Valve or Nexus Mods. 
