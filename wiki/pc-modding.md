---
sidebar: auto
---
# PC Modding
# Preface

::: danger DISCLAIMER
By choosing to use mods, you understand that:
- You may experience problems that don't exist in the vanilla game. 99.9% of bugs, crashes, and lag are due to mods.
- Mods are subject to being broken by updates and that's normal - be patient and respectful when this happens, as modders are volunteers with real lives.
- Beat Games aren't purposefully trying to break mods. They wish to work on the codebase and sometimes this breaks mods, but they are not out to kill mods.

Do not attack the devs for issues related to mods, and vice versa - modders and devs are two separate groups. Just don't be a jerk ok.
:::

Beat Saber natively supports custom songs, so if that's all you're looking for, you don't require more mods! It's a wise idea to install `SongCore` though, as this mod expands upon the base game functionality to improve loading times and provide functionality for other mods like the in-game downloader, custom leaderboards, playlists, etc.

::: warning
This guide is for PC-modding on Windows.  
If you have a Quest, see the [Quest Modding page](/quest-modding.md).  
If you're on Linux, check out the [Linux page](/modding/linux.md) or [QBeat](https://github.com/geefr/beatsaber-linux-goodies/blob/master/README.md)
:::

If you run into problems at any point, please head to the [support page](./support) and see if you can identify what went wrong before asking in the Discord server. Chances are, your answer is on that page!

## Installers
### Mod Assistant
> **THIS IS CURRENTLY THE RECOMMENDED MOD INSTALLER.**

__**Run the game at least once**__ before trying to mod the game! This applies to reinstalling your game too. 

A simple Beat Saber Mod Installer similar to the mod manager, but with additional features such as mod removal and version checking! Get it on [Assistant's GitHub](https://github.com/Assistant/ModAssistant/releases/latest)

![ModAssistant](./images/beginners-guide/modassistant.png)

## How to get more songs
### In-game Downloader
The `BeatSaver Downloader` Plugin allows you to download maps in-game using the `MORE SONGS` menu button on the `MODS` menu screen. This pulls maps directly from [BeatSaver](https://beatsaver.com)

### BeatSaver
[BeatSaver](https://beatsaver.com) is the master repository of custom songs made by the community. Many other tools and sites enhance the experience of downloading custom songs, but this site is the source of truth.
To install songs downloaded from the site, unzip them into a folder and place it into `Beat Saber/Beat Saber_Data/CustomLevels`.  You can also use the in-game downloader plugin, BeatList, or Mod Assistant's OneClick Install feature.

### Beast Saber
[Beast Saber](https://www.bsaber.com) (bsaber.com) is a site that tries to help make finding fantastic maps to play easier. It does this by categorizing the thousands of songs on beatsaver and lets you sort by a song's genre and many other attribute tags. It also has a full social feature where players can review songs and comment on them. One of the most used features is the "Curator Recommended" feature where a team plays through most songs released each day and recommends the ones that stand out, letting you [automatically download these in-game](https://bsaber.com/beatsync/).

### Song Management Apps
* [BeatList](https://github.com/Alaanor/beatlist) is an app to manage playlist and beatmaps, by Alaanor.

### Playlists
Place the playlist file into `Beat Saber/Playlists` and select it in-game, then hit download. You can create and download playlists using one of the programs above.

## Install Folder
_Where is Beat Saber installed?_

### Default Location
|  |  |
| --- | --- |
| Steam | `C:\Program Files (x86)\Steam\steamapps\common\Beat Saber\` |
| Oculus | `C:\Program Files\Oculus\Software\Software\hyperbolic-magnetism-beat-saber\` |

### Other Locations
**If you have moved your install folder to a different drive, it might be in the location below.**
Replace the drive letter `F` with the drive your game is installed on.
|  |  |
| --- | --- |
| Steam | `F:\SteamLibrary\steamapps\common\Beat Saber\` |
| Oculus | `F:\Oculus\Software\Software\hyperbolic-magnetism-beat-saber\` |

## How to uninstall mods
Either remove the dll from the `Plugins` folder, or click the `Uninstall` button in Mod Assistant.

## Manual Installation
A mod installer is the recommended way to install mods. See the section [above](#installers). If you have patched the game and just need to install Plugins that are not available in the installer, skip to step 4.

**Run the game at least once** before trying to mod the game! This applies to reinstalling your game too. 
### Install BSIPA 
1. Download [BSIPA](https://github.com/beat-saber-modding-group/BeatSaber-IPA-Reloaded/releases).
2. Navigate to your [install folder.](#install-folder) and extract the contents of BSPIA into it.
![Directory Clean](./images/beginners-guide/directory-clean.png "Directory Clean")
![Directory Ipa](./images/beginners-guide/directory-ipa.png "Directory Ipa")
3. Double click IPA.exe to patch the game. Any mods in the `Plugins` folder will now be loaded when starting the game. If there are errors, you probably didn't follow step 2 correctly.
![Directory Patched](./images/beginners-guide/directory-patched.png "Directory Patched")

### Install Mods
4. Download the mod(s) you wish to install, whether it be from GitHub, the #pc-mods channel, or other sources. **Make sure to download any dependencies required by the mod.**
![Directory Plugins](./images/beginners-guide/directory-plugins.png "Directory Plugins")
5. Some mods have installation instructions, some don't. Generally you can just drag and drop the zip contents into your beat saber install folder, and the files should go into the corresponding folders. 


## Where to go from here
* [Grips and Tricks](./grips-and-tricks.md)
* [Making Beatmaps](/mapping/)
* [Custom Sabers](/models/custom-sabers.md)
* [Custom Avatars](/models/custom-avatars.md)
* [Custom Platforms](/models/custom-platforms.md)
* [Setup Multiplayer](https://bs.assistant.moe/Multiplayer/)
* [Making Mods](/modding/)

## Have questions?
Visit the support channels in the [BSMG Discord](https://discord.gg/beatsabermods)!
