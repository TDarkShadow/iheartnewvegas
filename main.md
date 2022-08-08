[<< Back to Readme](readme.md)  
[<< Back to Setup](setup.md)

> PROTIP: Click on the list icon on the upper left corner of this document to see the index for this guide.

# NEW VEGAS S#ARP

## PREAMBLE

### Disclaimer

This guide is the second step in the installation of **New Vegas Sharp**. Please make sure to follow the [**Setup**](setup.md) section before proceeding.

### Creating a separator

Separators allow you to neatly separate installed mods in Mod Organizer 2 for ease of viewing. These can be created and then moved around in the left pane to place them where you want them to be. Separators can also be collapsed to keep your mod list clean and tidy. I suggest creating a separator for each mod category we will be installing (category names are highlighted in CAPS).

To create a separator, follow these stpes:

- Right click on the empty space on the left pane, below **Overwrite**, and click **Create Separator**.
- Name your separator and click **OK**.

## xNVSE PLUGINS

### Essential plugins

[**NVAC - New Vegas Anti Crash**](https://www.nexusmods.com/newvegas/mods/53635)  
Implements structured exception handling and sanity checking to reduce frequency of game crashes.

[**NVTF - New Vegas Tick Fix**](https://www.nexusmods.com/newvegas/mods/66537)  
Fixes the tick count bug (which creates noticable micro stutter), optimizes hash tables (helping performance and decreasing menu load times), and fixes the high FPS bug (fixing physics and lipsync at high framerates).

[**FNV Mod Limit Fix**](https://www.nexusmods.com/newvegas/mods/68714)  
Allows a maximum of 255 plugins to be loaded, as well as improving FPS, removing game stutter, and allowing for faster loading times (particularly when using a large number of mods).

[**OneTweak**](https://www.nexusmods.com/newvegas/mods/75685)  
Enables borderless window mode for safe alt-tabbing.
- After installation, click the **Tools** ![Tools](MO2/MO_ini.png) button, and click **INI Editor**. Select the **FalloutCustom.ini** tab.
- Set **bFull Screen** to 0.
- Click **Save** and close the window.

[**Improved Lighting Shaders**](https://www.nexusmods.com/newvegas/mods/69833)  
Almost completely fixes the exterior lighting bug, and allows up to four times the number of active lights.

### Expanded mod support

[**JIP LN NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/58277)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**JohnnyGuitar NVSE**](https://www.nexusmods.com/newvegas/mods/66927)  
Adds new functions, engine bug fixes and tweaks, and restored broken game features.

[**kNVSE Animation Plugin**](https://www.nexusmods.com/newvegas/mods/71336)  
Enables having custom animations for weapons and actors. Also fixes the engine-bound anim group limit problem.

[**ShowOff NVSE Plugin**](https://www.nexusmods.com/newvegas/mods/72541)  
Adds new functions, engine bug fixes and tweaks.
- Install **ShowOff NVSE** (Main files).
- Install **ShowOff INI** (Main files). Merge when prompted.

[**UIO - User Interface Organizer**](https://www.nexusmods.com/newvegas/mods/57174)  
An NVSE-powered plugin designed to manage and maintain all UI/HUD extensions added to the game by various mods.

[**yUI - User Ynterface**](https://www.nexusmods.com/newvegas/mods/74357)  
Aims to fix UI bugs and add new UI features. 
- Install **yUI** (Main files).
- Install **Matched Cursor - Fallout New Vegas** (Optional files). Merge when prompted.
- After installation, double-click the mod and select the **INI Files** tab.
- Select **yUI.ini**, and set **bMatchingCursor** to 1.
- Click **Save** and close the window.

> ℹ️ This matches the in-game cursor to the current HUD color.

## PATCHES

### General fixes

[**Ultimate Edition ESM Fixes**](https://www.nexusmods.com/newvegas/mods/77170)  
Optimizes and cleans the esms, as well as fixes some hard errors in the landscape. Boosts performance on modern systems with SSDs.
- Manually download **Ultimate Edition ESM Fixes** (Main files).
- Extract the contents of the archive.
- Run **Installer.exe**.
- Under the **ESM Fixes** header, navigate to **C:\Games\Fallout New Vegas Mods\MO2\mods**. Create an empty folder named **Ultimate ESM Fixes**. Select the folder.
- Click **INSTALL**.
- **EXIT** the program once the process is finished.
- In Mod Organizer 2, press **F5** to refresh the window. Activate the **Ultimate ESM Fixes** mod.

[**Yukichigai Unofficial Patch - YUP**](https://www.nexusmods.com/newvegas/mods/51664)  
Collection of bug fixes for Fallout: New Vegas and its DLCs, combined into one ESM.
- Install **YUP - Base Game and All DLC** (Main files).

[**Landscape Disposition Fix**](https://www.nexusmods.com/newvegas/mods/73937/)  
Small mod fixing several hundred vanilla floating objects, underground or above ground.

[**Navmesh Fixes and Improvements**](https://www.nexusmods.com/newvegas/mods/62041)  
Fixes virtually every navmesh where the edge connections were missing or pointing at misplaced or invalid triangles. Also makes improvements to the majority of the affected navmeshes.
- Install **Navmesh Fixes and Improvements - Base Game and ALL DLC** (Main files).

[**Enslaving Arcade Fix YUPdated**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Enslaving%20Arcade%20Fix%20YUPdated.7z)  
Adds an option to offer to enslave Arcade at any point before Caesar goes into his coma, as hinted by the game's quest journal.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/62923) to original mod by **Whyareall**. The featured version includes YUP fixes.

[**Map Marker Reputation Fix**](https://www.nexusmods.com/newvegas/mods/75816)  
Gives map markers of various faction-controlled locations the reputation of their respective faction.

[**Melee Reach Fixed YUPdated**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Melee%20Reach%20Fixed%20YUPdated.7z)  
Fixes the horribly inconsistent vanilla weapon reach for melee weapons.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/57729?) to original mod by **naugrim04**. The featured version omits outdated fixes.
 
[**Uncut Wasteland**](https://www.nexusmods.com/newvegas/mods/56625)  
Restores a huge amount of cut content from the game, from scenery and little random things, to NPCs and creatures.
- Install **Uncut Wasteland plus NPCs** (Main files).
- Install **Uncut Wasteland Pole Remover** (Optional files). Merge when prompted.

[**Uncut Wasteland Tweaks**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Uncut%20Wasteland%20Tweaks.7z)  
Includes YUP fixes, omits NPC restorations at the Ultra-Luxe Bathhouse, and replaces static Destitute Travelers with leveled, random NPCs.

[**Strip Lights Region Fix**](https://www.nexusmods.com/newvegas/mods/73596?)  
Fixes a vanilla issue about the Strip lights not showing in certain parts of the map.
- Install **Strip Lights Region Fix** (Main files).
- Install **Strip Lights Region Fix - Uncut Wasteland** (Optional files). Merge when prompted.

### Mesh fixes

[**New Vegas Mesh Improvement Mod**](https://www.nexusmods.com/newvegas/mods/74295)  
Optimizations and fixes for a large selection of meshes in the base game and DLCs.

[**Skinned Mesh Improvement Mod - SMIM - Creatures**](https://www.nexusmods.com/newvegas/mods/77477)  
Optimizations and fixes for a large selection of creature meshes in the base game and DLCs.

[**ISControl Enabler and Ironsights Adjuster**](https://www.nexusmods.com/newvegas/mods/75417)  
Dynamically adds ISControl node system animation support plus easy per-weapon sights adjustment.

[**Vanilla Iron Sights Realligned**](https://www.nexusmods.com/newvegas/mods/77672)  
Fixes all the iron sights on vanilla weapon meshes using ISControl Enabler. No meshes and no ESP.

[**Armor and Clothing First Person Clipping Fixes**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Armor%20and%20Clothing%20First%20Person%20Clipping%20Fixes.7z)  
Addresses first-person clipping for a variety of outfits, particularly noticeable when moving with a weapon drawn.

[**Female White Glove Society Mask Fix**](https://www.nexusmods.com/newvegas/mods/66940)  
Fixes the White Glove Society Mask mesh for female characters.

[**Fix for the Caesar Legion Armors YUPdated**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Fix%20for%20the%20Caesar%20Legion%20Armors%20YUPdated.7z)  
Fixes numerous issues with the Caesar Legion armor meshes, and flags the helmets appropriately so you can no longer equip inadequate headgear along with them.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/65004) to original mod by **YanL**. The featured version includes YUP fixes and omits unnecessary edits.

### Audio fixes

[**Elijah Voice Audio Files Fix**](https://www.nexusmods.com/newvegas/mods/73526)  
Fixes Elijah's voice loudness and clipping issues in Dead Money. 

[**High-Quality Classic Music**](https://www.nexusmods.com/newvegas/mods/72150)  
Replaces the low-quality soundtrack from the classic Fallout games with high-quality versions.

### NVSE fixes

[**Unofficial Patch NVSE Plus**](https://www.nexusmods.com/newvegas/mods/71239?)  
Collection of bug fixes for Fallout: New Vegas and its DLCs which require NVSE.

[**Ammo Burst Case Count Fix**](https://www.nexusmods.com/newvegas/mods/69175)  
Fixes the game only giving you one ammo case when your weapon uses more than one ammo count in a shot, for you and companions.

[**Melee VATS Animation Restoration**](https://www.nexusmods.com/newvegas/mods/73480)  
Brings back the VATS melee animations from Fallout 3.

[**lStewieAl's Tweaks and Engine Fixes**](https://www.nexusmods.com/newvegas/mods/66347)  
Engine bugfixes, optional tweaks and new features with no performance impact. Fully customisable via in-game menu and INIs.

[**Stewie Tweaks Custom INI**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Stewie%20Tweaks%20Custom%20INI.7z)  
Enables essential bugfix and quality-of-life settings, hand-picked by lStewieAl, as well as a number of gameplay tweaks. Based off [**Stewie Tweaks Essentials INI**](https://www.nexusmods.com/newvegas/mods/76522).

<details>
<summary>Enabled gameplay tweaks</summary>

```
bAdjustableScopeZoom = 1
bBinocularsOnly = 1
bClipSizeMatters = 1
bCookableGrenades = 1
bDoubleTapReloadToChangeAmmoType = 1
bHoldAndReleaseThrowables = 1
bManualReload = 1
bNoExitHacking = 1
bNoGrabOwnedItems = 1
bNoSkillTags = 1
iRemoveTags = 2
bNumberedDialogHotkeys = 1
bPickpocketOverhaul = 1
bPreventStealingCapsAfterRepair = 1
bQuickUse = 1
bRestore2Hotkey = 1
bShowInventorySortButton = 1
iOpenMapKey = 1
iOpenQuestsKey = 1
```
</details>

## USER INTERFACE

[**The Mod Configuration Menu**](https://www.nexusmods.com/newvegas/mods/42507)  
Allows any number of mods to be configured from a single menu, accessible through the Pause menu.
- Install **The Mod Configuration Menu** (Main files).
- Install **MCM BugFix 2** (Update files). Merge when prompted.

[**Vanilla UI Plus (New Vegas)**](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)  
Greatly improves the user interface without compromising the original style.
- Download the mod using the **DOWNLOAD NOW!** button.
- Check the following options in the FOMOD installer:
  - [X] Classic Pip-Boy Font
  - [X] Plugin
  - [X] WASD Compatible 

> ℹ️ The **Classic Pip-Boy Font** option includes the **Default Font Tweaks** option, and only enables said font exclusively in the Pip-Boy screen.

- After installation, double-click the mod and select the **Filetree** tab.
- Expand the **Menus\Prefabs\VUI+** folder, and double-click **settings.xml**.
- Set **VUI+DialogMaxHeight** to 276.
- Set **VUI+NumberedTopics** to 1.
- Save and close the file.

> ℹ️ This increases the amount of visible dialogue options and enables numbered dialogue options.

[**Clean Vanilla HUD**](https://www.nexusmods.com/newvegas/mods/70001)  
Cleans up HUD textures (such as the compass ticks or other arrows) that have went unnoticed.
- Stick to the default options in the FOMOD installer.

[**Clean Companion Wheel**](https://www.nexusmods.com/newvegas/mods/70486)  
Cleans up the Companion Wheel textures.
- Install **Clean Companion Wheel 256x256 Edition** (Main files).

[**Clean Vault Boy Paper Doll**](https://www.nexusmods.com/newvegas/mods/76966)  
Cleans up the Vault Boy paper doll textures.

[**Consistent Pip-Boy Icons**](https://www.nexusmods.com/newvegas/mods/65046)  
Bug fixes and consistency tweaks for icons in terms of coloring and transparency.
- Install **1. Consistent Pip-boy Icons** (Main files).
- Install **4. Vanilla UI Plus Patch** (Optional files). Merge when prompted.

[**Pop-Up Message Icons**](https://www.nexusmods.com/newvegas/mods/76516)  
Cleans up the Vault Boy pop up message icons.
- Stick to the default options in the FOMOD installer.

[**Satellite World Map**](https://www.nexusmods.com/newvegas/mods/58602)  
High-res satellite map for the Mojave Wasteland.
- Install **Satellite World Map** (Main files).

[**Satellite Maps DLC**](https://www.nexusmods.com/newvegas/mods/64292)  
High-res satellite maps for Dead Money, Honest Hearts, Old World Blues, and Lonesome Road.

[**FOV Slider**](https://www.nexusmods.com/newvegas/mods/55085)  
Adds an MCM menu that allows for adjusting the Fields of View for all of the game's camera views.

## QOL IMPROVEMENTS

[**Better Caravan Game Limit for Merchants YUPdated**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Better%20Caravan%20Game%20Limit%20for%20Merchants%20YUPdated.7z)  
Limits games of Caravan against merchants to one game every 3 days, rather than 5 games total.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/41147) to original mod by **Yukichigai**. The featured version includes YUP fixes.

[**Casino Exchange All**](https://www.nexusmods.com/newvegas/mods/35701)  
Allows you to trade in all your chips at once in the casino, for different types of currency.
- Install **Casino Exchange All 1-5a** (Main files).
- Stick to the default options in the FOMOD installer.

[**Console Paste Support**](https://www.nexusmods.com/newvegas/mods/65906)  
Enables hotkeys for pasting and enhanced movement/deletion of console commands.

[**Delay DLC Redux**](https://www.nexusmods.com/newvegas/mods/75851)  
Prevents the game's DLC from spamming the new game startup messages and requires you be near a given DLC's starting location to receive its quest, in addition to requiring the player to listen to the respective DLC's radio broadcast before the quest will start.
- Install **Delay DLC Redux** (Main files).

[**Essential DLC Enhancements Merged**](https://www.nexusmods.com/newvegas/mods/73803)  
A collection of small essential gameplay improvements for the official DLCs that have been fully merged, updated, and cleaned.

[**Faction Armor Redone YUPdated**](https://www.nexusmods.com/newvegas/mods/71415)  
Adjusts faction armor to only affect infamy, allowing positive reputation to be maintained while wearing faction armor.

[**Faster Pip-Boy Animation**](https://www.nexusmods.com/newvegas/mods/67761)  
Increases the speed of the Pip-Boy animation.
- Install **Faster Pip-Boy Animation (2x)** (Main files).

[**Immersive Primary Needs**](https://eddoursul.win/download/228)  
As hunger, thirst or sleep deprivation increase, the player is notified by periodic sound effects. These effects kick in shortly before the first penalties occur, so the player is given a chance to eat, drink or sleep in time.
- Install as **Immersive Primary Needs**.

[**JAM - Just Assorted Mods**](https://www.nexusmods.com/newvegas/mods/66666)  
A collection of toggleable mods, including dynamic crosshair, hit marker, hit indicator, visual objectives, hold breath, vanilla sprint, bullet time, weapon wheel, and loot menu.

> ℹ️ For detailed instructions on how the **Weapon Wheel** feature works, check out the [**Just Weapon Wheel**](https://www.nexusmods.com/newvegas/mods/67460) page.

[**JAM or Just Sprint Animation Replacers**](https://www.nexusmods.com/newvegas/mods/74839)  
Improves animation transitions when going from idle to sprint, plus allows the player to reload their weapons when sprinting.

[**Clean Just Weapons Wheel**](https://www.nexusmods.com/newvegas/mods/76357)  
Cleans up the Just Weapons Wheel textures.

[**Shut Up DLC Companions YUPdated**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Shut%20Up%20DLC%20Companions%20YUPdated.7z)  
Stops the companions from Dead Money and Honest Hearts from constantly saying all sorts of idle chatter.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/63082) to original mod by **ZuTheSkunk**. The featured version includes YUP fixes.

## VISUALS

[**Anniversary Anim Pack**](https://www.nexusmods.com/newvegas/mods/70158)  
Merge of many animation mods by the same author, improving the game's overall look and feel when it comes to gunplay.

[**Anniversary Anim Pack - General Bugfix**](https://www.nexusmods.com/newvegas/mods/72320)  
Fixes camera jumps, animation snapping, movement lock, and broken aim in 3rd person when using Anniversary Anim Pack.
- Install **AnniAnimPack_BugFix 1.3** (Main files).
- Install **Bonus Patch** (Main files). Merge when prompted.

[**FNV Clean Animations**](https://www.nexusmods.com/newvegas/mods/70599)  
Clean first person animations. No new idles, no bugs, no reload cancelling from shooting early or crouching, no compatibility issues.
- Install **FNV Clean Animations** (Main files).
- Install **FNV Clean Animations - Update 2.2.2** (Update files). Merge when prompted.

[**Viewmodel Recoil 0.308**](https://www.nexusmods.com/newvegas/mods/71852)  
Adds a visual recoil mod that affects first person model only and doesn't move the camera at all.

[**B42 Weapon Inertia**](https://www.nexusmods.com/newvegas/mods/64335)  
Adds weapon inertia, causing weapons to slightly lag behind camera movement to give a feeling of weight to them.

[**Diagonal Movement**](https://www.nexusmods.com/newvegas/mods/64333)  
Adds diagonal movement.

[**NV Compatibility Skeleton**](https://www.nexusmods.com/newvegas/mods/68776)  
A compatible skeleton for many animation mods.
- Check the following option in the FOMOD installer:
  - [X] Vanilla Weights

[**Character Expansions Revised**](https://www.nexusmods.com/newvegas/mods/64862)  
Visual overhaul of characters' faces, following vanilla aesthetics. 

[**Character Expansions Revised - FaceGen Tint Fix**](https://www.nexusmods.com/newvegas/mods/75268)  
Fixes colored tints on character faces. Visual comparison [**available here**](https://imgsli.com/ODY2MzE).
- Install as **Character Expansions Revised - FaceGen Tint Fix**.

[**Eyelashes New Vegas**](https://www.nexusmods.com/newvegas/mods/34790)  
Adds animated eyelashes to NPCs and the player character.
- Install **tkEyelashesFNV** (Main files).
- After installation, hide the mod's **tkEyelashesFNV_FemalesOnly.esp** plugin.

[**Eyelashes New Vegas ESP Replacer**](https://www.nexusmods.com/newvegas/mods/75268)  
Fixes issues with the plugin, and extends support to Honest Hearts' tribals and Dead Money's Christine.
- Install as **Eyelashes New Vegas**. Merge when prompted.

[**HD Teeth and Natural Eyelashes and Eyebrows**](https://www.nexusmods.com/newvegas/mods/53695)  
Improves teeth, eyelashes, and eyebrow textures.
- Install **Eyelashes 1.3** (Main files).
- Install **HD teeth 3.0** (Main files). Merge when prompted.
- Install **HQ eyebrows** (Main files). Merge when prompted.

[**Natural Eyes**](https://www.nexusmods.com/newvegas/mods/62811)  
Improves eye textures.
- Install **00 - Natural Eyes - Shadow** (Main files).

[**Vanilla Hair - No Shine**](https://www.nexusmods.com/newvegas/mods/50285)  
Removes shine from vanilla hairs.

[**A Little More Lamplight**](https://www.nexusmods.com/newvegas/mods/69226)  
Enhances the shoddy work on the vanilla functional streetlamps and lights of Outer Vegas, Camp McCarran, Camp Golf, and the NCRCF. 

[**Strip Lighting Overhaul**](https://www.nexusmods.com/newvegas/mods/73324)  
Adds lights to the Strip where lights existed but where not producing light. Also fixes a number of vanilla bugs via editing the environment and certain meshes.

[**Wasteland Grass Overhaul**](https://github.com/Sigourn/newvegassharp/raw/main/mods/Wasteland%20Grass%20Overhaul.7z)  
Improves grass textures.

> ℹ️ [**Link**](https://www.nexusmods.com/newvegas/mods/39856) to original mod by **vurt**. The featured version omits non-grass related meshes and textures.

[**Climate Control NVSE**](https://www.nexusmods.com/newvegas/mods/77205)  
NVSE plugin which fixes bugs and adds utilities for weather mods.
- Install **Climate Control NVSE** (Main files).
- Install **Longer Weather Transitions** (Optional files). Merge when prompted.

[**MoonlightNVSE**](https://www.nexusmods.com/newvegas/mods/77683)  
Fixes moonlight, making the moon the light caster instead of the sun.

[**Altitude - A Vanilla Plus Weather Mod**](https://www.nexusmods.com/newvegas/mods/71404)  
Vastly improves all the weathers in the game, without stepping on the toes of vanilla New Vegas's design too much.
- Install **Altitude** (Main files).
- Install **Altitude - Alternate Nights** (Optional files). Merge when prompted.
- Install **Altitude - Zion Ambient Music** (Optional files). Merge when prompted.

[**Accurate NASA Stars**](https://www.nexusmods.com/newvegas/mods/75522)  
New star texture and mesh using NASA satellite images to create a real-world accurate starfield for New Vegas.
- Install **Accurate Stars 4k** (Main files).

[**HD Moon 2K - NASA Satellite Images**](https://www.nexusmods.com/newvegas/mods/74022)  
HD retexture of the in game moon using NASA satellite images.

[**Elegant Sunglare Retexture**](https://www.nexusmods.com/newvegas/mods/75086)  
A replacement for the sun and sun-glare textures, for a simple, visually appealing style. Helps remove sky grain.

[**Night Sky Tweaks**](https://www.nexusmods.com/newvegas/mods/73529)  
Fixes the bright night sky horizons.
- Install **Night Sky Tweaks (No Plugin)** (Main files).

[**Improved LOD Noise Texture**](https://www.nexusmods.com/newvegas/mods/46451)  
Vastly improves the LOD noise texture used on distant land.
- Install **Improved LOD noise Texture** (Main files).

[**HD Mist**](https://www.nexusmods.com/newvegas/mods/58955)  
High resolution retexture for mist.
- Install **HD Mist 2K** (Main files).

[**ENB Friendlier HD Dust Storms**](https://www.nexusmods.com/newvegas/mods/64085)  
HD retexture of dust storms. Non-ENB version available.
- Install **3. Non-ENB HD Dust Storms - 2048** (Optional files).

[**More Subtle Hidden Valley Dust Storm**](https://www.nexusmods.com/newvegas/mods/70275)  
Tones down the dust storm effect near the Hidden Valley bunkers.

[**More Subtle New Vegas Light Pollution**](https://www.nexusmods.com/newvegas/mods/73579)  
Reduces the distant glow of New Vegas for the sake of darker nights.
- Install **Slightly Brighter** (Main files).

## GAMEPLAY

[**Follower Tweaks**](https://www.nexusmods.com/newvegas/mods/62180)  
Removes annoying features from some followers. Changes the effects of the Enhanced Sensors, Spotter, and Search and Mark perks. ED-Es no longer 'whirs' whilst moving.

[**Immersive Recoil 2.0**](https://www.nexusmods.com/newvegas/mods/61973)  
Adds recoil animations to player and NPCs. Recoil strength is calculated based on weapon base damage, requirements, condition and weight, and the character's skill and strength. Aiming down sights and crouching also reduces recoil.

[**Mass Ownership Tweaks**](https://www.nexusmods.com/newvegas/mods/74031)  
Logical fixes/improvements to ownership for certain cells/items, as well as adding dynamic ownership to many cells.

[**NPCs Sprint In Combat**](https://www.nexusmods.com/newvegas/mods/68179)  
NPCs will now sprint in melee combat instead of casually jogging. Uses custom sprint animations.

[**Passive Combat Music Tweaked**](https://www.nexusmods.com/newvegas/mods/69424)  
Combat music will only start when the player or an enemy start combat with each other.
- Install **New and Improved** (Main files).

[**Player Combat Priority**](https://www.nexusmods.com/newvegas/mods/71699)  
Makes enemies more likely to target the player in combat rather than companions.

[**SawyerBatty FNV**](https://www.nexusmods.com/newvegas/mods/76436)  
An edited version of Josh Sawyer's [**jsawyer**](https://fallout.fandom.com/wiki/JSawyer) mod, intended to be an exact compatible-only version with the bugs and inconsistencies fixed.

[**Improved Traits**](https://www.nexusmods.com/newvegas/mods/65403)  
Edits some vanilla traits and adds two new ones.

[**Better Character Creation**](https://www.nexusmods.com/newvegas/mods/70973)  
Improves the character creation by speeding up the process, adding specialized gear based on your tag skills, and making Wild Wasteland an opt-in feature rather than a trait.

## FINISHING TOUCHES

[**New Vegas Sharp Mod Setup**](https://github.com/Sigourn/newvegassharp/raw/main/mods/New%20Vegas%20Sharp%20Mod%20Setup.7z)  
Includes configuration files and patches for mods included in the guide.
- Check the corresponding options in the FOMOD installer based on the mods you have installed.

### Adjusting mod order and load order

[**New Vegas Sharp MO2 Profile Files**](https://github.com/Sigourn/newvegassharp/raw/main/mods/New%20Vegas%20Sharp%20MO2%20Profile%20Files.7z)  
Adjusts mod order and load order for New Vegas Sharp to work as intended.
- Extract the files into **C:\Games\Fallout New Vegas Mods\MO2\profiles\New Vegas Sharp**, overwriting when prompted.

### INI config

**falloutcustom.ini (Optional)**:
- Click the **Tools** ![Tools](MO2/MO_ini.png) button, and click **INI Editor**. Paste the following into **falloutcustom.ini**.

```
[Imagespace]
;Disables vanilla depth of field effect seen during dialogue.
bDoDepthOfField=0

[Interface]
;Reduces the amount of zoom when engaging in dialogue.
fDlgFocus=5.0000
;Set the Pip-Boy HUD color to match that of classic Fallout.
uPipboyColor=1022886143

[Grass]
;Increases grass density.
iMinGrassSize=40
```

### Settings config

The following settings need to be configured after you've already started a new game, using the in-game **Settings** option.

**Gameplay**:
- Set **Killcam Mode** to None.
- Set **Difficulty** to Hard.

**Controls -> Action Mapping**:
- Set **VATS** to Esc in order to disable the keybinding.
- Set **Ammo Swap** to Esc in order to disable the keybinding.

### MCM config

The following settings need to be configured after you've already started a new game, using the in-game **Mod Configuration** option.

**FOV Slider**:
- Set **Player Field of View** to 65.
- Set **Pipboy Field of View** to 55.

**Just Mods**:
- Disable **Visual Objectives**.
- Disable **Hold Breath**.
- Disable **Bullet Time**.
- Set **Crosshair 1st Sighting Mode** to Nothing.

# MOD KEYBINDINGS

Key | Function | Added by
------------ | ------------- | -------------
F6 | Create full save | lStewieAl's Tweaks
F10 | Reload current loaded save | lStewieAl's Tweaks
R (double tap) | Switch ammunition | lStewieAl's Tweaks
J | Open Pip-Boy quests tab | lStewieAl's Tweaks
M | Open Pip-Boy world map tab | lStewieAl's Tweaks
Ctrl-F | Apply filter for searching in Pip-Boy | lStewieAl's Tweaks
Shift+E | Pick up and equip | lStewieAl's Tweaks
Scroll wheel | Adjust binocular zoom | lStewieAl's Tweaks
H | Open weapon wheel | Just Assorted Mods
Shift+Movement | Sprint | Just Assorted Mods

# CHANGELOG

08-07-2022
- Full rewrite.

[<< Back to Readme](readme.md)  
[<< Back to Setup](setup.md)
