[<< Back to Main](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)

# LEFT MY HEART IN NEW VEGAS

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# BEFORE WE BEGIN

## DISCLAIMER

The guide presented here assumes you have already followed all instructions found in the [**Setup**](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup) page. Please abstain from using this guide until you've correctly set up Fallout: New Vegas and the recommended tools.

# PATCHES

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles, all while retaining the original triangle ordering at the cell edges whenever possible for maximum compatibility. Also makes improvements to the majority of the affected navmeshes, like adding gaps for obstacles such as rocks and trees.
- Install the **Navmesh Fixes and Improvements - Base Game and ALL DLC** main file.

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
A compilation of vital bug fixes for Fallout: New Vegas and its DLCs, all combined into one ESM. The only pure bug fix compilation available on the Nexus: no new features, no balance tweaks, no restored content.
- Install the **YUP - Base Game and All DLC** main file.

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bugfixes requiring NVSE.

[**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLC.

[**Weapon Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/65052)  
Fixes mesh errors, UV errors, incorrect flags, missing extra data, form lists, projectiles, and other weapon related bugs and errors.
- Also install the [**Viva New Vegas WMIM ESP Replacer**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/WMIM%20ESP%20Replacer.7z). Removes all changes the mod makes other than the changes required for the mesh fixes, as the original ESP has some bugs, conflicts, and many non-bug fix changes.

[**Throwable Weapon Fixes**](https://www.nexusmods.com/newvegas/mods/62767)  
A collection of fixes for throwable weapons, focused on projectiles.

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**Less Flickery City of New Vegas**](https://www.nexusmods.com/newvegas/mods/72061)  
Fixes the intense flickering in the city of New Vegas (such as when looking from Goodsprings Cemetery) due to extra white proxy meshes clipping into the object LOD meshes.

[**Sierra Madre Exterior Fixed**](https://www.nexusmods.com/newvegas/mods/66775)  
Fixes the texture on the Sierra Madre exterior.

<details>
	<summary>Optional Patches - Click to expand</summary>

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Ammo Script Fixes**](https://www.nexusmods.com/newvegas/mods/63997)  
Fixes several problems at the core level with how ammo scripts and effects work, plus some tweaks for consistency and fun.

[**Critical and Effects - Fixes and Tweaks**](https://www.nexusmods.com/newvegas/mods/69200)  
Fixes the damage dealing critical effects of most vanilla weapons so that they cannot cause you to miss "killcounts" and other proc effects such as crime responsibility.

[**Gauss Rifle VATS Fix - JIP**](https://www.nexusmods.com/newvegas/mods/69136)  
Fixes the Gauss Rifle not dealing headshot and critical damage in VATS.

[**Meltdown NVSE Upgrade**](https://www.nexusmods.com/newvegas/mods/65718)  
Overhauls the Meltdown perk to bring its workings under control and actually work as described.

[**Miss Fortune NVSE Upgrade**](https://www.nexusmods.com/newvegas/mods/64709)  
Makes Miss Fortune's effects more consistent. Will avoid affecting non-hostile targets, can now recognize and detonate all kinds of weapons, but won't detonate them near the player or companions.

[**Mostly Unarmed Tweaks**](https://www.nexusmods.com/newvegas/mods/69283)  
Fixes the fatigue-dealing weapons to deal correct and damage-adjusted fatigue to enemies and the player, plus a few more changes related to unarmed combat for player and NPCs.
- Also install [**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336).
- Also install [**ShowOff NVSE Plugin**](https://github.com/Demorome/Showoff-NVSE/releases).

> Both NVSE plugins are required by this mod.

[**Tesla Cannon Chaining**](https://www.nexusmods.com/newvegas/mods/65711)  
Upgrades the Tesla Cannon so that it can now actually chain between targets. The Tesla Beaton Prototype is turned into a continuous beam attack weapon.

[**Universal Pyromaniac Buff for Fire Effects**](https://www.nexusmods.com/newvegas/mods/71505)  
Makes the Pyromaniac perk affect *all* the lingering fire damage effects from weapons and ammo.

[**Dirty Pre-War Businesswear Texture Fix**](https://www.nexusmods.com/newvegas/mods/65774)  
Fixes the Dirty Pre-War Businesswear and Grimy Pre-War Businesswear having the incorrect textures.
- Undo the Armor name changes in **FNVEdit**.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.
- Hide **Female White Glove Society Mask.esp**. We will install a JSawyer Ultimate-compatible plugin in the **Overhauls** section.

[**Gun Runners Kiosk Glass Fix**](https://www.nexusmods.com/newvegas/mods/70293)  
Fixes the glass texture in the Gun Runners' kiosk.
- Only install the **Gun Runners Kiosk Glass Fix Alternate Version B** optional file.

[**Lonesome Road Carbon Shadow Fix**](https://www.nexusmods.com/newvegas/mods/64022)  
Corrects the burnt silhouette texture found in Lonesome Road to be accurate to real life.
</details>

# USER INTERFACE

[**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.
- Also install the **MCM BugFix 2** update file.

[**JIP Improved Recipe Menu**](https://www.nexusmods.com/newvegas/mods/59638)  
Makes the crafting interface easier, more efficient and less tedious to use. 

[**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- Check the following options in the FOMOD installer.
  - [X] Default Font Tweaks
  - [ ] Classic Pip-Boy Font
  - [ ] No Font Tweaks
  - [X] Plugin
  - [X] WASD Compatible 
- Right-click on the installed file and click **Open in Explorer**.
- Open **Menus\Prefabs\VUI++\settings.xml** using a text editor.
- Set **VUI+NumberedTopics** to 1.
- Save your changes.

> Displays numbers next to dialogue topics. A must have if using a mods that assigns dialogue topics numeric shortcuts.

[**Vanilla HUD Cleaned**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- Check the following options in the FOMOD installer.
  - Enable all **Modules** and **Tweaks** options. Do not enable the **DarnUI Specific** options.

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Lore-friendly overhaul of New Vegas icons to make them more consistent in terms of coloring and transparency. Includes other bug fixes.
- Install the **1. Consistent Pip-boy Icons** main file.
- Also install the **6. Vanilla UI Plus Patch** optional file.
- Optionally install [**Vanilla HD Missing Icon for Consistent Pip Boy Icons - No More Farting Vault Boy**](https://www.nexusmods.com/newvegas/mods/73375). Replaces the farting vault boy/junk image options of Consistent Pip Boy icons with an upscaled HD version of the vanilla missing item icon. 

[**Faction Map Icon Overhaul**](https://www.nexusmods.com/newvegas/mods/72181)  
Replaces the icons of several locations with Faction-appropriate ones.

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.
- Install the **Satellite World Map** main file.
- Also install [**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292). High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and  Lonesome Road.

# QUALITY OF LIFE IMPROVEMENTS

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

[**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.
- Install the **Faster Pip-Boy Animation (2x)** main file.

[**No More Dust Devils (and Whirlwinds)**](https://www.nexusmods.com/newvegas/mods/74167)  
Removes all the dust devils and whirlwinds from the game (and any DLC/mod that might use them). Optionally removes tumbleweeds too.

[**Simple DLC Delay**](https://www.nexusmods.com/newvegas/mods/62779)  
Delays DLC pop-ups until you meet certain level requirements or discover the entrances to the DLC areas.

[**Snowglobe Tweaks Fix**](https://www.nexusmods.com/newvegas/mods/67466)  
Requires the player to discover the snow globe display in the Lucky 38 Presidental Suite before being able to sell the snow globes to Jane. DLC snow globes now need to be sold to Jane, and the Dead Money snow globe rewards 2,000 caps instead of 2,000 Sierra Madre chips.

[**Weapon Binding Ritual No Message or Screenspace Effect**](https://www.nexusmods.com/newvegas/mods/73013)  
Makes the Weapon Binding Ritual visually consistent with other chems and buff items, and much less annoying as a result.
- Install this mod if you don't plan to use **JSawyer Ultimate**. Otherwise, we will install a JSawyer Ultimate-compatible plugin in the **Overhauls** section.

# GAMEPLAY

[**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

[**Follower Formula Redone**](https://www.nexusmods.com/newvegas/mods/71490)  
Limits the amount of followers the player can have depending on their Charisma stat divided by 2, rounded down. The player will need at least 2 Charisma to have one follower, and they can have 5 followers at most.

[**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving. 

[**Immersive Hit Reactions**](https://www.nexusmods.com/newvegas/mods/66646)  
Enemies will react more to getting shot or hit, making them feel less like a bullet sponge. The player can now also react to getting shot.

[**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

[**Jamming Fix and Optional Tweaks**](https://www.nexusmods.com/newvegas/mods/66293)  
Fixes the on-fire jamming for automatic weapons and adds an option for how often weapons jam.

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

[**Melee Cleave (a.k.a. Sweep)**](https://www.nexusmods.com/newvegas/mods/66187)  
Makes melee attacks hit multiple enemies.

[**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

[**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Prevents the game from becoming too easy by making enemies more likely to target the player in combat rather than companions.

[**Precise VATS (and actually useful Perception)**](https://www.nexusmods.com/newvegas/mods/69202)  
Requires the player's crosshair to be aiming at the target in order to activate VATS, namd makes the VATS activation range and target switching distance to be dynamic and dependent on a few factors, including Perception level, weapon scope, Enhanced Sensors and Spotter Perks, and Power Armor.

[**Simple Explosive Entry**](https://www.nexusmods.com/newvegas/mods/66992)  
Allows the player to use explosives to bypass locks. Items have a chance of being destroyed, with the exception of notes and quest items.

[**Well Rested Overhaul**](https://www.nexusmods.com/newvegas/mods/64628)  
Expands how the Well Rested effect works. Effect duration is now in actual game hours, gives a few more buffs aside from increased XP, and patches all the game prostitutes' scripts to also grant the buff for purchasing their services.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **Yukichigai Unofifcial Patch** Dialog Topic fixes.

<details>
	<summary>Optional Gameplay - Click to expand</summary>

[**Flirting Perks Require 5 Charisma**](https://www.nexusmods.com/newvegas/mods/67594)  
Black Widow, Cherchez La Femme, Confirmed Bachelor, and Lady Killer all require 5 or more Charisma to acquire now.
- Install the **JSawyer (Ultimate) version** main file.

[**Honest Hearts Workbench Crate Luck**](https://www.nexusmods.com/newvegas/mods/62415)  
Forces the Honest Hearts workbench crates (the only source of skill books in the Honest Hearts DLC) to obey the player character's Luck as opposed to generating random loot. The lone bottle of Nuka-Cola Quantum now also obey's the player character's Luck. 

[**Lobotomite Tweaks**](https://www.nexusmods.com/newvegas/mods/61706)  
Gives the Old World Blues Lobotomites traits similar to those of a freshly operated player.

[**Luck Based Sunset Sarsparilla Star Bottle Caps**](https://www.nexusmods.com/newvegas/mods/44884)  
Gives the player a Sunset Sarsaparilla Star Cap when drinking Sunset Sarsaparilla based on their Luck attribute. 

[**Mines Go Boom**](https://www.nexusmods.com/newvegas/mods/73514)  
Adds a chance for a mine to explode when you attempt to disarm it, based on your Explosives skill and Luck.
	
[**Rigged Shotgun Restoration (with Dead Money support)**](https://www.nexusmods.com/newvegas/mods/66863)  
Restores Fallout 3's rigged shotgun functionality: disarming a rigged shotgun earns you a single shotgun and a 20 gauge shell.
- Install the **Rigged Shotgun Restoration - Lore-Friendly** main file.

[**Sun Guard During Sunshine**](https://www.nexusmods.com/newvegas/mods/71710)  
Prevents the headgear Sun Guard effect to take place during nighttime and inside interiors.
</details>

# OVERHAULS

These mods rebuild existing mechanics from the ground up, making drastic changes to them that can't be summarized in a few lines without omitting important information, or outright modify how you approach to playing the game, be it because of increased difficulty or reworked mechanics.

[**JSawyer Ultimate Edition**](https://www.nexusmods.com/newvegas/mods/61592)  
Completely reconstructed version of Josh Sawyer's jsawyer.esp, made from the ground up. Tweaks inconsistencies, expands compatibility, re-adds some elements of cut content, and covers additional balance issues which were missed.
- Also install the **JSawyer Ultimate Edition - Push's Tweaks** optional file.
- Also install [**JSawyer Ultimate Edition Patches**](https://drive.google.com/file/d/1_OqmPUIjHKF_0gq0Cxw8U431MZcPig9Y/view?usp=sharing). A variety of patches for mods featured in this guide.

[**Anatomy Perks**](https://www.nexusmods.com/newvegas/mods/65648)  
Distributes the effect from the Living Anatomy perk to see the target's HP and DT, so that specific perks grant this bonus only against specific enemies. Alternatively, the Here and Now perk also includes this ability.

[**Perk-based Creature Loot**](https://www.nexusmods.com/newvegas/mods/73847)  
Locks loot-drops from animals, insects, and some mutants behind Hunter, Entomologist, and Purifier respectively.
- Also install [**Perk-based Creature Loot Patches**](https://drive.google.com/file/d/1eqQ953FCYwb4EQJiIMUBEXM7FyY58Kww/view?usp=sharing). Adds patches for **Anatomy Perks** and **JSawyer Ultimate Edition**, fixing conflicting Perk and Leveled List edits.

[**Improved Traits**](https://www.nexusmods.com/newvegas/mods/65403)  
Overhauls vanilla traits and adds two new ones.

[**FNV Opposite Traits**](https://www.nexusmods.com/newvegas/mods/69141)  
New Vegas has two Traits with opposite effects. This mod expands this idea to the game's other Traits.
- Install the **FNV Opposite Traits (YUP OWB)** main file.
- Delete the **Worldspace** record tab in **FNVEdit**. It contains dirty edits.

[**Laser Weapon Iron Sights**](https://www.nexusmods.com/newvegas/mods/70790)  
Adds iron sights to a variety of laser and plasma weapons which lacked any.
- Install the **Laser Weapon Iron Sights - Gun Runner's Arsenal Merged** and **Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged** main files.
- Also install the **Laser Weapon Iron Sights - Iron Sight Recoil Animations** and **Plasma Weapon Iron Sights - Iron Sight Recoil Animations** optional files.

[**Miscellaneous Tweaks Collection**](https://www.nexusmods.com/newvegas/mods/71847)  
Collection of gameplay tweaks by Qolore7.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **JSawyer Ultimate - Push's Tweaks** Ingredients tweaks for **NVDLC02RecipeHealingPoultice** and **NVDLC02RecipeDaturaAntivenom**.

[**Misc Gameplay Merge**](https://www.nexusmods.com/newvegas/mods/73921)  
Compilation of small gameplay mods by various authors, all fully fixed, optimized, and updated by Qolore7.
- Also install the **JSawyer Ultimate Edition Patch** optional file.

[**Less Map Markers**](https://www.nexusmods.com/newvegas/mods/73472)  
 Removes some map markers in an attempt to make exploration more interesting. 
- Enter **0015E8AA** into **FNVEdit**'s FormID filter. Forward the **YUP - Base Game + All DLC** Map Marker Name fix.

[**Mojave Arsenal**](https://www.nexusmods.com/newvegas/mods/62941)  
Adds ammo variants, reloading parts, and weapon mods as loot, fixes item naming conventions, improves recipes, and adds options for configuring Gun Runners' Arsenal.
- **Apply Filter to Show Conflicts** in **FNVEdit**.
  - Forward the **Unofficial Patch NVSE Plus** Challenge fix for **NVDLC05ChallengeDeathclawProHunter**.
  - Forward the **JSawyer Ultimate** Ingredients tweaks for **RecipePowderCharge**.
  - Forward the **Miscellaneous Tweaks** Conditions tweaks for **NVDLC02RecipeBreakdown45Auto**.
- Also install [**JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)**](https://www.nexusmods.com/newvegas/mods/62933). Ensures that JSawyer Ultimate's new junk rounds adhere to Mojave Arsenal's naming convention, and merges edits to a single toolbox leveled list. Additionally merges all GRA weapon mods onto vanilla weapons, disabling their GRA weapon variants, and integrates the new GRA weapons and mods into vanilla vendor lists.
  - **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the three **Miscellaneous Tweaks** Leveled List records for VendorWeaponsMeleeTier3.

[**RAD - Radiation (is) Actually Dangerous**](https://www.nexusmods.com/newvegas/mods/61343)  
Makes radiation work like in Fallout 4, by damaging your max health.
- Also install [**RAD - Radiation (is) Actually Dangerous - Overhaul**](https://www.nexusmods.com/newvegas/mods/71541). Rewrites the entire UI portion and makes major changes to the script, including rebalancing and bugfixes.

[**Unfound Loot**](https://eddoursul.win/mods/unfound-loot/)  
Dynamically lowers the amount of loot in the game.
- Install the **Unfound Loot 1.0rc2** main file located at the bottom of the page.
- Also install the [**Viva New Vegas Unfound Loot Custom INI**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Unfound%20Loot%20Custom%20INI.7z).

# CONTENT

[**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.
- Install the **Uncut Wasteland plus NPCs** main file.
- Also install the [**Viva New Vegas Uncut Wasteland Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Uncut%20Wasteland%20Tweaks.7z). Small collection of bug fixes and tweaks for Uncut Wasteland.

[**Mojave Raiders**](https://www.nexusmods.com/newvegas/mods/64660)  
Overhaul of New Vegas's raider factions, balancing their loot and adding more of them to fight.
- Also install [**JSawyer Ultimate - Mojave Raiders Patch**](https://www.nexusmods.com/newvegas/mods/62933). Resolves conflicts between a handful of leveled lists contained in JSawyer Ultimate and Mojave Raiders, and ensures that raiders spawn with .22LR rounds when using Varmint Rifles, to reflect JSawyer Ultimate's ammo change.
- Also install the [**Viva New Vegas Mojave Raiders Tweaks**](https://github.com/VivaNewVegas/Viva-New-Vegas-Patch-Emporium/blob/main/Mojave%20Raiders%20Tweaks.7z). Small collection of balance and consistency tweaks for Mojave Raiders.

[**Mojave Wildlife**](https://www.nexusmods.com/newvegas/mods/64638)  
Adds hundreds more leveled, vanilla-friendly creature spawn points throughout the whole Mojave, based off unused vanilla leveled lists. All spawn points are meticulously hand-placed and distributed as evenly and fairly as possible.
- Install the **Mojave Wildlife - Vanilla No Chanced Spawns Version** main file.

# AUDIO

[**Empty Clicks - Improved Dry Fire Sounds**](https://www.nexusmods.com/newvegas/mods/68941)  
Different dry fire (empty magazine) sounds depending on a weapon type and some other improvements.

[**More Accurate Geiger Clicking**](https://www.nexusmods.com/newvegas/mods/68605)  
Increases the Pip-Boy Geiger clicking beyond the vanilla default.

[**No Cocking Sound on Rifle Equip**](https://www.nexusmods.com/newvegas/mods/66698)  
Removes the cocking sound that plays every time you equip a rifle.

<details>
	<summary>Optional Audio - Click to expand</summary>

[**Female Nuka-Cola Drinking Sound Replacer**](https://www.nexusmods.com/newvegas/mods/68476)  
Replacer for the male drinking sound the game plays whenever you consume a Nuka-Cola.
- Install the **Female Nuka-Cola Drinking Sound replacer** main file.

> Because this mod replaces the vanilla sound, you should only use it when playing a female character.
</details>
	
# VISUALS

[**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

[**Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on all distant land.
- Install the **Improved LOD noise Texture** main file.

[**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of Hitman47101's [**Subtle Camera Motion**](https://www.nexusmods.com/newvegas/mods/67728), [**Iron Sights Recoil Animations**](https://www.nexusmods.com/newvegas/mods/67760), [**Fire Animation Variants**](https://www.nexusmods.com/newvegas/mods/67841), as well as new, previously unreleased animations.
- Also install [**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320). Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person.
  - Install both main files.

[**DiaMoveNVSE**](https://www.nexusmods.com/newvegas/mods/66451)  
Enables simple diagonal movements for the player character.

[**Ragdolls**](https://www.nexusmods.com/newvegas/mods/59147)  
Improves ragdoll behaviour for all NPC/Creatures in the game, and restores hit reactions. Includes configuration options.
- Install the **Ragdolls** main file.
- **Apply Filter to Show Conflicts** in **FNVEdit**.
  - Forward the **YUP - Base Game + All DLC** Model fix for **DLCPittTrogBodyPartData**.
  - Forward the **YUP - Base Game + All DLC** Body Part fix for **NVDLC01GhostBodyPartData**.
  - Forward the **YUP - Base Game + All DLC** Ragdoll fix for **NVDLC03BrainBotbodypartdata**.
  - Forward the **YUP - Base Game + All DLC** Actor Base fix for **TrogRagdoll**.

[**Viewmodel Recoil**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

> This mod is compatible with **Immersive Recoil 2.0** (which we installed earlier) and **B42 Weapon Inertia** (which we will install next).

[**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

[**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A skeleton with compatibility for the latest mods.

[**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 
- Also install **Character Expansions Revised - YUP**, **Character Expansions Revised - JSU**, **Character Expansions Revised - UW**, and **Character Expansions Revised - MR**.
- Also install [**Character Expansions Revised - AIO Patch**](https://drive.google.com/file/d/1Niq7CocdYuYGY8v6_ZUhWphynCxxyTIp/view?usp=sharing). 

[**Wasteland Flora and Terrain Overhaul**](https://www.nexusmods.com/newvegas/mods/39856)  
Adds more tree and plant variants, implements 3D LODs, and improves grass.
- Install both main files.
- Hide **WFO - Vanilla.esp**.
- Also install [**Wasteland Flora and Terrain Overhaul ESP Replacer**](https://drive.google.com/file/d/1Me0MIZ8apGPxrj7cmSpKUD-vC9jmlZ3k/view?usp=sharing). Removes all new trees and new variants, making it a pure mesh and texture replacer for additional trees not covered by the **Vanilla Tree Replacer** file.

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 
- Enter **001294d6** into **FNVEdit**'s FormID filter. Forward the **YUP - Base Game + All DLC** Rotation fix.

[**Strip Lights Region Fix**](https://www.nexusmods.com/newvegas/mods/73596)  
Fixes a vanilla issue about the Strip lights not showing in certain parts of the map.
- Check the following option in the FOMOD installer.
  - [ ] The Living Desert
  - [X] Uncut Wasteland
  - [ ] Vault 22 Flora Overhaul Remastered

[**Better Strip View**](https://www.nexusmods.com/newvegas/mods/73261)  
Adds the Strip signs and moves the Strip buildings to where they should be.
- Install the **Better Strip View** main file.
- Enter **00149D78** into **FNVEdit**'s FormID filter. Forward the **YUP - Base Game + All DLC** Acoustic Space fix.

[**Lucky 38 Lights Redone**](https://www.nexusmods.com/newvegas/mods/73273)  
Modifies the Lucky 38 lights before and after they have been turned on during the Mr. House/Yes Man questlines.
- Check the following option in the FOMOD installer.
  - [ ] Gold Lights
  - [X] Silver Lights
  - [ ] Extras Inside the Strip
  - [X] Extras Everywhere
  - [ ] Extras None
  - [ ] Pollution Gold Tint
  - [X] Patch for Better Strip View

[**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the distant glow of New Vegas for the sake of darker nights.
- Install the **Slightly Brighter** main file.
- Also install the [**More Subtle New Vegas Light Pollution Better Strip View Patch**](https://drive.google.com/file/d/1yzntXnRhaCJGsGzUpRytHOyBQ-qNH4qb/view?usp=sharing).

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

[**FNV Realistic Wasteland Lighting**](https://www.nexusmods.com/newvegas/mods/52037)  
Complete weather overhaul designed to make the game look more realistic. Improves lighting, weather, clouds, stars, moon and the overall look and feel of the wasteland.
- Install the **FNV Realistic Wasteland Lighting - All DLC** main file.
- Also install the **FNV RWL All DLC - Patch Collection** optional file.
- Also install [**RWL Tweaked - Light Tweaks**](https://drive.google.com/file/d/1g-OESAeJfAbsCSPGDoP1uwOTtH9I9qHL/view). Includes changes to the Pip-Boy light and other light sources.
- Also install [**FNV RWL All DLC - Strip Lights AIO Patch**](https://drive.google.com/file/d/1RBmcg0DDkqzqWcc68lTDP_0sbknu3i-j/view?usp=sharing). Solves conflicts with **Strip Lights Region Fix** and **Lucky 38 Lights Redone**.
- Also install [**RWLE - ReShade SweetFX**](https://drive.google.com/file/d/1dGT-BhI3xM9Zt90jYXJDwmZ3Aj8oQNDe/view). Adjusted SweetFX preset.
  - Extract the contents of the archive in your **Root** folder.
- **Apply Filter to Show Conflicts** in **FNVEdit**.
  - Forward the **YUP - Base Game + All DLC** Object Bounds fix for **GreenhouseWorld01**.
  - Forward the **DLC Enhancements** Region Data Entry Sound tweaks for **NVDLC02MapEasternVirgin**, **NVDLC02TheNarrowsRegion**, **NVDLC02MapTheThreeMarysRegion**, and **NVDLC02ZionValleyRegion**.

[**Mojave Nights - A Moon and Stars Replacer**](https://www.nexusmods.com/newvegas/mods/44381)  
High quality retexture for night sky and moon.
- Install the **Mojave Nights FOMOD** main file. I suggest setting the moon to 200% size.
- Copy of **textures\sky\skystars.dds** and paste it inside **textures\NVDLC02\sky**.

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.

<details>
	<summary>Optional Visuals - Click to expand</summary>

[**Bathroom Doors Overhaul**](https://www.nexusmods.com/newvegas/mods/69486)  
Replaces and adds bathrooms doors all over the Mojave Wasteland. People can finally take a dump in private.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **YUP - Base Game + All DLC** Encounter Zone fix for **NiptonHouse7Tinker**.

[**Lucky 38 Intro Poster**](https://www.nexusmods.com/newvegas/mods/54430)  
Adds the Lucky 38 poster from the game's intro FMV.

[**Lucky 38 Mainframe No Fingerprints**](https://www.nexusmods.com/newvegas/mods/74055)  
Gets rid of the big fingerprint on Mr. House/Yes Man's screen.
- Also install the **Securitrons No Fingerprints** optional file.
	
[**McCarran Escalator Glass**](https://www.nexusmods.com/newvegas/mods/63284)  
Makes the McCarran escalator glass texture transparent.

[**McCarran Main Terminal Transparent Glass**](https://www.nexusmods.com/newvegas/mods/69041)  
Makes the McCarran Terminal glass transparent.
- Install the **McCarran_Glass_transparency_Vanilla_version** main file.

[**Lower-Sitting Ranger Hat**](https://www.nexusmods.com/newvegas/mods/68799)  
Modifies the Ranger Hat so it sits slightly lower on the head. 

[**Metal Helmets - Female Replacements**](https://www.nexusmods.com/newvegas/mods/56699)  
Replaces the female Metal Armor helmets with their male counterparts.

[**Power Armor Gloves**](https://www.nexusmods.com/newvegas/mods/58800)  
Adds armored gloves to all Power Armors in the game.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **YUP - Base Game + All DLC** FormIDs fix for **ArmorPowerList**.

[**Unisex Motorcycle Helmets**](https://www.nexusmods.com/newvegas/mods/36892)  
Replaces the male Motorcycle helmet with its female counterpart.

[**Y-17 Trauma Override Harness Gloves**](https://www.nexusmods.com/newvegas/mods/56301)  
Adds gloves to Y-17 Trauma Override Harness, fixing an in-game inconsistency.

[**Worn-Out Scope Crosshair Replacers**](https://www.nexusmods.com/newvegas/mods/43181)  
Replaces the vanilla scopes with worn-out scopes to give them a post-apocalyptic feel.
- Install the **Worn-Out Scopes** main file.

[**Alsatian NCR Guard Dogs**](https://www.nexusmods.com/newvegas/mods/39232)  
Replaces the vicious NCR guard dogs with Alsatian dogs.

[**Bighorner Model Variants**](https://www.nexusmods.com/newvegas/mods/62672)  
Adds model variations for Bighorners. Now there's a visual difference between Bighorners, their calfs, and their bulls.
- Install the **Bighorner Model Variants - Standard** main file.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **YUP - Base Game + All DLC** Record Flags fix for **NVCrBigHornerCalfDEAD**.

[**Brahmin Variant Redux**](https://www.nexusmods.com/newvegas/mods/58871)  
Adds model variations for Brahmin. Healthy Brahmin, sick Brahmin, random amount of horns, and calf-looking Brahmin calfs.
- **Apply Filter to Show Conflicts** in **FNVEdit**.
  - Forward the **YUP - Base Game + All DLC** Record Flags fix for **DeadBrahmin**.
  - Forward the **YUP - Base Game + All DLC** Record Flags fix for **DeadBrahmin2**.
  - Forward the **YUP - Base Game + All DLC** Configuration Flags, Level, and Packages fixes for **DEADCaravanBrahmin**.
  - Forward the **YUP - Base Game + All DLC** Record Flags fix for **VFSBrahminPackWaterDEAD**.
  - Forward the **YUP - Base Game + All DLC** Record Flags, Configuration Flags, Level, and Packages fixes for **DEADCaravanBrahminCGCave**.

[**Healthier Yao Guai**](https://www.nexusmods.com/newvegas/mods/49707)  
Makes Yao Guai look less mutated and more like actual bears.
- Install the **Real Bears** main file.
- Hide **Big Bears.esp**.

[**Securitrons in CRT**](https://www.nexusmods.com/newvegas/mods/63258)  
Adds CRT lines to the monitors of Securitrons.
- Also install the **OWB in CRT** optional file.

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.
- Install the **tkEyelashesFNV** main file.
- Hide **tkEyelashesFNV_FemalesOnly.esp**.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **YUP - Base Game + All DLC** Female Head Data Part fix for **AfricanAmericanChild**.
- Replace **Characters\head\HeadOld.nif** with **Characters\Eyelashes\LashesHeadOld.nif** under the **HispanicOldAged** Race record.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.
- Install all three main files.

[**Natural Eyes**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.
- Install the **00 - Natural Eyes - Shadow** main file.

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

[**Vanilla Underwear Replacer**](https://www.nexusmods.com/newvegas/mods/64006)  
Replacer for the default underwear, removing the shirt for males and tweaking the shape of the female top.

[**New Vegas - Enhanced Camera**](https://www.nexusmods.com/newvegas/mods/55334)  
Enables visible body and player shadows when in first person. Also, any points where the game force switches to 3rd person are now in 1st person.

[**Empty Weapons**](https://www.nexusmods.com/newvegas/mods/67245)  
Slides stay locked back on empty handguns.

[**Tweaked Standing Idle**](https://www.nexusmods.com/newvegas/mods/42662)  
Straightens out the backs and shoulders of NPCs, and also relaxes the right hand for NPCs wearing power armor. 
- Also install [**Tweaked Standing Idle Fix**](https://www.nexusmods.com/newvegas/mods/57041). Enables Headtracking and face animations.

[**Pip-Boy 2000 Mk VI**](https://www.nexusmods.com/newvegas/mods/65980)  
New Pip-Boy 2000 Mk VI with custom scratch-made meshes, textures and working clock like in Fallout 76.
- Install the **Pip-Boy 2000 Mk VI replacer version** main file.
- Also install the **Working date and clock for replacer** optional file.
- Also install [**Pip-Boy 2000 MK VI (Wasteland Edition) Retexture**](https://www.nexusmods.com/newvegas/mods/65999). Gives the Pip-Boy 2000 Mk VI a grittier texture.
- Also install [**NPC Arm Mounted Pip-Boy 2000 Mk VI**](https://drive.google.com/file/d/1x__HD37kKOdKDo_wF0vy3C7-1hn0U3KI/view). Makes NPCs wear the new Pip-Boy 2000 Mk VI.
</details>

# BODY REPLACERS

[**TYPE4 - Body and Armors**](https://www.nexusmods.com/newvegas/mods/66903)  
Female body replacer featuring no neckseams and much improved arms and upperbody. Complete set of armor and clothing with support for all DLCs.
- Also install [**TYPE 4 Patches**](https://drive.google.com/file/d/15PlLJxpq_AsnbaNZlSkTndXwM83oIfu_/view?usp=sharing). A variety of patches for mods featured in this guide.
- Delete the following records in **FNVEdit**.
  - ArmorRadiationSuit
  - ArmorRadiationSuitAdvanced
  - MS03EnvironmentSuit
  - CSArmorRadiationSuit
- Hide the **meshes\armor\enclavescientist** folder.

> This removes the Radiation Suit and related changes which are, frankly, terrible.

[**Mannequin Races**](https://www.nexusmods.com/newvegas/mods/62785)  
Adds seven new custom races to Fallout New Vegas.
- Also install the **00 - EGM files for hairs** optional file.

[**Mannequin Races - TYPE4**](https://www.nexusmods.com/newvegas/mods/68994)  
TYPE4 textures and meshes for Mannequin Races.
- Also install the **01 - TYPE4 Underwear** optional file.

[**Body and Face Textures Workshop**](https://www.nexusmods.com/newvegas/mods/55174)  
High resolution textures for Type-based female bodies.
- Install the **00 - Default Version - CORE** and **00b - Raider Textures** main files.
- Also install the **00 - Dead Money DLC - Christine face** and **01 - Old Female** update files.
- Also install the **01 - Detailed Face Normalmap**, **03 - Body Hairy Clean**, and **05 - Face Vanilla Feel** optional files.

[**Body and Face Textures Workshop for Mannequin Races**](https://drive.google.com/file/d/1tP8AwU1k6WgddbVZScF6A8GW12uu1Teo/view?usp=sharing)  
High resolution textures for Mannequin Races. Uses the **09 - Face Vanilla Feel - Freckles** texture for the player character.

[**T6M Neck Adjusted Outfit Replacers**](https://drive.google.com/file/d/17BjQgaU_IlHBHMhtEuJ6rJ2jUHnoBhXh/view?usp=sharing)  
Outfit replacers for Combat Armor (including variations), Prostitute Outfits, and Raider Outfits.

# FNVLODGen

**FNVLODGen** lets you generate LOD for our installed mods.

[**FNVLODGen**](https://www.nexusmods.com/newvegas/mods/58562)  
Allows generation of LOD for worldspaces by scanning all mods in the load order that add visible from distant objects.
- Manually download the **FNVLODGen** main file.
- Extract the contents of the archive to **Fallout New Vegas Mods\FNVLODGen**.

## Registering FNVLODGen in Mod Organizer 2

For FNVLODGen to work in Mod Organizer 2, we need to register and configure it.

- Click the **Modify Executables** ![Executables](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Executables.png) button.
- Click the **Add an executable** ![AddExe](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_Add_File.png) button and select *Add from file...*.
- Navigate to FNVLODGen's folder (**C:\Games\Fallout New Vegas Mods\FNVLODGen**) and double click its .exe file.
- In the **Arguments** field, paste **-o:"C:\Games\Fallout New Vegas Mods\FNVLODGen Output\**.
- Click **Apply** and then **OK**.

> This argument will make the files generated through FNVLODGen appear in a folder called **FNVLODGen Output** on your **Fallout New Vegas Mods** folder.

## Installing LOD resources

[**FNVLODGen Resources**](https://www.nexusmods.com/newvegas/mods/58562)  
Adds extra meshes for LOD generation.
- Install the **FNVLODGen Resources** main file.
- **Apply Filter to Show Conflicts** in **FNVEdit**. Forward the **Vurt's - WFO** Record Flags tweaks for **HoneyMesquitePickable**.

[**LOD Additions and Improvements**](https://www.nexusmods.com/newvegas/mods/61206)  
Adds extra meshes for LOD generation.
- **Apply Filter to Show Conflicts** in **FNVEdit**.
  - Forward the **YUP - Base Game + All DLC** Record Flags fix for **SCOLMetroExtRailsStraitS3b**.
  - Forward the **YUP - Base Game + All DLC** Record Flags fix for **TentSideALTNV02**.
  - Forward the **YUP - Base Game + All DLC** Record Flags fix for **TentSideALTNV03**.

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
NVAC - New Vegas Anti Crash
NVTF - New Vegas Tick Fix
NVTF Custom INI
FNV Mod Limit Fix
Console Paste Support
Improved Lighting Shaders
Navmesh Fixes and Improvements
Yukichigai Unofficial Patch - YUP
Unofficial Patch NVSE Plus
New Vegas Mesh Improvement Mod
Weapon Mesh Improvement Mod
WMIM ESP Replacer
Throwable Weapon Fixes
Landscape Disposition Fix
Less Flickery City of New Vegas
Sierra Madre Exterior Fixed
	Ammo Burst Case Count Fix
	Ammo Script Fixes
	Critical and Effects - Fixes and Tweaks
	Gauss Rifle VATS Fix - JIP
	Meltdown NVSE Upgrade
	Miss Fortune NVSE Upgrade
	Mostly Unarmed Tweaks
	kNVSE Animation Plugin
	ShowOffNVSE
	Tesla Cannon Chaining
	Universal Pyromaniac Buff for Fire Effects
	Dirty Pre-War Businesswear Texture Fix
	Female White Glove Society Mask Fix
	Gun Runners Kiosk Glass Fix Alternate Version B
	Lonesome Road Carbon Shadow Fix
UIO - User Interface Organizer
The Mod Configuration Menu
The Mod Configuration Menu Bugfix
JIP Improved Recipe Menu
Vanilla UI Plus (New Vegas)
Clean Vanilla HUD
Consistent Pip-Boy Icons
Consistent Pip-Boy Icons Vanilla UI Plus Patch
	Vanilla HD Missing Icon for Consistent Pip Boy Icons - No More Farting Vault Boy
Faction Map Icon Overhaul
Satellite World Map
Satellite Maps DLC
Better Character Creation
Faster Pip-Boy Animation
No More Dust Devils (and Whirlwinds)
Simple DLC Delay
Snowglobe Tweaks Fix
Weapon Binding Ritual No Message or Screenspace Effect
Essential DLC Enhancements Merged
Follower Formula Redone
Follower Tweaks
Immersive Hit Reactions - Makes Combat Responsive
Immersive Recoil 2.0
Jamming Fix and Optional Tweaks
JAM - Just Assorted Mods
Melee Cleave (a.k.a. Sweep)
NPCs Sprint In Combat
Player Combat Priority
Precise VATS (and actually useful Perception)
Simple Explosive Entry
Well Rested Overhaul
	Flirting Perks Require 5 Charisma (JSUE Version)
	Honest Hearts Workbench Crate Luck
	Lobotomite Tweaks
	Luck Based Sunset Sarsaparilla Star Bottle Caps
	Mines Go Boom
	Rigged Shotgun Restoration - Lore-Friendly
	Sun Guard During Sunshine
JSawyer Ultimate Edition
JSawyer Ultimate Edition - Push's Tweaks
JSawyer Ultimate Edition Patches
Anatomy Perks
Perk-based Creature Loot
Perk-based Creature Loot Patches
Improved Traits
FNV Opposite Traits (YUP OWB)
Improved Traits and Opposite Traits Patches
Laser Weapon Iron Sights - Gun Runner's Arsenal Merged
Laser Weapon Iron Sights - Iron Sight Recoil Animations
Plasma Weapon Iron Sights - Gun Runner's Arsenal Merged
Plasma Weapon Iron Sights - Iron Sight Recoil Animations
Miscellaneous Tweaks Collection
Misc Gameplay Merge
Misc Gameplay Merge - JSawyer Ultimate Edition Patch
Less Map Markers
Mojave Arsenal
JSawyer Ultimate Edition - Mojave Arsenal Patch (GRA Merged)
RAD - Radiation (is) Actually Dangerous
RAD - Radiation (is) Actually Dangerous - Overhaul
Unfound Loot
Unfound Loot Custom INI
Uncut Wasteland Plus NPCs
Uncut Wasteland Tweaks
Mojave Raiders
JSawyer Ultimate - Mojave Raiders Patch
Mojave Raiders Tweaks
Mojave Wildlife - Vanilla No Chanced Spawns Version
Empty Clicks
More Accurate Geiger Clicking
No Cocking Sound on Rifle Equip
Female Nuka-Cola Drinking Sound Replacer
FOV Slider
Improved LOD Noise Texture
Anniversary Anim Pack
Anniversary Anim Pack - General Bugfix
Anniversary Anim Pack - General Bugfix Bonus Patch
DiaMoveNVSE
Ragdolls
Viewmodel Recoil
B42 Weapon Inertia
NV Compatibility Skeleton
Character Expansions Revised
Character Expansions Revised - YUP
Character Expansions Revised - JSU
Character Expansions Revised - UW
Character Expansions Revised - MR
Character Expansions Revised - AIO Patch
A Little More Lamplight
Strip Lights Region Fix
Lucky 38 Lights Redone
More Subtle New Vegas Light Pollution - Slightly Brighter
More Subtle New Vegas Light Pollution Better Strip View Patch
Strip Lighting Overhaul
FNV Realistic Wasteland Lighting
FNV RWL All DLC - Patch Collection
FNV RWL All DLC - Strip Lights AIO Patch
RWL Tweaked - Light Tweaks
Mojave Nights
Night Sky Tweaks
	Bathroom Doors Overhaul
	Lucky 38 Intro Poster
	Lucky 38 Mainframe No Fingerprints
	Securitrons No Fingerprints
	McCarran Escalator Glass
	McCarran Main Terminal Transparent Glass
	Lower-sitting Ranger Hat
	Metal Helmets - Female Replacements
	Power Armor Gloves
	Unisex Motorcycle Helmets
	Y-17 Trauma Override Harness Gloves
	Worn-Out Scope Crosshair Replacers
	Alsatian NCR Guard Dogs
	Bighorner Model Variants
	Brahmin Variant Redux
	Healthier Yao Guai - Real Bears
	Securitrons in CRT
	OWB in CRT
	Eyelashes New Vegas
	HD Teeth
	Natural Eyelashes
	Natural Eyebrows
	Natural Eyes - Shadow
	Vanilla Hair - No Shine
	Vanilla Underwear Replacer
	New Vegas - Enhanced Camera
	Empty Weapons
	Tweaked Standing Idle
	Tweaked Standing Idle Fix
	Pip-Boy 2000 Mk VI
	Pip-Boy 2000 Mk VI Working Date and Clock
	Pip-Boy 2000 Mk VI (Wasteland Edition) Retexture
	NPC Arm Mounted Pip-Boy 2000 Mk VI (Pluginless)
FNVLODGen Resources
LOD Additions and Improvements
FNV LOD Supplementation
TCM's LOD Overhaul
Better Strip View
Wasteland Flora and Terrain Overhaul
Wasteland Flora and Terrain Overhaul ESP Replacer
Wasteland Flora Overhaul - Vanilla Tree Replacer with LOD
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
Ragdolls.esm
Character Expansions Revised.esm
YUP - NPC Fixes (Base Game + All DLC).esp
Unofficial Patch NVSE Plus.esp
WMIMNV.esp
ThrowableFixes.esp
LessFlickeryCityOfNewVegas.esp
	MigMultiCase.esp
	AmmoScriptFixes.esp
	CriticalEffectFixes.esp
	MigGaussFix.esp
	MigMeltdown.esp
	MigFortune.esp
	MigKao.esp
	MigTeslaChain.esp
	Pre-War Businesswear Fix.esp
	PyromaniacEffectsBuff.esp
The Mod Configuration Menu.esp
JIP Improved Recipe Menu.esp
Vanilla UI Plus.esp
map_icon_overhaul.esp
Better Character Creation.esp
Simple DLC Delay.esp
Snowglobe Tweaks.esp
DLC Enhancements.esp
Follower Formula Redone.esp
Follower Tweaks.esp
Immersive Hit Reactions.esp
ImmersiveRecoil.esp
JamFix.esp
JustAssortedMods.esp
MeleeCleave.esp
NPCsSprint.esp
Player Combat Priority.esp
hz_Precise VATS.esp
Simple Explosive Entry.esp
migWellRested.esp
	Honest Hearts Workbench Crate Luck.esp
	Lobotomites.esp
	Sunset Sarsaparilla Star Caps Random Luck.esp
	MinesGoBoom.esp
	Rigged Shotgun Restoration - Lore-Friendly.esp
	Sun Guard During Sunshine.esp
JSawyer Ultimate.esp
JSawyer Ultimate - Push's Tweaks.esp
JSawyer Ultimate YUP Patch.esp
JSawyer Ultimate WMIM Patch.esp
JSawyer Ultimate WMIM Patch.esp
Female White Glove Society Mask JSUE.esp
Weapon Binding Ritual No Message JSUE.esp
	Charisma Perk Requirements.esp
MigAnatomy.esp
Perk-based Creature Loot.esp
Perk-based Creature Loot Anatomy Perks Patch.esp
Perk-based Creature Loot JSUE Patch.esp
Improved Traits.esp
Improved Traits Improved.esp
Improved Traits - JSU.esp
FNVOppositeTraits.esp
FNVImprovedOppositeTraits.esp
FNVImprovedOppositeTraits - JSU.esp
LaserWeaponIronSights.esp
PlasmaWeaponIronSights.esp
Miscellaneous Tweaks.esp
Misc Gameplay Merge - JSUE Patch.esp
Less Map Markers.esp
Mojave Arsenal.esp
JSawyer Ultimate - Mojave Arsenal Patch (GRA Merged).esp
RAD.esp
Unfound Loot.esp
Uncut Wasteland.esp
Uncut Wasteland Tweaks.esp
Mojave Raiders.esp
JSawyer Ultimate - Mojave Raiders Patch.esp
Mojave Raiders Tweaks.esp
Mojave Wildlife (Vanilla-Style + No Chanced).esp
hz_Empty Clicks.esp
More Accurate Geiger Clicking.esp
FOVSlider.esp
VM_Recoil.esp
B42Inertia.esp
Character Expansions Revised - Extras.esp
Character Expansions Revised - YUP.esp
Character Expansions Revised - JSU.esp
Character Expansions Revised - UW.esp
Character Expansions Revised - MR.esp
Character Expansions Revised - AIO Patch.esp
	Bathroom Doors Overhaul - All IN ONE.esp
	Lucky 38 intro poster.esp
	Metal Helmet Female Replacements.esp
	lexx_armored_pagloves.esp
	Alsatian NCR Guard Dogs.esp
	CIB Bighorners.esp
	CIB Bighorners - HH.esp
	lexx_brahmin-variant.esp
	Skinny Bears.esp
	tkEyelashesFNV.esp
	EmptyWeapons.esp
	MCPipBoy2000MK6_clock.esp
FNVLODGen.esp
tmzLODadditions.esp
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
FNV RWL All DLC - Strip Lights AIO Patch.esp
RWL Tweaked - Light Tweaks.esp
Mojave Nights.esp
```
</details>

## GENERATING LOD

With all our mods and resources installed, we can finally generate our LOD.

- Run **FNVLODGen** in MO2.
- Right click on the list of worldspaces, and click **Select All**.
- Click **Generate**. The process will take some time.
- After the **LOD Generator: finished (you can close this application now)** message appears, close the program.
- Navigate to your **Fallout New Vegas Mods\FNVLODGen Output** folder, and make an archive out of the **textures** and **meshes** folder. Name it **FNVLODGen Output**.
- Install **FNVLODGen Output** with MO2.

## MOD CONFIG

### Optional falloutcustom.ini tweaks

Paste the following into **falloutcustom.ini**.

```
[Display]
bAllowScreenShot=0

[Imagespace]
bDoDepthOfField=0
```

> This disables the vanilla depth of field effect seen during dialogue, as well as the screenshots feature in favor of SweetFX's.

### JIP LN NVSE Plugin

Open the mod's .ini file and make the following adjustments.

```
bEnableFO3Repair=1
bNPCWeaponMods=1
uWMChanceMin=5
uWMChanceMax=15
```

### New Vegas - Enhanced Camera

Open the mod's .ini file and make the following adjustments.

```
bFirstPersonSitting=0
bFirstPersonKnockout=0
bFirstPersonDeath=0
fDlgFocusOverride=6.0
```

### FOV Slider

Open the mod's .ini file and make the following adjustments.

```
fDefaultWorldFOV=85.0000
fDefault1stPersonFOV=70.0000
fPipboy1stPersonFOV=65.0000
```

### DiaMoveNVSE

Open the mod's .ini file and make the following adjustments.

```
bEnableHeadTurn=false
```

> if you also use [**New Vegas - Enhanced Camera**](https://www.nexusmods.com/newvegas/mods/55334/), set EnableECCompatible=True.

# MOD KEYBINDINGS

> This section includes mods from the optional sections of the guide.

This is a handy reference table which will hopefully help you have a better idea of what new hotkeys are available to you, having followed this guide from beginning to end.

Key | Function | Added by
------------ | ------------- | -------------
Y | Fast forward time | Pass the Time

# ACKNOWLEDGMENTS

This guide wouldn't be possible without Qolore's excellent work at [**Viva New New Vegas**](https://vivanewvegas.github.io/index.html). I'm just standing on the shoulders of giants.

# CHANGELOG

- 🆕 Mod has been added to the guide.
- ⚠️ Mod has been updated or its installation/configuration instructions have changed.
- 🚫 Mod has been removed from the guide.

<details>
	<summary>1.0 (November 30th)</summary>

- Initial release.
</details>

[<< Back to Main](https://github.com/Sigourn/newvegas-sharp/blob/main/README.md#left-my-heart-in-new-vegas)  
[<< Back to Setup](https://github.com/Sigourn/newvegas-sharp/blob/main/setup.md#new-vegas-setup)
