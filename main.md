[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# DISCLAIMER

The guide presented here assumes you have already followed all instructions found in the [**Setup**](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup) page, and are familiar with Mod Organizer 2, which we will be using to install the mods in this document. Please abstain from using this guide until you've correctly set up Fallout: New Vegas and the recommended tools.

# LEFT MY HEART IN NEW VEGAS

## xNVSE PLUGINS

[**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)  
Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download the **NVHR** main file.
- Extract the contents of the archive and run **cpu_info.exe**. It will determine which file you need to install.
- Place the **.dll** file from the appropiate folder (indicated by **cpu_info.exe**) in your game's **Root** folder.

> ℹ️ Modern alternative to [**New Vegas Stutter Remover**](https://www.nexusmods.com/newvegas/mods/34832) which should be used in its place.

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**ShowOff NVSE Plugin**](https://github.com/Demorome/Showoff-NVSE/releases)  
Adds new functions, engine bug fixes and tweaks.
- Click the **ShowOffNVSE.7z** under **Assets** to download it.
- Install manually in Mod Organizer 2.
 
[**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336)  
Enables having custom animations for weapons and actors. Also fixes the engine-bound anim group limit problem.

[**yUI - User Ynterface**](https://www.nexusmods.com/newvegas/mods/74357)  
Aims to fix UI bugs and add new UI features. 

Files to install:
- **yUI** (Main files)
- **Matched Cursor - Fallout New Vegas** (Optional files)  

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

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).

[**Improved lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.

[**Console Paste Support**](https://www.nexusmods.com/newvegas/mods/65906)  
Enables hotkeys for pasting and enhanced movement/deletion of console commands.

## PATCHES

### Bug fixes

⭐ [**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
Collection of bug fixes for Fallout: New Vegas and its DLCs, combined into one ESM.

Files to install:
- **YUP - Base Game and All DLC** (Main files)

⭐ [**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

⭐ [**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.

Files to install:
- **Navmesh Fixes and Improvements - Base Game and ALL DLC** (Main files)

### NVSE bug fixes

⭐ [**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bug fixes for Fallout: New Vegas and its DLCs which require NVSE.

⭐ [**lStewieAl's Tweaks**](https://www.nexusmods.com/newvegas/mods/66347)  
Engine bugfixes, optional tweaks and new features with no performance impact. Fully customisable via in-game menu and INIs.

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Ammo Script Fixes**](https://www.nexusmods.com/newvegas/mods/63997)  
Fixes several problems at the core level with how ammo scripts and effects work, plus some tweaks for consistency and fun.

[**Critical and Effects - Fixes and Tweaks**](https://www.nexusmods.com/newvegas/mods/69200)  
Fixes the damage dealing critical effects of most vanilla weapons so that they cannot cause you to miss "killcounts" and other proc effects such as crime responsibility.

[**Gauss Rifle VATS Fix - JIP**](https://www.nexusmods.com/newvegas/mods/69136)  
Fixes the Gauss Rifle not dealing headshot and critical damage in VATS.

[**Mostly Unarmed Tweaks**](https://www.nexusmods.com/newvegas/mods/69283)  
Fixes the fatigue-dealing weapons to deal correct and damage-adjusted fatigue to enemies and the player; tweaks the effects of Unarmed special attacks; allows NPCs to use Unarmed special attacks.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
Visual and audio fixes for thrown projectiles.

[**Universal Pyromaniac Buff for Fire Effects**](https://www.nexusmods.com/newvegas/mods/71505)  
Makes the Pyromaniac perk affect *all* the lingering fire damage effects from weapons and ammo.

### Mesh fixes and optimization

⭐ [**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLC.

⭐ [**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.

Additional files to install:
- [**WMIM ESP Replacer**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/WMIM%20ESP%20Replacer.7z)  
  Removes unnecessary, non-bugfix edits. Made by **Qolore**.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.

[**Less Flickery City of New Vegas**](https://www.nexusmods.com/newvegas/mods/72061)  
Fixes the intense flickering in the city of New Vegas (such as when looking from Goodsprings Cemetery) due to extra white proxy meshes clipping into the object LOD meshes.

## USER INTERFACE

### Menus

⭐ [**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

⭐ [**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.

Files to install:
- **The Mod Configuration Menu** (Main files)
- **MCM BugFix 2** (Optional files)

⭐ [**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- FOMOD options to install:
  - [X] Default Font Tweaks
  - [X] Plugin
  - [X] WASD Compatible 

> ℹ️ The **Classic Pip-Boy Font** option includes the **Default Font Tweaks** option, and is a matter of preference. I personally use it alongside a tweaked Pip-Boy color for that classic Fallout feel (this tweak is present in the **INI Config** section.

⭐ [**JIP Improved Recipe Menu**](https://www.nexusmods.com/newvegas/mods/59638)  
Makes the crafting interface easier, more efficient and less tedious to use. 

[**Vanilla HUD Cleaned**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- FOMOD options to install:
  - All **Modules** and **Tweaks** options.
  - Skip the **DarnUI Specific** options.

[**Clean Companion Wheel**](https://www.nexusmods.com/newvegas/mods/70486)  
Cleans up textures surrounding the Companion Wheel.

Files to install:
- **Clean Companion Wheel 256x256 Edition** (Main files)

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.

Files to install:
- **Satellite World Map** (Main files)

Additional files to install:
- [**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292)  
  High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and Lonesome Road.

### Icons

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Lore-friendly overhaul of New Vegas icons to make them more consistent in terms of coloring and transparency. Includes other bug fixes.

Files to install:
- **1. Consistent Pip-boy Icons** (Main files).
- **2. Consistent Addon Icons** (Main files)  
  - FOMOD options to install:
    - [X] Interfaceshared0 Addon
- **3. Consistent Glow Icons** (Main files)  
  - FOMOD options to install:
    - [X] Main File
- **6. Vanilla UI Plus Patch** (Optional files)  

[**Vanilla HD Missing Icon for Consistent Pip Boy Icons**](https://www.nexusmods.com/newvegas/mods/73375)  
Replaces the farting vault boy with an upscaled HD version of the vanilla missing item icon.

## GAMEPLAY QOL

⭐ [**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

⭐ [**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.

Files to install:
- **Faster Pip-Boy Animation (2x)** (Main files)

⭐ [**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

⭐ [**Laser Weapon Iron Sights**](https://www.nexusmods.com/newvegas/mods/70790)  
Adds iron sights to a variety of laser and plasma weapons which lacked any.

Files to install:
- **Laser Weapon Iron Sights - Gun Runner's Arsenal Merged** (Main files)
- **Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged** (Main files)
- **Laser Weapon Iron Sights - Iron Sight Recoil Animations** (Optional files)
- **Plasma Weapon Iron Sights - Iron Sight Recoil Animations** (Optional files)

⭐ [**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874)  
Adds a hotkey to automatically select the currently selected grenade/mine, as well as a hotkey to scroll through your available grenades/mines. Read the description for instructions on how these features work.

Additional files to install:
- [**Quick Grenade Hotkey Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Quick%20Grenade%20Hotkey%20Tweaks.7z)  
  Adjusts the positioning of the grenade/mine icon to not overlap with other UI elements, and removes the unnecessary "no grenade/mine" icon.

⭐ [**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

[**Hunting Revolver Iron Sights**](https://www.nexusmods.com/newvegas/mods/73124?)  
Removes the scope from the Hunting Revolver and makes it a separate weapon mod.

Files to install:
- **Hunting Revolver Iron Sights** (Main files)

Additional files to install:
- [**Consistent Pip-Boy Icons Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Consistent%20Pip-Boy%20Icons%20-%20Hunting%20Revolver%20Iron%20Sights%20Patch.7z)

[**Stars Turned Face Up**](https://www.nexusmods.com/newvegas/mods/70419)  
Turns all Sunset Sarsaparilla star bottle caps face up, allowing you to spot them more easily.

## GAMEPLAY

⭐ [**B42 Melee Bash**](https://www.nexusmods.com/newvegas/mods/68055)  
Adds melee attacks for non-melee weapons.

⭐ [**Enhanced Vision**](https://eddoursul.win/mods/enhanced-vision/)  
Power Armor helmets and other high-tech gear now enable enhanced vision modes like Night Vision, Heat Vision and EM Vision. If there’s no Power Armor equipped as a power source, energy cells are required while these modes are active. Upgrades for other kinds of helmets and eyeglasses can be purchased through the MCM panel.

⭐ [**Faction Warning and Reputation Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Faction%20Warning%20and%20Reputation%20Tweaks.7z)  
Replaces the faction armor warning pop-ups with corner messages, and lowers reputation penalties for crimes.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/62183) to original mod by **PushTheWinButton**. The featured version drops the restored Primm Reputation and omits the tweaks to reputation scripts.

⭐ [**Follower Formula Redone**](https://www.nexusmods.com/newvegas/mods/71490)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most. 

Additional files to install:
- **Follower Formula Redone ESP Replacer**  
  Incorporates YUP fixes.

⭐ [**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving.

⭐ [**Jamming Fix and Optional Tweaks**](https://www.nexusmods.com/newvegas/mods/66293)  
Fixes the on-fire jamming for automatic weapons and adds an option for how often weapons jam.

⭐ [**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

Additional files to install:
- [**JAM Animation Replacers**](https://www.nexusmods.com/newvegas/mods/74839)  
  Improves animation transitions when going from idle to sprint, plus allows the player to reload their weapons when sprinting.

> ℹ️ For detailed instructions on how the **Weapon Wheel** feature works, [**see here**](https://www.nexusmods.com/newvegas/mods/67460).

⭐ [**Less Map Markers**](https://www.nexusmods.com/newvegas/mods/73472)  
Removes many map markers to make exploration more interesting.

Additional files to install:
- **Less Map Markers ESP Replacer**  
  Incorporates YUP fixes.

⭐ [**Melee Cleave (a.k.a. Sweep)**](https://www.nexusmods.com/newvegas/mods/66187)  
Makes melee attacks hit multiple enemies.

⭐ [**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods, fully fixed, optimized, and updated, ranging from quality of life improvements, gameplay and balance tweaks, and visual tweaks.

Additional files to install:
- **Misc Gameplay Merge ESM Replacer**  
  Incorporates YUP fixes.

⭐ [**Miscellaneous Tweaks Collection**](https://www.nexusmods.com/newvegas/mods/71847)    
Collection of gameplay and balance tweaks.

Additional files to install:
- [**Miscellaneous Tweaks Collection Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Miscellaneous%20Tweaks%20Collection%20Tweaks.7z)  
  Nerfs Feral Ghoul Reavers, removes most new map markers for consistency with Less Map Markers, ties Honest Hearts recipes to reaching Zion (mirroring how other DLC recipes work), and adds a new Mojave Express dropbox outside Camp McCarran.

⭐ [**No Stealing After Repair**](https://eddoursul.win/mods/no-stealing-after-repair/)  
After vendor repair, moves the payment into the vendor’s container instead of their inventory, making the caps unavailable for pickpocketing yet allowing to use them for barter. If a vendor has no container attached (in rare cases), the caps are simply removed.

⭐ [**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

⭐ [**NPCs Use Aid Items**](https://www.nexusmods.com/newvegas/mods/68742)  
NPCs will now use aid items in combat. They will not consume their loot; instead, they will simulate consuming items they can potentially carrying.

⭐ [**RAD - Radiation (is) Actually Dangerous**](https://www.nexusmods.com/newvegas/mods/61343)  
Makes radiation work like in Fallout 4, by damaging your max health.

Additional files to install:
- [**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541)  
  Rewrites the entire UI portion and makes major changes to the script, including rebalancing and bugfixes.

⭐ [**Reload Reloaded**](https://www.nexusmods.com/newvegas/mods/62266)  
Fixes issues with Agility and Strength modifiers for reloading and throwing weapons; makes sneak critical hit damage scale with Sneak; allows grenade throwing range to be affected by Strength.

⭐ [**Simple Explosive Entry**](https://www.nexusmods.com/newvegas/mods/66992)  
Allows the player to use explosives to bypass locks. Items have a chance of being destroyed, with the exception of notes and quest items.

[**Standarized NCR Supply Caches**](https://www.nexusmods.com/newvegas/mods/74145)  
Swaps out the current, barely-useful supply cache loot table with a static one, whose contents are scaled with the player level.
- Only install **Patchy's Preferred Preparedness Package - Scaler Moon Edition** (Main files).

[**Thrown Weapon Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Thrown%20Weapon%20Tweaks%20(Dec%2022nd).7z)  
NPCs no longer consume thrown weapons, and Throwing Hatchet's damage is reduced.

## OVERHAULS

⭐ [**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of Josh Sawyer's mod, made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.

Files to install:
- **JSawyer Ultimate Edition** (Main files)
- **JSawyer Ultimate Edition - Push's Tweaks** (Optional files)  

> ℹ️ It is recommended that you play New Vegas at **Hard** difficulty or lower when using this mod.

Additional files to install:
- [**JSawyer Ultimate Edition Tweaks and Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20Tweaks%20and%20Patches.7z)  
  BAIN options to install:
  - [X] 00 JSUE Tweaks
  - [X] 01 JSUE Push's Tweaks + Miscellanous Tweaks
- [**Misc Gameplay Merge JSawyer - Ultimate Edition Patch**](https://www.nexusmods.com/newvegas/mods/73921)  

⭐ [**Mojave Arsenal**](https://www.nexusmods.com/newvegas/mods/62941)  
Adds ammo variants, reloading parts, and weapon mods as loot, fixes item naming conventions, improves recipes, and adds options for configuring Gun Runners' Arsenal.

Additional files to install:
- [**JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)**](https://www.nexusmods.com/newvegas/mods/62933)
- [**Mojave Arsenal Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Mojave%20Arsenal%20Patches.7z)  
  BAIN options to install:
  - [X] 00 Hunting Revolver Iron Sights + JSUE Mojave Arsenal (GRA Merged)
  - [X] 01 Miscellaneous Tweaks + JSUE Mojave Arsenal (GRA Merged)
  - [X] 02 JSUE Push's Tweaks

[**Consistent Pip-Boy Icons Mod Patches**](https://www.nexusmods.com/newvegas/mods/65046)  
Upscales icons from a selection of mods.
- FOMOD options to install:
  - [X] Mojave Arsenal

> ℹ️ If you don't mind unnecessary files in your computer which will otherwise have no effect in the game, you can simply install the default options.

⭐ [**Famine - A Loot Rarity Mod**](https://www.nexusmods.com/newvegas/mods/74985)  
Simple and comprehensive loot scarcity mod using event-based scripting.

⭐ [**New Vegas Economy Improved**](https://www.nexusmods.com/newvegas/mods/71604)  
Fully-scripted, lightweight, and compatible item value overhaul, taking into consideration important aspects of the vanilla economy balance. Applies a moderate reduction in value to high-value items, and a small reduction to low-value items.

Files to install:
- **New Vegas Economy Improved** (Main files)

⭐ [**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Makes enemies more likely to target the player in combat rather than companions.

⭐ [**Repair Tools**](https://www.nexusmods.com/newvegas/mods/74884)  
Makes repairing more difficult by making each repair require a consumable Repair Tools item.

Files to install:
- **Repair Tools** (Main files)
- **Repair Tools - JSawyer Ultimate Push's Tweaks Patch** (Optional files)

⭐ [**Improved Traits and Opposite Traits**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Improved%20Traits%20and%20Opposite%20Traits.7z)  
- BAIN options to install:
  - [X] 00 Improved Traits and Opposite Traits
  - [X] 01 JSUE Patch

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/65403) to original mod by **TrueVoidwalker**. The featured plugin fixes a handful of oversights and disables an overpowered trait. 

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/69141) to original mod by **cbgreely**. The featured plugin was cleaned.

⭐ [**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

[**Anatomic Perks**](https://www.nexusmods.com/newvegas/mods/65648)  
Distributes the effect from the Living Anatomy perk to see the target's HP and DT, so that specific perks grant this bonus only against specific enemies.
The Here and Now perk now includes the original effects from Living Anatomy. 

[**Cannibal Reborn**](https://www.nexusmods.com/newvegas/mods/64789)  
Balanced cannibalism overhaul with immersive gore effects.

Additional files to install:
- [**Cannibal Reborn Expanded**](https://www.nexusmods.com/newvegas/mods/75054)  
  Expands Cannibal Reborn to also cover the Ghastly Scavenger perk.

## CONTENT

⭐ [**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.

Files to install:
- **Uncut Wasteland plus NPCs** (Main files)
- **Uncut Wasteland Pole Remover** (Optional files)

Additional files to install:
- [**Uncut Wasteland Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Uncut%20Wasteland%20Tweaks.7z)  
  Includes YUP fixes; omits the NPC restorations at the Ultra-Luxe Bathhouse and replaces static Destitute Travelers with leveled, random NPCs.

⭐ [**The Strip NPCs Uncut - Content Restoration**](https://www.nexusmods.com/newvegas/mods/71503)  
Restores some cut but fully-functional NPCs to the Strip.

⭐ [**Mojave Raiders**](https://www.nexusmods.com/newvegas/mods/64660)  
Overhaul of New Vegas's raider factions, balancing their loot and adding more of them to fight.

Additional files to install:
- [**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933)

⭐ [**Khans Friendly to Fiends**](https://www.nexusmods.com/newvegas/mods/72381)  
Makes Fiends passive to the player when using a Great Khan outfit, and makes Fiends passive to Great Khans. Additionally restores fully functional cut dialogue when talking to Cook-Cook, Violet, and Driver Nephi. 

Additional files to install:
- [**Khans Friendly to Fiends Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Khans%20Friendly%20to%20Fiends%20Patches.7z)
  - BAIN options to install:
    - [X] 00 Mojave Raiders
    - [X] 01 Character Expansions Revised

⭐ [**Mojave Wildlife**](https://www.nexusmods.com/newvegas/mods/64638)  
Adds hundreds more leveled, vanilla-friendly creature spawn points throughout the whole Mojave, based off unused vanilla leveled lists. All spawn points are meticulously hand-placed and distributed as evenly and fairly as possible.

Files to install:
- **Mojave Wildlife - Vanilla No Chanced Spawns Version** (Main files)

[**Canvas Backpacks - Remade**](https://www.nexusmods.com/newvegas/mods/71510)  
Adds backpacks to the game, with different colors and faction options. Most can be bought, some can only be found.

Files to install:
- **Canvas Backpacks - Remade** (Main files)
- **Strapless Update** (Optional files)  

Additional files to install:
- [**Canvas Backpacks - Remade Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Canvas%20Backpacks%20-%20Remade%20Tweaks.7z)  
  Edits the icons and rebalances the stats of backpacks.
  - BAIN options to install:
    - [00] JSUE  

## AUDIO

⭐ [**All Weapon Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/62870)  
Replaces every gun sound in the game, from ballistic to energy weapons.

Additional files to install:
- [**All Weapon Sounds Overhaul ESP Replacer**](https://github.com/VivaNewVegas/Living-in-New-Vegas/blob/master/All%20Weapon%20Sounds%20Overhaul%20ESP%20Replacer.7z)  
  Scripted version that vastly improves compatibility with other mods.
- [**All Weapon Sounds Overhaul WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/All%20Weapon%20Sounds%20Overhaul%20WMIM%20Patch.7z)  

⭐ [**All Explosion Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/66946)  
Replaces every explosion sound in the game.

Files to install:
- **All Explosion Sounds Overhaul BSA and YUP Patch** (Main files)
- **All Explosion Sounds Overhaul SCRIPT Version** (Optional files)

⭐ [**Immersive Primary Needs**](https://eddoursul.win/mods/immersive-primary-needs/)  
As hunger, thirst or sleep deprivation increase, the player is notified by periodic sound effects. These effects kick in shortly before the first penalties occur, so the player is given a chance to eat, drink or sleep in time.

[**Female Nuka-Cola Drinking Sound Replacer**](https://www.nexusmods.com/newvegas/mods/68476)  
Replacer for the male drinking sound the game plays whenever you consume a Nuka-Cola.

Files to install:
- **Female Nuka-Cola Drinking Sound replacer** (Main files)

> ⚠️ You should only use this mod when playing a female character, since it replaces the vanilla male drinking sound.

## VISUALS

### Animations

⭐ [**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of many animation mods by the same author, improving the game's overall look and feel when it comes to gunplay.

Files to install:
- **Anniversary Anim Pack** (Main files)
- **Weapon Mesh Improvement Mod Patch** (Optional files)  

Additional files to install:
- [**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320)  
  Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person.
  
  Files to install:
    - **AnniAnimPack_BugFix 1.3** (Main files)
    - **Bonus Patch** (Main files)

⭐ [**FNV Clean Animations**](https://www.nexusmods.com/newvegas/mods/70599)  
Clean first person animations. No new idles, no bugs, no reload cancelling from shooting early or crouching, no compatibility issues.

Files to install:
- **FNV Clean Animations** (Main files)
- **FNV Clean Animations - Update 2.2.2** (Update files)

⭐ [**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

⭐ [**Viewmodel Recoil**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

⭐ [**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

Additional files to install:
- [**Ragdolls Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Ragdolls%20Patches.7z)  
  - BAIN options to install:
    - [X] 00 YUP
    - [X] 01 DLC Enhancements

[**Chill Companions**](https://eddoursul.win/mods/chill-companions/)  
When companions are in a familiar and safe environment, they automatically go into sandbox mode. Instead of following you, they wander around, eat, sleep, and sit.

[**Diagonal Movement**](https://www.nexusmods.com/newvegas/mods/64333)  
Adds proper diagonal movement animations.

[**360 Movement**](https://www.nexusmods.com/newvegas/mods/71940)  
Adds 360 degrees movement with procedural leaning and auto vanity mode, like modern Bethesda games.
- FOMOD options to install:
  - [X] Full 360 Sneak Options
  - [X] Diagonal Movement Patch

[**Player Headtracking**](https://www.nexusmods.com/newvegas/mods/66741)  
Enables headtracking for the player character, rotating their head in the direction of the closest actor.

[**Ragdolls**](https://www.nexusmods.com/newvegas/mods/59147)  
Improves ragdoll behaviour for all NPC/Creatures in the game and restores hit reactions. Very configurable.

⭐ [**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A compatible skeleton for many animation mods.
- FOMOD options to install:
  - [X] Vanilla Weights

### NPCs

⭐ [**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 
- Hide **Character Expansions Revised - Extras.esp**.

Additional files to install:
- [**Character Expansions Revised - Additional Patches**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Character%20Expansions%20Revised%20-%20Additional%20Patches.7z)  
  - BAIN options to install:
    - [X] 00 Complete
      All in one merge of Extras.esp, YUP, JSawyer Ultimate Edition, Uncut Wasteland, and Mojave Raiders patches.
- [**FaceGen Tint Fixes for Character Expansions Revised**](https://drive.google.com/file/d/1OzY-_zi3RfVkIMvaQJvb-3DZc9AhGH9H/view?usp=sharing)  
  Fixes colored tints on character faces.
  - [**Visual comparison.**](https://imgsli.com/ODY2MzE)

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/71577?) to original mod by **BobG123**, whose fixed meshes were used as a resource for this mod.

### Equipment

⭐ [**Helmet Overlay**](https://www.nexusmods.com/newvegas/mods/67870)  
Adds overlays for various headwear items, From facemasks, to glasses, to helmets. Overlays will stack if you can wear the items together.
- FOMOD options to install:
  - [X] Medium (2K) Resolution

> ℹ️ Because slideshows work by placing the slides in front of your character, you will see the helmet overlays unless you remove your helmet before slideshows play.

[**Worn-Out Scope Crosshair Replacers**](https://www.nexusmods.com/newvegas/mods/43181)  
Replaces the vanilla scopes with worn-out scopes to give them a post-apocalyptic feel.

Files to install:
- **Worn-Out Scopes** (Main files)

[**No Pip-Boy Glove**](https://www.nexusmods.com/newvegas/mods/69258)  
Removes the completely useless Pip-Boy glove from player and NPCs.

Files to install:
- **No Pip-Boy Glove - No ESP** (Main files)

[**Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/65980)  
New Pip-Boy 2000 Mk VI with custom scratch-made meshes, textures and working clock like in Fallout 76.

Files to install:
- **Pip-Boy 2000 Mk VI replacer version** (Main files)
- **Working date and clock for replacer** (Optional files)

Additional files to install:
- [**Pip-Boy 2000 Mk VI Working Buttons**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Pip-Boy%202000%20Mk%20VI%20Working%20Buttons.7z)  
  Makes the Pip-Boy's buttons functional. Mod by **AleksMarch**.
- [**Pip-Boy 2000 MK VI (Wasteland Edition) Retexture**](https://www.nexusmods.com/newvegas/mods/65999)  
  Gives the Pip-Boy 2000 Mk VI a grittier texture.
- [**NPC Arm Mounted Pip-Boy 2000 Mk VI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/NPC%20Arm%20Mounted%20Pip-Boy%202000%20Mk%20VI.7z)  
  Makes NPCs wear the new Pip-Boy 2000 Mk VI.

### VFX

⭐ [**IMPACT**](https://www.nexusmods.com/newvegas/mods/57113)  
Ballistic VFX overhaul. Bullet holes match ammo, casings match ammo, new custom particle effects impacts.

Files to install:
- **IMPACT - The Michael Bay** (Main files)

Additional files to install:
- [**IMPACT - Compatibility Edition**](https://www.nexusmods.com/newvegas/mods/62050)  
  Automatically patches all weapons in the game, DLC, and mods, to have the appropriate shell casings and Impact Data Sets based on their ammo types.

⭐ [**EXE - Effect teXtures Enhanced**](https://www.nexusmods.com/newvegas/mods/62989)  
Remakes all visual effects in the game.

⭐ [**Enhanced Blood Textures**](https://www.nexusmods.com/newvegas/mods/34917)  
Remakes blood visual effects, including the addition of new types of wounds based on weapon type.

⭐ [**Gore Overhaul**](https://www.nexusmods.com/newvegas/mods/67666)  
Retextures the gore assets to give them a severely detailed look with attention to minor details. Also improves on the exploding head meshes to give it more gore bits.

Additional files to install:
- [**Gore Overhaul Optimized**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Gore%20Overhaul%202.0%20(Optimized).7z)  
  Optimizes the very high resolution assets, without noticeably sacrificing quality.

### Environment

⭐ [**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

Additional files to install:
- **A Little More Lamplight ESP Replacer**  
  Incorporates YUP fixes.

⭐ [**Lightweight Strip Overhaul**](https://www.nexusmods.com/newvegas/mods/65665)  
Turns walls from junk to brick, cleans the litter up off of the street, and buffs out the cracked marble and peeling wallpaper as well as much more, making the Strip far more pleasing to the eye.

Files to install:
- **Lightweight Strip Overhaul - No Walls** (Main files)
- **Lightweight Strip Overhaul - Uncut Wasteland Patch** (Optional files)

⭐ [**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

Additional files to install:
- [**Lightweight Strip Overhaul Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Strip%20Lighting%20Overhaul%20LSO%20Patch.7z)  
  Addresses terrain conflicts with Lightweight Strip Overhaul.

⭐ [**Wasteland Flora and Terrain Overhaul Grass**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Wasteland%20Flora%20and%20Terrain%20Overhaul%203.6b%20Grass.7z)  
Improves grass textures.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/39856) to original mod by **vurt**. The featured version removes all mesh and texture changes minus those for grass.

⭐ [**Windows of the Mojave**](https://www.nexusmods.com/newvegas/mods/67247)  
Improves interior atmosphere, fixing inconsistencies with cell interiors where the buildings had outside windows but no interior windows whatsoever.

⭐ [**FNV Realistic Wasteland Lighting**](https://www.nexusmods.com/newvegas/mods/52037)  
Complete weather overhaul designed to make the game look more realistic. Improves lighting, weather, clouds, stars, moon and the overall look and feel of the wasteland.

Files to install:
- **FNV Realistic Wasteland Lighting - All DLC** (Main files)
- **FNV RWL All DLC - Patch Collection** (Optional files)

Additional files to install:
- **FNV Realistic Wasteland Lighting ESP Replacer**  
  Incorporates YUP fixes.
- [**RWLE - ReShade SweetFX**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/ReShade%20SweetFX%201.1.7z)  
  SweetFX preset by **Camo**.
  - Extract the contents of the archive in your **Root** folder.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/52037) to original mod by **Sal203** and **Camo**. The featured version includes YUP fixes.

⭐ [**Mojave Nights - A Moon and Stars Replacer**](https://www.nexusmods.com/newvegas/mods/44381)  
High quality retexture for night sky and moon.

Files to install:
- **Mojave Nights FOMOD** (Main files)
  - FOMOD options to install:
    - [X] 80% Moon size.
    - [X] Enhanced Night Sky.
    - [X] Low-glow Moon.
- Copy the **textures\sky\skystars.dds** file and paste it inside the **textures\NVDLC02\sky** folder.

> ℹ️ This will also apply the new night sky texture to Zion.

⭐ [**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

[**Subtle Light Beams and Rays**](https://www.nexusmods.com/newvegas/mods/71613)  
Removes the fake interior light rays and tones the exterior light beams down dramatically. 
- Hide **Subtle Light Beams and Rays.esp**.

> ℹ️ This restores interior light rays.

## LOD

⭐ **Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on distant land.

Files to install:
- **Improved LOD noise Texture** (Main files)

⭐ [**FNVLODGen Resources**](https://www.nexusmods.com/newvegas/mods/58562)  
Adds extra meshes for LOD generation.

Files to install:
- **FNVLODGen Resources** (Main files)

⭐ [**LOD Additions and Improvements**](https://www.nexusmods.com/newvegas/mods/61206)  
Adds extra meshes for LOD generation.

Additional files to install:
- **LOD Additions and Improvements ESP Replacer**  
  Incorporates YUP fixes.

⭐ [**FNV LOD Supplementation**](https://www.nexusmods.com/newvegas/mods/72099)  
Adds extra meshes for LOD generation.

⭐ [**Better Strip View**](https://www.nexusmods.com/newvegas/mods/73261)  
Adds visible Strip signs and moves the Strip buildings to where they should be.

Additional files to install:
- [**More Subtle New Vegas Light Pollution Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Better%20Strip%20View%20More%20Subtle%20New%20Vegas%20Light%20Pollution%20Patch.7z)  

⭐ [**TCM's LOD Overhaul**](https://www.nexusmods.com/newvegas/mods/70155)  
Adds extra meshes for LOD generation.

⭐ [**Hoover Dam Jets Restored and Distant**](https://www.nexusmods.com/newvegas/mods/72135)  
Restores the cut outflow jets to Hoover Dam and makes them visible up and down the Colorado.

⭐ [**Strip Lights Region Fix**](https://www.nexusmods.com/newvegas/mods/73596)  
Fixes a vanilla issue about the Strip lights not showing in certain parts of the map.

Files to install:
- **Strip Lights Region Fix** (Main files)
- FOMOD options to install:
  - [X] Uncut Wasteland
- **Strip Lights Region Fix - Hoover Dam Jets Restored and Distant** (Optional files)

Additional files to install:
- [**Mormon Fort Region Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Mormon%20Fort%20Region%20Fix%201.0.7z)  
  Add-on that fixes an issue where the Lucky 38 would disappear from the Old Mormon Fort worldspace. Mod by **Nehred**.

⭐ [**Lucky 38 Lights Redone**](https://www.nexusmods.com/newvegas/mods/73273)  
Modifies the Lucky 38 lights before and after they have been turned on during the Mr. House/Yes Man questlines.
- FOMOD options to install:
  - [X] Gold Lights
  - [X] Extras Everywhere
  - [X] Pollution Gold Tint
  - [X] Patch for Better Strip View

⭐ [**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the exaggerated glow of New Vegas.

Files to install:
- **Slightly Brighter** (Main files)

⭐ [**FNV RWL All DLC - Worldspace Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FNV%20RWL%20All%20DLC%20-%20Worldspace%20Patch.7z)  
All-in-one patch for Better Strip View, Strip Lights Region Fix, Mormon Fort Region Fix, and Lucky 38 Lights Redone.

## Finishing touches

### Mod order and load order

The mod order dictates the priority a given mod's assets have over the mods installed before it. Respect this order to ensure assets are overwritten as intended.

<details>
<summary>Mod order</summary>

```
DLC: TribalPack
DLC: OldWorldBlues
DLC: MercenaryPack
DLC: LonesomeRoad
DLC: HonestHearts
DLC: GunRunnersArsenal
DLC: DeadMoney
DLC: ClassicPack
DLC: CaravanPack
JIP LN NVSE Plugin
JohnnyGuitar NVSE
ShowOffNVSE
kNVSE Animation Plugin
yUI - User Ynterface
NVAC - New Vegas Anti Crash
NVTF - New Vegas Tick Fix
FNV Mod Limit Fix
Improved Lighting Shaders
Console Paste Support
Yukichigai Unofficial Patch - YUP
Landscape Disposition Fix
Navmesh Fixes and Improvements
Unofficial Patch NVSE Plus
lStewieAl's Tweaks
lStewieAl's Tweaks INI
Ammo Burst Case Count Fix
Gauss Rifle VATS Fix - JIP
Ammo Script Fixes
Critical and Effects - Fixes and Tweaks
Mostly Unarmed Tweaks
Throwable Weapon Fixes
Universal Pyromaniac Buff for Fire Effects
New Vegas Mesh Improvement Mod
Weapon Mesh Improvement Mod
WMIM ESP Replacer
Female White Glove Society Mask
Less Flickery City of New Vegas
UIO - User Interface Organizer
The Mod Configuration Menu
The Mod Configuration Menu Bugfix
Vanilla UI Plus (New Vegas)
JIP Improved Recipe Menu
Clean Vanilla HUD
Clean Companion Wheel
Satellite World Map
Satellite Maps DLC
Consistent Pip-Boy Icons
Vanilla HD Missing Icon for Consistent Pip Boy Icons - No More Farting Vault Boy
Essential DLC Enhancements Merged
Faster Pip-Boy Animation
FOV Slider
Consistent Pip-Boy Icons - Hunting Revolver Iron Sights Patch
Laser Weapon Iron Sights
Quick Grenade Hotkey
Quick Grenade Hotkey Tweaks
Simple DLC Delay
Hunting Revolver Iron Sights
Stars Turned Face Up
B42 Melee Bash
Enhanced Vision
Faction Warning and Reputation Tweaks
Follower Tweaks
Jamming Fix and Optional Tweaks
JAM - Just Assorted Mods
JAM Animation Replacers
Enhanced Vision
Follower Formula Redone
Follower Formula Redone ESP Replacer
Less Map Markers
Less Map Markers ESP Replacer
Melee Cleave (a.k.a. Sweep)
Misc Gameplay Merge
Misc Gameplay Merge ESM Replacer
Miscellaneous Tweaks Collection
Miscellaneous Tweaks Collection Tweaks
No Stealing After Repair
NPCs Sprint In Combat
NPCs Use Aid Items
RAD - Radiation (is) Actually Dangerous
RAD - Radiation (is) Actually Dangerous - Overhaul
Reload Reloaded
Simple Explosive Entry
Standarized NCR Supply Caches - Scaler Moon Edition
Thrown Weapon Tweaks
JSawyer Ultimate Edition
JSawyer Ultimate Edition Tweaks and Patches
Mojave Arsenal
JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)
Mojave Arsenal Patches
Misc Gameplay Merge - JSawyer Ultimate Edition Patch
Famine - A Loot Rarity Mod
New Vegas Economy Improved
Player Combat Priority
Repair Tools
Improved Traits and Opposite Traits
Better Character Creation
Anatomic Perks
Cannibal Reborn
Cannibal Reborn Expanded
Consistent Pip-Boy Icons Mod Patches
Uncut Wasteland
Uncut Wasteland Tweaks
The Strip NPCs Uncut - Content Restoration
Mojave Raiders
JSawyer Ultimate - Mojave Raiders Patch
Khans Friendly to Fiends
Khans Friendly to Fiends Patches
Mojave Wildlife - Vanilla No Chanced Spawns Version
Canvas Backpacks - Remade
Canvas Backpacks - Remade Tweaks
All Weapon Sounds Overhaul
All Weapon Sounds Overhaul ESP Replacer
All Weapon Sounds Overhaul WMIM Patch
All Explosion Sounds Overhaul
All Explosion Sounds Overhaul SCRIPT Version
Immersive Primary Needs
Female Nuka-Cola Drinking Sound Replacer
Anniversary Anim Pack
Anniversary Anim Pack - General Bugfix
FNV Clean Animations
Immersive Recoil
Viewmodel Recoil
B42 Weapon Inertia
Ragdolls
Ragdolls Patches
Chill Companions
Diagonal Movement
360 Movement
Player Headtracking
NV Compatibility Skeleton
Character Expansions Revised
Character Expansions Revised - Additional Patches
FaceGen Tint Fixes for Character Expansions Revised
Helmet Overlay
Worn-Out Scope Crosshair Replacers
No Pip-Boy Glove
Pip-Boy 2000 Mk VI
Pip-Boy 2000 Mk VI Working Buttons
Pip-Boy 2000 Mk VI (Wasteland Edition) Retexture
NPC Arm Mounted Pip-Boy 2000 Mk VI (Pluginless)
IMPACT
IMPACT - Compatibility Edition
EXE - Effect teXtures Enhanced
Enhanced Blood Textures
Gore Overhaul
Gore Overhaul Optimized
A Little More Lamplight
A Little More Lamplight ESP Replacer
LSO - A Lightweight Strip Overhaul
Lightweight Strip Overhaul - Uncut Wasteland Patch
Strip Lighting Overhaul
Strip Lighting Overhaul LSO Patch
Wasteland Flora and Terrain Overhaul
Windows of the Mojave
FNV Realistic Wasteland Lighting - All DLC
FNV Realistic Wasteland Lighting - All DLC ESP Replacer
Mojave Nights
Night Sky Tweaks
Subtle Light Beams and Rays
Improved LOD Noise Texture
FNVLODGen Resources
LOD Additions and Improvements
LOD Additions and Improvements ESP Replacer
FNV LOD Supplementation
Better Strip View
Better Strip View More Subtle New Vegas Light Pollution Patch
TCM's LOD Overhaul
Hoover Dam Jets Restored and Distant
Strip Lights Region Fix
Mormon Fort Region Fix
Lucky 38 Lights Redone
More Subtle New Vegas Light Pollution (Slightly Brighter)
FNV RWL All DLC - Worldspace Patch
FNV Custom INIs
```
</details>

The load order dictates the priority a given mod's plugins have over the mods' plugins loaded before them. Respect this order to ensure plugin records are overridden as intended.

<details>
<summary>Load order</summary>

```
FalloutNV.esm
DeadMoney.esm
HonestHearts.esm
OldWorldBlues.esm
LonesomeRoad.esm
GunRunnersArsenal.esm
ClassicPack.esm
MercenaryPack.esm
TribalPack.esm
CaravanPack.esm
YUP - Base Game + ALL DLC.esm
Landscape Disposition Fix.esm
Navmesh Fixes and Improvements.esm
Misc Gameplay Merge.esm
Ragdolls.esm
Character Expansions Revised.esm
Lightweight Strip Overhaul.esm
Helmet Overlay.esm
YUP - NPC Fixes (Base Game + All DLC).esp
Unofficial Patch NVSE Plus.esp
MigMultiCase.esp
AmmoScriptFixes.esp
CriticalEffectFixes.esp
MigGaussFix.esp
MigKao.esp
ThrowableFixes.esp
PyromaniacEffectsBuff.esp
WMIMNV.esp
LessFlickeryCityOfNewVegas.esp
The Mod Configuration Menu.esp
Vanilla UI Plus.esp
JIP Improved Recipe Menu.esp
DLC Enhancements.esp
FOVSlider.esp
LaserWeaponIronSights.esp
PlasmaWeaponIronSights.esp
Quick Grenade Hotkey.esp
Simple DLC Delay.esp
Hunting Revolver Iron Sights.esp
Stars Turned Face Up.esp
Enhanced Vision.esp
Faction Warning and Reputation Tweaks.esp
Follower Formula Redone.esp
Follower Tweaks.esp
JamFix.esp
JustAssortedMods.esp
Less Map Markers.esp
MeleeCleave.esp
Miscellaneous Tweaks.esp
Miscellaneous Tweaks... Tweaks.esp
NPCsSprint.esp
NPC Use Aid.esp
RAD.esp
Reload Reloaded.esp
Simple Explosive Entry.esp
Patchy's Preferred Preparedness Package - Scaler Moon Edition.esp
Thrown Weapon Tweaks.esp
JSawyer Ultimate.esp
JSawyer Ultimate - Push's Tweaks.esp
JSawyer Ultimate - Push's Tweaks - Miscellaneous Tweaks Patch.esp
JSawyer Ultimate Tweaks.esp
Mojave Arsenal.esp
JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged).esp
JSawyer Ultimate - Mojave Arsenal Patch - Hunting Revolver Iron Sights Patch.esp
JSawyer Ultimate - Mojave Arsenal Patch - Miscellaneous Tweaks Patch.esp
JSawyer Ultimate - Push's Tweaks - Mojave Arsenal Patch.esp
Misc Gameplay Merge - JSUE Patch.esp
Famine.esp
NV Economy Improved.esp
Player Combat Priority.esp
Repair Tools.esp
Repair Tools - JSU (Push's Tweaks) Patch.esp
FNVOppositeTraits.esp
Improved Traits.esp
Improved FNVOppositeTraits.esp
Improved Traits and FNVOppositeTraits JSUE Patch.esp
Better Character Creation.esp
MigAnatomy.esp
Cannibal Reborn.esp
Cannibal Reborn Expanded.esp
Uncut Wasteland.esp
Uncut Wasteland pole remover.esp
Uncut Wasteland Tweaks.esp
Lightweight Strip Overhaul - Uncut Wasteland Patch.esp
Uncut Strip NPCs.esp
Mojave Raiders.esp
JSawyer Ultimate - Mojave Raiders Patch.esp
Mojave Wildlife (Vanilla-Style + No Chanced).esp
QwibNewBackpacks.esp
QwibNewBackpacks Tweaks JSUE.esp
All Weapon Sounds Overhaul .esp
All Weapon Sounds Overhaul WMIM Patch.esp
Explosive Sounds Overhaul.esp
Immersive Primary Needs.esp
rockbiter_AnimationSounds.esp
ImmersiveRecoil.esp
VM_Recoil.esp
B42Inertia.esp
Ragdolls - YUP Patch.esp
Ragdolls - DLC Enhancements Patch.esp
Chill Companions.esp
Diagonal movement.esp
360Movement.esp
360Movement - Diagonal movement Patch.esp
Player Headtracking.esp
Character Expansions Revised - Complete.esp
MCPipBoy2000MK6_clock.esp
dD - Enhanced Blood Main NV.esp
IMPACT.esp
Little More Lamplight.esp
Strip Lighting Overhaul.esp
Strip Lighting Overhaul LSO Patch.esp
Windows of the Mojave v1.2.1.esp
vegasglow.esp
Better Strip View.esp
Better Strip View vegasglow Patch.esp
Distant Water Jets.esp
Strip Lights Region Fix.esp
Strip Lights Region Fix - Uncut Wasteland.esp
Strip Lights Region Fix - Distant Water Jets.esp
Mormon Fort Region Fix.esp
Lucky 38 Lights Redone.esp
Mormon Fort Region Fix - Lucky 38 Lights Redone.esp
FNV Realistic Wasteland Lighting - All DLC.esp
FNV RWL All DLC - Worldspace Patch.esp
Mojave Nights.esp
FNVLODGen.esp
tmzLODadditions.esp
```
</details>

### Generating LOD

With all our mods and resources installed, we can finally generate our LOD.

- Run **FNVLODGen** in MO2.
- Right click on the list of worldspaces, and click **Select All**. Uncheck **FreesideFortWorld "Old Mormon Fort"**.
- Click **Generate**. The process will take some time.
- After the **LOD Generator: finished (you can close this application now)** message appears, close the program.

> ⚠️ Having too many LOD mods installed can cause **FNVLODGen** to fail at generating LOD appropriately. At the moment, the only scenario where I've found this to happen is at the Old Mormon Fort. Hence why are generating its LOD separate from the rest of the worldspaces.

- Now disable the following mods:
  - **LOD Additions and Improvements**
  - **LOD Additions and Improvements YUP ESP Replacer**
  - **FNV LOD Supplementation**
  - **TCM's LOD Overhaul**
- Run **FNVLODGen** in MO2.
- Right click on the list of worldspaces, and click **Select None**. Check **FreesideFortWorld "Old Mormon Fort"**.
- Click **Generate**. The process will take some time.
- After the **LOD Generator: finished (you can close this application now)** message appears, close the program.

> ⚠️ Remember to re-enable the disabled LOD mods.

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

**Enhanced Vision**:
- Set **Vision mode hotkey** to **N**.

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

**Mojave Arsenal Custom INI (Optional)**:
- Double-click the installed mod to open the **Information...** window.
- Click the **INI Files** tab, and make the following adjustments in **Mojave Arsenal.ini**.
- Click on the diskette icon to save your changes.

```
bLowConditionLoot=0
```

> ℹ️ Disables the Low Condition Loot feature, in favor of **Famine - A Loot Rarity Mod**'s own implementation.

**falloutcustom.ini (Optional)**:
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Paste the following into **falloutcustom.ini**.

```
[Display]
bAllowScreenShot=0

[Imagespace]
bDoDepthOfField=0

[Interface]
fDlgFocus=6.0000
uPipboyColor=1022886143
```

> ℹ️ Disables the built-in screenshot feature in favor of SweetFX's (which will account for its post-processing effects); disables vanilla depth of field effect seen during dialogue; reduces the amount of zoom when engaging in dialogue; tweaks the Pip-Boy HUD color to match that of classic Fallout.

**SweetFX (Optional)**:
- Open **Fallout New Vegas\SweetFX\SweetFX_settings.txt** using a text editor and make the following adjustments.

```
USE_VIBRANCE = 1
USE_CURVES = 1
```

> ℹ️ Restores the SweetFX preset to RWLE's original configuration.

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
X | Melee weapon bash | B42 Melee Bash
N | Enable enhanced vision/scroll through vision modes | Enhanced Vision
H | Open weapon wheel | Just Assorted Mods
V | Enable bullet time | Just Assorted Mods
Shift+Movement | Sprint | Just Assorted Mods

# CHANGELOG

- 🆕 Mod has been added to the guide.
- ⚠️ Mod has been updated or its installation/configuration instructions have changed.
- 🚫 Mod has been removed from the guide.

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)

