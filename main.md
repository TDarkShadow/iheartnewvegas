[<< Back to Main](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)

# LEFT MY HEART IN NEW VEGAS

Last browsed for mods on December 10th, 2021.

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# BEFORE WE BEGIN

## DISCLAIMER

The guide presented here assumes you have already followed all instructions found in the [**Setup**](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup) page. Please abstain from using this guide until you've correctly set up Fallout: New Vegas and the recommended tools.

## MODDING TIPS

### Don't uninstall mods mid-playthrough

A lot of things can go wrong when uninstalling a mod mid-playthrough. Some, expected. Some, completely unexpected.

### Always keep backup saves

Before you install a mod you are not completely sure about, make a backup of your save in case things go wrong.  
Before you uninstall a mod you are not completely sure about, make a backup of your save in case things go wrong.

### Read the descriptions

Mod descriptions exist for a reason. The elaborate ones, usually for a *good* reason. Apart from describing what a mod is supposed to, descriptions tend to list things such as:

- Requirements: mods or utilities a given mod needs to work as intended.
- Compatibility issues: known conflicts with other mods, whether general or specific.
- Known issues: bugs or unintended behavior.

Reading descriptions helps you troubleshoot mods, and what's more, decide beforehand whether a mod is worth the trouble of installing it.

### File structure matters

The file structure is how files are organized for the game to read and use them. Incorrect file structure accounts for a good deal of mods that don’t work properly.

### Installing Nexus mods with Mod Organizer 2

Because Mod Organizer 2 is associated with Nexus links, mods downloaded in Nexus will be instantly added to Mod Organizer 2.

- Click **Mod manager download** under the file you want to download.
- Click **Slow download**.
- In Mod Organizer 2, click on the **Downloads** tab. You can check the download progress for your file there.
- Right-click the downloaded file, and click **Install**.
- MO2 will prompt you to give the mod a name. I suggest giving it a descriptive name, such as mod name + version number (e.g. **Yukichigai Unofficial Patch - YUP 12.2**).
- Click **OK**.
- The mod will appear in the left pane. Check the box next to it to finish installation.

> Whenever you are asked to install a mod from Nexus, limit yourself to the main file, unless explicitly told to install additional or different files. Likewise, if there are multiple main files present, you will be told which ones you need to install.

### Installing multiple files from a same Nexus mod with Mod Organizer 2

There will be times when you will be asked to install multiple files from the same mod page. These can be either updates or optional files regarding a given mod, or multiple different mods from the same page, usually compilation pages for minor mods which the author didn't think deserved individual mod pages.

Mod Organizer 2 allows the user to either merge, replace, or rename the file being installed.

![ModExists](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_ModExists.png)

What these options do is simple:

- **Merge** merges the contents of the file being installed with those of the file of the same name already installed. The new files will take priority over the old files, overwriting as necessary. This is useful when installing an update file which only includes certain files from the new mod.
- **Replace** replaces the contents of the already installed file with those of the newly installed file. This is akin to uninstalling the old file, and installing the new file. It is recommended you use this option whenever a mod has received a new update, as the update may not necessarily overwrite the old files.
- **Rename** installs the new file as a separate mod with a different name. In the case of compilation pages, this is a very useful feature as it lets you keep the different files (mods) as different installed mods.

> The guide will tell you when you need to merge, replace, or rename files in order to avoid problems.

### Manually installing mods with Mod Organizer 2

Sometimes authors will block the **Mod manager download** option in Nexus, and you will have to download the mod manually. On other occasions, you will download a mod from a different site altogether.

- Download your file.
- In Mod Organizer 2, click the **Install a new mod from archive** ![Archive](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Archive.png) button.
- Navigate to the folder where the downloaded file is stored and double click on it.
- MO2 will prompt you to give the mod a name. I suggest giving it a descriptive name, e.g. "mod name" + "version number".
- Click **OK**.
- The mod will appear in the left pane. Check the box next to it to finish installation.

### FOMOD installers

FOMOD installers allow users to customize how they want their mods to be installed, given a handful of options provided by the mod authors.

This guide has a few mods packaged as FOMOD installers. Only options you should install will be listed, accompanied by a checked box. If it is not listed, then you *must* skip that option.

### Hiding files

Mod Organizer 2 lets you hide specific files from your installed mods, like assets and plugins. A hidden plugin is treated as a deactivated plugin, with the bonus that it will no longer be listed in your load order. This is particularly useful when your load order is cluttered by deactivated plugins. Hiding assets is useful when you want certain files not to overwrite another mod's.

- To hide a plugin, right click on your installed mod and click **Information...**.
- On the **Filetree** tab, right click on the plugins, folders, or files you want to hide, and click **Hide**.
- Mod Organizer 2 will hide the files, and these will no longer affect your game.

### Creating a separator

Separators allow you to neatly separate installed mods in Mod Organizer 2 for ease of viewing. These can be created and then moved around in the left pane to place them where you want them to be.

- Right click on the empty space on the left pane, below **Overwrite**, and click **Create Separator**.
- Name your separator and click **OK**.

I suggest creating a separator for each of the following mod categories. Separators can be collapsed to keep your mod list clean and tidy, which you will come to appreciate when you install over 100 mods.

### The Overwrite folder

The **Overwrite** folder is the destiny folder for a handful of files, including **config** folders which contain the configuration files for a number of NVSE mods. There's always a chance files in the **Overwrite** folder will overwrite assets and/or plugins from your installed mods, but for the purpose of this guide, you don't need to worry about them.

# PATCHES

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.
- Install the **Navmesh Fixes and Improvements - Base Game and ALL DLC** main file.

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
A compilation of vital bug fixes for Fallout: New Vegas and its DLCs, all combined into one ESM. The only pure bug fix compilation available on the Nexus: no new features, no balance tweaks, no restored content.
- Install the **YUP - Base Game and All DLC** main file.

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLC.

[**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.
- Also install [**WMIM ESP Replacer**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/WMIM%20ESP%20Replacer.7z). Removes all changes the mod makes other than the changes required for the mesh fixes, as the original ESP has some bugs, conflicts, and many non-bug fix changes. Made by **Qolore**.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
A collection of fixes for throwable weapons, focused on projectiles.

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bugfixes requiring NVSE.

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Ammo Script Fixes**](https://www.nexusmods.com/newvegas/mods/63997)  
Fixes several problems at the core level with how ammo scripts and effects work, plus some tweaks for consistency and fun.

[**Critical and Effects - Fixes and Tweaks**](https://www.nexusmods.com/newvegas/mods/69200)  
Fixes the damage dealing critical effects of most vanilla weapons so that they cannot cause you to miss "killcounts" and other proc effects such as crime responsibility.

[**lStewieAl's Tweaks**](https://www.nexusmods.com/newvegas/mods/66347)  
Engine bugfixes, optional tweaks and new features with no performance impact. Fully customisable via in-game menu and INIs.

Additional files to install:
- [**lStewieAl's Tweaks Custom INI**](https://drive.google.com/file/d/1e3nKqfTKFi846dAZ6t4-EAD8MwDyN4Zo/view?usp=sharing). Enables many quality of life improvements, as well as gameplay and balance tweaks.

> For a comprehensive list of the features enabled by this INI, check the spoiler below.

<details>
	<summary>lStewieAl's Tweaks Custom INI - Click to expand</summary>

Notable gameplay tweaks include the following:

- Levelup menu max skill values are capped based on SPECIAL.
- Vendors obey their Buy/Sell flags, restricting which items they accept.
- Binoculars can now zoom in and out.
- Holding the attack button for grenades decreases their detonation timer.
- Entering VATS costs AP.
- Broken items can be equipped.
- Throwables can be held and released, like grenades.
- Living Anatomy perk shows Damage Resistance.
- Unconscious actors can be looted.
- Luck doesn't affect gambling.
- Manual reload.
- VATS' range is tied to current weapon's range.
- Slower backpedalling.
- Can't grab owned items.
- Opening Pip-Boy in combat costs AP.
- Skill level requirement for skill checks is hidden.
- Dialogue topics are numbered.
- Pickpocket formula takes into account item weight, target Perception, and detection value.
- Reload jams are affected by Agility.
- Repairing items gives XP.
- Robotic companions heal with Scrap Metal instead of Stimpaks.
- Sneak attack critical hits are only possible with melee weapons.
- Weapon mods can be unequipped.
</details>

<details>
	<summary>Patches (Optional) - Click to expand</summary>

[**Gauss Rifle VATS Fix - JIP**](https://www.nexusmods.com/newvegas/mods/69136)  
Fixes the Gauss Rifle not dealing headshot and critical damage in VATS.

[**Universal Pyromaniac Buff for Fire Effects**](https://www.nexusmods.com/newvegas/mods/71505)  
Makes the Pyromaniac perk affect *all* the lingering fire damage effects from weapons and ammo.

[**Dirty Pre-War Businesswear Texture Fix**](https://www.nexusmods.com/newvegas/mods/65774)  
Fixes the Dirty Pre-War Businesswear and Grimy Pre-War Businesswear having the incorrect textures.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.

[**Gun Runners Kiosk Glass Fix**](https://www.nexusmods.com/newvegas/mods/70293)  
Fixes Gun Runners' kiosk glass texture. Also adds a window speak thru.
- Only install **Gun Runners Kiosk Glass Fix Alternate Version** (under Optional files).

[**Less Flickery City of New Vegas**](https://www.nexusmods.com/newvegas/mods/72061)  
Fixes the intense flickering in the city of New Vegas (such as when looking from Goodsprings Cemetery) due to extra white proxy meshes clipping into the object LOD meshes.

[**No More Dust Devils (and Whirlwinds)**](https://www.nexusmods.com/newvegas/mods/74167)  
Improves game performance by removing all the dust devils and whirlwinds from the game (and any DLC/mod that might use them). Optionally removes tumbleweeds too.

[**No Muzzle Flash Lights**](https://c6-dev.github.io/mods/no_muzzle_flash_lights/)  
Improves game performance in combat by disabling lights cast on the environment by enemy muzzle flashes. Optionally removes player muzzle flashes too.
</details>

# USER INTERFACE

[**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.

Additional files to install:
- **MCM BugFix 2** (under Optional files).

[**JIP Improved Recipe Menu**](https://www.nexusmods.com/newvegas/mods/59638)  
Makes the crafting interface easier, more efficient and less tedious to use. 

[**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- FOMOD options to install:
  - [X] Default Font Tweaks
  - [ ] Classic Pip-Boy Font
  - [ ] No Font Tweaks
  - [X] Plugin
  - [X] WASD Compatible 

> The **Classic Pip-Boy Font** option includes the **Default Font Tweaks** option, and is a matter of preference. I personally use it alongside a tweaked Pip-Boy color for that classic Fallout feel (this tweak is present in the **INI Config** section.

[**Vanilla HUD Cleaned**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- FOMOD options to install:
  - All **Modules** and **Tweaks** options.
  - Skip the **DarnUI Specific** options.

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Lore-friendly overhaul of New Vegas icons to make them more consistent in terms of coloring and transparency. Includes other bug fixes.
- Install the **1. Consistent Pip-boy Icons** main file.

Additional files to install:
- **6. Vanilla UI Plus Patch** (under Optional files).

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.
- Install the **Satellite World Map** main file.

Additional files to install:
- [**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292). High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and  Lonesome Road.

<details>
	<summary>User Interface (Optional) - Click to expand</summary>

[**Vanilla HD Missing Icon for Consistent Pip Boy Icons - No More Farting Vault Boy**](https://www.nexusmods.com/newvegas/mods/73375)  
Replaces the farting vault boy/junk image options of Consistent Pip Boy icons with an upscaled HD version of the vanilla missing item icon.
</details>
	
# GAMEPLAY QOL

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

[**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.
- Install the **Faster Pip-Boy Animation (2x)** main file.

[**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

[**Snowglobe Tweaks Fix**](https://www.nexusmods.com/newvegas/mods/67466)  
Requires the player to discover the snow globe display in the Lucky 38 Presidental Suite before being able to sell the snow globes to Jane. DLC snow globes now need to be sold to Jane, and the Dead Money snow globe rewards 2,000 caps instead of 2,000 Sierra Madre chips.

<details>
	<summary>Gameplay QOL (Optional) - Click to expand</summary>

[**Delayed Malcolm**](https://www.nexusmods.com/newvegas/mods/74598)  
Delays the appearance of Malcolm Holmes, instead of allowing him to appear as soon as you pick your first Sunset Sarsaparilla Star bottle cap.
- Only install **Delayed Malcolm (random)**.

[**Ending Slideshows Ultimate Edition Overhaul**](https://www.nexusmods.com/newvegas/mods/74595)  
Merges the DLC ending slideshows with the main game's ending slideshow for one complete "Ultimate Edition" package. Updates the vanilla slideshow to the standards later adopted in the DLC.
</details>

# GAMEPLAY

[**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

[**Follower Formula Redone**](https://www.nexusmods.com/newvegas/mods/71490)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most.

[**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving. 

[**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

[**Jamming Fix and Optional Tweaks**](https://www.nexusmods.com/newvegas/mods/66293)  
Fixes the on-fire jamming for automatic weapons and adds an option for how often weapons jam.

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

Additional files to install:
- [**JAM - Just Assorted Mods Custom INI**](https://drive.google.com/file/d/1ILWL2wG1Fm-HtBlwQJhCHAy26VEFuJie/view?usp=sharing). Disables Hit Marker, Hit Indicator, Visual Objectives, Hold Breath, and Bullet Time. Sets 1st Person Mode crosshair to dynamic and 1st Sighting Mode to none. Reduces Sprint speed.

> For detailed instructions on how the **Weapon Wheel** feature works, [**see here**](https://www.nexusmods.com/newvegas/mods/67460).

[**Melee Cleave (a.k.a. Sweep)**](https://www.nexusmods.com/newvegas/mods/66187)  
Makes melee attacks hit multiple enemies.

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods by various authors, all fully fixed, optimized, and updated by Qolore7.

[**Mostly Unarmed Tweaks**](https://www.nexusmods.com/newvegas/mods/69283)  
Fixes the fatigue-dealing weapons to deal correct and damage-adjusted fatigue to enemies and the player, plus a few more changes related to unarmed combat for player and NPCs.

[**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

[**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Prevents the game from becoming too easy by making enemies more likely to target the player in combat rather than companions.

[**Precise VATS (and actually useful Perception)**](https://www.nexusmods.com/newvegas/mods/69202)  
Requires the player's crosshair to be aiming at the target in order to activate VATS, namd makes the VATS activation range and target switching distance to be dynamic and dependent on a few factors, including Perception level, weapon scope, Enhanced Sensors and Spotter Perks, and Power Armor.

[**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874)  
Adds a hotkey to automatically select the currently selected grenade/mine, as well as a hotkey to scroll through your available grenades/mines. Read the description for instructions on how these features work.

Additional files to install:
- [**Quick Grenade Hotkey Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Quick%20Grenade%20Hotkey%20Tweaks.7z). Adjusts the positioning of the grenade/mine icon to not overlap with other UI elements, and removes the unnecessary "no grenade/mine" icon. Made by **Qolore**.

[**Simple Explosive Entry**](https://www.nexusmods.com/newvegas/mods/66992)  
Allows the player to use explosives to bypass locks. Items have a chance of being destroyed, with the exception of notes and quest items.

[**Well Rested Overhaul**](https://www.nexusmods.com/newvegas/mods/64628)  
Expands how the Well Rested effect works. Effect duration is now in actual game hours, gives a few more buffs aside from increased XP, and patches all the game prostitutes' scripts to also grant the buff for purchasing their services.

<details>
	<summary>Gameplay (Optional) - Click to expand</summary>

[**Honest Hearts Workbench Crate Luck**](https://www.nexusmods.com/newvegas/mods/62415)  
Forces the Honest Hearts workbench crates (the only source of skill books in the Honest Hearts DLC) to obey the player character's Luck as opposed to generating random loot. The lone bottle of Nuka-Cola Quantum now also obey's the player character's Luck. 

[**Lobotomite Tweaks**](https://www.nexusmods.com/newvegas/mods/61706)  
Makes the Old World Blues Lobotomites more challenging by equiparating their traits with those of a freshly operated player.

[**Rigged Shotgun Restoration (with Dead Money support)**](https://www.nexusmods.com/newvegas/mods/66863)  
Restores Fallout 3's rigged shotgun functionality: disarming a rigged shotgun earns you a single shotgun and a 20 gauge shell.
- Install the **Rigged Shotgun Restoration - Lore-Friendly** main file.

[**Tesla Cannon Chaining**](https://www.nexusmods.com/newvegas/mods/65711)  
Upgrades the Tesla Cannon so that it can now actually chain between targets, as it was suggested from the game files but which doesn't actually happen the way it would have been intended in Broken Steel. The Tesla Beaton Prototype is turned into a continuous beam attack weapon.
</details>

# OVERHAULS

These mods rebuild existing mechanics from the ground up, making drastic changes to them that can't be summarized in a few lines without omitting important information, or outright modify how you approach to playing the game, be it because of increased difficulty or reworked mechanics.

[**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of [**jsawyer.esp**](https://fallout-archive.fandom.com/wiki/JSawyer), made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.

Additional files to install:
- **JSawyer Ultimate Edition - Push's Tweaks** (under Optional files).
- [**JSawyer Ultimate Edition Patches**](https://drive.google.com/file/d/1G7YMRR6JXLDU6WhS1hOYZlAD8PW56tP4/view?usp=sharing). Includes patches for **Yukichigai Unofficial Patch**, **Weapon Mesh Improvement Mod**, and **Throwable Weapon Fixes**.
- [**JSawyer Ultimate Edition Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/JSawyer%20Ultimate%20Edition%20Tweaks.7z). Reduces loot, and disables the new Wasteland Merchant and Deranged Bright Brotherhood members. Made by **Qolore**.
- [**Misc Gameplay Merge JSawyer Ultimate Edition Patch**](https://www.nexusmods.com/newvegas/mods/73921) (under Optional files)-

> It is recommended that you play New Vegas at **Hard** difficulty or lower.

[**Laser Weapon Iron Sights**](https://www.nexusmods.com/newvegas/mods/70790)  
Adds iron sights to a variety of laser and plasma weapons which lacked any.
- Install the **Laser Weapon Iron Sights - Gun Runner's Arsenal Merged** and **Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged** main files.

Additional files to install:
- **Laser Weapon Iron Sights - Iron Sight Recoil Animations** (under Optional files).
- **Plasma Weapon Iron Sights - Iron Sight Recoil Animations** (under Optional files).

[**Miscellaneous Tweaks Collection**](https://www.nexusmods.com/newvegas/mods/71847)  
Collection of gameplay tweaks by Qolore7.

[**Less Map Markers**](https://www.nexusmods.com/newvegas/mods/73472)  
 Removes some map markers in an attempt to make exploration more interesting. 

[**Mojave Arsenal**](https://www.nexusmods.com/newvegas/mods/62941)  
Adds ammo variants, reloading parts, and weapon mods as loot, fixes item naming conventions, improves recipes, and adds options for configuring Gun Runners' Arsenal.

Additional files to install:
- [**JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)**](https://www.nexusmods.com/newvegas/mods/62933). Ensures that JSawyer Ultimate's new junk rounds adhere to Mojave Arsenal's naming convention, and merges edits to a single toolbox leveled list. Additionally merges all GRA weapon mods onto vanilla weapons, disabling their GRA weapon variants, and integrates the new GRA weapons and mods into vanilla vendor lists.

[**RAD - Radiation (is) Actually Dangerous**](https://www.nexusmods.com/newvegas/mods/61343)  
Makes radiation work like in Fallout 4, by damaging your max health.

Additional files to install:
- [**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541). Rewrites the entire UI portion and makes major changes to the script, including rebalancing and bugfixes.

[**Unfound Loot**](https://eddoursul.win/mods/unfound-loot/)  
Dynamically lowers the amount of loot in the game.
- Install the **Unfound Loot 1.0rc2** main file located at the bottom of the page.

Additional files to install:
- [**Unfound Loot Custom INI**](https://drive.google.com/file/d/1qPl1C0p5kpK3FDcdrlikQYyxbjcUT_bD/view?usp=sharing). Adjusts loot scarcity.

<details>
	<summary>Overhauls (Optional) - Click to expand</summary>

[**Alternative Repairing**](https://www.nexusmods.com/newvegas/mods/52510)  
Adds repair parts for you to craft and buy, though crafting will likely be your main method of acquiring them. The goal is not to completely revamp item repair, but instead to give you more options and add a bit of satisfaction to scavenging junk.
	
> Note that you will still be able to repair equipment with similar equipment, as in vanilla. An optional feature we will configure requires the player to craft Repair Tools in order to perform any repair.

> This mod is listed under **Optional** because many players may not be interested in expanding the crafting aspect of the game.

Additional files to install:
- [**Alternative Repairing ESP Replacer**](https://drive.google.com/file/d/17JVKIjq90urWOM10twnDb4Uj_Ono5208/view?usp=sharing). Forwards **Yukichigai Unofficial Patch** fixes, including extending the Weapon Repair Kit sound fix to all new Kits.
- [**Alternative Repairing Custom INI**](https://drive.google.com/file/d/1eAek8R92nEReKmR1I-KRyDd0VT8MTg4U/view?usp=sharing). Adds a prefix to parts; disables weapon and armor degradation tweaks; lowers threshold at which apparel is considered clothing.

[**Consistent Pip-Boy Icons Mod Patches**](https://www.nexusmods.com/newvegas/mods/65046)
Upscales one **Mojave Arsenal** icon.
- FOMOD options to install:
  - [X] Alternative Repairing
  - [X] Mojave Arsenal

> Note that, if you wish, you can simply install all default options. This however adds a lot of unnecessary files to your computer.

[**Armor Damage Overhaul**](https://www.nexusmods.com/newvegas/mods/73267)  
Overhauls armor degradation so that it is based on the damage your armor receives, instead of the damage the player receives. This means that high level armor, which on top of having more durability also has better DT and DR, will degrade faster than before.

[**Anatomic Perks**](https://www.nexusmods.com/newvegas/mods/65648)  
Distributes the effect from the Living Anatomy perk to see the target's HP and DT, so that specific perks grant this bonus only against specific enemies.
The Here and Now perk now includes the original effects from Living Anatomy. 

[**Meltdown NVSE Upgrade**](https://www.nexusmods.com/newvegas/mods/65718)  
Overhauls the Meltdown perk to bring its workings under control and actually work as described.

Additional files to install:
- [**Meltdown NVSE Upgrade Custom INI**](https://drive.google.com/file/d/1j7SX1ms_reMGTkVJyrN-9AIPXmraNqfJ/view?usp=sharing). Disables the Rampage feature and the Meltdown feature for companions.

[**Miss Fortune NVSE Upgrade**](https://www.nexusmods.com/newvegas/mods/64709)  
Makes Miss Fortune's effects more consistent. Will avoid affecting non-hostile targets, can now recognize and detonate all kinds of weapons, but won't detonate them near the player or companions.

[**Improved Traits**](https://www.nexusmods.com/newvegas/mods/65403)  
Overhauls vanilla traits and adds two new ones.

[**FNV Opposite Traits**](https://www.nexusmods.com/newvegas/mods/69141)  
New Vegas has two Traits with opposite effects. This mod expands this idea to the game's other Traits.
- Install the **FNV Opposite Traits (YUP OWB)** main file.

[**Improved Opposite Traits and JSUE Patches**](https://drive.google.com/file/d/1zRbTVYbJ5Zba1DQLH5VDY_KwB6LxAwe9/view?usp=sharing)  
Fixes issues with **Improved Traits**, patches **FNV Opposite Traits** for compatibility with **Improved Traits**, and patches both mods for compatibility with **JSawyer Ultimate Edition**. Original patches by Qolore7.
</details>

# CONTENT

[**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.
- Install the **Uncut Wasteland plus NPCs** main file.

Additional files to install:
- [**Uncut Wasteland Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Uncut%20Wasteland%20Tweaks.7z). Small collection of bug fixes and tweaks for Uncut Wasteland. Made by **Qolore**.

[**Mojave Raiders**](https://www.nexusmods.com/newvegas/mods/64660)  
Overhaul of New Vegas's raider factions, balancing their loot and adding more of them to fight.

Additional files to install:
- [**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933). Resolves conflicts between a handful of leveled lists contained in JSawyer Ultimate and Mojave Raiders, and ensures that raiders spawn with .22LR rounds when using Varmint Rifles, to reflect JSawyer Ultimate's ammo change.
- [**Mojave Raiders Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Mojave%20Raiders%20Tweaks.7z). Small collection of balance and consistency tweaks for Mojave Raiders. Made by **Qolore**.

[**Mojave Wildlife**](https://www.nexusmods.com/newvegas/mods/64638)  
Adds hundreds more leveled, vanilla-friendly creature spawn points throughout the whole Mojave, based off unused vanilla leveled lists. All spawn points are meticulously hand-placed and distributed as evenly and fairly as possible.
- Install the **Mojave Wildlife - Vanilla No Chanced Spawns Version** main file.

# VISUALS

[**Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on all distant land.
- Install the **Improved LOD noise Texture** main file.

[**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of Hitman47101's [**Subtle Camera Motion**](https://www.nexusmods.com/newvegas/mods/67728), [**Iron Sights Recoil Animations**](https://www.nexusmods.com/newvegas/mods/67760), [**Fire Animation Variants**](https://www.nexusmods.com/newvegas/mods/67841), as well as new, previously unreleased animations.

Additional files to install:
- [**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320). Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person.
  - Install both main files.

[**Viewmodel Recoil**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

> This mod is compatible with **Immersive Recoil 2.0** (which we installed earlier) and **B42 Weapon Inertia** (which we will install next).

[**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

[**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A skeleton with compatibility for the latest mods.
- The default FOMOD options are fine.

[**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

Additional files to install:
- [**FOV Slider Custom INI**](https://drive.google.com/file/d/1V9Sd35fNQ7KCKGLwzBIpXVXBShfeOrYD/view?usp=sharing). Increases field of view. Recommended to be used alongside **Pip-Boy 2000 Mk VI**, which we will install next.

[**Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/65980)  
New Pip-Boy 2000 Mk VI with custom scratch-made meshes, textures and working clock like in Fallout 76.
- Install the **Pip-Boy 2000 Mk VI replacer version** main file.

Additional files to install:
- **Working date and clock for replacer** (under Optional files).
- [**Pip-Boy 2000 MK VI (Wasteland Edition) Retexture**](https://www.nexusmods.com/newvegas/mods/65999). Gives the Pip-Boy 2000 Mk VI a grittier texture.
- [**Pip-Boy 2000 Mk VI Working Buttons**](https://drive.google.com/file/d/1aOW7BEOM2HfIs2IbtdsApQ05MGpMLn9F/view?usp=sharing). Makes the Pip-Boy's buttons functional. Made by AleksMarch.
- [**NPC Arm Mounted Pip-Boy 2000 Mk VI**](https://drive.google.com/file/d/1XXsje7UP_m_c0s8xrJ2fhZor84IlxPLV/view?usp=sharing). Makes NPCs wear the new Pip-Boy 2000 Mk VI.

[**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 

Additional files to install:
- **Character Expansions Revised - YUP** (under Optional files).
- **Character Expansions Revised - JSU** (under Optional files).
- **Character Expansions Revised - UW** (under Optional files).
- **Character Expansions Revised - MR** (under Optional files).
- [**Character Expansions Revised - AIO Patch**](https://drive.google.com/file/d/1Niq7CocdYuYGY8v6_ZUhWphynCxxyTIp/view?usp=sharing). Ensures compatibility between all of the above patches.

[**Wasteland Flora and Terrain Overhaul**](https://www.nexusmods.com/newvegas/mods/39856)  
Adds more tree and plant variants, implements 3D LODs, and improves grass.
- Install **Wasteland Flora and Terrain Overhaul** first, and then install **Wasteland Flora Overhaul - Vanilla tree replacer with LOD**.
- Hide **WFO - Vanilla.esp**.

Additional files to install:
- [**Wasteland Flora and Terrain Overhaul ESP Replacer**](https://drive.google.com/file/d/1Me0MIZ8apGPxrj7cmSpKUD-vC9jmlZ3k/view?usp=sharing). Removes all new trees and new variants, making it a pure mesh and texture replacer for additional trees not covered by the **Vanilla Tree Replacer** file.

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

[**Strip Lights Region Fix**](https://www.nexusmods.com/newvegas/mods/73596)  
Fixes a vanilla issue about the Strip lights not showing in certain parts of the map.
- Check the following option in the FOMOD installer.
  - [ ] The Living Desert
  - [X] Uncut Wasteland
  - [ ] Vault 22 Flora Overhaul Remastered

[**Better Strip View**](https://www.nexusmods.com/newvegas/mods/73261)  
Adds the Strip signs and moves the Strip buildings to where they should be.

[**Lucky 38 Lights Redone**](https://www.nexusmods.com/newvegas/mods/73273)  
Modifies the Lucky 38 lights before and after they have been turned on during the Mr. House/Yes Man questlines.
- Check the following option in the FOMOD installer.
  - [X] Gold Lights
  - [ ] Silver Lights
  - [ ] Extras Inside the Strip
  - [X] Extras Everywhere
  - [ ] Extras None
  - [X] Pollution Gold Tint
  - [X] Patch for Better Strip View

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

[**FNV Realistic Wasteland Lighting**](https://www.nexusmods.com/newvegas/mods/52037)  
Complete weather overhaul designed to make the game look more realistic. Improves lighting, weather, clouds, stars, moon and the overall look and feel of the wasteland.
- Install the **FNV Realistic Wasteland Lighting - All DLC** main file.

Additional files to install:
- **FNV RWL All DLC - Patch Collection** (under Optional files).
- [**FNV RWL All DLC - Light Tweaks**](https://drive.google.com/file/d/1jRZOqcuCoZqW8KBPPXV4Jk0mIG4qVXjE/view?usp=sharing). Includes changes to the Pip-Boy light and other light sources.
- [**FNV RWL All DLC - Strip Lights AIO Patch**](https://drive.google.com/file/d/1RBmcg0DDkqzqWcc68lTDP_0sbknu3i-j/view?usp=sharing). Solves conflicts with **Strip Lights Region Fix** and **Lucky 38 Lights Redone**.
- [**RWLE - ReShade SweetFX**](https://drive.google.com/file/d/1moXaMjQ31u0FOMgq-kBNXIakDNW_RyI-/view?usp=sharing). Adjusted SweetFX preset.
  - Extract the contents of the archive in your **Root** folder.

[**Mojave Nights - A Moon and Stars Replacer**](https://www.nexusmods.com/newvegas/mods/44381)  
High quality retexture for night sky and moon.
- Install the **Mojave Nights FOMOD** main file.
  - FOMOD options to install:
    - [X] 80% Moon size.
    - [X] Enhanced Night Sky.
    - [X] Low-glow Moon.
- Copy **textures\sky\skystars.dds** and paste it inside **textures\NVDLC02\sky**.

> This will also apply the new night sky texture to Zion.

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

<details>
	<summary>Visuals (Optional) - Click to expand</summary>

[**Diagonal Movement**](https://www.nexusmods.com/newvegas/mods/64333)  
Adds proper diagonal movement animations.

[**360 Movement**](https://www.nexusmods.com/newvegas/mods/71940)  
Adds 360 degrees movement with procedural leaning and auto vanity mode, like modern Bethesda games.
- FOMOD options to install:
  - [X] Full 360 Sneak Options
  - [X] Diagonal Movement Patch

[**Action Camera**](https://www.nexusmods.com/newvegas/mods/66006)  
A tighter and more dramatic view in 3rd-person mode, inspired by Resident Evil 4.

[**Better Gas Leak Effect**](https://www.nexusmods.com/newvegas/mods/55606)  
Makes the gas leak effect much more visible. Accidentally blowing yourself up shouldn't be as common now.

[**HQ Dust Storm FX**](https://www.nexusmods.com/newvegas/mods/53863)  
Retextures dust storms so they aren't as much of an eyesore now.

Additional files to install:
- **Dust Storm Meshes** (under Optional files).

[**HD Mist**](https://www.nexusmods.com/newvegas/mods/58955)  
Retextures mist so that it isn't as much of an eyesore now.
- Only install **HD Mist 2K**.

[**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the distant glow of New Vegas for the sake of darker nights.
- Install the **Slightly Brighter** main file.

Additional files to install:
- [**More Subtle New Vegas Light Pollution Better Strip View Patch**](https://drive.google.com/file/d/1yzntXnRhaCJGsGzUpRytHOyBQ-qNH4qb/view?usp=sharing).

[**Bathroom Doors Overhaul**](https://www.nexusmods.com/newvegas/mods/69486)  
Replaces and adds bathrooms doors all over the Mojave Wasteland. People can finally take a dump in private.
- FOMOD options to install:
  - [X] ALL IN ONE.

[**McCarran Main Terminal Transparent Glass**](https://www.nexusmods.com/newvegas/mods/69041)  
Mesh replacer.
- Only install **McCarran_Glass_transparency_Vanilla_version**.

[**McCarran Escalator Glass**](https://www.nexusmods.com/newvegas/mods/63284)  
Retextures the escalator glass at McCarran so that it isn't as much of an eyesore now.

[**Lucky 38 Intro Poster**](https://www.nexusmods.com/newvegas/mods/54430)  
Adds the Lucky 38 poster seen on the game's intro cinematic to the Lucky 38.

[**Lucky 38 Mainframe No Fingerprints**](https://www.nexusmods.com/newvegas/mods/74055)  
Mesh replacer to remove the huge fingerprint seen on Mr. House's screen.

[**Lower-sitting Ranger Hat**](https://www.nexusmods.com/newvegas/mods/68799)  
Modifies the NCR Ranger Hat and Zion Park Ranger Hat so they sit slightly lower on the head.

[**Metal Helmets - Female Replacements**](https://www.nexusmods.com/newvegas/mods/56699)  
Replaces the female Metal Armor helmets with their male counterparts.

[**Power Armor Gloves**](https://www.nexusmods.com/newvegas/mods/58800)  
Adds armored gloves to all Power Armors in the game.

[**Simple Glowing Ranger Visors**](https://www.nexusmods.com/newvegas/mods/66628)  
Makes the visors of all the Ranger Helmets have a glowing effect.
- Install **Simple Glowing Ranger Visors (No Neck Covers)**.

> The **Neck Covers** alternate file makes Ranger Helmets look goofy when worn without Ranger Armor.

[**Unisex Motorcycle Helmets**](https://www.nexusmods.com/newvegas/mods/36892)  
Replaces the male Motorcycle helmet with its female counterpart.

[**Worn-Out Scope Crosshair Replacers**](https://www.nexusmods.com/newvegas/mods/43181)  
Replaces the vanilla scopes with worn-out scopes to give them a post-apocalyptic feel.
- Install the **Worn-Out Scopes** main file.

[**Securitrons in CRT**](https://www.nexusmods.com/newvegas/mods/63258)  
Adds CRT lines to the monitors of Securitrons.

Additional files to install:
- **OWB in CRT** (under Optional files).

[**Tweaked Standing Idle**](https://www.nexusmods.com/newvegas/mods/42662)  
Straightens out the backs and shoulders of NPCs, and also relaxes the right hand for NPCs wearing power armor. 

Additional files to install:
- [**Tweaked Standing Idle Fix**](https://www.nexusmods.com/newvegas/mods/57041). Enables Headtracking and face animations.

[**Healthier Yao Guai**](https://www.nexusmods.com/newvegas/mods/49707)  
The Yao Guai asset was created for Fallout 3. It looks like a heavily mutated creature, which clashes with Honest Heart's far more healthy and less irradiated enemies. This mod makes Yao Guai blend in better with the other Zoin creatures.
- Only install **Real Bears* (under Optional files).
- Hide **Big Bears.esp**.

[**Y-17 Trauma Override Harness GLOVES**](https://www.nexusmods.com/newvegas/mods/56301)  
Adds gloves to Y-17 Trauma Override Harness, fixing the inconsistency of skeletons being able to move their hands without help.

[**Lonesome Road Carbon Shadow Fix**](https://www.nexusmods.com/newvegas/mods/64022)  
Corrects the burnt silhouette texture found in Lonesome Road to be accurate to real life.
</details>

# AUDIO (OPTIONAL)

[**All Weapon Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/62870)  
Replaces every gun sound in the game, from ballistic to energy weapons.

Additional files to install:
- [**All Weapon Sounds Overhaul ESP Replacer**](https://github.com/VivaNewVegas/Living-in-New-Vegas/blob/master/All%20Weapon%20Sounds%20Overhaul%20ESP%20Replacer.7z). Replaces the ESP with a scripted version that vastly improves compatibility with other mods. Made by **Qolore**.
- [**All Weapon Sounds Overhaul WMIM Patch**](https://drive.google.com/file/d/1EbSEnsWllEqtnMjHg_NnFRVX3oEiaObS/view?usp=sharing). Patches weapon sounds for compatibility with **Weapon Mesh Improvement Mod**.

[**All Explosion Sounds Overhaul**](https://www.nexusmods.com/newvegas/mods/66946)  
Replaces every explosion sound in the game.

Additional files to install:
- **All Explosion Sounds Overhaul SCRIPT Version** (under Optional files). Replaces the ESP with a scripted version that vastly improves compatibility with other mods. Made by **Qolore**.

[**Classic Level Up Sounds**](https://www.nexusmods.com/newvegas/mods/56807)  
Replaces level up sound and level up screen music with sounds from classic Fallout games.
	
[**Classic XP Sound**](https://www.nexusmods.com/newvegas/mods/64514)  
Replaces exp gain sound with the sound from classic Fallout games.

[**Empty Clicks - Improved Dry Fire Sounds**](https://www.nexusmods.com/newvegas/mods/68941)  
Different dry fire (empty magazine) sounds depending on a weapon type and some other improvements.

[**More Accurate Geiger Clicking**](https://www.nexusmods.com/newvegas/mods/68605)  
Increases the Pip-Boy Geiger clicking beyond the vanilla default.

[**No Cocking Sound on Rifle Equip**](https://www.nexusmods.com/newvegas/mods/66698)  
Removes the cocking sound that plays every time you equip a rifle.

[**Female Nuka-Cola Drinking Sound Replacer**](https://www.nexusmods.com/newvegas/mods/68476)  
Replacer for the male drinking sound the game plays whenever you consume a Nuka-Cola.
- Install the **Female Nuka-Cola Drinking Sound replacer** main file.

> Because this mod replaces the vanilla sound, you should only use it when playing a female character.

# LOD RESOURCES

[**FNVLODGen Resources**](https://www.nexusmods.com/newvegas/mods/58562)  
Adds extra meshes for LOD generation.
- Install the **FNVLODGen Resources** main file.

[**LOD Additions and Improvements**](https://www.nexusmods.com/newvegas/mods/61206)  
Adds extra meshes for LOD generation.

[**FNV LOD Supplementation**](https://www.nexusmods.com/newvegas/mods/72099)  
Adds extra meshes for LOD generation.

[**TCM's LOD Overhaul**](https://www.nexusmods.com/newvegas/mods/70155)  
Adds extra meshes for LOD generation.

# FINISHING TOUCHES

## FINAL MOD ORDER AND LOAD ORDER

The mod order dictates the priority a given mod's assets have over the mods installed before it. Respect this order to ensure assets are overwritten as intended.

> Indented you will find mods from the optional sections of the guide.

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
Navmesh Fixes and Improvements
Yukichigai Unofficial Patch - YUP
Landscape Disposition Fix
New Vegas Mesh Improvement Mod
Weapon Mesh Improvement Mod
WMIM ESP Replacer
Throwable Weapon Fixes
Unofficial Patch NVSE Plus
Ammo Burst Case Count Fix
Ammo Script Fixes
Critical and Effects - Fixes and Tweaks
lStewieAl's Tweaks
lStewieAl's Tweaks INI
	Gauss Rifle VATS Fix - JIP
	Universal Pyromaniac Buff for Fire Effects
	Dirty Pre-War Businesswear Texture Fix
	Female White Glove Society Mask Fix
	Gun Runners Kiosk Glass Fix Alternate Version
	Less Flickery City of New Vegas
	No More Dust Devils (and Whirlwinds)
	No Muzzle Flash Lights
UIO - User Interface Organizer
The Mod Configuration Menu
The Mod Configuration Menu Bugfix
JIP Improved Recipe Menu
Vanilla UI Plus (New Vegas)
Clean Vanilla HUD
Consistent Pip-Boy Icons
Consistent Pip-Boy Icons Vanilla UI Plus Patch
	Vanilla HD Missing Icon for Consistent Pip Boy Icons - No More Farting Vault Boy
Satellite World Map
Satellite Maps DLC
Better Character Creation
Faster Pip-Boy Animation
Simple DLC Delay
Snowglobe Tweaks Fix
	Delayed Malcolm
	Ending Slideshows Ultimate Edition Overhaul
Essential DLC Enhancements Merged
Follower Formula Redone
Follower Tweaks
Immersive Recoil 2.0
Jamming Fix and Optional Tweaks
JAM - Just Assorted Mods
JAM - Just Assorted Mods Custom INI
Melee Cleave (a.k.a. Sweep)
Misc Gameplay Merge
Mostly Unarmed Tweaks
NPCs Sprint In Combat
Player Combat Priority
Precise VATS (and actually useful Perception)
Quick Grenade Hotkey
Quick Grenade Hotkey Tweaks
Simple Explosive Entry
Well Rested Overhaul
	Honest Hearts Workbench Crate Luck
	Lobotomite Tweaks
	Rigged Shotgun Restoration - Lore-Friendly
JSawyer Ultimate Edition
JSawyer Ultimate Edition - Push's Tweaks
JSawyer Ultimate Edition Tweaks
JSawyer Ultimate Edition Patches
Misc Gameplay Merge - JSawyer Ultimate Edition Patch
Laser Weapon Iron Sights - Gun Runner's Arsenal Merged
Laser Weapon Iron Sights - Iron Sight Recoil Animations
Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged
Plasma Weapon Iron Sights - Iron Sight Recoil Animations
Miscellaneous Tweaks Collection
Less Map Markers
Mojave Arsenal
JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)
RAD - Radiation (is) Actually Dangerous
RAD - Radiation (is) Actually Dangerous - Overhaul
Unfound Loot
Unfound Loot Custom INI
	Alternative Repairing
	Alternative Repairing ESP Replacer
	Alternative Repairing Custom INI
	Consistent Pip-Boy Icons Mod Patches
	Armor Damage Overhaul
	Anatomic Perks
	Meltdown NVSE Upgrade
	Miss Fortune NVSE Upgrade
	Tesla Cannon Chaining
	Improved Traits
	FNV Opposite Traits (YUP OWB)
	Improved Opposite Traits and JSUE Patches
Uncut Wasteland Plus NPCs
Uncut Wasteland Tweaks
Mojave Raiders
JSawyer Ultimate - Mojave Raiders Patch
Mojave Raiders Tweaks
Mojave Wildlife - Vanilla No Chanced Spawns Version
Improved LOD Noise Texture
Anniversary Anim Pack
Anniversary Anim Pack - General Bugfix
Anniversary Anim Pack - General Bugfix Bonus Patch
Viewmodel Recoil
B42 Weapon Inertia
Diagonal Movement
NV Compatibility Skeleton
360 Movement
FOV Slider
FOV Slider Custom INI
Pip-Boy 2000 Mk VI
Pip-Boy 2000 Mk VI Working Date and Clock
Pip-Boy 2000 Mk VI Working Buttons
Pip-Boy 2000 Mk VI (Wasteland Edition) Retexture
NPC Arm Mounted Pip-Boy 2000 Mk VI (Pluginless)
Character Expansions Revised
Character Expansions Revised - YUP
Character Expansions Revised - JSU
Character Expansions Revised - UW
Character Expansions Revised - MR
Character Expansions Revised - AIO Patch
A Little More Lamplight
Strip Lights Region Fix
Lucky 38 Lights Redone
Strip Lighting Overhaul
FNV Realistic Wasteland Lighting
FNV RWL All DLC - Patch Collection
FNV RWL All DLC - Light Tweaks
FNV RWL All DLC - Strip Lights AIO Patch
Mojave Nights
Night Sky Tweaks
	Action Camera
	Better Gas Leak Effect
	HQ Dust Storm FX
	HQ Dust Storm FX - Dust Storm Meshes
	HD Mist
	More Subtle New Vegas Light Pollution - Slightly Brighter
	More Subtle New Vegas Light Pollution Better Strip View Patch
	Bathroom Doors Overhaul
	McCarran Main Terminal Transparent Glass
	McCarran Escalator Glass
	Lucky 38 Intro Poster
	Lucky 38 Mainframe No Fingerprints
	Lower-sitting Ranger Hat
	Metal Helmets - Female Replacements
	Power Armor Gloves
	Simple Glowing Ranger Visors
	Unisex Motorcycle Helmets
	Worn-Out Scope Crosshair Replacers
	Securitrons in CRT
	OWB in CRT
	Tweaked Standing Idle
	Tweaked Standing Idle Fix
	Healthier Yao Guai
	Y-17 Trauma Override Harness GLOVES
	Lonesome Road Carbon Shadow Fix
	All Weapon Sounds Overhaul
	All Weapon Sounds Overhaul ESP Replacer
	All Weapon Sounds Overhaul WMIM Patch
	All Explosion Sounds Overhaul
	All Explosion Sounds Overhaul SCRIPT Version
	Classic Level Up Sounds
	Classic XP Sound
	Empty Clicks
	More Accurate Geiger Clicking
	No Cocking Sound on Rifle Equip
	Female Nuka-Cola Drinking Sound Replacer
FNVLODGen Resources
LOD Additions and Improvements
FNV LOD Supplementation
TCM's LOD Overhaul
Wasteland Flora and Terrain Overhaul
Wasteland Flora and Terrain Overhaul ESP Replacer
Wasteland Flora Overhaul - Vanilla Tree Replacer with LOD
Better Strip View
```
</details>

The load order dictates the priority a given mod's plugins have over the mods' plugins loaded before them. Respect this order to ensure plugin records are overridden as intended.

> Indented you will find mods from the optional sections of the guide.

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
Navmesh Fixes and Improvements.esm
YUP - Base Game + ALL DLC.esm
Landscape Disposition Fix.esm
Misc Gameplay Merge.esm
Character Expansions Revised.esm
YUP - NPC Fixes (Base Game + All DLC).esp
WMIMNV.esp
ThrowableFixes.esp
Unofficial Patch NVSE Plus.esp
MigMultiCase.esp
AmmoScriptFixes.esp
CriticalEffectFixes.esp
	MigGaussFix.esp
	PyromaniacEffectsBuff.esp
	Pre-War Businesswear Fix.esp
	Female White Glove Society Mask.esp
	LessFlickeryCityOfNewVegas.esp
The Mod Configuration Menu.esp
JIP Improved Recipe Menu.esp
Vanilla UI Plus.esp
map_icon_overhaul.esp
Better Character Creation.esp
Simple DLC Delay.esp
Snowglobe Tweaks.esp
	Delayed Malcolm.esp
	Ending Slideshows Ultimate Edition Overhaul.esp
DLC Enhancements.esp
Follower Formula Redone.esp
Follower Tweaks.esp
ImmersiveRecoil.esp
JamFix.esp
JustAssortedMods.esp
MeleeCleave.esp
MigKao.esp
NPCsSprint.esp
Player Combat Priority.esp
hz_Precise VATS.esp
Quick Grenade Hotkey.esp
Simple Explosive Entry.esp
migWellRested.esp
	Honest Hearts Workbench Crate Luck.esp
	Lobotomitess.esp
	Rigged Shotgun Restoration - Lore-Friendly.esp
JSawyer Ultimate.esp
JSawyer Ultimate - Push's Tweaks.esp
JSUE Tweaks.esp
YUP - JSUE Patch.esp
WMIM - JSUE Patch.esp
Throwable Fixes - JSUE Patch.esp
Misc Gameplay Merge - JSUE Patch.esp
LaserWeaponIronSights.esp
PlasmaWeaponIronSights.esp
Miscellaneous Tweaks.esp
Less Map Markers.esp
Mojave Arsenal.esp
JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged).esp
RAD.esp
Unfound Loot.esp
	Alternative Repairing.esp
	Alternative Repairing - Honest Hearts.esp
	Alternative Repairing - Lonesome Road.esp
	MigArmorDegen.esp
	MigAnatomy.esp
	MigMeltdown.esp
	MigFortune.esp
	MigTeslaChain.esp
	Improved Traits.esp
	Improved Traits Improved.esp
	Improved Traits - JSUE Patch.esp
	FNVOppositeTraits.esp
	FNVOppositeTraits Improved.esp
	FNVOppositeTraits Improved - JSUE Patch.esp
Uncut Wasteland.esp
Uncut Wasteland Tweaks.esp
Mojave Raiders.esp
JSawyer Ultimate - Mojave Raiders Patch.esp
Mojave Raiders Tweaks.esp
Mojave Wildlife (Vanilla-Style + No Chanced).esp
VM_Recoil.esp
B42Inertia.esp
FOVSlider.esp
MCPipBoy2000MK6_clock.esp
Character Expansions Revised - Extras.esp
Character Expansions Revised - YUP.esp
Character Expansions Revised - JSU.esp
Character Expansions Revised - UW.esp
Character Expansions Revised - MR.esp
Character Expansions Revised - AIO Patch.esp
	Diagonal movement.esp
	360Movement.esp
	360Movement - Diagonal movement Patch.esp
	Action Camera.esp
	Bathroom Doors Overhaul - ALL IN ONE.esp
	Lucky 38 intro poster.esp
	Metal Helmet Female Replacements.esp
	lexx_armored_pagloves.esp
	Skinny Bears.esp
	All Weapon Sounds Overhaul.esp
	All Weapon Sounds Overhaul WMIM Patch.esp
	Explosive Sounds Overhaul.esp
	hz_Empty Clicks.esp
	More Accurate Geiger Clicking.esp
Vurt's WFO.esp
Little More Lamplight.esp
Strip Lights Region Fix.esp
Strip Lights Region Fix - Uncut Wasteland.esp
Better Strip View.esp
	vegasglow.esp
	More Subtle New Vegas Light Pollution Better Strip View Patch.esp
Lucky 38 Lights Redone.esp
Strip Lighting Overhaul.esp
FNV Realistic Wasteland Lighting - All DLC.esp
FNV RWL All DLC - Brighter Nights.esp
FNV RWL All DLC - No Overcast Weather.esp
FNV RWL All DLC - Light Tweaks.esp
FNV RWL All DLC - Strip Lights AIO Patch.esp
Mojave Nights.esp
FNVLODGen.esp
tmzLODadditions.esp
```
</details>

## FNVEDIT INSTRUCTIONS

The following mods have conflict issues that need to be addressed, or otherwise aspects we want to see tweaked. It's possible you haven't installed all of them, so simply skip the corresponding instructions.

To make these edits, you will have to launch **FNVEdit** through Mod Organizer 2. Under each spoiler you will find:

- The **plugins** that need to be loaded. This can be one, when it comes to editing a single plugin, or more, when it comes to forwarding changes from one mod to another. Forwarding a change means applying the same change to a mod that sits later in the load order. We will always apply the change to the plugin corresponding to the mod we are trying to fix. This will always be the plugin listed *last* under each spoiler.
- The **instructions** to follow, and the **record** which those instructions have to be applied to. To search for a given record, copy the record ID (which you will find in **bold** at the end of the instructions) and paste it into FNVEdit's **FormID filter** (the empty box labeled **FormID** after you've loaded your plugins in FNVEdit), and then press Enter. This will search for that given record.

Once you've made your edits, you need to exit FNVEdit, and **Save** your changes when prompted.

<details>
	<summary>Dirty Pre-War Businesswear Texture Fix</summary>

Plugins to load:
- **Pre-War Businesswear Fix.esp**

Instructions:
- Forward the vanilla **Name** field for record **0005C682**
- Forward the vanilla **Name** field for record **000B1056**
</details>

<details>
	<summary>Mostly Unarmed Tweaks</summary>

Plugins to load:
- **WMIMNV.eps**
- **MigKao.esp**

Instructions:
- Forward the **Sound - Melee - Swing** field for record **0013316D**
</details>

<details>
	<summary>Well Rested Overhaul</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **migWellRested.esp**

Instructions:
- Forward the **Prompt** field for record **00136240**
- Forward the **Response Text** field for record **001569BC**
</details>

<details>
	<summary>Tesla Cannon Chaining</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **JSawyer Ultimate.esp**
- **MigTeslaChain.esp**

Instructions:
- Forward the **Critical Data** **On Death** flag and **Health** fields for record **0301199E**
</details>

<details>
	<summary>JSawyer Ultimate Edition</summary>

Plugins to load:
- **Female White Glove Society Mask.esp**
- **JSawyer Ultimate.esp**

Instructions:
- Forward the **Female Biped Model** field for record **001168A4**
</details>

<details>
	<summary>Miscellaneous Tweaks Collection</summary>

Plugins to load:
- **JSawyer Ultimate - Push's Tweaks.esp**
- **Miscellaneous Tweaks.esp**

Instructions:
- Forward the **Ingredients** section for record **0201103D**
- Forward the **Ingredients** section for record **02011108**
</details>

<details>
	<summary>Less Map Markers</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **Less Map Markers.esp**

Instructions:
- Forward the **Name** field for record **0015E8AA**
</details>

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

<details>
	<summary>Meltdown NVSE Upgrade</summary>

Plugins to load:
- **MigMeltdown.esp**

Instructions:
- Forward the vanilla **Conditions** section for record **0014609A**
</details>

<details>
	<summary>FNV Opposite Traits</summary>

Plugins to load:
- **FNVOppositeTraits.esp**

Instructions:
- Delete the **Worldspace** tab. It contains dirty edits.
</details>

<details>
	<summary>Action Camera</summary>

Plugins to load:
- **Action Camera.esp**

Instructions:
- Delete the **Quest** and **Script** tabs. They are responsible for the shoulder-swapping feature of the mod, which we are not interested in.
</details>

<details>
	<summary>A Little More Lamplight</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **Little More Lamplight.esp**

Instructions:
- Forward the **Rotation** field for record **001294D6**.
</details>

<details>
	<summary>Better Strip View</summary>

Instructions:
- Run **FNVEditQuickAutoClean**.
- Double-click **Better Strip View.esp**.
- Close the window when the process is finished.
</details>

<details>
	<summary>FNV Realistic Wasteland Lighting</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **DLC Enhancements.esp**
- **FNV Realistic Wasteland Lighting - All DLC.esp**

Instructions:
- Forward the **Object Bounds** section for record **0012A914**
- Forward the **Region Data Entry** (**Sound**) section for record **0200BCB2**
- Forward the **Region Data Entry** (**Sound**) section for record **0200BCB9**
- Forward the **Region Data Entry** (**Sound**) section for record **0200C977**
- Forward the **Region Data Entry** (**Sound**) section for record **020110C0**
</details>

<details>
	<summary>Bathroom Doors Overhaul</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **Bathroom Doors Overhaul - ALL IN ONE.esp**

Instructions:
- Forward the **Ownership** section for record **0010E02A**
- Forward the **Enconter Zone** section for record **001385C4**
</details>

<details>
	<summary>Power Armor Gloves</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **lexx_armored_pagloves.esp**

Instructions:
- Forward the **FormIDs** section for record **0001515B**
</details>

<details>
	<summary>FNVLODGen Resources</summary>

Plugins to load:
- **Vurt's WFO.esp**
- **FNVLODGen.esp**

Instructions:
- Foward the new **Record Flags** fields for record **001093CE**
</details>

<details>
	<summary>LOD Additions and Improvements</summary>

Plugins to load:
- **YUP - Base Game + All DLC.esm**
- **tmzLODadditions.esp**

Instructions:
- Forward the **Record Flags** fields for record **001680AF**
- Forward the **Record Flags** fields for record **0015F5F6**
- Forward the **Record Flags** fields for record **0015F5F7**
</details>
		
## GENERATING LOD

With all our mods and resources installed, we can finally generate our LOD.

- Run **FNVLODGen** in MO2.
- Right click on the list of worldspaces, and click **Select All**.
- Click **Generate**. The process will take some time.
- After the **LOD Generator: finished (you can close this application now)** message appears, close the program.
- Navigate to your **Fallout New Vegas Mods\FNVLODGen Output** folder, and make an archive out of the **textures** and **meshes** folder. Name it **FNVLODGen Output**.
- Install **FNVLODGen Output** with MO2.

## MCM CONFIG

### Quick Grenade Hotkey

- Set **Grenade Hotkey** to **G**.
- Set **Grenade Swap Hotkey** to **C**.

### Mojave Arsenal

- Enable **Low Condition Loot**.
- Disable **Custom Weapons**.
- Enable **Optimized Ammo**.
- Enable **Pulse Slug Recipes**.

### Alternative Repairing

- Enable **Repair Tools**.
- Set **Repair Kits** to **Multi-use**.

## INI CONFIG

### JIP LN NVSE Plugin

Open **NVSE\Plugins\jip_nvse.ini** using a text editor and make the following adjustments.

```
bEnableFO3Repair=1
bNPCWeaponMods=1
uWMChanceMin=5
uWMChanceMax=15
```

> Enables Fallout 3-style repair, as well as a chance for random NPCs to have weapon mods.

### No Muzzle Flash Lights (Optional)

Open **Config\NMFL\NMFL.ini** using a text editor and make the following adjustments.

```
iMuzzleFlashLightsMode = 1
```

> Disables muzzle flash lights for both player and NPCs.

### Vanilla UI Plus

Open **Menus\Prefabs\VUI+\settings.xml** using a text editor and make the following adjustments.

```
<_VUI+NumberedTopics> 1 </_VUI+NumberedTopics>
```

> Displays numbers next to dialogue topics. Intended to be used alongside my **lStewieAl's Tweaks Custom INI**.

### Ending Slideshows Ultimate Edition Overhaul (Optional)

Open **Config\Ending Slideshows Ultimate Edition Overhaul.ini** using a text editor and make the following adjustments.

```
bTrueLonesomeRoad=1
bNoDeadMoneyTeleport=1
```

> Stops the game from teleporting the player to the DLC entrance at both Dead Money and Lonesome Road.

### falloutcustom.ini (Optional)

Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. Paste the following into **falloutcustom.ini**.

```
[Display]
bAllowScreenShot=0

[Imagespace]
bDoDepthOfField=0

[Interface]
fDlgFocus=6.0000
uPipboyColor=1776042495
```

> Disables the built-in screenshot feature in favor of SweetFX's (which will account for its post-processing effects); disables vanilla depth of field effect seen during dialogue; reduces the amount of zoom when engaging in dialogue; tweaks the Pip-Boy HUD color to match that of classic Fallout.

### SweetFX (Optional)

Open **Fallout New Vegas\SweetFX\SweetFX_settings.txt** using a text editor and make the following adjustments.
- Set USE_VIBRANCE = 1
- Set USE_CURVES = 1

> This restores the SweetFX preset to RWLE's original configuration.

# MOD KEYBINDINGS

This is a handy reference table which will hopefully help you have a better idea of what new hotkeys are available to you, having followed this guide from beginning to end.

Key | Function | Added by
------------ | ------------- | -------------
Q | Drop selected item in Pip-Boy | lStewieAl's Tweaks
I | Toggle HUD | lStewieAl's Tweaks
J | Open Pip-Boy quests | lStewieAl's Tweaks
N | Toggle Pip-Boy light | lStewieAl's Tweaks
N | Toggle scope night vision | lStewieAl's Tweaks
M | Open Pip-Boy map | lStewieAl's Tweaks
Ctrl-F | Filter menus in Pip-Boy | lStewieAl's Tweaks
Shift+E | Pick locked door even if you have the key | lStewieAl's Tweaks
Shift+E | Pick up and equip | lStewieAl's Tweaks
Scroll wheel | Adjust binocular zoom | lStewieAl's Tweaks
G | Equip grenade/mine | Quick Grenade Hotkey
C + Scroll wheel | Scroll through grenades/mines | Quick Grenade Hotkey
H | Open weapon wheel | Just Assorted Mods
Shift+Movement | Sprint | Just Assorted Mods

# CHANGELOG

- 🆕 Mod has been added to the guide.
- ⚠️ Mod has been updated or its installation/configuration instructions have changed.
- 🚫 Mod has been removed from the guide.

<details>
	<summary>1.0.4 (December 12th)</summary>

- ⚠️ Changed fDlgFocus setting in **falloutcustom.ini**.
</details>

<details>
	<summary>1.0.3 (December 11th)</summary>

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
- ⚠️ [**Unfound Loot Custom INI**](https://drive.google.com/file/d/1qPl1C0p5kpK3FDcdrlikQYyxbjcUT_bD/view?usp=sharing). Updated to increase the influence of Luck in loot removal, and to make loot removal less dramatic at high Luck. Now loot reduction will range from 90% to 25% (1 Luck and 10 Luck, respectively, as opposed to 90% to 80%).
- ⚠️ [**Alternative Repairing Custom INI**](https://drive.google.com/file/d/1eAek8R92nEReKmR1I-KRyDd0VT8MTg4U/view?usp=sharing). Updated to lower threshold at which apparel is considered clothing. Now JSUE-edited outfits like Leather Armor and Armored Vault Jumpsuits will be repaired with Light Armor Parts.
- ⚠️ [**FOV Slider Custom INI**](https://drive.google.com/file/d/1V9Sd35fNQ7KCKGLwzBIpXVXBShfeOrYD/view?usp=sharing). Updated to reduce weapon FOV.
- 🚫 [**WMIM Mesh Fix**](https://drive.google.com/file/d/1YIpCl0PccRdpQ2ISSMfHS_2gVx4-PtW2/view?usp=sharing). A leftover from when my guide was still a spreadsheet for me to follow, and hadn't been updated to reflect the latest **WMIM ESP Replacer**, which already includes this file.
</details>

<details>
	<summary>1.0.2 (December 10th)</summary>

- 🆕 [**Alternative Repairing**](https://www.nexusmods.com/newvegas/mods/52510). This mod includes in-game **Mod Config** instructions.
- 🆕 [**Quick Grenade Hotkey**](https://www.nexusmods.com/newvegas/mods/64874). This mod includes in-game **Mod Config** instructions.
- ⚠️ [**lStewieAl's Tweaks Custom INI**](https://drive.google.com/file/d/1e3nKqfTKFi846dAZ6t4-EAD8MwDyN4Zo/view?usp=sharing). Updated to increase EXP gain from repairs to 5 EXP (instead of 1 EXP).
- Added additional **Mod Config** tweaks for **falloutcustom.ini**.
- Added link to **Just Weapon Hweel** under **Just Assorted Mods**, which explains how the Weapon Wheel feature works.
</details>

<details>
	<summary>1.0.1 (December 8th)</summary>

- Added missing HQ Dust Storm FX - Dust Storm Meshes to **Mod order**.
- Removed FNVEdit instructions from each separate mod in favor of a single section dedicated to fixing each plugin.
</details>

<details>
	<summary>1.0 (December 7th)</summary>

- Initial release.
- Fixed Custom INI links.
- Completed Keybindings section.
- Added Mojave Arsenal configuration instructions.
- Added SweetFX optional configuration instructions.
</details>

[<< Back to Main](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)
