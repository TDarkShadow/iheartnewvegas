[<< Back to Main](https://github.com/Sigourn/morrowind-sharp/blob/master/readme.md#morrowind-a-morrowind-modding-guide)

# NEW VEGAS SETUP

# Requirements

- An english copy of the game from [**GOG**](https://www.gog.com/game/fallout_new_vegas_ultimate_edition).
  - Installation instructions are found on the next section. 
- A [**Nexus**](https://users.nexusmods.com/register) account. This guide assumes you are using a Free account, so no need to pay for Premium.
- A file archiver. I recommend [**7-Zip**](https://www.7-zip.org/).
- A text editor. I recommend [**Notepad++**](https://notepad-plus-plus.org/downloads/v7.9.5/).
- [**DirectX Runtime Libraries**](https://www.microsoft.com/en-us/download/details.aspx?id=8109).
- [**Microsoft VC++ 2013**](https://www.microsoft.com/en-us/download/details.aspx?id=40784) (x86 version) and [**Microsoft VC++ 2015-2019**](https://docs.microsoft.com/en-GB/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions).

# Installation

You should install Fallout: New Vegas outside all default Windows folders (Program Files, Program Files (x86), Desktop, and Documents for example). Windows User Account Control monitors these folders, which can cause problems later on.

Your Fallout: New Vegas **Root** folder is where Fallout: New Vegas will be installed, and where the game's executable (**FalloutNV.exe**), launcher (**FalloutNVLauncher.exe**), .ini file (**Morrowind.ini**), and **Data** folder will be found.

For the purpose of this guide, this will be our **Root** folder and where you should install Fallout: New Vegas:
```
C:\Games\Fallout New Vegas
```
Additional, you will need a folder where to install our mod manager and keep your mods. I recommend the following path:
```
C:\Games\Fallout New Vegas Mods
```

> Make sure you don't create your Fallout New Vegas Mods folder inside your Fallou New Vegas folder, or else you will run into issues when you try to launch the game through Mod Organizer 2, most importantly, your mods not being registered.

# Generating fresh .INI files

- Run FalloutNVLauncher.exe from the game's Root folder.
- Click OK to both pop-ups that say **Detecting Video Hardware**. If there aren't any pop-ups, navigate to Documents\My Games\FalloutNV and delete all the files ending in .INI, then retry.
- Select **Options** then select the **Ultra** preset option. A way to improve performance without drastically changing the game's visuals is by disabling shadows. New Vegas only features actor shadows which are barely visible, but which can still have a big performance impact if there are many NPCs in one area.
- Set the **Resolution** option to your preference.
- Click **OK** then **Exit**.

# Utilities

[**FNV BSA Decompressor**](https://www.nexusmods.com/newvegas/mods/65854?)  
Decompresses the Fallout New Vegas BSAs and repacks them without zlib compression for performance, Also transcodes the .ogg sounds effects to .wav so they work. It also extracts any mp3 files to loose files because they will not play when in a BSA.
- Manually download the **FNV BSA Decompressor** main file.
- Run **FNV BSA Decompressor.exe**, select your game's **Root** folder and press the **Decompress** button.
- Close the program after the patching process is done.

[**FNV 4GB Patcher**](https://www.nexusmods.com/newvegas/mods/62552?)  
Makes Fallout New Vegas 4GB Aware. Automatically loads NVSE if present.
- Manually download the **FNV 4GB Patch** main file.
- Place the **FalloutNVpatch.exe** in your game's **Root** folder and run it as an Administrator.
- Close the command prompt after the patching process is done.

> From now on, run the game through the **New Vegas** option in Mod Organizer 2, rather than the **NVSE** option.

# xNVSE

[**xNVSE**](https://github.com/xNVSE/NVSE/releases)  
New Vegas Script Extender (xNVSE) expands the engine and scripting capabilities of Fallout New Vegas. This framework is required by many modern mods.
- Click the **nvse_6_2_4.7z** under **Assets** to download it.
- Extract the contents of the archive to the game's **Root** folder.

[**New Vegas Heap Replacer**](https://www.nexusmods.com/newvegas/mods/69779)  
Replaces the in-game heap with a faster, more optimized version. It should decrease load times, remove some stutter and slightly improve frame rate. 
- Manually download the **NVHR** main file.
- Run **cpu_info.exe**. It will determine which file you need to install.
- Place the **.dll** file from the appropiate folder (indicated by **cpu_info.exe**) into your game's **Root** folder.

> This mod is not compatible with [**New Vegas Stutter Remover**](https://www.nexusmods.com/newvegas/mods/34832).



# Mod Organizer 2

[**Mod Organizer 2**](https://www.nexusmods.com/skyrimspecialedition/mods/6194)  
**Mod Organizer 2** is an excellent mod manager, offering lots of quality of life conveniences that make modding an easy and quick process. The most popular alternative is **Wrye Mash**. However, I’ve found that it isn’t anywhere near as intuitive as Mod Organizer 2 is, which is why we will only use it for the features Mod Organizer 2 lacks.

> Nexus Mod Manager and Vortex are two popular mods managers, however, they have significant issues and should be avoided.

- Manually download the **Mod Organizer 2** main file.
- Run the **Mod Organizer 2.exe**.
- When prompted to choose an install location, choose your Morrowind **Mods** folder (**C:\Games\Morrowind Mods\MO2**).
- When installation has finished, uncheck the option and click **Finish**.

## Configuration

### Administrator privileges

- Navigate to Mod Organizer 2's directory (**C:\Games\Morrowind Mods\MO2**) and right-click **ModOrganizer.exe**. Click **Properties**.
- In the **Compatibility** tab, check **Run this program as an administrator** and click **Apply**.
- Click **Accept** to close this window.

### Initial setup

- Run **ModOrganizer.exe**.
- Mod Organizer 2 will prompt you to **Create a new instance**. Click **Create a portable instance**.
- You will be asked to select a game to manage. Click **Browse...** and select your Morrowind **Root** folder.
- You will be asked to select a folder where data will be stored. The default MO2 folder is fine.
- Click **Next** and then **Finish**. Mod Organizer 2 will now launch.
- From the pop-up called **Register?**, click **Yes**. This will allow Mod Organizer 2 to handle Nexus links.

> If Mod Organizer 2 prompts you to **Show tutorial?**, click **No**.

### Adjusting mod and load order

Your installed mods are listed on the pane to the left. This is the order in which Morrowind loads their assets, with mods closer to the bottom overwriting the assets of mods closer to the top (if conflicting assets are present). We will refer to it as our **mod order**.

Reorganize it to read as follows using drag and drop.
```
DLC: Tribunal
DLC: Bloodmoon
Unmanaged: XE Sky Variations
```
Your plugins are listed on the pane to the right. This is the order in which Morrowind loads their plugins, with plugins closer to the bottom overwriting the records of plugins closer to the top (if conflicting records are present). We will refer to it as our **load order**.

Reorganize it to read as follows using drag and drop.
```
Morrowind.esm
Tribunal.esm
Bloodmoon.esm
XE Sky Variations.esp
```

> **XE Sky Variations** is an optional mod included in MGE XE that will randomize the sky colour and sunrise/sunset every day. It requires high quality sky scattering enabled (more on that later), and MWSE installed.

> You can hide unnecessary information in Mod Organizer 2 by right clicking on the headers above the installed mods, and unchecking the tabs you don't want to see. I suggest unchecking everything but the **Conflicts**, **Flags**, and **Priority** boxes. You can also click on the **X** to the bottom right of the **load order** panel, hiding unnecessary background information seen on the pane below.

### Adjusting Morrowind.ini

One of the patches we installed with the Morrowind Code Patch, **Rain/snow collision**, requires a few .ini edits to work properly.

- Click the **Tools** ![Tools](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_ini.png) button, and click **INI Editor**. **morrowind.ini** will now open.
- Use CTRL+F to input the section names and edit the respective entries to use these values. Note that **Weather Snow** may be found much further down below than the others, just below the **Archives** section.

```
[Weather Rain]
Rain Diameter=1200
Max Raindrops=1500

[Weather Thunderstorm]
Rain Diameter=1200
Max Raindrops=3000

[Weather Snow]
Snow Diameter=1600
Max Snowflakes=1500
```

- Click **Save** and close the window.

### Setting up Profiles

Mod Organizer 2 has a feature called **Profiles**, which lets you quickly change from one mod setup to another.

- Click the **Configure profiles** ![Profiles](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Profiles.png) button.
- Check the following options:
  - [X] Use profile-specific Game INI files.
  - [X] Use profile-specific Save Games.
  - [ ] Automatic Archive Invalidation.
- With the **Default** profile selected, click **Copy**. Type in **Morrowind#** and click **OK**. Close the window.
- On the **Profile** tab, select the **Morrowind#** profile.

Morrowind# will be the profile we'll be modding. You can always revert to the **Default** profile to quickly deactivate all installed mods.

# CONFIGURING MGE XE IN MO2

- In Mod Organizer 2, click on the executables dropdown menu to the left of the **Run** button, and select **MGE XE**. 
- Click **Run** to run the executable.

> Always remember to run MGE XE through Mod Organizer 2 to detect the Virtual Files folder.

### In-game tab

![Screenshot](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MGE%20XE%20In-game%20272.png)

Apart from the recommended settings (as seen on the image), there are a couple of options you should look out for.

**Windowed mode**
- Most users then to ALT+TAB during gameplay. However, if you want to maximize performance at the cost of stability when ALT+TABbing, you should uncheck this option.

**Options**
- Checking **Disable MGE in-game** will disable all advanced graphics settings, including MGE XE's water shader. Recommended for vanilla graphics purists.

**Morrowind engine settings**
- You may be tempted to enable **High detail actor shadows (buggy)**. As the name says, they are buggy and can be very taxing on your framerate. I don't recommend them.

### Config tab

**Information**
- Click the **Report max AA and AF** under **Information** to get your graphics card's max antialiasing and anisotropic filtering levels.

### Graphics tab

![Screenshot](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MGE%20XE%20Graphics%20272.png)

Apart from the recommended settings (as seen on the image), there are a couple of options you should look out for.

**Display**
- You should select your resolution and refresh rate.
- Set your **Antialiasing** and **Anisotropic filtering** settings to the values reported in the **Config** tab.
- Turn **VSync** on to prevent screen-tearing.

**Renderer**
- Check **Enable shaders**.
- Higher **Menu UI scaling** settings will scale up the UI. If you are playing on high resolutions (1080p and higher) I recommend starting with values at 1,20.
- Lower **FPS Limiter** settings will increase the consistency of your framerate. I personally set it to **60**.

**Shader setup...**
- On the **Set active shaders** window, click **Modding >>>**. Double clicking on the **Available shaders** makes them **Active shaders**, meaning the game will run them.
- For now, set your shader combination as follows.
```
SSAO HQ
Underwater Effects
Underwater Interior Effects
Sunshafts
```
- Click **Save** after setting up your shader chain.

> Note that **Antialiasing**, **Anisotropic filtering**, **VSync**, and **Enable shaders** will all take a heavy toll on your framerate.

### Distant Land tab

This tab lets you generate distant land, which in other words means you will see beyond the vanilla Morrowind fog. Tweaking these settings to achieve the optimal look can be difficult, and it boils down to personal taste. Distant Land can really hurt your FPS, especially when used alongside shaders, as there's more to post-process.

All options minus **Use Distant Land** and **Distant land generator wizard** are disabled when you get to this tab. We need to generate distant land for these options to become available.

- Click **Distant land generator wizard**.
- On the **Distant Land Setup Wizard**, click **Select all**. The checked plugins will be used for distant land generation.
- Click **Continue**. This will open the **Distant Land Generation** window.
- In the **Land Textures** tab, simply click **Create Land Textures**. By default, the options you should see are 2048 and 1024 texture and normalmap resolution, respectively.
- In the **Land Meshes** tab, select **Ultra High** from the **World mesh detail** dropdown menu. Click **Create Land Meshes**.
- In the **Statics** tab:
  - Set **Minimum Static Size** to 100.
  - Check **Include reflective water in interiors**.
  - Check **Use lists of statics overriding parameters set above**.
  - Click **Edit list**.
    - Click **Add**.
    - Navigate to your **Morrowind\mge3** folder, and double-click **00_main.ovr**.
    - Click **Save**.
  - Click **Create Statics**.
- Once the statics have been created, click **Finish**.

> A rule of thumb is to regenerate your distant land any time you install or uninstall mods. Most importantly, the process will be much easier as you only need to click on **Run above steps using saved / default settings** the next time you are on the **Distant Land Generation** window. On your first distant land generation, MGE XE defaults to **Distant Land configuration setup...**.

![Screenshot](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MGE%20XE%20272.png)

Now that you are back on the **Distant Land** tab you will see all previously unavailable options are now enabled. To get you started, I recommend you copy the settings as shown in the image above. In the future you may want to modify them.

> Note that Per-pixel lighting takes a heavy toll on your framerate. You can disable it entirely, or limit it to **Interiors only**.

> These draw distance settings will preserve the foggy aesthetic of vanilla Morrowind, which I recommend over the absurd draw distance seen in most modern Morrowind screenshots. If you are aching for a little bit of extra draw distance, I suggest increasing the **Draw Distance** to 5,0, and cranking up the **Above Water Fog** settings to Start 3,0 and End 5,0.

# IN-GAME CONFIGURATION

It's time to finally run Morrowind.

- In Mod Organizer 2, click on the executables dropdown menu to the left of the **Run** button, and select **Morrowind**. 
- Click **Run** to run the executable.

> Always remember to run Morrowind through Mod Organizer 2 to detect the Virtual Files folder.

- Once the game has finished loading, click **Options** and click the **Video** tab.
- The **Gamma Correction** slider lets you increase/decrease the brightness of your game. I like to play Morrowind with the slider roughly 40-45% of the way from left to right, making the game look less washed out.
- Turn the **Real-time Shadows** slider all the way to the left, disabling them. Morrowind's shadows are buggy, ugly, and are not worth the performance hit.
- Turn the **View Distance** slider all the way to the right, maximizing render distance for actors and other statics.

> If your game crashes when trying to access the **Video** tab, it may be because you are running Morrowind at a resolution unsupported by the game.

> You should not adjust your resolution through the **Video** tab, as it will crash the game. Instead, run **MGE XE** and adjust it there.

# TOOLS

Because mods can conflict with one another, or have bugs/unintended changes themselves, we will be installing a number of tools to help us troubleshoot and get rid of these issues. Detailed instructions on how to use these tools can be found in the [**Tools**](https://github.com/Sigourn/morrowind-sharp/blob/master/mwtools.md#tools) guide, however, you will be redirected to them when the time is right to use them.

## TES3View, TES3Merge, TESAME

[**TES3View**](https://drive.google.com/file/d/1r1IzfCNH-mGYp_Q1-IeRpMg5SKQnm52u/view?usp=sharing)  
Used to see the structure of mods and detect conflicts.
- Extract the contents of the file in **Morrowind Mods\TES3View**. 

> The version I'm hosting can be downloaded from [**xEdit's GitHub**](https://github.com/TES5Edit/TES5Edit/releases). Both the folder and the .exe have been renamed to TES3View in order for the tool to work for Morrowind, and several unnecessary .exes dropped to reduce download size.

[**TES3Merge**](https://www.nexusmods.com/morrowind/mods/46870)  
Used to solve conflicts by merging conflicting records into a separate plugin, **Merged Objects.esp**.
- Extract the contents of the file in **Morrowind Mods\TES3Merge**.

[**TESAME**](http://mw.modhistory.com/download-95-15443)  
Used to clean plugins and solve conflicts by manually deleting conflicting or dirty records (unintended changes by the mod's author).
- Extract the contents of the file in **Morrowind Mods\TESAME**.

### Registering tools in Mod Organizer 2

For our modding tools to work in Mod Organizer 2, we need to register and configure them. You will have to repeat these steps for each of the three tools installed above.

- Click the **Modify Executables** ![Executables](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Executables.png) button.
- Click the **Add an executable** ![AddExe](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_Add_File.png) button and select *Add from file...*.
- Navigate to the folder of the tool you want to install (each found inside **C:\Games\Morrowind Mods**) and double click its .exe file.
- In the **Start In** field, select your Morrowind **Root** folder (**C:\Games\Morrowind**).
- Click **Apply**, and repeat the process for the remaining tools.

## Wrye Mash

[**Wrye Mash**](https://www.nexusmods.com/morrowind/mods/45439)  
Wrye Mash is a mod manager and a tool used to repair and update saves, update the masters of mods, and to run tes3cmd in order to clean plugins and generate a **multipatch**.
- Download and run the **Wrye Mash 2019 x64 - Installer** main file.
- When prompted to choose an install location, choose your Morrowind **Root** folder (**C:\Games\Morrowind**).
- When installation has finished, click **Finish** to launch the **Wrye Mash 2019 Configuration Wizard**.
- Eventually the installation wizard will ask you to fill the following entries:
   - **Morrowind directory**: select your Morrowind **Root** folder (**C:\Games\Morrowind**). A message should appear under the directory saying that morrowind.ini and "Data files" folder were found.
   - **Mods Installers directory**: select your Morrowind mods folder (**C:\Games\Morrowind Mods**).
- Click **Next** and then click **Finish**.
- Wrye Mash x64 will now launch. Close the program.

> The **Mods Installers directory** is redundant to us, as we use Mod Organizer 2 to install our mods. However, assigning a directory is required to install Wrye Mash.

> **Mlox** is a tool to analyze and sort your plugin order. However, because I checked for conflicts between the plugins in this guide myself, there's no need for it.

- Download the **Wrye Mash 2021 - x64 - beta6 - manual installation archive** update file.
- Extract the contents of the file in your Morrowind **Root** folder (**C:\Games\Morrowind**), and overwrite when prompted.

> This will update WryeMash to the latest version.

### tes3cmd

[**tes3cmd**](https://github.com/john-moonsugar/tes3cmd/releases/)  
This tool is used to clean plugins by automatically deleting identical-to-master records (records that are usually *unintended* by the author as they do nothing in practice, but which may override *intended* changes by other mods) and solve a number of conflicts/issues by means of a plugin, **multipatch.esp**.
- Expand **Assets** under "v0.40-pre-release-2 (with trial Windows .exe)" and download **tes3cmd.exe**.
- Place tes3cmd.exe in **C:\Games\Morrowind\Data Files**.

> Unlike the other tools, tes3cmd doesn't need to be registered in Mod Organizer 2 as it is directly run from Wrye Mash, which we have already registered.

### Registering Wrye Mash in Mod Organizer 2

- Click the **Modify Executables** ![Executables](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO_Executables.png) button.
- Click the **Add an executable** ![AddExe](https://raw.githubusercontent.com/Sigourn/morrowind-sharp/master/MO2_Add_File.png) button and select *Add from file...*.
- Navigate to **C:\Games\Morrowind\Mopy** and double click **mash64.exe**.
- Click **Apply** and then **OK**.

> Unlike the other tools, it's not necessary to specify a **Start In** field for Wrye Mash.

# MOVING ON TO MORROWIND#

[To Morrowind# >>](https://github.com/Sigourn/morrowind-sharp/blob/master/mw%23.md#morrowind)  
[<< Back to Main](https://github.com/Sigourn/morrowind-sharp/blob/master/readme.md#morrowind-a-morrowind-modding-guide)
