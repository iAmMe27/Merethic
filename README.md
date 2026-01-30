![Merethic Banner](img/Splash.png)

First things first: **this list contains adult content and you must be of legal age in your country. This means 18+ in most countries, 21+ in others. It is up to you to be sure of the age requirement in your country.**

# Contents
- [Contents](#contents)
- [What is Merethic?](#what-is-merethic)
- [Quick Links](#quick-links)
- [Need Support?](#need-support)
  - [Asking for support in Discord](#asking-for-support-in-discord)
- [Support me?](#support-me)
- [Load Order Library](#load-order-library)
- [Preface](#preface)
- [Hardware Requirements](#hardware-requirements)
  - [Storage Space](#storage-space)
- [You Will Need](#you-will-need)
- [Pre-Installation](#pre-installation)
  - [Install Microsoft Visual C++ Redistributable Packages](#install-microsoft-visual-c-redistributable-packages)
  - [Setup your Antivirus](#setup-your-antivirus)
  - [Setup your Page File](#setup-your-page-file)
  - [Remove OneDrive](#remove-onedrive)
  - [Disable Steam Overlay](#disable-steam-overlay)
  - [Set game language to English](#set-game-language-to-english)
  - [Change Steam's Updating Behavior](#change-steams-updating-behavior)
  - [Install Skyrim SE](#install-skyrim-se)
  - [Install Creation Kit](#install-creation-kit)
  - [Start Skyrim SE](#start-skyrim-se)
  - [Manually download non-Nexus mods](#manually-download-non-nexus-mods)
- [Install Merethic in Wabbajack](#install-merethic-in-wabbajack)
  - [Select the Modlist](#select-the-modlist)
  - [Select Installation \& Download Folders](#select-installation--download-folders)
    - [Installation Folder \[1\]](#installation-folder-1)
    - [Download Folder \[2\]](#download-folder-2)
    - [Starting the Installation \[3\]](#starting-the-installation-3)
  - [Installation is finished](#installation-is-finished)
- [Post-Installation](#post-installation)
  - [Creating a desktop shortcut](#creating-a-desktop-shortcut)
- [Mod Setup](#mod-setup)
- [Updating Merethic](#updating-merethic)
- [Uninstalling Merethic](#uninstalling-merethic)

# What is Merethic?
Merethic is a NSFW Skyrim modlist that aims to improve and add upon the Skyrim experience. It's a power fantasy list with new lands and new areas added to Skyrim to encourage exploring.

# Quick Links
:arrow_down: [All Manual Downloads](https://github.com/iAmMe27/Merethic/wiki)

:file_folder: [Known Problematic Downloads](https://github.com/iAmMe27/Merethic/wiki/Known-Commonly-Failing-Downloads)

:exclamation: [Common Issues](CommonIssues.md)

:question: [Frequently Asked Questions](FAQ.md)

:wrench: [Advanced Extras - including Performance LODs](Advanced.md)

# Need Support?

If you encounter any issues that are not answered in this file, have a look at [Common Issues](CommonIssues.md) first.  
There is also a [FAQ](FAQ.md).  
Gameplay information can be found [here](Gameplay.md).

If the documentation provided does not provide you with an answer, or if you just want to chat and hang out, feel free to join our discord (link below).

> [!WARNING]
> Only Windows 10 or 11 operating systems are supported. Windows LTSC, special variants, lightened editions or any other modified variant ***WILL NOT WORK.*** Linux installations also ***WILL NOT WORK.*** If you get it working on Linux, that's great, but not something we can officially support.

## Asking for support in Discord
If you want to ask for support in Discord, grab the "Merethic" role in onboarding or in "Channels & Roles" at the top of the channel list.  
Before asking your question, please use the discord search function and check pinned messages in relevant channels.

Still haven't found an answer to your problem?  
Please make sure to ask your question in the appropriate channel.

- merethic-general -> General discussion about the list or included mods.
- merethic-modified -> Support-Channel for vanilla installs (if you changed files, added or deleted mods in your install, ask for support here).
- merethic-support -> Support-Channel for vanilla (unchanged) installs.

[![DiscordButton](img/DiscordButton.png)](https://discord.gg/iAmModlist)

# Support me?

If you like the modlist, consider buying me a coffee or something.  

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z7CKSPJ)

# Load Order Library
[Preview of the modlist can be found on Load Order Library here.](https://loadorderlibrary.com/lists/merethic-3)



# Preface
Just to set some expectations and boundaries surrounding modlist development here, there's a couple things I'd like to say first.

1. As a modlist user, I expect some small efforts into fixing your own issues, mostly by searching the documentation provided here and by the Discord channels. It's very likely any issue you encounter has already been solved - if this is the case and it's well known, don't be surprised if you get ignored.
   
2. Support shouldn't be expected as instant - I have a full time job on top of this, as do my mod team, so I ask for a little bit of patience.
   
3. Do not expect a 100% polished, well-balanced and "perfect" experience. I am a 1-person dev team and expecting more from me than you would from AAA game studios is insanity.
   
4. We're modding a nearly 14 year old game here, please temper your expectations some.
   
5. I won't have a specific area for suggestions for mods to add. I used to have one and from what I've seen there and in other modlist situations is that people suggest mods that don't fit a lists theme or generally "bad" mods and then feel as if they're ignored or get annoyed when we say "won't add this".

# Hardware Requirements

|             | CPU                             | RAM                 | GPU                                             |
|-------------|---------------------------------|---------------------|-------------------------------------------------|
| Minimum     | Intel 7th Gen,  AMD 3000 Series | 16GB DDR4 @ 3000MHz | RTX 3070 (at least 8GB of VRAM) |
| Recommended | Intel 9th Gen, AMD 5800X        | 32GB DDR4 @ 3600MHz | RTX 4070                        |

## Storage Space 

As of v1.3.3, the current storage requirements are:

| Downloads   | Installation   | Total   |
|-------------|----------------|---------|
| 276GB       | 530GB          | 806GB   |

Your installation must be on an ***internal*** SSD. External SSDs & HDDs are too slow for modlists to run from. Downloads **can** be put onto an external SSD or HDD.

# You Will Need
  * A Nexus Premium Account
  * A LoversLab Account
  * Patience
  * The ability to read - *if you got this far, I commend your ability* :)

>[!WARNING]
>Merethic requires all Creation Club content - **you need the $20 AE upgrade from Steam to install!**

# Pre-Installation

**This stuff needs to be done BEFORE starting the Wabbajack installation.**

## Install Microsoft Visual C++ Redistributable Packages
>[!CAUTION]
>MO2 and various SKSE mods need this - don't skip it.
>
>[Download Visual C++ Redistributable Package.](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

## Setup your Antivirus
Before you say "I don't have an antivirus" - you do, it's built into Windows. You *need* to exclude your Wabbajack folder and your Merethic installation folder from your antivirus' real-time protection stuff as it will interfere with your install. It can and will interfere whilst you are playing too, causing poor performance and obvious stuttering.

> [!TIP]
> How do I do this, you ask? [Click here to find out how.](https://support.microsoft.com/en-gb/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26)

If you use another antivirus program, refer to their steps for adding an exclusion.

> [!WARNING]
> If you use Webroot, BitDefender, Norton or Kaspersky, I recommend you stop using these as these programs ***actively*** interfere with modlists even when they are excluded. Plus, you're wasting your money.

## Setup your Page File
Skyrim modlists need a large amount of memory to allocate, regardless of how much RAM you have.

<details>
<summary>To setup your pagefile:</summary>

1. Hold down the *LEFT* Windows key and press **R**
2. Type in `systempropertiesadvanced` in the run box and then press ENTER
3. Under the "Performance" option, click the "Settings..." button
4. Switch to the "Advanced" tab
5. Under "Virtual Memory", click the "Change..." button
6. Uncheck `Automatically manage...` if it's checked
7. Select your *fastest* SSD in the list of drives
8. Check "Custom Size"
9. Set `Initial Size` to 20480
10. Set `Maximum Size` to 20480 also
    1.  *Note: you can set this up to 40000 if you have the space, this will let the pagefile expand to as large as 40GB*
11. Press the "Set" button
12. Press OK
13. Press APPLY and then OK
14. Restart your PC to apply the pagefile setting

</details>

## Remove OneDrive
If you have OneDrive and it is sync'ing your Documents folder, it's time to remove it. It will interfere with saves and will lead to crashes whilst you're playing.

## Disable Steam Overlay
The Steam overlay is known to cause issues, especially when using ENBs. Do so by heading into Steam, right clicking on Skyrim in your game library and clicking **Properties** > **General** > **Deselect "Enable Steam Overlay while in-game"**.

## Set game language to English
Wabbajack and Merethic only support English language versions of Skyrim. Right click on Skyrim in your game library and click **Properties** > **Language** > **Select English**.

## Change Steam's Updating Behavior
Do this by right clicking on Skyrim in your game library and clicking **Properties** > **Updates** > **Change Automatic Updates to "Only update this game when I launch it"**. Whilst you're in here, it's also recommended to disable Steam Cloud too.

## Install Skyrim SE
Once you've done the steps above, you can now set Steam to download Skyrim but ***do not*** install Skyrim to a protected folder, such as `Desktop`, `Downloads` or `Program Files` of any kind. It's best to create a new, dedicated folder for it using the Steam Library function somewhere on the root of your drive such as `C:\SteamLibrary`. A lot of people have a dedicated secondary drive for their games, keeping the OS install separate; using this secondary drive will also work.

## Install Creation Kit
You will also need Skyrim Special Edition Creation Kit installed from Steam (make sure to enable software/tools if you can't see it).  
If you don't have the Creation Kit installed, the Wabbajack Installation will fail.

## Start Skyrim SE
Start Skyrim and let it load to the main menu.
It will ask if you want to download the Creation Club content.

Click yes and **DO NOT DO ANYTHING ELSE** until the downloads are finished.
Tabbing out (and other actions) will cause problems with the downloaded files, so hands off the keyboard and let it do its thing.

> [!TIP]
> If you are not on a fresh install, still go into the Creations menu and make sure all Creation Club content is enabled and downloaded.

## Manually download non-Nexus mods

It is required that you download all non-Nexus mods in your browser prior to running Wabbajack. All links to mods not hosted on Nexus Mods can be [found here](https://github.com/iAmMe27/Merethic/wiki).

> [!CAUTION]
> Currently, downloading Loverslab mods through wabbajack does not work. Even though it shows the mod page and you can click the download button, it will not pass the file check at the end and Wabbajack will throw an error. Don't skip this step, even if you successfully downloaded LL mods through wabbajack in the past.

# Install Merethic in Wabbajack
Installing the list is straight forward, Wabbajack will do most of the heavy lifting for you - you only have to tell it where to put stuff.

## Select the Modlist
Open Wabbajack.  
Always open Wabbajack with the Wabbajack Launcher.exe instead of the wabbajack.exe directly, to make sure you're always using the latest version.

- Click on "Browse lists"
![Image](/img/wj_install_1.png)

- In the next window, make sure the "NSFW" and "Non-featured" toggles are **__toggled ON__**, and search for the name of the modlist.  
Once it shows up on the right, click on it.
![Image](/img/wj_install_2.png)

- Once the detailed view is open, click "Download & Install".
![Image](/img/wj_install_3.png)

## Select Installation & Download Folders
![Image](/img/wj_install_4.png)

### Installation Folder [1]
This folder is where the modlist will be **__installed in__**.  
Set the installation location to a folder on the root of a drive, something like `C:\Merethic`.  

> [!CAUTION]
> Do not install Merethic to your game folder or in any protected folders such as your Documents or Program Files.

### Download Folder [2] 
This folder is where the downloaded mods will be stored.  
The **Non-Nexus mods** you downloaded in the last step **go here**.

> [!TIP]
> If you want to save space on your fast SSD, this folder can be stored on slower drives, even an HDD.  
> We suggest you keep your downloads and don't delete them after, so if you want to update or reinstall the list, you don't have to download everything all over again.

### Starting the Installation [3]
Once you have set your folders, hit **GO** and let it do its thing.

> [!CAUTION]
> Once you click "Install", there is no going back, the installation will start.
>
> Therefore, make **DOUBLE SURE** you have set your Download and Installation folder correctly.  
> Upon start of the installation, your Installation folder **WILL BE EMPTIED**.  
> So if you have them the wrong way around, Wabbajack can **and will DELETE ALL YOUR DOWNLOADS**!
>
> You have been warned.

## Installation is finished
Once the install is finished, you will see the following screen.  
Click "Open in File Explorer" to open your installation folder and start ModOrganizer.exe in there, then continue to the next step.

If your screen does not like this (especially if you have a red box with an error on the lower left), have a look at our [Common Issues](CommonIssues.md) page. 

![Image](/img/wj_install_5.png)


# Post-Installation
After Wabbajack has given you the installation successful screen, you're free to close it. Navigate to the Merethic installation folder and run MO2 by double-clicking `ModOrganizer.exe`.

>[!WARNING]
>**DO NOT UNDER ANY CIRCUMSTANCES RUN LOOT.**
> 
>The load order is exactly as intended out of the box and you do not need to change it.

## Creating a desktop shortcut
Open MO2, ensure **Merethic** is selected in the dropdown and click the "Shortcut" button. From the small dropdown menu, click "Desktop".

![Desktop Shortcut Creation](img/DesktopShortcut00.png)

# Mod Setup
When starting a new game, create your character and once done, *DO NOTHING ELSE* and allow the mods to initialise.

1. Once initialised, open the MCM Config menu, navigate to the MCM Recorder menu and run `Part 1`. Play the recording and allow it to finish.
2. Save your game and reload.
3. Navigate to the same menu and run `Part 2`.
4. Save your game and reload.

**IED currently needs manual setup:**

Without the game paused, press `RIGHT SHIFT + BACKSPACE` to open the IED menu and in the top menu bar, click `View` and then `Gear Nodes` to open the Gear Positioning menu.

![](img/IED01.jpg)

In the Gear Nodes menu, ensure you are in the `Global` tab, with the `Player` option selected and then ensure `Sync` is ticked. Then from the `Preset` dropdown, select the `Merethic` preset.

![](img/IED02.png)

Once selected, hit the `Apply` button and then click `OK` on the confirmation dialog box.

![](img/IED03.jpg)

# Updating Merethic
When an update is released, please always check the [changelog](changelog.md) first. Backup your saves before you commit to any updates, Wabbajack doesn't usually touch save files, it does has the ability to delete them if it wanted to.

If you have added anything to this modlist at all, Wabbajack will also delete those. You should know how to stop it from doing this if you're going to add stuff to modlists.

# Uninstalling Merethic
Just delete the Merethic folder and it'll be gone.
