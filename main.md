[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# DISCLAIMER

The guide presented here assumes you have already followed all instructions found in the [**Setup**](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup) page, and are familiar with Mod Organizer 2, which we will be using to install the mods in this document. Please abstain from using this guide until you've correctly set up Fallout: New Vegas and the recommended tools.

Whenever you install a mod in Mod Organizer 2, the mod manager assigns it a default name, which is either the name of the Nexus page from where it is being downloaded from, or, when manually installing a mod, the name of the file.

By default, it is implied that whenever you are asked to install a mod, you must install only the main file, and no other file.
That said, the following scenarios can happen, and you will be explicitly told how to proceed:
- You must install the main file under a different name.
- You must install one or some main files from a Nexus page with multiple main files.
- You must install additional files from the same Nexus page, be them additional main files, update files, or optional files.
- You must skip the main file altogether and install only optional files.

To reduce clutter, you will often be asked to merge one file with the main file. "Main file" here not necessarily refers to the main file as stated in the Nexus page. Often, it refers to the first file of all files you will be asked to download. This is the case of pages with multiple main files which are all standalone from each other.

When in doubt, refer back to this section.

# LEFT MY HEART IN NEW VEGAS

## xNVSE PLUGINS

[**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)  
Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download the **NVHR** main file.
- Extract the contents of the archive and run **cpu_info.exe**. It will determine which file you need to install.
- Place the **.dll** file from the appropiate folder (indicated by **cpu_info.exe**) in your game's **Root** folder.

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**ShowOff NVSE Plugin**](https://github.com/Demorome/Showoff-NVSE/releases)  
Adds new functions, engine bug fixes and tweaks.
- Click the **ShowOffNVSE.7z** under **Assets** to download it.
 
[**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336)  
Enables having custom animations for weapons and actors. Also fixes the engine-bound anim group limit problem.

[**yUI - User Ynterface**](https://www.nexusmods.com/newvegas/mods/74357)  
Aims to fix UI bugs and add new UI features. 

Additional files to install:
- **Matched Cursor - Fallout New Vegas** (Optional files)  
  Merge with the main file.

[**NVAC - New Vegas Anti Crash**](https://www.nexusmods.com/newvegas/mods/53635)  
Implements structured exception handling and sanity checking to reduce frequency of game crashes.

[**OneTweak**](https://www.nexusmods.com/skyrim/mods/40706)  
Enables borderless window mode for safe alt-tabbing.
- Manually download the **OneTweak** main file.
- Extract the contents of the archive. Renamed the **SKSE** folder to **NVSE**, and merge the folder with your **Fallout New Vegas\Data\NVSE** folder.
- Launch Mod Organizer 2.
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Select the **FalloutCustom.ini** tab.
- Set **bFull Screen** to 0.

[**NVTF - New Vegas Tick Fix**](https://www.nexusmods.com/newvegas/mods/66537)  
Fixes the tick count bug (which creates noticable micro stutter), optimizes hash tables (helping performance and decreasing menu load times), and fixes the high FPS bug (fixing physics and lipsync at high framerates).
- Install as **NVTF - New Vegas Tick Fix**.

[**NVTF Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/NVTF%20Custom%20INI.7z)  
Custom configuration that enables a number of settings to achieve the best balance between performance and stability.

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).

[**Improved lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.

[**Console Paste Support**](https://www.nexusmods.com/newvegas/mods/65906)  
Enables hotkeys for pasting and enhanced movement/deletion of console commands.

## PATCHES

### Bug fixes

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
Collection of bug fixes for Fallout: New Vegas and its DLCs, combined into one ESM.

Files to install:
- **YUP - Base Game and All DLC** (Main files)

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.

Files to install:
- **Navmesh Fixes and Improvements - Base Game and ALL DLC** (Main files)

### NVSE bug fixes

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bug fixes for Fallout: New Vegas and its DLCs which require NVSE.

[**lStewieAl's Tweaks and Engine Fixes**](https://www.nexusmods.com/newvegas/mods/66347)  
Engine bugfixes, optional tweaks and new features with no performance impact. Fully customisable via in-game menu and INIs.

[**lStewieAl's Tweaks Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/lStewieAl's%20Tweaks%20Custom%20INI.7z)  
Custom configuration that enables many quality of life improvements, as well as gameplay and balance tweaks.

<details>
	<summary>Detailed list of tweaks</summary>

- Numbered dialogue topics.
- Hidden skill requirements for skill checks.
- Guns require enough ammo to fire a full round (clip size matters).
- Holding the attack button for grenades decreases their detonation timer.
- Throwables can be held and released, like grenades.
- Capping of level up menu max skill values based on SPECIAL. At a SPECIAL value of 1, a skill is capped to 55.
- Vendors obey their Buy/Sell flags, restricting which items they accept. Meant to be used alongside **Misc Gameplay Merge** (Gameplay section).
- Can't steal caps after paying for repairs.
- Increased XP for discovering locations. Meant to be used alongside **Less Map Markers** (Overhauls section).
- Binoculars can zoom in and out.
- Entering VATS costs AP.
- Opening Pip-Boy in combat costs AP.
- Living Anatomy perk shows Damage Resistance.
- Unconscious actors can be looted.
- Manual reloading.
- Slower backpedalling.
- Owned items can't be grabbed and moved around.
- VATS' range is tied to current weapon's range.
- Pickpocket formula takes into account item weight, target Perception, and detection value.
- Agility affects reload jams.
- Repairing items gives XP.
- Robotic companions heal with Scrap Metal instead of Stimpaks.
- Sneak attack critical hits can only be dealt with melee weapons.
- Broken armor is automatically unequipped.
- Weapon mods can be unequipped.
</details>

### Mesh fixes and optimization

[**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLC.

[**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.

[**Weapon Mesh Improvement Mod ESP Replacer**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/WMIM%20ESP%20Replacer.7z)  
Removes unnecessary, non-bugfix edits.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
Visual and audio fixes for thrown projectiles.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.

[**Less Flickery City of New Vegas**](https://www.nexusmods.com/newvegas/mods/72061)  
Fixes the intense flickering in the city of New Vegas (such as when looking from Goodsprings Cemetery) due to extra white proxy meshes clipping into the object LOD meshes.

## USER INTERFACE

### Menus

[**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.

Additional files to install:
- **MCM BugFix 2** (Optional files)  
  Merge with the main file.

[**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- FOMOD options to install:
  - [X] Default Font Tweaks
  - [X] Plugin
  - [X] WASD Compatible 

> ℹ️ The **Classic Pip-Boy Font** option includes the **Default Font Tweaks** option, and is a matter of preference. I personally use it alongside a tweaked Pip-Boy color for that classic Fallout feel (this tweak is present in the **INI Config** section.

[**JIP Improved Recipe Menu**](https://www.nexusmods.com/newvegas/mods/59638)  
Makes the crafting interface easier, more efficient and less tedious to use. 

[**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

[**FOV Slider Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FOV%20Slider%20Custom%20INI%201.0.3.7z)  
Custom configuration that increases field of view. Recommended to be used alongside **Pip-Boy 2000 Mk VI**, which we will install in the **Visuals** section.

[**Vanilla HUD Cleaned**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- FOMOD options to install:
  - All **Modules** and **Tweaks** options.
  - Skip the **DarnUI Specific** options.

[**Clean Companion Wheel**](https://www.nexusmods.com/newvegas/mods/70486)  
Cleans up textures surrounding the Companion Wheel.

Files to install:
- **Clean Companion Wheel 256x256 Edition** (Main files)

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Bug fixes and consistency tweaks for icons in terms of coloring and transparency.

Files to install:
- **1. Consistent Pip-boy Icons** (Main files)  
- **2. Consistent Addon Icons** (Main files)  
  Merge with the main file.
  - FOMOD options to install:
    - [X] Interfaceshared0 Addon
- **3. Consistent Glow Icons** (Main files)  
  Merge with the main file.
  - FOMOD options to install:
    - [X] Main File
- **6. Vanilla UI Plus Patch** (Optional files)  
  Merge with the main file.

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.

Files to install:
- **Satellite World Map** (Main files)

[**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292)  
High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and Lonesome Road.

## GAMEPLAY QOL

[**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

[**Faction Warning and Reputation Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Faction%20Warning%20and%20Reputation%20Tweaks.7z)  
Replaces the faction armor warning pop-ups with corner messages, and lowers reputation penalties for crimes.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/62183) to original mod by **PushTheWinButton**. The featured version drops the restored Primm Reputation and omits the tweaks to reputation scripts.

[**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.

Files to install:
- **Faster Pip-Boy Animation (2x)** (Main files)

[**Laser Weapon Iron Sights**](https://www.nexusmods.com/newvegas/mods/70790)  
Adds iron sights to a variety of laser and plasma weapons which lacked any.

Files to install:
- **Laser Weapon Iron Sights - Gun Runner's Arsenal Merged** (Main files)  
- **Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged** (Main files)  
  Merge with the main file.
- **Laser Weapon Iron Sights - Iron Sight Recoil Animations** (Optional files)  
  Merge with the main file.
- **Plasma Weapon Iron Sights - Iron Sight Recoil Animations** (Optional files)  
  Merge with the main file.

[**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874)  
Adds a hotkey to automatically select the currently selected grenade/mine, as well as a hotkey to scroll through your available grenades/mines. Read the description for instructions on how these features work.

[**Quick Grenade Hotkey Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Quick%20Grenade%20Hotkey%20Tweaks.7z)  
Adjusts the positioning of the grenade/mine icon to not overlap with other UI elements, and removes the unnecessary "no grenade/mine" icon.

[**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

## GAMEPLAY

[**Follower Formula Redone**](https://www.nexusmods.com/newvegas/mods/71490)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most. 

[**Follower Formula Redone ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Follower%20Formula%20Redone%20ESP%20Replacer.7z)  
Forwards Yukichigai Unofficial Patch fixes.

[**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving.

[**Jamming Fix and Optional Tweaks**](https://www.nexusmods.com/newvegas/mods/66293)  
Fixes the on-fire jamming for automatic weapons and adds an option for how often weapons jam.

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

> ℹ️ For detailed instructions on how the **Weapon Wheel** feature works, [**see here**](https://www.nexusmods.com/newvegas/mods/67460).

[**Just Assorted Mods Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Just%20Mods%20Assorted%20Custom%20INI.7z)  
Custom configuration that disables Visual Objectives and Hold Breath. Sets 1st Person Mode crosshair to dynamic and 1st Sighting Mode to none. Sets Bullet Time to use VATS sounds, and use the V hotkey.

[**JAM or Just Sprint Animation Replacers**](https://www.nexusmods.com/newvegas/mods/74839)  
Improves animation transitions when going from idle to sprint, plus allows the player to reload their weapons when sprinting.

[**Less Map Markers**](https://www.nexusmods.com/newvegas/mods/73472)  
Removes many map markers to make exploration more interesting.

[**Melee Cleave (a.k.a. Sweep)**](https://www.nexusmods.com/newvegas/mods/66187)  
Makes melee attacks hit multiple enemies.

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods, fully fixed, optimized, and updated, ranging from quality of life improvements, gameplay and balance tweaks, and visual tweaks.

[**Misc Gameplay Merge YUP Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Misc%20Gameplay%20Merge%20YUP%20Patch.7z)  
Compatibility patch for Yukichigai Unofficial Patch.

[**Miscellaneous Tweaks Collection**](https://www.nexusmods.com/newvegas/mods/71847)    
Collection of gameplay and balance tweaks.

[**Miscellaneous Tweaks Collection Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Miscellaneous%20Tweaks%20Collection%20Tweaks.7z)  
Nerfs Feral Ghoul Reavers, removes most new map markers for consistency with Less Map Markers, ties Honest Hearts recipes to reaching Zion (mirroring how other DLC recipes work), and adds a new Mojave Express dropbox outside Camp McCarran.

[**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

[**NPCs Use Aid Items**](https://www.nexusmods.com/newvegas/mods/68742)  
NPCs will now use aid items in combat. They will not consume their loot; instead, they will simulate consuming items they can potentially carrying.

[**RAD - Radiation (is) Actually Dangerous**](https://www.nexusmods.com/newvegas/mods/61343)  
Makes radiation work like in Fallout 4, by damaging your max health.

[**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541)  
Rewrites the entire UI portion of RAD and makes major changes to the script, including rebalancing and bugfixes.

[**Reload Reloaded**](https://www.nexusmods.com/newvegas/mods/62266)  
Fixes issues with Agility and Strength modifiers for reloading and throwing weapons; makes sneak critical hit damage scale with Sneak; allows grenade throwing range to be affected by Strength.

[**Simple Explosive Entry**](https://www.nexusmods.com/newvegas/mods/66992)  
Allows the player to use explosives to bypass locks. Items have a chance of being destroyed, with the exception of notes and quest items.

## OVERHAULS

[**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of Josh Sawyer's mod, made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.

Additional files to install:
- **JSawyer Ultimate Edition - Push's Tweaks** (Optional files)  
  Merge with the main file.

> ℹ️ It is recommended that you play New Vegas at **Hard** difficulty or lower when using this mod.

[**JSawyer Ultimate Edition - Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20-%20Tweaks.7z)  
Incorporates Yukichigai Unofficial Patch, Weapon Mesh Improvement Mod, and Throwable Weapon Fixes fixes. Disables the out of place Wasteland Adventurer.

[**Mojave Arsenal**](https://www.nexusmods.com/newvegas/mods/62941)  
Adds ammo variants, reloading parts, and weapon mods as loot, fixes item naming conventions, improves recipes, and adds options for configuring Gun Runners' Arsenal.

[**Mojave Arsenal Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Mojave%20Arsenal%20Custom%20INI.7z)  
Custom configuration that disables most GRA features.

[**JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)**](https://www.nexusmods.com/newvegas/mods/62933)  
Compatibility patch for JSawyer Ultimate.

[**Famine - A Loot Rarity Mod**](https://www.nexusmods.com/newvegas/mods/74985)  
Simple and comprehensive loot scarcity mod using event-based scripting.

[**New Vegas Economy Improved**](https://www.nexusmods.com/newvegas/mods/71604)  
Fully-scripted, lightweight, and compatible item value overhaul, taking into consideration important aspects of the vanilla economy balance. Applies a moderate reduction in value to high-value items, and a small reduction to low-value items.

Files to install:
- **New Vegas Economy Improved** (Main files)

[**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Makes enemies more likely to target the player in combat rather than companions.

[**Repair Tools**](https://www.nexusmods.com/newvegas/mods/74884)  
Makes repairing more difficult by making each repair require a consumable Repair Tools item.

Additional files to install:
- **Repair Tools - JSawyer Ultimate Push's Tweaks Patch** (Optional files)  
  Merge with the main file.

[**FNV Opposite Traits**](https://www.nexusmods.com/newvegas/mods/69141?)  
Expands the idea of traits with opposite effects (seen in Fast Shot and Trigger Discipline) to the game's other traits.

Files to install:
- **FNV Opposite Traits (YUP OWB)** (Main files)

[**Improved Traits**](https://www.nexusmods.com/newvegas/mods/65403)  
Edits some vanilla traits and adds two new ones.

[**Improved Traits Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Improved%20Traits%20Tweaks.7z)  
Addresses an unintentional edit that removed Small Frame's Agility requirements, and adds the missing icon for the Four Eyes trait.

[**Improved FNV Opposite Traits**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Improved%20FNV%20Opposite%20Traits.7z)  
Gives the new traits from FNV Opposite Traits the Improved Traits treatment.

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

[**Consistent Pip-Boy Icons Mod Patches**](https://www.nexusmods.com/newvegas/mods/65046)  
Collection of upscaled icons for a variety of mods.
- Install as **Consistent Pip-Boy Icons - Mod Patches**.
- FOMOD options to install:
  - [X] B42 Melee Bash
  - [X] Mojave Arsenal

[**JSawyer Ultimate Edition Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20Patches.7z)  
Collection of compatibility patches for a variety of mods installed so far.
- BAIN options to install:
  - [X] 00 Misc Gameplay Merge
  - [X] 01 Push's Tweaks + Miscellaneous Tweaks
  - [X] 02 Push's Tweaks + Mojave Arsenal
  - [X] 03 Mojave Arsenal (GRA Merged) + Miscellaneous Tweaks
  - [X] 04 FNV Opposite Traits
  - [X] 05 Improved Traits

## CONTENT

[**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.

Files to install:
- **Uncut Wasteland plus NPCs** (Main files)
- **Uncut Wasteland Pole Remover** (Optional files)  
  Merge with the main file.

[**Uncut Wasteland Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Uncut%20Wasteland%20Tweaks.7z)  
Includes YUP fixes; omits the NPC restorations at the Ultra-Luxe Bathhouse and replaces static Destitute Travelers with leveled, random NPCs.

[**The Strip NPCs Uncut - Content Restoration**](https://www.nexusmods.com/newvegas/mods/71503)  
Restores some cut but fully-functional NPCs to the Strip.

[**Mojave Raiders**](https://www.nexusmods.com/newvegas/mods/64660)  
Overhaul of New Vegas's raider factions, balancing their loot and adding more of them to fight.

Additional files to install:
- **Mojave Raiders - No NPC Throwing Weapon Consumption** (Optional files)  
  Merge with the main file.

[**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933)  
Compatibility patch for JSawyer Ultimate.

[**Khans Friendly to Fiends**](https://www.nexusmods.com/newvegas/mods/72381)  
Makes Fiends passive to the player when using a Great Khan outfit, and makes Fiends passive to Great Khans. Additionally restores fully functional cut dialogue when talking to Cook-Cook, Violet, and Driver Nephi. 

Files to install:
- **Khans Friendly to Fiends** (Main files)  
- **Mojave Raiders Patch** (Main files)  
  Merge with the main file.

[**Mojave Wildlife**](https://www.nexusmods.com/newvegas/mods/64638)  
Adds hundreds more leveled, vanilla-friendly creature spawn points throughout the whole Mojave, based off unused vanilla leveled lists. All spawn points are meticulously hand-placed and distributed as evenly and fairly as possible.

Files to install:
- **Mojave Wildlife - Vanilla No Chanced Spawns Version** (Main files)

## AUDIO

[**All Weapon Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/62870)  
Replaces every gun sound in the game, from ballistic to energy weapons.

[**All Weapon Sounds Overhaul ESP Replacer**](https://github.com/VivaNewVegas/Living-in-New-Vegas/blob/master/All%20Weapon%20Sounds%20Overhaul%20ESP%20Replacer.7z)  
Scripted ESP replacer that vastly improves compatibility with other mods.

[**All Weapon Sounds Overhaul WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/All%20Weapon%20Sounds%20Overhaul%20WMIM%20Patch.7z)  
Compatibility patch for Weapon Mesh Improvement Mod.

[**All Explosion Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/66946)  
Replaces every explosion sound in the game.

Additional files to install:
- **All Explosion Sounds Overhaul SCRIPT Version** (Optional files)  
  Merge with the main file.

[**Immersive Primary Needs**](https://eddoursul.win/mods/immersive-primary-needs/)  
As hunger, thirst or sleep deprivation increase, the player is notified by periodic sound effects. These effects kick in shortly before the first penalties occur, so the player is given a chance to eat, drink or sleep in time.

Files to install:
- **Project Nevada - Immersive Primary Needs 1.1**  
  Install as **Immersive Primary Needs**.

[**Female Nuka-Cola Drinking Sound Replacer**](https://www.nexusmods.com/newvegas/mods/68476)  
Replacer for the male drinking sound the game plays whenever you consume a Nuka-Cola.

Files to install:
- **Female Nuka-Cola Drinking Sound replacer** (Main files)

> ⚠️ You should only use this mod when playing a female character, since it replaces the vanilla male drinking sound.

## VISUALS

### Animations

[**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of many animation mods by the same author, improving the game's overall look and feel when it comes to gunplay.

Additional files to install:
- **Weapon Mesh Improvement Mod Patch** (Optional files)  
  Merge with the main file.

[**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320)  
Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person when using Anniversary Anim Pack.
  
Files to install:
- **AnniAnimPack_BugFix 1.3** (Main files)  
- **Bonus Patch** (Main files)  
  Merge with the main file.

[**FNV Clean Animations**](https://www.nexusmods.com/newvegas/mods/70599)  
Clean first person animations. No new idles, no bugs, no reload cancelling from shooting early or crouching, no compatibility issues.

Additional files to install:
- **FNV Clean Animations - Update 2.2.2** (Update files)  
  Merge with the main file.

[**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

[**Viewmodel Recoil 0.308**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

[**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

[**Ragdolls**](https://www.nexusmods.com/newvegas/mods/59147)  
Improves ragdoll behaviour for all NPC/Creatures in the game and restores hit reactions. Very configurable.

Files to install:
- **Ragdolls** (Main files)

[**Ragdolls Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Ragdolls%20Custom%20INI.7z)  
Custom configuration that enables ragdoll momentum, corpse toucher, hit reactions, and complex death reactions features. 

[**Ragdolls YUP Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Yukichigai Unofficial Patch.

[**Ragdolls DLC Enhancements Patch**](https://www.nexusmods.com/newvegas/mods/75268)  
Compatibility patch for Essential DLC Enhancements.

[**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A compatible skeleton for many animation mods.
- FOMOD options to install:
  - [X] Vanilla Weights

### VFX

[**IMPACT**](https://www.nexusmods.com/newvegas/mods/57113)  
Ballistic VFX overhaul. Bullet holes match ammo, casings match ammo, new custom particle effects impacts.

Files to install:
- **IMPACT - The Michael Bay** (Main files)

[**IMPACT - Compatibility Edition**](https://www.nexusmods.com/newvegas/mods/62050)  
Scripted ESP replacer that automatically patches all weapons in the game, DLC, and mods, to have the appropriate shell casings and Impact Data Sets based on their ammo types.

[**EXE - Effect teXtures Enhanced**](https://www.nexusmods.com/newvegas/mods/62989)  
Remakes all visual effects in the game.

[**Enhanced Blood Textures**](https://www.nexusmods.com/newvegas/mods/34917)  
Remakes blood visual effects, including the addition of new types of wounds based on weapon type.

[**Gore Overhaul**](https://www.nexusmods.com/newvegas/mods/67666)  
Retextures the gore assets to give them a severely detailed look with attention to minor details. Also improves on the exploding head meshes to give it more gore bits.

[**Gore Overhaul Optimized Textures**](https://www.nexusmods.com/newvegas/mods/75268)  
Optimizes the very high resolution textures, without noticeably sacrificing quality.

### Characters

[**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 

[**Character Expansions Revised - YUP - JSU - UW - MR - KFF**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Character%20Expansions%20Revised%20-%20YUP%20-%20JSU%20-%20UW%20-%20MR%20-%20KFF.7z)  
Merged compatibility patch for Yukichigai Unofficial Patch, JSawyer Ultimate, Uncut Wasteland, Mojave Raiders, and Khans Friendly to Fiends.

[**FaceGen Tint Fixes for Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/75268)  
Fixes colored tints on character faces.
- [**Visual comparison.**](https://imgsli.com/ODY2MzE)

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/71577?) to original mod by **BobG123**, whose fixed meshes were used as a resource for this mod.

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.

Files to install:
- **tkEyelashesFNV** (Main files)
  - Hide **tkEyelashesFNV_FemalesOnly.esp**.

[**Eyelashes New Vegas ESP Replacer**](https://www.nexusmods.com/newvegas/mods/74893)  
ESP Replacer that fixes issues with the plugin, and extends support to Honest Hearts' tribals and Dead Money's Christine.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.

Files to install:
- **Eyelashes 1.3** (Main files)  
- **HD teeth 3.0** (Main files)  
  Merge with the main file.
- **HQ eyebrows** (Main files)  
  Merge with the main file.

[**Natural Eyes by zzjay**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.

Files to install:
- **00 - Natural Eyes - Shadow** (Main files)

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

### Environment

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

[**Wasteland Flora Overhaul Grass**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Wasteland%20Flora%20Overhaul%20Grass.7z)  
Improves grass textures.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/39856) to original mod by **vurt**. All non-grass related meshes and textures were removed.

[**Windows of the Mojave**](https://www.nexusmods.com/newvegas/mods/67247)  
Improves interior atmosphere, fixing inconsistencies with cell interiors where the buildings had outside windows but no interior windows whatsoever.

[**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the distant glow of New Vegas for the sake of darker nights.

Files to install:
- **Slightly Brighter** (Main files)

[**FNV Realistic Wasteland Lighting**](https://www.nexusmods.com/newvegas/mods/52037)  
Complete weather overhaul designed to make the game look more realistic. Improves lighting, weather, clouds, stars, moon and the overall look and feel of the wasteland.

Files to install:
- **FNV Realistic Wasteland Lighting - All DLC** (Main files)

[**FNV Realistic Wasteland Lighting ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FNV%20Realistic%20Wasteland%20Lighting%20ESP%20Replacer.7z)  
ESP replacer that includes Yukichigai Unofficial Patch fixes, brighter nights, no overcast weather, and ambient music in the Zion Valley.

[**Mojave Nights - A Moon and Stars Replacer**](https://www.nexusmods.com/newvegas/mods/44381)  
High quality retexture for night sky and moon.

Files to install:
- **Mojave Nights FOMOD** (Main files)
  - FOMOD options to install:
    - [X] 80% Moon size.
    - [X] Enhanced Night Sky.
    - [X] Low-glow Moon.
- Copy the **textures\sky\skystars.dds** file and paste it inside the **textures\NVDLC02\sky** folder.

> ℹ️ This will also apply the new night sky texture to Zion.

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

## LOD

[**Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on distant land.

Files to install:
- **Improved LOD noise Texture** (Main files)

[**FNVLODGen Resources**](https://www.nexusmods.com/newvegas/mods/58562)  
Adds extra meshes for LOD generation.

Files to install:
- **FNVLODGen Resources** (Main files)  
  Install as **FNVLODGen Resources**.

[**LOD Additions and Improvements**](https://www.nexusmods.com/newvegas/mods/61206)  
Adds extra meshes for LOD generation.

[**LOD Additions and Improvements YUP Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/LOD%20Additions%20and%20Improvements%20YUP%20Patch.7z)  
Compatibility patch for Yukichigai Unofficial Patch.

[**FNV LOD Supplementation**](https://www.nexusmods.com/newvegas/mods/72099)  
Adds extra meshes for LOD generation.

[**TCM's LOD Overhaul**](https://www.nexusmods.com/newvegas/mods/70155)  
Adds extra meshes for LOD generation.

[**Much Needed LOD**](https://www.nexusmods.com/newvegas/mods/64805)  
Adds extra meshes for LOD generation.

[**Much Needed LOD YUP Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Much%20Needed%20LOD%20YUP%20Patch.7z)  
Compatibility patch for Yukichigai Unofficial Patch.

[**FNVLODGen Output**](https://drive.google.com/file/d/12NDJu8vqal7z1AURhn1nuSBRv6TXpqnj/view?usp=sharing)  
Generated LOD for users who have followed the guide from beginning to bottom. Uses vanilla textures.

> ⚠️ ONLY INSTALL THIS MOD IF YOU'VE FOLLOWED THE **VISUALS** AND **LOD** SECTIONS TO THE LETTER. Else, you will have to generate your own LOD following the instructions in the following section.

## FINISHING TOUCHES

### Mod order and load order

[**Left My Heart In New Vegas Modlist and Loadorder**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Left%20My%20Heart%20In%20New%20Vegas%20Modlist%20and%20Loadorder.7z)  
Adjusts mod order and load order for Left My Heart In New Vegas to work as intended.
- Extract the files into **C:\Games\Fallout New Vegas Mods\MO2\profiles\Left My Heart In New Vegas**, overwriting when prompted.

> ℹ️ Mod order dictates the priority a given mod's assets have over the mods installed before it. This is handled by **modlist.txt**.
 
> ℹ️ Load order dictates the priority a given mod's plugins have over the mods' plugins loaded before them. This is handled by **loadorder.txt**.

### Generating LOD

Assuming you use a different mod setup than the one recommended in the guide, you will have to generate LOD yourself.

- Run **FNVLODGen** in MO2.
- Right click on the list of worldspaces, and click **Select All**.
- Click **Generate**. The process will take some time.
- After the **LOD Generator: finished (you can close this application now)** message appears, close the program.

Now all that's left is to install our generated LOD.

- Navigate to your **Fallout New Vegas Mods\FNVLODGen Output** folder, and make an archive out of the **textures** and **meshes** folder. Name it **FNVLODGen Output**.
- Install **FNVLODGen Output** with MO2.

### Settings config

The following settings need to be configured after you've already started a new save, using the in-game **Settings** option.

**Gameplay**:
- Set **Killcam Mode** to None.
- Set **Difficulty** to Hard.

**Controls -> Action Mapping**:
- Set **VATS** to Esc in order to disable the keybinding.
- Set **Ammo Swap** to Esc in order to disable the keybinding.

### MCM config

The following settings need to be configured after you've already started a new save, using the in-game **Mod Configuration** option.

**Quick Grenade Hotkey**:
- Set **Grenade Hotkey** to **G**.
- Set **Grenade Swap Hotkey** to **C**.

**RAD**:
- Enable **Hardcore**.
- Enable **Alternate**.
- Enable **Incremental**.
- Enable **JSawyer Incremental**.

> ℹ️ Sleep deprivation affects max AP; makes all needs affect max AP, with sleep deprivation setting in later than hunger and thirst; makes needs affect max AP at rates similar to how needs cause stat penalties; makes the former setting follow JSawyer's stat penalties progression.

### INI config

**JIP LN NVSE Plugin**:
- Double-click the installed mod to open the **Information...** window.
- Click the **INI Files** tab, and make the following adjustments in **jip_nvse.ini**.
- Click on the diskette icon to save your changes.

```
bEnableFO3Repair=1

bLocalizedDTDR=1

bVoiceModulationFix=0

bNPCWeaponMods=1
uWMChanceMin=5
uWMChanceMax=15
```

> ℹ️ Enables Fallout 3-style repair, localized damage (allowing headshots to be more powerful when the enemy has no helmet), and a chance for random NPCs to have weapon mods. Disables the voice modulation fix, which could cause noticeable audio popping, particularly in Elijah's dialogue.

**yUI - User Ynterface**:
- Double-click the installed mod to open the **Information...** window.
- Click the **INI Files** tab, and make the following adjustments in **jip_nvse.ini**.
- Click on the diskette icon to save your changes.

```
bMatchingCursor = 1
```

> ℹ️ Matches cursor color to HUD color.

**Vanilla UI Plus**:
- Open **Menus\Prefabs\VUI+\settings.xml** using a text editor and make the following adjustments.

```
<_VUI+DialogMaxTopics> 6 </_VUI+DialogMaxTopics>

<_VUI+NumberedTopics> 1 </_VUI+NumberedTopics>
```

> ℹ️ Increases the amount of visible dialogue topics; displays numbers next to dialogue topics (intended to be used alongside my **lStewieAl's Tweaks Custom INI**).

**falloutcustom.ini (Optional)**:
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Paste the following into **falloutcustom.ini**.

```
[Imagespace]
bDoDepthOfField=0

[Interface]
fDlgFocus=6.0000
uPipboyColor=1022886143
```

> ℹ️ Disables vanilla depth of field effect seen during dialogue; reduces the amount of zoom when engaging in dialogue; tweaks the Pip-Boy HUD color to match that of classic Fallout.

# MOD KEYBINDINGS

This is a handy reference table which will hopefully help you have a better idea of what new hotkeys are available to you, having followed this guide from beginning to end.

Key | Function | Added by
------------ | ------------- | -------------
F6 | Create full save | lStewieAl's Tweaks
F10 | Reload current loaded save | lStewieAl's Tweaks
Left ALT | Skip player deathcam when dying | lStewieAl's Tweaks
R (double tap) | Switch ammunition | lStewieAl's Tweaks
I | Toggle HUD | lStewieAl's Tweaks
J | Open Pip-Boy quests tab | lStewieAl's Tweaks
Hold Tab | Toggle scope night vision when aiming down the scope | lStewieAl's Tweaks
M | Open Pip-Boy world map tab | lStewieAl's Tweaks
Ctrl-F | Apply filter for searching in Pip-Boy | lStewieAl's Tweaks
Shift+E | Pick locked door even if you have the key | lStewieAl's Tweaks
Shift+E | Pick up and equip | lStewieAl's Tweaks
Scroll wheel | Adjust binocular zoom | lStewieAl's Tweaks
G | Equip/unequip grenade/mine | Quick Grenade Hotkey
C + Scroll wheel | Scroll through grenades/mines | Quick Grenade Hotkey
H | Open weapon wheel | Just Assorted Mods
V | Enable bullet time | Just Assorted Mods
Shift+Movement | Sprint | Just Assorted Mods

# CHANGELOG

02-06-2022
- Reworked the guide as it will be split into a main and add-on documents, like my Morrowind guide is. Pretty much every mod removed since the last update will be present in this add-on guide.
- Mod order and load order is now handled by a download that needs to be installed on your MO2 profile folder. These require mods to be installed under specific names, those of which are provided by default by MO2. The ones that require a different name are mentioned in the guide.
- **No Stealing After Repair** is now included in **lStewieAl's Tweaks Custom INI**.
- **FNVLODGen Output** has been updated to reflect the removal of many LOD mods.
- Added **Much Needed LOD YUP Patch**.

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)
