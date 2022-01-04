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

> ℹ️ This mod is a modern alternative to [**New Vegas Stutter Remover**](https://www.nexusmods.com/newvegas/mods/34832).

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Extension of the New Vegas Script Extender which adds new functions, engine bug fixes and tweaks, and restored broken game features.
- Download the main file using the **Mod Manager Download** option.
- Install this mod in Mod Organizer 2.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Extension of the New Vegas Script Extender which adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**ShowOff NVSE Plugin**](https://github.com/Demorome/Showoff-NVSE/releases)  
Extension of the New Vegas Script Extender which adds new functions, engine bug fixes and tweaks.
- Click the **ShowOffNVSE.7z** under **Assets** to download it.
- Install manually in Mod Organizer 2.
 
[**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336)  
Extension of the New Vegas Script Extender which enables having custom animations for weapons and actors. Also fixes the engine-bound anim group limit problem.

[**NVAC - New Vegas Anti Crash**](https://www.nexusmods.com/newvegas/mods/53635)  
Extension of the New Vegas Script Extender that implements structured exception handling and sanity checking to reduce frequency of game crashes.

[**OneTweak**](https://www.nexusmods.com/skyrim/mods/40706)  
Extension of the New Vegas Script Extender that enables borderless window mode for safe alt-tabbing.
- Manually download the **OneTweak** main file.
- Extract the contents of the archive. Renamed the **SKSE** folder to **NVSE**, and merge the folder with your **Fallout New Vegas\Data\NVSE** folder.
- Launch Mod Organizer 2.
- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Select the **FalloutCustom.ini** tab.
- Set **bFull Screen** to 0.

[**NVTF - New Vegas Tick Fix**](https://www.nexusmods.com/newvegas/mods/66537)  
Extension of the New Vegas Script Extender that fixes the tick count bug (which creates noticable micro stutter), optimizes hash tables (helping performance and decreasing menu load times), and fixes the high FPS bug (fixing physics and lipsync at high framerates).

Additional files to install:
- [**NVTF Custom INI**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/NVTF%20Custom%20INI.7z). Enables a number of settings to achieve the best balance between performance and stability. Made by **Qolore**.

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Extension of the New Vegas Script Extender that allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).

[**Improved lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Extension of the New Vegas Script Extender that almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.

[**Console Paste Support**](https://www.nexusmods.com/newvegas/mods/65906)  
Extension of the New Vegas Script Extender that enables hotkeys for pasting and enhanced movement/deletion.

## PATCHES

### Bug fixes

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
Collection of bug fixes for Fallout: New Vegas and its DLCs, combined into one ESM.
- Install **YUP - Base Game and All DLC** (Main files).

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.
- Install **Navmesh Fixes and Improvements - Base Game and ALL DLC** (Main files).

### NVSE bug fixes

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bug fixes for Fallout: New Vegas and its DLCs which require NVSE.

[**lStewieAl's Tweaks**](https://www.nexusmods.com/newvegas/mods/66347)  
Engine bugfixes, optional tweaks and new features with no performance impact. Fully customisable via in-game menu and INIs.

Additional files to install:
- [**lStewieAl's Tweaks Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/lStewieAl's%20Tweaks%20Custom%20INI%20(Jan%203rd).7z). Enables many quality of life improvements, as well as gameplay and balance tweaks.
- Major gameplay tweaks include:
  - Capping of level up menu max skill values based on SPECIAL. At a SPECIAL value of 1, a skill is capped to 55.
  - Vendors obey their Buy/Sell flags, restricting which items they accept. Meant to be used alongside **Misc Gameplay Merge** (Gameplay section).
  - Increased XP for discovering locations. Meant to be used alongside **Less Map Markers** (Overhauls section).
  - Binoculars can zoom in and out.
  - Holding the attack button for grenades decreases their detonation timer.
  - Throwables can be held and released, like grenades.
  - Entering VATS costs AP.
  - Opening Pip-Boy in combat costs AP.
  - Living Anatomy perk shows Damage Resistance.
  - Unconscious actors can be looted.
  - Manual reloading.
  - VATS' range is tied to current weapon's range.
  - Slower backpedalling.
  - Owned items can't be grabbed and moved around.
  - Skill level requirement for skill checks is hidden.
  - Dialogue topics are numbered.
  - Pickpocket formula takes into account item weight, target Perception, and detection value.
  - Agility affects reload jams.
  - Repairing items gives XP.
  - Robotic companions heal with Scrap Metal instead of Stimpaks.
  - Sneak attack critical hits can only be dealt with melee weapons.
  - Broken armor is automatically unequipped.
  - Weapon mods can be unequipped.

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Ammo Script Fixes**](https://www.nexusmods.com/newvegas/mods/63997)  
Fixes several problems at the core level with how ammo scripts and effects work, plus some tweaks for consistency and fun.

[**Critical and Effects - Fixes and Tweaks**](https://www.nexusmods.com/newvegas/mods/69200)  
Fixes the damage dealing critical effects of most vanilla weapons so that they cannot cause you to miss "killcounts" and other proc effects such as crime responsibility.

[**Crippled Limb Reaction Enforcer**](https://www.nexusmods.com/newvegas/mods/73147)  
Makes the idle animations for crippled limbs come through in situations where the game cannot pick them correctly like when the damage comes from an explosion. Also makes NPCs get some more debuffs from crippling like the player does.

[**Gauss Rifle VATS Fix - JIP**](https://www.nexusmods.com/newvegas/mods/69136)  
Fixes the Gauss Rifle not dealing headshot and critical damage in VATS.

[**Universal Pyromaniac Buff for Fire Effects**](https://www.nexusmods.com/newvegas/mods/71505)  
Makes the Pyromaniac perk affect *all* the lingering fire damage effects from weapons and ammo.

### Mesh fixes and optimization

[**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLC.

[**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.

Additional files to install:
- [**WMIM ESP Replacer**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/WMIM%20ESP%20Replacer.7z). Removes unnecessary, non-bugfix edits. Made by **Qolore**.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
A collection of visual and audio fixes and tweaks for throwable weapons, focused on projectiles.

[**Dirty Pre-War Businesswear Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Dirty%20Pre-War%20Businesswear%20Fix%201.0.7z)  
Fixes the Dirty Pre-War Businesswear having the incorrect texture.
- BAIN options to install:
  - [X] 00 Core
  - [X] 01 Vanilla

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.
- Install **Female White Glove Society Mask** (Main files).

[**Less Flickery City of New Vegas**](https://www.nexusmods.com/newvegas/mods/72061)  
Fixes the intense flickering in the city of New Vegas (such as when looking from Goodsprings Cemetery) due to extra white proxy meshes clipping into the object LOD meshes.

[**No More Dust Devils (and Whirlwinds)**](https://www.nexusmods.com/newvegas/mods/74167)  
Improves game performance by removing all the dust devils and whirlwinds from the game (and any DLC/mod that might use them). Optionally removes tumbleweeds too.

[**No More Muzzle Flash Lights**](https://www.nexusmods.com/newvegas/mods/73742)  
Improves game performance in combat by disabling lights cast on the environment by player and enemy muzzle flashes.

> ℹ️ For an alternative mod that disables enemy muzzle flashes only, check out [**No Muzzle Flash Lights**](https://c6-dev.github.io/mods/no_muzzle_flash_lights/).

## USER INTERFACE

### Menus

[**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.

Additional files to install:
- **MCM BugFix 2** (Optional files).

[**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- FOMOD options to install:
  - [X] Default Font Tweaks
  - [X] Plugin
  - [X] WASD Compatible 

> ℹ️ The **Classic Pip-Boy Font** option includes the **Default Font Tweaks** option, and is a matter of preference. I personally use it alongside a tweaked Pip-Boy color for that classic Fallout feel (this tweak is present in the **INI Config** section.

[**Vanilla HUD Cleaned**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- FOMOD options to install:
  - All **Modules** and **Tweaks** options.
  - Skip the **DarnUI Specific** options.

[**Clean Companion Wheel**](https://www.nexusmods.com/newvegas/mods/70486)  
Cleans up textures surrounding the Companion Wheel.
- Install **Clean Companion Wheel 256x256 Edition** (Main files).

[**JIP Improved Recipe Menu**](https://www.nexusmods.com/newvegas/mods/59638)  
Makes the crafting interface easier, more efficient and less tedious to use. 

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.
- Install **Satellite World Map** (Main files).

Additional files to install:
- [**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292). High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and  Lonesome Road.

### Icons

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Lore-friendly overhaul of New Vegas icons to make them more consistent in terms of coloring and transparency. Includes other bug fixes.
- Install **1. Consistent Pip-boy Icons**  (Main files).

Additional files to install:
- **2. Consistent Addon Icons** (Main files). **Merge** with the main file.
  - FOMOD options to install:
    - [X] Interfaceshared0 Addon
- **3. Consistent Glow Icons** (Main files). **Merge** with the main file.
  - FOMOD options to install:
    - [X] Main File
- **6. Vanilla UI Plus Patch** (Optional files). **Merge** with the main file.
- [**Vanilla HD Missing Icon for Consistent Pip Boy Icons**](https://www.nexusmods.com/newvegas/mods/73375). Replaces the farting vault boy with an upscaled HD version of the vanilla missing item icon.

## GAMEPLAY QOL

[**Ending Slideshows Ultimate Edition Overhaul**](https://www.nexusmods.com/newvegas/mods/74595)  
Merges the DLC ending slideshows with the main game's ending slideshow for one complete "Ultimate Edition" package. Updates the vanilla slideshow to the standards later adopted in the DLC.

[**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.
- Install **Faster Pip-Boy Animation (2x)** (Main files).

[**Laser Weapon Iron Sights**](https://www.nexusmods.com/newvegas/mods/70790)  
Adds iron sights to a variety of laser and plasma weapons which lacked any.
- Install **Laser Weapon Iron Sights - Gun Runner's Arsenal Merged** and **Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged** (Main files). **Merge** both main files.

Additional files to install:
- **Laser Weapon Iron Sights - Iron Sight Recoil Animations** (Optional files). **Merge** with the main file.
- **Plasma Weapon Iron Sights - Iron Sight Recoil Animations** (Optional files). **Merge** with the main file.

[**Motion Sickness Destroyer**](https://www.nexusmods.com/newvegas/mods/65732)  
Removes all motion blur, double vision, and other nasty nauseous effects from Imagespaces and Imagespace Modifers. Compatible with every single mod.

[**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874)  
Adds a hotkey to automatically select the currently selected grenade/mine, as well as a hotkey to scroll through your available grenades/mines. Read the description for instructions on how these features work.

Additional files to install:
- [**Quick Grenade Hotkey Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Quick%20Grenade%20Hotkey%20Tweaks.7z). Adjusts the positioning of the grenade/mine icon to not overlap with other UI elements, and removes the unnecessary "no grenade/mine" icon. Made by **Qolore**.

[**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

[**Snowglobe Tweaks Fix**](https://www.nexusmods.com/newvegas/mods/67466)  
Requires the player to discover the snow globe display in the Lucky 38 Presidental Suite before being able to sell the snow globes to Jane. DLC snow globes now need to be sold to Jane, and the Dead Money snow globe rewards 2,000 caps instead of 2,000 Sierra Madre chips.

## GAMEPLAY

### Tweaks

[**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

[**Faction Warning and Reputation Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Faction%20Warning%20and%20Reputation%20Tweaks.7z)  
Replaces the faction armor warning pop-ups with corner messages, and lowers reputation penalties for crimes. Based off [**Simple Reputation and Disguises**](https://www.nexusmods.com/newvegas/mods/62183) by **PushTheWinButton**.

[**Follower Formula Redone YUP**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Follower%20Formula%20Redone%201.4%20YUP.7z)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most. 

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/71490) to original mod by **Qolore**, edited to include YUP fixes.

[**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving.

[**Jamming Fix and Optional Tweaks**](https://www.nexusmods.com/newvegas/mods/66293)  
Fixes the on-fire jamming for automatic weapons and adds an option for how often weapons jam.

[**Less Map Markers YUP**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Less%20Map%20Markers%201.0%20YUP.7z)  
Removes some map markers in an attempt to make exploration more interesting.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/73472) to original mod by **Nehred**, edited to include YUP fixes.

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods by various authors, all fully fixed, optimized, and updated by **Qolore**, ranging from quality of life improvements, gameplay tweaks, and visual tweaks.

Additional files to install:
- **Misc Gameplay Merge JSawyer Ultimate Edition Patch** (Optional files).
- [**Misc Gameplay Merge YUP ESM Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Misc%20Gameplay%20Merge%201.7%20YUP%20ESM%20Replacer.7z). 

[**Mine and Explosion Tweaks**](https://www.nexusmods.com/newvegas/mods/71730)  
Allows mines to be triggered by flying NPCs if close enough to them; makes EMP mines triggerable only by robots and Power Armored NPCs; causes mines to detonate instantly if directly stepped on; makes lingering effects from explosions (such as fire) continue to cause damage if an actor walks by them.

[**Mostly Unarmed Tweaks**](https://www.nexusmods.com/newvegas/mods/69283)  
Fixes the fatigue-dealing weapons to deal correct and damage-adjusted fatigue to enemies and the player; tweaks the effects of Unarmed special attacks; allows NPCs to use Unarmed special attacks.

[**Rigged Shotgun Restoration (with Dead Money support)**](https://www.nexusmods.com/newvegas/mods/66863)  
Restores Fallout 3's rigged shotgun functionality: disarming a rigged shotgun earns you a single shotgun and a 20 gauge shell.
- Install **Rigged Shotgun Restoration - Lore-Friendly** (Main files).

[**Well Rested Overhaul YUP**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Well%20Rested%20Overhaul%201.0%20YUP.7z)  
Expands how the Well Rested effect works. Effect duration is now in actual game hours, gives a few more buffs aside from increased XP, and patches all the game prostitutes' scripts to also grant the buff for purchasing their services.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/64628) to original mod by **miguick**, edited to include YUP fixes.

[**Lobotomite Tweaks**](https://www.nexusmods.com/newvegas/mods/61706)  
Makes the Old World Blues Lobotomites more challenging by equiparating their traits with those of a freshly operated player.

### Features and mechanics

[**Alternative Repairing**](https://www.nexusmods.com/newvegas/mods/52510)  
Adds Repair Tools, required to perform repairs, and repair parts for you to craft and buy, giving you alternate methods of repairing equipment.

Additional files to install:
- [**Alternative Repairing Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Alternative%20Repairing%20Tweaks.7z). Forwards **Yukichigai Unofficial Patch** fixes, including extending the Weapon Repair Kit sound fix to all new Kits; custom INI adds a prefix to parts, disables weapon and armor degradation tweaks, and lowers threshold at which apparel is considered clothing.

> ℹ️ For an alternative mod that only features the Repair Tools mechanic, check out [**Repair Tools**](https://www.nexusmods.com/newvegas/mods/74884?).

[**B42 Inspect**](https://www.nexusmods.com/newvegas/mods/71624)  
Adds a fully animated ammunition and weapon condition checking system to the game, complete with scratch made animations and a custom HUD element. The ammo check HUD displays the name of the weapon, the ammo type you're using, the rounds left in your current mag and how much ammo you have left in total. Condition checking HUD simply shows you weapons condition.

[**B42 Melee Bash**](https://www.nexusmods.com/newvegas/mods/68055)  
Adds melee attacks for non-melee weapons.

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

Additional files to install:
- [**JAM - Just Assorted Mods Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JAM%20-%20Just%20Assorted%20Mods%20Custom%20INI%20(Dec%2014th).7z). Disables Visual Objectives, Hold Breath, and Bullet Time. Sets 1st Person Mode crosshair to dynamic and 1st Sighting Mode to none. Reduces Sprint speed.

> ℹ️ For detailed instructions on how the **Weapon Wheel** feature works, [**see here**](https://www.nexusmods.com/newvegas/mods/67460).

[**Immersive Fast Travel Requirements**](https://www.nexusmods.com/newvegas/mods/73627)  
Makes fast travel cost one Purified Water and one of either a Trail Mix or Caravan Lunch, with a perk to lower/remove the requirement. Trail Mixes and Caravan Lunches have also been added to vendor inventories.

[**Melee Cleave (a.k.a. Sweep)**](https://www.nexusmods.com/newvegas/mods/66187)  
Makes melee attacks hit multiple enemies.

> ℹ️ For an alternative mod that restricts this feature to a Perk, check out [**Melee Cleave (a.k.a. Sweep) but as a Perk**](https://www.nexusmods.com/newvegas/mods/74703).

[**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

[**Precise VATS (and actually useful Perception)**](https://www.nexusmods.com/newvegas/mods/69202)  
Requires the player's crosshair to be aiming at the target in order to activate VATS, namd makes the VATS activation range and target switching distance to be dynamic and dependent on a few factors, including Perception level, weapon scope, Enhanced Sensors and Spotter Perks, and Power Armor.

[**RAD - Radiation (is) Actually Dangerous**](https://www.nexusmods.com/newvegas/mods/61343)  
Makes radiation work like in Fallout 4, by damaging your max health.

Additional files to install:
- [**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541). Rewrites the entire UI portion and makes major changes to the script, including rebalancing and bugfixes.

[**Simple Explosive Entry**](https://www.nexusmods.com/newvegas/mods/66992)  
Allows the player to use explosives to bypass locks. Items have a chance of being destroyed, with the exception of notes and quest items.

## OVERHAULS

### Balance

[**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of [**jsawyer.esp**](https://fallout-archive.fandom.com/wiki/JSawyer), made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.

Additional files to install:
- **JSawyer Ultimate Edition - Push's Tweaks** (Optional files). INI config and collection of minor tweaks, partly inspired by the harder pre-patch balance of the game. **Merge** with the main file.
- [**JSawyer Ultimate Edition - Qolore's Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20-%20Qolore's%20Tweaks.7z). Disables the new Wasteland Merchant and Deranged Bright Brotherhood members, and tweaks Bright Brotherhood loot. Made by **Qolore**.
- [**JSawyer Ultimate Edition - Vanilla-ish Companion Suite**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20-%20Vanilla-ish%20Companion%20Suite.7z). Removes **JSUE**-exclusive nerfs to companions, and decreases carry weight for companions as in the original mod.
- [**JSawyer Ultimate Edition Fixes**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/JSawyer%20Ultimate%20Edition%20Fixes%20(Dec%2021).7z). Includes patches for **Yukichigai Unofficial Patch**, **Weapon Mesh Improvement Mod**, and **Throwable Weapon Fixes**.
  - BAIN options to install:
    - [X] AIO Fixes
  - Hide **Female White Glove Society.esp**. This collection already includes it.

> ℹ️ It is recommended that you play New Vegas at **Hard** difficulty or lower.

[**Miscellaneous Tweaks Collection Tweaked**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Miscellaneous%20Tweaks%20Collection%20Tweaked%202.5.7z)  
Collection of gameplay and balance tweaks.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/71847) to original mod by **Qolore**, edited to remove conflicting edits with **Mojave Arsenal** and **Mojave Raiders**, revert health and melee damage buffs to Feral Ghoul Reavers, and remove most map markers added for consistency with **Less Map Markers**.

[**Mojave Arsenal**](https://www.nexusmods.com/newvegas/mods/62941)  
Adds ammo variants, reloading parts, and weapon mods as loot, fixes item naming conventions, improves recipes, and adds options for configuring Gun Runners' Arsenal.

Additional files to install:
- [**JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)**](https://www.nexusmods.com/newvegas/mods/62933). Ensures that JSawyer Ultimate's new junk rounds adhere to Mojave Arsenal's naming convention, and merges edits to a single toolbox leveled list. Additionally merges all GRA weapon mods onto vanilla weapons, disabling their GRA weapon variants, and integrates the new GRA weapons and mods into vanilla vendor lists.

[**New Vegas Economy Improved**](https://www.nexusmods.com/newvegas/mods/71604)  
Fully-scripted, lightweight, and compatible item value overhaul, taking into consideration important aspects of the vanilla economy balance. Applies a moderate reduction in value to high-value items, and a small reduction to low-value items.
- Install **New Vegas Economy Improved** (Main files).

[**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Prevents the game from becoming too easy by making enemies more likely to target the player in combat rather than companions.

[**Thrown Weapon Tweaks**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Thrown%20Weapon%20Tweaks%20(Dec%2022nd).7z)  
NPCs no longer consume thrown weapons. Throwing Hatchet's damage was reduced to its **Old World Blues** stats.

[**Unfound Loot**](https://eddoursul.win/mods/unfound-loot/)  
Dynamically lowers the amount of loot in the game.
- Install the **Unfound Loot 1.0rc2** main file located at the bottom of the page.

Additional files to install:
- [**Unfound Loot Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Unfound%20Loot%20Custom%20INI%201.0.3.7z). Reduces loot scarcity, and heightens the impact Luck has on it.

[**Consistent Pip-Boy Icons Mod Patches**](https://www.nexusmods.com/newvegas/mods/65046)  
Upscales icons from a selection of mods.
- FOMOD options to install:
  - [X] Alternative Repairing
  - [X] B42 Melee Bash
  - [X] Mojave Arsenal

> ℹ️ If you don't mind unnecessary files in your computer which will otherwise have no effect in the game, you can simply install the default options (which include patches for both of these mods).

### Perks and traits

[**Anatomic Perks**](https://www.nexusmods.com/newvegas/mods/65648)  
Distributes the effect from the Living Anatomy perk to see the target's HP and DT, so that specific perks grant this bonus only against specific enemies.
The Here and Now perk now includes the original effects from Living Anatomy. 

[**Meltdown NVSE Upgrade Tweaked**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Meltdown%20NVSE%20Upgrade%201.3.2%20Tweaked.7z)  
Overhauls the Meltdown perk to bring its workings under control and actually work as described.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/65718) to original mod by **miguick**, edited to revert Perk requirements to vanilla, disable the player-only Rampage feature, and disable the companion Meltdown feature.

[**Miss Fortune NVSE Upgrade**](https://www.nexusmods.com/newvegas/mods/64709)  
Makes Miss Fortune's effects more consistent. Will avoid affecting non-hostile targets, can now recognize and detonate all kinds of weapons, but won't detonate them near the player or companions.

[**Improved Traits and Opposite Traits**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Improved%20Traits%20and%20Opposite%20Traits.7z)  
Overhauls vanilla traits, adds two new ones, and expands the idea of opposite traits (present in two vanilla traits) to the game's other traits.
- BAIN options to install:
  - [X] 00 Improved Traits and Opposite Traits
  - [X] 01 JSUE Patch

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/65403) to original mod by **TrueVoidwalker**, edited to fix issues and disable an overpowered trait. 

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/69141) to original mod by **cbgreely**, cleaned.

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

## CONTENT

### Restored content

[**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.
- Install **Uncut Wasteland plus NPCs** (Main files).

Additional files to install:
- **Uncut Wasteland Pole Remover** (Optional files). Removes restored utility poles with glitched animations. **Merge** with the main file.
- [**Uncut Wasteland Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Uncut%20Wasteland%20Tweaks.7z). Forwards **YUP** fixes, omits the NPC restorations at the Ultra-Luxe Bathhouse, and replaces static Destitute Travelers with leveled, random NPCs. Made by **Qolore**.

### Enemies

[**Mojave Raiders**](https://www.nexusmods.com/newvegas/mods/64660)  
Overhaul of New Vegas's raider factions, balancing their loot and adding more of them to fight.

Additional files to install:
- [**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933). Overrides **JSUE**'s edits to Raider/Fiend leveled lists, and ensures that raiders spawn with .22LR rounds when using Varmint Rifles.

[**Mojave Wildlife**](https://www.nexusmods.com/newvegas/mods/64638)  
Adds hundreds more leveled, vanilla-friendly creature spawn points throughout the whole Mojave, based off unused vanilla leveled lists. All spawn points are meticulously hand-placed and distributed as evenly and fairly as possible.
- Install **Mojave Wildlife - Vanilla No Chanced Spawns Version** (Main files).

## VISUALS

### Animations

[**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of Hitman47101's [**Subtle Camera Motion**](https://www.nexusmods.com/newvegas/mods/67728), [**Iron Sights Recoil Animations**](https://www.nexusmods.com/newvegas/mods/67760), [**Fire Animation Variants**](https://www.nexusmods.com/newvegas/mods/67841), as well as new, previously unreleased animations.

Additional files to install:
- [**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320). Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person.
  - Install **AnniAnimPack_BugFix 1.3** (Main files).
  - Install **Bonus Patch** (Main files). **Merge** into the other main file.

[**Diagonal Movement**](https://www.nexusmods.com/newvegas/mods/64333)  
Adds proper diagonal movement animations.

[**360 Movement**](https://www.nexusmods.com/newvegas/mods/71940)  
Adds 360 degrees movement with procedural leaning and auto vanity mode, like modern Bethesda games.
- FOMOD options to install:
  - [X] Full 360 Sneak Options
  - [X] Diagonal Movement Patch

[**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

[**Viewmodel Recoil**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

[**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

[**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A skeleton with compatibility for the latest mods.
- Install the default FOMOD options.

[**Companions Combat-Ready**](https://www.nexusmods.com/newvegas/mods/66391)  
Companions ready their weapons when you do.

[**Empty Weapons**](https://www.nexusmods.com/newvegas/mods/67245)  
Slides stay locked back on empty handguns.

[**Tweaked Standing Idle**](https://www.nexusmods.com/newvegas/mods/42662)  
Straightens out the backs and shoulders of NPCs, and also relaxes the right hand for NPCs wearing power armor. 

Additional files to install:
- [**Tweaked Standing Idle Fix**](https://www.nexusmods.com/newvegas/mods/57041). Enables Headtracking and face animations.

### Camera

[**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

Additional files to install:
- [**FOV Slider Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FOV%20Slider%20Custom%20INI%201.0.3.7z). Increases field of view. Recommended to be used alongside **Pip-Boy 2000 Mk VI**, which we will install next.

### Creatures and NPCs

[**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 

Additional files to install:
- **Character Expansions Revised - YUP** (Optional files). **Merge** with the main file.
- **Character Expansions Revised - JSU** (Optional files). **Merge** with the main file.
- **Character Expansions Revised - UW** (Optional files). **Merge** with the main file.
- **Character Expansions Revised - MR** (Optional files). **Merge** with the main file.
- [**Character Expansions Revised - AIO Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Character%20Expansions%20Revised%20-%20AIO%20Patch.7z). Ensures compatibility between all of the above patches.

[**FaceGen Tint Fixes for Character Expansions Revised**](https://drive.google.com/file/d/1OzY-_zi3RfVkIMvaQJvb-3DZc9AhGH9H/view?usp=sharing)  
Fixes colored tints on character faces. Meant to be used alongside **Character Expansions Revised**. 
- [**Visual comparison.**](https://imgsli.com/ODY2MzE)

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/71577?) to original mod by **BobG123**, whose fixed meshes were used as a resource for this mod.

[**Alsatian NCR Guard Dogs**](https://www.nexusmods.com/newvegas/mods/39232/)  
Replaces the vanilla NCR vicious dogs with German Shepard models.

[**Bighorner Model Variants Merged**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Bighorner%20Model%20Variants%20Merged.7z)  
Implements bighorner resources by **CIB**, so that there's now a visual difference between bighorners, their calfs, and their bulls.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/62672) to original mod by **miguick**, edited to merge ESPs and include YUP fixes.

[**Simple Brahmin Variants Redux**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Simple%20Brahmin%20Variants%20Redux.7z)  
Makes Brahmin look healthier, keeping the vanilla sick variant for specific cases. Brahmin calfs have been made distinct from standard brahmin, and lamps on pack Brahmin emit light during the night.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/58871) to original mod by **Lexx**, edited to include YUP fixes and simplify its implementation, removing horn variations.

[**Healthier Yao Guai Pluginless**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Healthier%20Yao%20Guai%20Pluginless.7z)  
The Yao Guai asset was created for Fallout 3. It looks like a heavily mutated creature, which clashes with Honest Heart's far more healthy and less irradiated enemies. This mod makes Yao Guai blend in better with the other Zoin creatures.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/49707) to original mod by **Sinvence**, edited to make it a pluginless replacer.

[**Y-17 Trauma Override Harness GLOVES**](https://www.nexusmods.com/newvegas/mods/56301)  
Adds gloves to Y-17 Trauma Override Harness, fixing the inconsistency of skeletons being able to move their hands without help.

### Environment

[**Bathroom Doors Overhaul**](https://www.nexusmods.com/newvegas/mods/69486)  
Replaces and adds bathrooms doors all over the Mojave Wasteland. People can finally take a dump in private.
- FOMOD options to install:
  - [X] ALL IN ONE.

Additional files to install:
- [**Bathroom Doors Overhaul YUP ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Bathroom%20Doors%20Overhaul%201.3%20YUP%20ESP%20Replacer.7z). Forwards YUP fixes.

[**Gun Runners Kiosk Glass Fix**](https://www.nexusmods.com/newvegas/mods/70293)  
Fixes Gun Runners' kiosk glass texture. Also adds a window speak thru.
- Only install **Gun Runners Kiosk Glass Fix Alternate Version** (Optional files).

[**Lightweight Strip Overhaul**](https://www.nexusmods.com/newvegas/mods/65665)  
Turns walls from junk to brick, cleans the litter up off of the street, and buffs out the cracked marble and peeling wallpaper as well as much more, making the Strip far more pleasing to the eye.

Files to install:
- **Lightweight Strip Overhaul** (Main files).
- **Lightweight Strip Overhaul - Uncut Wasteland Patch** (Optional files).

[**Palm Tree Replacer**](https://www.nexusmods.com/newvegas/mods/72917)  
Replaces the dated palm trees seen on the Strip with more detailed models.

[**The Strip Planters Fixed**](https://www.nexusmods.com/newvegas/mods/73406)  
Improves the appearance of the Strip planters.

[**Lucky 38 Mainframe No Fingerprints**](https://www.nexusmods.com/newvegas/mods/74055)  
Mesh replacer to remove the huge fingerprint seen on Mr. House's screen.

[**McCarran Escalator Glass**](https://www.nexusmods.com/newvegas/mods/63284)  
Retextures the escalator glass at McCarran so that it isn't as much of an eyesore now.

[**McCarran Main Terminal Transparent Glass**](https://www.nexusmods.com/newvegas/mods/69041)  
Mesh replacer.
- Install **McCarran_Glass_transparency_Vanilla_version** (Main files).

[**Windows of the Mojave**](https://www.nexusmods.com/newvegas/mods/67247)  
Fixes inconsistencies with cell interiors where the buildings had outside windows but no interior windows whatsoever.

Additional files to install:
- [**Windows Redux**](https://www.nexusmods.com/newvegas/mods/70225). Retexture of the window, mainly seen in The Tops if using the Windows of the Mojave mod.

### Equipment

[**Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/65980)  
New Pip-Boy 2000 Mk VI with custom scratch-made meshes, textures and working clock like in Fallout 76.
- Install the **Pip-Boy 2000 Mk VI replacer version** main file.

Additional files to install:
- **Working date and clock for replacer** (Optional files). **Merge** with the main file.
- [**Pip-Boy 2000 MK VI (Wasteland Edition) Retexture**](https://www.nexusmods.com/newvegas/mods/65999). Gives the Pip-Boy 2000 Mk VI a grittier texture.
- [**Pip-Boy 2000 Mk VI Working Buttons**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Pip-Boy%202000%20Mk%20VI%20Working%20Buttons.7z). Makes the Pip-Boy's buttons functional. Made by AleksMarch.
- [**NPC Arm Mounted Pip-Boy 2000 Mk VI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/NPC%20Arm%20Mounted%20Pip-Boy%202000%20Mk%20VI.7z). Makes NPCs wear the new Pip-Boy 2000 Mk VI.

[**No Pip-Boy Glove**](https://www.nexusmods.com/newvegas/mods/69258)  
Removes the completely useless Pip-Boy glove from player and NPCs.
- Install **No Pip-Boy Glove - No ESP** (Main files).

[**Lower-sitting Ranger Hat**](https://www.nexusmods.com/newvegas/mods/68799)  
Modifies the NCR Ranger Hat and Zion Park Ranger Hat so they sit slightly lower on the head.

[**Metal Helmets - Female Replacements**](https://www.nexusmods.com/newvegas/mods/56699)  
Replaces the female Metal Armor helmets with their male counterparts.
- Hide **textures\interface**.

> ℹ️ This hides unnecessary textures that also overwrite those from **Consistent Pip-Boy Icons**.

[**Power Armor Gloves YUP**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Power%20Armor%20Gloves%201.1%20YUP.7z)  
Adds armored gloves to all Power Armors in the game.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/58800) to original mod by **Lexx*, edited to remove unnecessary records and include YUP fixes.

[**Simple Glowing Ranger Visors**](https://www.nexusmods.com/newvegas/mods/66628)  
Makes the visors of all the Ranger Helmets have a glowing effect.
- Install **Simple Glowing Ranger Visors (No Neck Covers)**.

> ℹ️ The **Neck Covers** alternate file makes Ranger Helmets look goofy when worn without Ranger Armor.

[**Worn-Out Scope Crosshair Replacers**](https://www.nexusmods.com/newvegas/mods/43181)  
Replaces the vanilla scopes with worn-out scopes to give them a post-apocalyptic feel.
- Install the **Worn-Out Scopes** main file.

[**Honest Hearts Gecko Leathers Improved**](https://www.nexusmods.com/newvegas/mods/42316)  
Gives Gecko-backed outfits an unique look.
- Only install **Improved Gecko Textures for vanilla bodies** (Optional files).

Additional files to install:
- [**Honest Hearts Gecko Leathers Improved ESP Replacer and JSUE Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Honest%20Hearts%20Gecko%20Leathers%20Improved%20ESP%20Replacer%20and%20JSUE%20Patch.7z). Forwards **YUP** fixes and adds a patch for **JSawyer Ultimate Edition**.
  - BAIN options to install:
    - [X] 00 ESP Replacer
    - [X] 01 JSUE Patch

### VFX

[**Better Gas Leak Effect**](https://www.nexusmods.com/newvegas/mods/55606)  
Makes the gas leak effect much more visible. Accidentally blowing yourself up won't be as common now.

[**Burning Campfire Redone**](https://www.nexusmods.com/newvegas/mods/63623)  
Lights up campfires when activating them.

Additional files to install:
- [**Burning Campfire Redone 2**](https://www.nexusmods.com/newvegas/mods/68181). Improves the original mod and adds support for Honest Hearts' campfires.

[**IMPACT**](https://www.nexusmods.com/newvegas/mods/57113)  
Ballistic VFX overhaul. Bullet holes match ammo, casings match ammo, new custom particle effects impacts.
- Install **IMPACT - The Michael Bay** (Main files).

> ℹ️ My computer can run this version without issues. Check the **Readme** front page to compare your build against mine and decide for yourself which option you'd like to install.

Additional files to install:
- [**IMPACT - Compatibility Edition**](https://www.nexusmods.com/newvegas/mods/62050). Plugin replacer that automatically patches all weapons in the game, DLC, and mods, to have the appropriate shell csings and Impact Data Sets based on their ammo types.

[**EXE - Effect teXtures Enhanced**](https://www.nexusmods.com/newvegas/mods/62989)  
Remakes all visual effects in the game.

[**Enhanced Blood Textures**](https://www.nexusmods.com/newvegas/mods/34917)  
Remakes blood visual effects, including the addition of new types of wounds based on weapon type.

[**HQ Dust Storm FX**](https://www.nexusmods.com/newvegas/mods/53863)  
Retextures dust storms so they aren't as much of an eyesore now.

Additional files to install:
- **Dust Storm Meshes** (Optional files). **Merge** with the main file.

[**HD Mist**](https://www.nexusmods.com/newvegas/mods/58955)  
Retextures mist so that it isn't as much of an eyesore now.
- Only install **HD Mist 2K**.

[**Securitrons in CRT**](https://www.nexusmods.com/newvegas/mods/63258)  
Adds CRT lines to the monitors of Securitrons.

Additional files to install:
- **OWB in CRT** (Optional files). **Merge** in MO2.

### Weather and lighting

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

Additional files to install:
- [**A Little More Lamplight YUP ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/A%20Little%20More%20Lamplight%201.2%20YUP%20ESP%20Replacer.7z). Forwards YUP fixes.

[**Simple Interior Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/71390)  
Simple scripted interior lighting overhaul which darkens interior. Automatically works with any mod.

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

> ⚠️ This mod overwrites **The Strip Planters Fixed**. We will load that mod after this one in the **Mod order** section.

Additional files to install:
- [**Lightweight Strip Overhaul Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Strip%20Lighting%20Overhaul%20LSO%20Patch.7z). Addresses terrain conflicts with **Lightweight Strip Overhaul**.

[**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the exaggerated glow of New Vegas.
- Install **Slightly Brighter** (Main files).

[**Subtle Light Beams and Rays**](https://www.nexusmods.com/newvegas/mods/71613)  
Removes the fake interior light rays and tones the exterior light beams down dramatically. 
- Hide **Subtle Light Beams and Rays.esp**.

> ℹ️ This restores interior light rays.

[**FNV Realistic Wasteland Lighting**](https://www.nexusmods.com/newvegas/mods/52037)  
Complete weather overhaul designed to make the game look more realistic. Improves lighting, weather, clouds, stars, moon and the overall look and feel of the wasteland.
- Install the **FNV Realistic Wasteland Lighting - All DLC** main file.

Additional files to install:
- [**FNV Realistic Wasteland Lighting - All DLC YUP ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FNV%20Realistic%20Wasteland%20Lighting%20-%20All%20DLC%205.542%20YUP%20ESP%20Replacer.7z). Forwards YUP fixes and solves compatibility issues with **DLC Enhancements**.
- [**RWLE - ReShade SweetFX**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/ReShade%20SweetFX%201.1.7z). Original SweetFX preset by **xCamoLegend**.
  - Extract the contents of the archive in your **Root** folder.

> ⚠️ Weather mods such as this one should always load near last your load order. We will address this in the **Mod order** section.

[**Mojave Nights - A Moon and Stars Replacer**](https://www.nexusmods.com/newvegas/mods/44381)  
High quality retexture for night sky and moon.
- Install the **Mojave Nights FOMOD** main file.
  - FOMOD options to install:
    - [X] 80% Moon size.
    - [X] Enhanced Night Sky.
    - [X] Low-glow Moon.
- Copy **textures\sky\skystars.dds** and paste it inside **textures\NVDLC02\sky**.

> ℹ️ This will also apply the new night sky texture to Zion.

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

## AUDIO

### SFX

[**All Weapon Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/62870)  
Replaces every gun sound in the game, from ballistic to energy weapons.

Additional files to install:
- [**All Weapon Sounds Overhaul ESP Replacer**](https://github.com/VivaNewVegas/Living-in-New-Vegas/blob/master/All%20Weapon%20Sounds%20Overhaul%20ESP%20Replacer.7z). Replaces the ESP with a scripted version that vastly improves compatibility with other mods. Made by **Qolore**.
- [**All Weapon Sounds Overhaul WMIM Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/All%20Weapon%20Sounds%20Overhaul%20WMIM%20Patch.7z). Patches weapon sounds for compatibility with **Weapon Mesh Improvement Mod**.

[**All Explosion Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/66946)  
Replaces every explosion sound in the game.

Additional files to install:
- **All Explosion Sounds Overhaul SCRIPT Version** (Optional files). Replaces the ESP with a scripted version that vastly improves compatibility with other mods. Made by **Qolore**.

[**Immersive Primary Needs**](https://eddoursul.win/mods/immersive-primary-needs/)  
As hunger, thirst or sleep deprivation increase, the player is notified by periodic sound effects. These effects kick in shortly before the first penalties occur, so the player is given a chance to eat, drink or sleep in time.

[**Immersive Pickup Sounds**](https://www.nexusmods.com/newvegas/mods/61815)  
Adds custom pickup sounds when looting different items.
- Install **Immersive Pickup Sounds - Compatibility Version** (Main files).

[**Empty Clicks - Improved Dry Fire Sounds**](https://www.nexusmods.com/newvegas/mods/68941)  
Different dry fire (empty magazine) sounds depending on a weapon type and some other improvements.

Additional files to install:
- [**Empty Clicks Custom INI**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Empty%20Clicks%20Custom%20INI.7z). Enables animations in both first and third person views, and realistic mode.

[**More Accurate Geiger Clicking**](https://www.nexusmods.com/newvegas/mods/68605)  
Increases the Pip-Boy Geiger clicking beyond the vanilla default.

[**No Cocking Sound on Rifle Equip**](https://www.nexusmods.com/newvegas/mods/66698)  
Removes the cocking sound that plays every time you equip a rifle.

[**Female Nuka-Cola Drinking Sound Replacer**](https://www.nexusmods.com/newvegas/mods/68476)  
Replacer for the male drinking sound the game plays whenever you consume a Nuka-Cola.
- Install the **Female Nuka-Cola Drinking Sound replacer** main file.

> ⚠️ You should only use this mod when playing a female character, since it replaces the vanilla male drinking sound.

## LOD RESOURCES

[**Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on all distant land.
- Install the **Improved LOD noise Texture** main file.

[**FNVLODGen Resources**](https://www.nexusmods.com/newvegas/mods/58562)  
Adds extra meshes for LOD generation.
- Install the **FNVLODGen Resources** main file.

Additional files to install:
- [**FNVLODGen Resources ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FNVLODGen%20Resources%201.1%20ESP%20Replacer.7z). Compatible with **Wasteland Flora and Terrain Overhaul**.

[**LOD Additions and Improvements**](https://www.nexusmods.com/newvegas/mods/61206)  
Adds extra meshes for LOD generation.

Additional files to install:
- [**LOD Additions and Improvements YUP ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/LOD%20Additions%20and%20Improvements%201.0.7%20YUP%20ESP%20Replacer.7z). Forwards YUP fixes.

[**FNV LOD Supplementation**](https://www.nexusmods.com/newvegas/mods/72099)  
Adds extra meshes for LOD generation.

[**Better Strip View**](https://www.nexusmods.com/newvegas/mods/73261)  
Adds the Strip signs and moves the Strip buildings to where they should be.

Additional files to install:
- [**Better Strip View ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Better%20Strip%20View%201.6%20ESP%20Replacer.7z). Cleaned by **Sigourn**.
- [**More Subtle New Vegas Light Pollution Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Better%20Strip%20View%20More%20Subtle%20New%20Vegas%20Light%20Pollution%20Patch.7z). Addresses conflicts with pollution light placement.

[**TCM's LOD Overhaul**](https://www.nexusmods.com/newvegas/mods/70155)  
Adds extra meshes for LOD generation.

[**Strip Lights Region Fix**](https://www.nexusmods.com/newvegas/mods/73596)  
Fixes a vanilla issue about the Strip lights not showing in certain parts of the map.
- Check the following option in the FOMOD installer.
  - [X] Uncut Wasteland

Additional files to install:
- [**Mormon Fort Region Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Mormon%20Fort%20Region%20Fix%201.0.7z). Fixes an issue where the Lucky 38 would disappear from the Old Mormon Fort worldspace. Mod by **Nehred**.

[**Lucky 38 Lights Redone**](https://www.nexusmods.com/newvegas/mods/73273)  
Modifies the Lucky 38 lights before and after they have been turned on during the Mr. House/Yes Man questlines.
- Check the following option in the FOMOD installer.
  - [X] Gold Lights
  - [X] Extras Everywhere
  - [X] Pollution Gold Tint
  - [X] Patch for Better Strip View

> ⚠️ This mod overwrites **More Subtle New Vegas Light Pollution**. We will load that mod after this one in the **Mod order** section.

[**FNV RWL All DLC - Worldspace Patch**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/FNV%20RWL%20All%20DLC%20-%20Worldspace%20Patch.7z)  
Ensures compatibility between **FNV Realistic Wasteland Lighting** and **Better Strip View**, **Strip Lights Region Fix**, **Mormon Fort Region Fix**, and **Lucky 38 Lights Redone**.

[**Wasteland Flora and Terrain Overhaul**](https://www.nexusmods.com/newvegas/mods/39856)  
Adds more tree and plant variants, implements 3D LODs, and improves grass.
- Install **Wasteland Flora and Terrain Overhaul** first, and then install **Wasteland Flora Overhaul - Vanilla tree replacer with LOD**.
- Hide **WFO - Vanilla.esp**.

Additional files to install:
- [**Wasteland Flora and Terrain Overhaul ESP Replacer**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/Wasteland%20Flora%20and%20Terrain%20Overhaul%20ESP%20Replacer.7z). Edited to remove all new trees and variants, making it a pure mesh and texture replacer for additional trees not covered by the **Vanilla Tree Replacer** file.

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
NVAC - New Vegas Anti Crash
NVTF - New Vegas Tick Fix
NVTF Custom INI
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
Ammo Script Fixes
Critical and Effects - Fixes and Tweaks
Crippled Limb Reaction Enforcer
Gauss Rifle VATS Fix - JIP
Universal Pyromaniac Buff for Fire Effects
New Vegas Mesh Improvement Mod
Weapon Mesh Improvement Mod
WMIM ESP Replacer
Throwable Weapon Fixes
Dirty Pre-War Businesswear Fix
Female White Glove Society Mask
Less Flickery City of New Vegas
No More Dust Devils (and Whirlwinds)
No More Muzzle Flash Lights
UIO - User Interface Organizer
The Mod Configuration Menu
The Mod Configuration Menu Bugfix
Vanilla UI Plus (New Vegas)
Clean Vanilla HUD
Clean Companion Wheel
JIP Improved Recipe Menu
Satellite World Map
Satellite Maps DLC
Consistent Pip-Boy Icons
Vanilla HD Missing Icon for Consistent Pip Boy Icons - No More Farting Vault Boy
Ending Slideshows Ultimate Edition Overhaul
Faster Pip-Boy Animation
Laser Weapon Iron Sights
Motion Sickness Destroyer
Quick Grenade Hotkey
Quick Grenade Hotkey Tweaks
Simple DLC Delay
Snowglobe Tweaks Fix
Essential DLC Enhancements Merged
Faction Warning and Reputation Tweaks
Follower Formula Redone YUP
Follower Tweaks
Jamming Fix and Optional Tweaks
Less Map Markers YUP
Misc Gameplay Merge
Misc Gameplay Merge YUP ESM Replacer
Mine and Explosion Tweaks
Mostly Unarmed Tweaks
Rigged Shotgun Restoration - Lore-Friendly
Well Rested Overhaul YUP
Lobotomite Tweaks
Alternative Repairing
Alternative Repairing Tweaks
B42 Inspect
B42 Melee Bash
JAM - Just Assorted Mods
JAM - Just Assorted Mods Custom INI
Immersive Fast Travel Requirements
Melee Cleave (a.k.a. Sweep)
NPCs Sprint In Combat
Precise VATS (and actually useful Perception)
RAD - Radiation (is) Actually Dangerous
RAD - Radiation (is) Actually Dangerous - Overhaul
Simple Explosive Entry
JSawyer Ultimate Edition
JSawyer Ultimate Edition - Qolore's Tweaks
JSawyer Ultimate Edition - Vanilla-ish Companion Suite
JSawyer Ultimate Edition Fixes
Misc Gameplay Merge - JSawyer Ultimate Edition Patch
Miscellaneous Tweaks Collection Tweaked
Mojave Arsenal
JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)
New Vegas Economy Improved
Player Combat Priority
Thrown Weapon Tweaks
Unfound Loot
Unfound Loot Custom INI
Anatomic Perks
Meltdown NVSE Upgrade Tweaked
Miss Fortune NVSE Upgrade
Improved Traits and Opposite Traits
Better Character Creation
Consistent Pip-Boy Icons Mod Patches
Uncut Wasteland
Uncut Wasteland Tweaks
Mojave Raiders
JSawyer Ultimate - Mojave Raiders Patch
Mojave Wildlife - Vanilla No Chanced Spawns Version
Anniversary Anim Pack
Anniversary Anim Pack - General Bugfix
Diagonal Movement
360 Movement
Immersive Recoil
Viewmodel Recoil
B42 Weapon Inertia
NV Compatibility Skeleton
Companions Combat-Ready
Empty Weapons
Tweaked Standing Idle
Tweaked Standing Idle Fix
FOV Slider
FOV Slider Custom INI
Character Expansions Revised
Character Expansions Revised - AIO Patch
FaceGen Tint Fixes for Character Expansions Revised
Alsatian NCR Guard Dogs
Simple Bighorner Variants
Simple Brahmin Variants
Simple Healthier Yao Guai
Y-17 Trauma Override Harness GLOVES
Bathroom Doors Overhaul
Bathroom Doors Overhaul YUP ESP Replacer
Gun Runners Kiosk Glass Fix Alternate Version
LSO - A Lightweight Strip Overhaul
Lightweight Strip Overhaul - Uncut Wasteland Patch
Palm Tree Replacer
Lucky 38 Mainframe No Fingerprints
McCarran Escalator Glass
McCarran Main Terminal Transparent Glass
Windows of the Mojave
Windows Redux
Pip-Boy 2000 Mk VI
Pip-Boy 2000 Mk VI Working Buttons
Pip-Boy 2000 Mk VI (Wasteland Edition) Retexture
NPC Arm Mounted Pip-Boy 2000 Mk VI (Pluginless)
No Pip-Boy Glove
Lower-sitting Ranger Hat
Metal Helmets - Female Replacements
Power Armor Gloves YUP
Simple Glowing Ranger Visors
Worn-Out Scope Crosshair Replacers
Honest Hearts Gecko Leathers Improved
Honest Hearts Gecko Leathers Improved ESP Replacer and JSUE Patch
Better Gas Leak Effect
Burning Campfire REDONE
Burning Campfire REDONE 2
IMPACT
IMPACT - Compatibility Edition
EXE - Effect teXtures Enhanced
Enhanced Blood Textures
HQ Dust Storm FX
HD Mist
Securitrons in CRT
A Little More Lamplight
A Little More Lamplight YUP ESP Replacer
Simple Interior Lighting Overhaul
Strip Lighting Overhaul
Strip Lighting Overhaul LSO Patch
The Strip Planters Fixed
Subtle Light Beams and Rays
FNV Realistic Wasteland Lighting
FNV Realistic Wasteland Lighting - All DLC YUP ESP Replacer
Mojave Nights
Night Sky Tweaks
All Weapon Sounds Overhaul
All Weapon Sounds Overhaul ESP Replacer
All Weapon Sounds Overhaul WMIM Patch
All Explosion Sounds Overhaul
All Explosion Sounds Overhaul SCRIPT Version
Immersive Pickup Sounds - Compatibility Version
Immersive Primary Needs
Empty Clicks
Empty Clicks Custom INI
More Accurate Geiger Clicking
No Cocking Sound on Rifle Equip
Female Nuka-Cola Drinking Sound Replacer
Improved LOD Noise Texture
FNVLODGen Resources
FNVLODGen Resources ESP Replacer
LOD Additions and Improvements
LOD Additions and Improvements YUP ESP Replacer
FNV LOD Supplementation
Better Strip View
Better Strip View ESP Replacer
Better Strip View More Subtle New Vegas Light Pollution Patch
TCM's LOD Overhaul
Strip Lights Region Fix
Mormon Fort Region Fix
Lucky 38 Lights Redone
More Subtle New Vegas Light Pollution (Slightly Brighter)
FNV RWL All DLC - Worldspace Patch
Wasteland Flora and Terrain Overhaul
Wasteland Flora and Terrain Overhaul ESP Replacer
Wasteland Flora Overhaul - Vanilla Tree Replacer with LOD
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
Character Expansions Revised.esm
Lightweight Strip Overhaul.esm
YUP - NPC Fixes (Base Game + All DLC).esp
Unofficial Patch NVSE Plus.esp
MigMultiCase.esp
AmmoScriptFixes.esp
CriticalEffectFixes.esp
MigCrippled.esp
MigGaussFix.esp
PyromaniacEffectsBuff.esp
WMIMNV.esp
ThrowableFixes.esp
Dirty Pre-War Businesswear Fix.esp
LessFlickeryCityOfNewVegas.esp
The Mod Configuration Menu.esp
Vanilla UI Plus.esp
JIP Improved Recipe Menu.esp
Ending Slideshows Ultimate Edition Overhaul.esp
LaserWeaponIronSights.esp
PlasmaWeaponIronSights.esp
Motion Sickness Reduction Mod.esp
Quick Grenade Hotkey.esp
Simple DLC Delay.esp
Snowglobe Tweaks.esp
DLC Enhancements.esp
Faction Warning and Reputation Tweaks.esp
Follower Formula Redone.esp
Follower Tweaks.esp
JamFix.esp
Less Map Markers.esp
MigAAMines.esp
MigKao.esp
Rigged Shotgun Restoration - Lore-Friendly.esp
migWellRested.esp
Lobotomitess.esp
Alternative Repairing.esp
Alternative Repairing - Honest Hearts.esp
Alternative Repairing - Lonesome Road.esp
B42Inspect.esp
B42Bash.esp
JustAssortedMods.esp
Fast Travel Requirements.esp
MeleeCleave.esp
NPCsSprint.esp
hz_Precise VATS.esp
RAD.esp
Simple Explosive Entry.esp
JSawyer Ultimate.esp
JSawyer Ultimate - Push's Tweaks.esp
JSawyer Ultimate - Qolore's Tweaks.esp
JSawyer Ultimate - Vanilla-ish Companion Suite.esp
JSawyer Ultimate - AIO Fixes.esp
Misc Gameplay Merge - JSUE Patch.esp
Miscellaneous Tweaks.esp
Mojave Arsenal.esp
JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged).esp
NV Economy Improved.esp
Player Combat Priority.esp
Thrown Weapon Tweaks.esp
Unfound Loot.esp
MigAnatomy.esp
MigMeltdown.esp
MigFortune.esp
FNVOppositeTraits.esp
Improved Traits.esp
Improved FNVOppositeTraits.esp
Improved Traits and FNVOppositeTraits JSUE Patch.esp
Better Character Creation.esp
Uncut Wasteland.esp
Uncut Wasteland pole remover.esp
Uncut Wasteland Tweaks.esp
Lightweight Strip Overhaul - Uncut Wasteland Patch.esp
Mojave Raiders.esp
JSawyer Ultimate - Mojave Raiders Patch.esp
Mojave Wildlife (Vanilla-Style + No Chanced).esp
Diagonal movement.esp
360Movement.esp
360Movement - Diagonal movement Patch.esp
ImmersiveRecoil.esp
VM_Recoil.esp
B42Inertia.esp
Companions Combat-Ready.esp
EmptyWeapons.esp
FOVSlider.esp
Character Expansions Revised - Extras.esp
Character Expansions Revised - YUP.esp
Character Expansions Revised - JSU.esp
Character Expansions Revised - UW.esp
Character Expansions Revised - MR.esp
Character Expansions Revised - AIO Patch.esp
Alsatian NCR Guard Dogs.esp
Bighorner Model Variants Merged.esp
Simple Brahmin Variants Redux.esp
Bathroom Doors Overhaul - ALL IN ONE.esp
Windows of the Mojave v1.2.1.esp
Metal Helmet Female Replacements.esp
MCPipBoy2000MK6_clock.esp
lexx_armored_pagloves.esp
ImprovedGeckoLeatherArmor.esp
ImprovedGeckoLeatherArmor JSUE Patch.esp
Burning Campfire.esp
BC2.esp
IMPACT.esp
dD - Enhanced Blood Main NV.esp
All Weapon Sounds Overhaul.esp
All Weapon Sounds Overhaul WMIM Patch.esp
Explosive Sounds Overhaul.esp
ImmersivePickupSoundsFNV.esp
Immersive Primary Needs.esp
hz_Empty Clicks.esp
More Accurate Geiger Clicking.esp
Little More Lamplight.esp
Strip Lighting Overhaul.esp
Strip Lighting Overhaul LSO Patch.esp
vegasglow.esp
Better Strip View.esp
Better Strip View vegasglow Patch.esp
Strip Lights Region Fix.esp
Strip Lights Region Fix - Uncut Wasteland.esp
Mormon Fort Region Fix.esp
Lucky 38 Lights Redone.esp
Mormon Fort Region Fix - Lucky 38 Lights Redone.esp
FNV Realistic Wasteland Lighting - All DLC.esp
FNV RWL All DLC - Worldspace Patch.esp
Mojave Nights.esp
Vurt's WFO.esp
FNVLODGen.esp
tmzLODadditions.esp
```
</details>

### FNVEdit instructions

The following mods have conflict issues that need to be addressed, or otherwise aspects we want to see tweaked.

To make these edits, you will have to launch **FNVEdit** through Mod Organizer 2. Under each spoiler you will find:

- The **plugins** that need to be loaded. This can be one, when it comes to editing a single plugin, or more, when it comes to forwarding changes from one mod to another. Forwarding a change means applying the same change to a mod that sits later in the load order. We will always apply the change to the plugin corresponding to the mod we are trying to fix. This will always be the plugin listed *last* under each spoiler.
- The **instructions** to follow, and the **record** which those instructions have to be applied to. To search for a given record, copy the record ID (which you will find in **bold** at the end of the instructions) and paste it into FNVEdit's **FormID filter** (the empty box labeled **FormID** after you've loaded your plugins in FNVEdit), and then press Enter. This will search for that given record.

Once you've made your edits, you need to exit FNVEdit, and **Save** your changes when prompted.

<details>
	<summary>Mojave Arsenal</summary>

Plugins to load:
- **Unofficial Patch NVSE Plus.esp**
- **JSawyer Ultimate - Push's Tweaks.esp**
- **Miscellaneous Tweaks.esp**
- **Mojave Arsenal.esp**

Instructions:
- Forward the **Ingredients** section for record **00140A66**
- Forward the **Conditions** section for record **02010CD9**
- Forward the **Description** field for record **05000A4B**
</details>

<details>
	<summary>JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)</summary>

Plugins to load:
- **Miscellaneous Tweaks.esp**
- **JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged).esp**

Instructions:
- Forward the three **Leveled List Entries** for record **0011FBCF**
- When asked to, add **Miscellaneous Tweaks.esp** as a master file.
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

### MCM config

**Quick Grenade Hotkey**:
- Set **Grenade Hotkey** to **G**.
- Set **Grenade Swap Hotkey** to **C**.

**Mojave Arsenal**:
- Enable **Low Condition Loot**.
- Disable **New Ammo**.
- Disable **Custom Weapons**.
- Enable **Optimized Ammo**.
- Enable **Pulse Slug Recipes**.

**Alternative Repairing**:
- Enable **Repair Tools**.
- Set **Repair Kits** to **Multi-use**.

### INI CONFIG

**JIP LN NVSE Plugin**:
- Double-click the installed mod to open the **Information...** window.
- Click the **INI Files** tab, and make the following adjustments in **jip_nvse.ini**.
- Click on the diskette icon to save your changes.

```
bEnableFO3Repair=1
bNPCWeaponMods=1
uWMChanceMin=5
uWMChanceMax=15
```

> ℹ️ Enables Fallout 3-style repair, as well as a chance for random NPCs to have weapon mods.

**Vanilla UI Plus**:
- Open **Menus\Prefabs\VUI+\settings.xml** using a text editor and make the following adjustments.

```
<_VUI+DialogMaxTopics> 6 </_VUI+DialogMaxTopics>

<_VUI+NumberedTopics> 1 </_VUI+NumberedTopics>
```

> ℹ️ Increases the amount of visible dialogue topics; displays numbers next to dialogue topics (intended to be used alongside my **lStewieAl's Tweaks Custom INI**).

**Ending Slideshows Ultimate Edition Overhaul (Optional)**:
- Double-click the installed mod to open the **Information...** window.
- Click the **INI Files** tab, and make the following adjustments in **Ending Slideshows Ultimate Edition Overhaul.ini**.
- Click on the diskette icon to save your changes.

```
bTrueLonesomeRoad=1
bNoDeadMoneyTeleport=1
```

> ℹ️ Stops the game from teleporting the player to the DLC entrance at both Dead Money and Lonesome Road.

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
uHUDColor=1022886143
```

> ℹ️ Disables the built-in screenshot feature in favor of SweetFX's (which will account for its post-processing effects); disables vanilla depth of field effect seen during dialogue; reduces the amount of zoom when engaging in dialogue; tweaks the Pip-Boy HUD color to match that of classic Fallout; tweaks the interface color to match that of classic Fallout.

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
N | Toggle Pip-Boy light | lStewieAl's Tweaks
N | Toggle scope night vision | lStewieAl's Tweaks
M | Open Pip-Boy world map tab | lStewieAl's Tweaks
Ctrl-F | Apply filter for searching in Pip-Boy | lStewieAl's Tweaks
Shift+E | Pick locked door even if you have the key | lStewieAl's Tweaks
Shift+E | Pick up and equip | lStewieAl's Tweaks
Scroll wheel | Adjust binocular zoom | lStewieAl's Tweaks
O | Check weapon ammo | B42 Inspect
P | Check weapon condition | B42 Inspect
X | Weapon bash | B42 Melee Bash
G | Equip grenade/mine | Quick Grenade Hotkey
C + Scroll wheel | Scroll through grenades/mines | Quick Grenade Hotkey
H | Open weapon wheel | Just Assorted Mods
Shift+Movement | Sprint | Just Assorted Mods

# CHANGELOG

- 🆕 Mod has been added to the guide.
- ⚠️ Mod has been updated or its installation/configuration instructions have changed.
- 🚫 Mod has been removed from the guide.

<details>
	<summary>January 4th</summary>

Last cull before the next big update.

- ⚠️ **Y-17 Trauma Override Harness GLOVES** (Visuals, Creatures and NPCs). Moved to this section.
- 🚫 **Vanilla Loading Screens HD** (User Interface). The vanilla loading screens look like shit, upscaling or not.
- 🚫 **Unisex Motorcycle Helmets** (Visuals, Equipment). Some appreciate the vanilla Spaceballs helmet.
</details>

<details>
	<summary>January 3rd</summary>

- Added **Merge** instructions for a number of mods, in cases where you need to download multiple files from the same page. This will unclutter your mod order while changing no functionality whatsoever.
- 🆕 **Faction Warning and Reputation Tweaks** (Gameplay, Tweaks).
- ⚠️ **lStewieAl's Tweaks Custom INI**. Updated. Luck affects gambling once again, broken items can't be equipped anymore, and broken armor is automatically unequipped as a balance measure to prevent benefitting from the effects of broken equipment.
- ⚠️ **Alternative Repairing** (Gameplay, Features and Mechanics). ESP replacer and custom INI merged into a single **Alternative Repairing Tweaks** file.
- ⚠️ **Meltdown NVSE Upgrade** (Overhauls, Balance). ESP replacer and custom INI merged into a single **Meltdown NVSE Upgrade Tweaked** file.
- ⚠️ **Improved Traits** and **FNV Opposite Traits** (Overhauls, Traits). Replaced the original mods and ESP replacers with a single download that contains both fixed mods, the Improved Traits patch for Opposite Traits, and the JSawyer Ultimate patch.
- ⚠️ **Better Character Creation** (Overhauls, Perks and Traits). Moved into this section as it includes the changes removed to Improved Traits Improved.
- ⚠️ **Uncut Wasteland** (Content). Added **Uncut Wasteland Pole Remover**.
- ⚠️ **Bighorner Model Variants** (Visuals, Creatures and NPCs). Replaced the original mod and ESP replacer with a single download that consists of a single plugin (instead of two).
- ⚠️ **Brahmin Variant Redux** (Visuals, Creatures and NPCs). Replaced the original mod and ESP replacer with a single download that consists of a stripped down, more compatible version of the original mod.
- ⚠️ **Healthier Yao Guai** (Visuals, Creatures and NPCs). Replaced the original mod with a download that consists of a pluginless mod.
- 🚫 **Delayed Malcolm** (Gameplay QOL). Addresses a non-issue: a better mod would simply get rid of this stupid quest altogether.
- 🚫 **Honest Hearts Workbench Crate Luck** (Gameplay, Tweaks). Addresses a non-issue: most players rightfully wouldn't know about workbench crates spawning skill books if it wasn't pointed out to them. 
- 🚫 **Simple Reputation and Disguises** (Gameplay, Features and Mechanics). Replaced with **Faction Warning and Reputation Tweaks**.
- 🚫 **Meat's Back On The Menu Boys** (Gameplay, Features and Mechanics). Addresses a non-issue: even if being able to purchase meat is nice, the mess hall is located in such an inconvenient location that players are much more likely to get their food someplace else.
- 🚫 **Tesla Cannon Chaining** (Gameplay, Features and Mechanics). Addresses a non-issue.
- 🚫 **Armor Damage Overhaul** (Overhauls, Balance). While I see the logic behind the mod, I can't say it works well enough during gameplay.
- 🚫 **Lucky 38 Intro Poster** (Visuals, Environment). Addresses a non-issue.
- 🚫 **Lonesome Road Carbon Shadow Fix** (Visuals, Environment). Addresses a non-issue.
- 🚫 **Companion Radiation Suit** (Visuals, Creatures and NPCs). Heavily irradiated areas are few and far between in the game, and having multiple companions at once could turn this mod into an annoyance as you can't instantly tell who is who.
- 🚫 **Classic Level Up Sounds** (Audio). It's not that I didn't like the mod, but it is the kind of nostalgia pandering I'm not interested in anymore.
- 🚫 **Classic XP Sound** (Audio). Same as above.
</details>

<details>
	<summary>December 30th</summary>

- Added mention to **Melee Cleave (a.k.a. Sweep) but as a Perk**.
- Moved **Gun Runners Kiosk Glass Fix** to Visuals, Environment.
- 🆕 **No More Muzzle Flash Lights** (Mesh fixes and optimization). Replaces **No Muzzle Flash Light**.
- 🆕 **Motion Sickness Destroyer** (Gameplay QOL).
- 🆕 **B42 Inspect** (Gameplay, Features and mechanics).
- 🆕 **B42 Melee Bash** (Gameplay, Features and mechanics).
- 🆕 **No Pip-Boy Glove** (Visuals, Equipment).
</details>

<details>
	<summary>December 26th Hotfix</summary>

- ⚠️ Fixed issues in **Mod order** and **Load order**. Many thanks to user **Belmor** for spotting these!
  - Added **Lightweight Strip Overhaul.esm** and **Lightweight Strip Overhaul - Uncut Wasteland Patch.esp** to load order.
  - Added **Enhanced Blood Textures** to mod order.
  - Added **FNV RWL All DLC - Worldspace Patch.esp** to load order.
  - Removed JSUE suffix from **Female White Glove Society Mask** in mod order.
  - Removed **Immersive Recoil Custom INI** from mod order.
  - Removed duplicate **Improved LOD Noise Texture** from mod under (before Animations).
  - Removed **FNV RWL All DLC - Strip Lights AIO Patch.esp** from load order.
</details>

<details>
	<summary>December 25th</summary>

Merry Christmas!
	
- Many visual mods have been moved to **LOD Resources** since they require LOD generation to work as intended.
- 🆕 (Overhauls, Balance) Added **JSawyer Ultimate Edition - Vanilla-ish Companion Suite**.
- 🆕 (Visuals, Environment) Added **Lightweight Strip Overhaul**. Includes a patch for **Uncut Wasteland**.
- 🆕 (Visuals, Environment) Added **Palm Tree Replacer**.
- 🆕 (Visuals, Environment) Added **The Strip Planters Fixed**.
- 🆕 (Visuals, Weather and Lighting) Re-added **More Subtle New Vegas Light Pollution**. Upon consulting real life pictures and having a better understanding on what light pollution actually is, I've come to the conclusion that this is much better than vanilla.
- 🆕 (Visuals, Weather and Lighting) Added **Strip Lighting Overhaul LSO Patch**.
- 🆕 (LOD Resources) Added **Better Strip View More Subtle New Vegas Light Pollution Patch**.
- 🆕 (LOD Resources) Added **Mormon Fort Region Fix**.
- ⚠️ (Mod keybindings) Added new ammo switch hotkey.
- ⚠️ (Patches, NVSE) Updated **lStewieAl's Tweaks Custom INI**. Items you buy no longer have a minimum value of 1 cap. This led to unreasonable scenarios, such as an ammo case having the same value as a complete bullet of the same type.
- ⚠️ (Overhauls, Balance) Updated **Miscellaneous Tweaks ESP Replacer**. Feral Ghoul Reavers have had their HP and melee damage tweaks reverted to vanilla. Qolore is only human, after all.
- ⚠️ (LOD Resources) Updated **FNV RWL All DLC - Worldspace Patch** (formerly **Strip Lights AIO Patch**).
- ⚠️ (Generating LOD) Expanded LOD generation instructions, bypassing a bug with the Lucky 38 vanishing from the Old Mormon Fort worldspace.
</details>
	
<details>
	<summary>December 21st Hot Update</summary>

- ⚠️ (Overhauls, Balance) Updated **JSUE Tweaks** to remove redundant records already included in **Miscellaneous Tweaks Collection**. Also renamed the mod to **JSawyer Ultimate Edition - Qolore's Tweaks**.
- ⚠️ (Overhauls, Balance) Updated **JSawyer Ultimate Edition Fixes**. Removed redundant records from the YUP patch, and made an AIO plugin to reduce plugin count. 
- ⚠️ (Overhauls, Balance) Updated **Miscellaneous Tweaks Collection** for compatibility with **Mojave Arsenal** and **Mojave Raiders**. Functionally the mod remains the same when following the recommended load order.
- ⚠️ (Overhauls, Balance) Replaced **Mojave Raiders Tweaks** with **Thrown Weapon Tweaks**.
- ⚠️ (INI Config) Increased max amount of dialogue topics in **Vanilla UI Plus**.
- 🚫 (Visuals, Weather and Lighting) Removed **More Subtle New Vegas Light Pollution**.
</details>

<details>
	<summary>December 21st</summary>

- Moved Mod Organizer 2 instructions to the **Setup** document.
- Moved xNVSE plugins to the **Main** document, after instructions on how to install Mod Organizer 2 have been given in **Setup**.
- Merged optional mods with the rest. These are what set this guide apart from **Viva New Vegas**, meaning there was no point in keeping them hidden.
- Separated categories into sub-categories, mirroring my Morrowind guide.
- Removed most **FNVEdit** instructions in favor of ESP replacers. Mods that are regularly updated still include FNVEdit instructions.
- ⚠️ (Visuals, Weather and lighting) Modified **FNV Realistic Wasteland Lighting** installation instructions.
- 🆕 (User interface, Menus) Added **Vanilla Loading Screens HD**.
- 🆕 (Overhauls, Balance) Added **New Vegas Economy Improved**.
- 🆕 (Visuals, VFX) Added **Burning Campfire REDONE**.
- 🆕 (Visuals, VFX) Added **IMPACT**.
- 🆕 (Visuals, VFX) Added **EXE - Effect teXtures Enhanced**.
- 🆕 (Visuals, VFX) Added **Enhanced Blood Textures**.
- 🆕 (Audio) Added **Immersive Pickup Sounds**.
</details>

<details>
	<summary>December 19th</summary>

- 🆕 (Visuals, Optional) Added **Alsatian NCR Guard Dogs**.
- 🆕 (Visuals, Optional) Added **Bighorner Model Variants**. This mod includes **FNVEdit instructions**.
- 🆕 (Visuals, Optional) Added **Brahmin Variant Redux**. This mod includes **FNVEdit instructions**.
</details>

<details>
	<summary>December 17th</summary>

- 🆕 (Visuals) Added **FaceGen Tint Fixes for Character Expansions Revised**.
- ⚠️ (INI Config) Tweaked Pip-Boy HUD color. Added HUD color tweak.
- ⚠️ (FNVEdit instructions) Expanded instructions for **Simple Reputation and Disguises**; added instructions for **Follower Formula Redone**, **Misc Gameplay Merge**, **Companion Radiation Suit**, and **Ending Slideshows Ultimate Edition Overhaul**. Removed FNVEdit instructions for **Dirty Pre-War Businesswear Fix**. All these have been made with the latest **Yukichigai Unofficial Patch** update in mind.
</details>

<details>
	<summary>December 15th</summary>

- ⚠️ (Patches) Updated **lStewieAl's Tweaks Custom INI**. Removed Q for drop item hotkey in Pip-Boy (right-clicking does the same job), disabled weapon range affecting V.A.T.S. (as **Precise VATS** already does something similar), increased XP for discovering locations, and incorporated **Action Camera**'s GMST tweaks.
- 🆕 (Patches, Optional) Added **Crippled Limb Reaction Enforcer**.
- 🆕 (Gameplay, Optional) Added **Mine and Explosion Tweaks**.
- 🆕 (Visuals, Optional) Added **Empty Clicks Custom INI**.
- 🆕 (Visuals, Optional) Added **Windows of the Mojave**.
- 🆕 (Visuals, Optional) Added **Window Redux**.
- 🚫 (Visuals, Optional) Removed **Action Camera**. Now included in **lStewieAl's Tweaks Custom INI**.
</details>

<details>
	<summary>December 14th</summary>

- ⚠️ (Patches) Updated **lStewieAl's Tweaks Custom INI**. Removed annoying tweaks to lockpicking interface.
- ⚠️ (User interface) Added additional files for **Consistent Pip-Boy Icons**.
- ⚠️ (Gameplay) Updated **Just Assorted Mods Custom INI**. Improved compatibility with **Diagonal movement**.
- ⚠️ (Visuals) Updated **FNV Realistic Wasteland Lighting - All DLC Tweaks**. It now includes fog tweaks in addition to light tweaks.
- 🆕 (User interface) Added **Clean Companion Wheel**.
- 🆕 (Gameplay) Added **Simple Reputation and Disguises**. This mod includes **FNVEdit instructions**.
- 🆕 (Visuals) Added **Simple Interior Lighting Overhaul**.
- 🆕 (Visuals) Added **Subtle Light Beams and Rays**.
- 🆕 (Visuals, Optional) Added **Companions Combat-Ready**.
- 🆕 (Visuals, Optional) Added **Companion Radiation Suit**.
- 🆕 (Visuals, Optional) Added **Empty Weapons**.
</details>

<details>
	<summary>December 13th</summary>

- All **I♥NV**-only mods linked from github.
- Expanded **Mod Keybindings** section.
- Expanded description of **lStewieAl's Tweaks Custom INI**.
- 🆕 (Patches) Added [**Dirty Pre-War Businesswear Fix**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/%5BI%E2%99%A5NV%5D%20Dirty%20Pre-War%20Businesswear%20Fix%201.0.7z). This one doesn't include meshes nor changes to the Grimy Pre-War Businesswear (which was already fixed by YUP). Instead, it uses a Texture Set to implement the change, and also a TYPE 4-compatible version.
- 🆕 (Gameplay) Added [**Meat's Back On The Menu Boys (YUP**](https://github.com/Sigourn/iheartnewvegasrepository/blob/main/%5BI%E2%99%A5NV%5D%20Meat's%20Back%20on%20the%20Menu%20Boys%201.0%20(YUP).7z)
- 🆕 (Overhauls) Added [**Immersive Fast Travel Requirements**](https://www.nexusmods.com/newvegas/mods/73627)
- 🆕 (Visuals) Added [**Honest Hearts Gecko Leathers Improved**](https://www.nexusmods.com/newvegas/mods/42316)
- 🆕 (Audio) Added [**Immersive Primary Needs**](https://eddoursul.win/mods/immersive-primary-needs/)
- ⚠️ (Patches) Updated **lStewieAl's Tweaks Custom INI** to address settings I forgot to set. Pickpocketing now also gives the player 10 XP (instead of 1). 
- ⚠️ (falloutcustom.ini) Updated fDlgFocus setting in **falloutcustom.ini**.
- 🚫 (Patches) Removed [**Dirty Pre-War Businesswear Texture Fix**](https://www.nexusmods.com/newvegas/mods/65774).
</details>

<details>
	<summary>December 11th</summary>

- Renamed "In-game Mod Config" and "Mod Config" to "MCM Config" and "INI Config", respectively.
- 🆕 [**No Muzzle Flash Lights**](https://c6-dev.github.io/mods/no_muzzle_flash_lights/) (Patches, Optional)
- 🆕 [**Delayed Malcolm**](https://www.nexusmods.com/newvegas/mods/74598) (Gameplay QOL, Optional)
- 🆕 [**Ending Slideshows Ultimate Edition Overhaul**](https://www.nexusmods.com/newvegas/mods/74595) (Gameplay QOL, Optional). This mod includes optional INI instructions.
- 🆕 [**VNV JSawyer Ultimate Edition Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/JSawyer%20Ultimate%20Edition%20Tweaks.7z) (Overhauls)
- 🆕 [**Armor Damage Overhaul**](https://www.nexusmods.com/newvegas/mods/73267) (Overhauls, Optional)
- 🆕 [**Pip-Boy 2000 Mk VI Working Buttons**](https://drive.google.com/file/d/1aOW7BEOM2HfIs2IbtdsApQ05MGpMLn9F/view?usp=sharing) (Visuals)
- 🆕 [**Diagonal Movement**](https://www.nexusmods.com/newvegas/mods/64333) (Visuals, Optional)
- 🆕 [**360 Movement**](https://www.nexusmods.com/newvegas/mods/71940) (Visuals, Optional)
- 🆕 [**Action Camera**](https://www.nexusmods.com/newvegas/mods/66006) (Visuals, Optional). This mod includes FNVEdit instructions.
- 🆕 [**Simple Glowing Ranger Visors**](https://www.nexusmods.com/newvegas/mods/66628) (Visuals, Optional)
- 🆕 [**All Weapon Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/62870) (Audio, Optional)
- 🆕 [**All Explosion Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/66946) (Audio, Optional)
- 🆕 [**Classic Level Up Sounds**](https://www.nexusmods.com/newvegas/mods/56807) (Audio, Optional)
- 🆕 [**Classic XP Sound**](https://www.nexusmods.com/newvegas/mods/64514) (Audio, Optional)
- ⚠️ Updated **Unfound Loot Custom INI** to increase the influence of Luck in loot removal, and to make loot removal less dramatic at high Luck. Now loot reduction will range from 90% to 25% (1 Luck and 10 Luck, respectively, as opposed to 90% to 80%).
- ⚠️ Updated **Alternative Repairing Custom INI** to lower threshold at which apparel is considered clothing. Now JSUE-edited outfits like Leather Armor and Armored Vault Jumpsuits will be repaired with Light Armor Parts.
- ⚠️ Updated **FOV Slider Custom INI** to lower weapon FOV.
- 🚫 **WMIM Mesh Fix**. Already included in **WMIM ESP Replacer**.
</details>

<details>
	<summary>December 10th</summary>

- 🆕 [**Alternative Repairing**](https://www.nexusmods.com/newvegas/mods/52510). This mod includes in-game **Mod Config** instructions.
- 🆕 [**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874). This mod includes in-game **Mod Config** instructions.
- Added additional **Mod Config** tweaks for **falloutcustom.ini**.
- Added link to **Just Weapon Hweel** under **Just Assorted Mods**, which explains how the Weapon Wheel feature works.
</details>

<details>
	<summary>December 8th</summary>

- Added missing HQ Dust Storm FX - Dust Storm Meshes to **Mod order**.
- Removed FNVEdit instructions from each separate mod in favor of a single section dedicated to fixing each plugin.
</details>

<details>
	<summary>December 7th</summary>

- Initial release.
- Fixed Custom INI links.
- Completed Keybindings section.
- Added Mojave Arsenal configuration instructions.
- Added SweetFX optional configuration instructions.
</details>

[<< Back to Readme](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)
