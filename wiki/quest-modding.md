---
sidebar: auto
---
# Quest Modding

## Installation 

Currently there are two working tools for installing custom songs and mods on your Quest:
* [BeatSaberQuestInstaller (windows only GUI for installing BMBF)](https://github.com/NyanBlade/BeatSaberQuestInstaller/releases)
* [BMBF installed via SideQuest](https://github.com/kihecido/BMBF/releases)

For new users, BeatSaberQuestInstaller may be easier to use as it handles some of the more confusing parts of modding/updating a modded game, such as restoring scores and installing adb.

### Installing with BeatSaberQuestInstaller

:::warning
Make sure you run the installer as administrator!
:::

If you're a new user, then follow the first 3 steps in the BeatSaberQuestInstaller, then go to the utilities tab and backup your scores.

If you've previously modded Beat Saber, you also need to go there to uninstall the game, but make sure you backup **BEFORE** uninstalling.

![BeatSaberQuestInstaller](./images/beginners-guide/bsqioptions.png)

Once you've done what you need, go to step 4 in the installer. After completing the steps, open BMBF from the channels tab in Oculus TV or Unknown Sources in your library.

### Installing BMBF with SideQuest

If you haven't already, download and setup [SideQuest](https://sidequestvr.com/#/setup-howto)

Open SideQuest and connect your Quest to your PC. If you've previously modded Beat Saber or have scores you want to backup, go to `My Apps` located in the top bar of the window and find Beat Saber.

Click the cog next to it then press the `BACKUP GAME DATA` button, if you have a modded game you also need to uninstall it by pressing the `UNINSTALL APP` button.

![SideQuestUninstall](./images/beginners-guide/squninstall.png)

You can later restore your save from the same menu, after modding.

Install the latest BMBF apks via the `Install APK from folder` button shown below.

![InstallAPK](./images/beginners-guide/apkfromfolder.png)

Once they've successfully installed, make sure you have the latest version of Beat Saber installed and unmodded. 
:::warning
Run Beat Saber once and close it before modding!
:::

After running Beat Saber once, open BMBF from Oculus TV channels tab or Unknown Sources in your library. Follow each step exactly as you're told, and then you should be see [bsaber.com](https://www.bsaber.com). This is where you can download any custom songs available.

## Restoring save data

### Restoring from BeatSaberQuestInstaller

Make sure you've run the game modded once, then go to the `UTILITIES` tab in the BeatSaberQuestInstaller and press the `TRANSFER SCORES` button. You can also do this from step 4 in the installer.

### Restoring from SideQuest

Go back to the same menu you used to backup your data and click the `OPEN BACKUPS` button.
From there, find your newest backup folder, open it, and delete the Mods folder (this is to prevent potentially old or incompatible mods from breaking your game).

Afterwards, go back to the menu and press the circular arrows located beside your latest backup. This is to restore your scores.
The button is highlighted in the image [here](#installing-bmbf-with-sidequest).

## Installing mods from your PC

:::warning
Make sure your quest and PC are on the same network!
:::

Open BMBF in your Quest and go to the `Tools` tab, there you should see a web address and a version number similar to what's show below.

![ip](./images/beginners-guide/ip.png)

On your PC, open your browser and type the address into the search bar.

You should be greeted with this screen below.

![bmbfweb](./images/beginners-guide/bmbfweb.png)

Now just drag any Quest compatible mods into the upload box and sync. If the mod was originally made for an older version, then it won't automatically enable. To enable an old mod, go to the `Mods` tab and enable it from there.

If you want to use the same method of downloading songs as you do in BMBF in your Quest, just replace `upload` in the URL with `browser`.

## Useful links and alternative guides

* [Oculus Quest BMBF Installation Guide](https://bsaber.com/oculus-quest-custom-songs/)
* [General Guide by Sc2ad for Learning The Basics of Asset Modding](https://github.com/sc2ad/beat-saber-community-wiki/blob/master/asset-modding-guide.md)
* [Collection of All Current Guides for Asset Mods Such As Sabers and Notes Made by RedBrumbler](https://github.com/RedBrumbler/BMBFCustomSabers/wiki/RedBrumblers-Asset-Mod-Guide-Wiki)
* [Fixing Out of Sync Audio](https://bsaber.com/quest-out-of-sync/)
