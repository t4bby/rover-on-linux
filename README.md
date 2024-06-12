## This modifies the game anti-cheat. Use at your discretion. You've been warned. I am not responsible for any in-game bans.

# Wuthering Weather Linux Installation
Status: Works as of `June 12, 2024`.


## Preview
Tested on: Steam Deck `SteamOS 3.7`
![](/assets/works.png)

## Requirements
- ProtonGE `GE-Proton9-7` (latest) 
- Heroic Launcher 

## Heroic Launcher Installation
1. Download the `Windows` setup file from their website:
https://wutheringwaves.kurogames.com/en/
2. From `Heroic Launcher` -> `Add Game`

### Set these values
Title: `Wuthering Waves`
#### Show Advanced Settings
- Wine Prefix: `/home/deck/Games/Heroic/Prefixes/default/Wuthering Waves`
- Wine Version: `Proton - GE-Proton9-7`

3. Click `Run Installer First`
![](/assets/heroic/1.png)

4. Select the setup file you have downloaded from their website (e.g. `WutheringWaves-overseas-setup-1.5.3.0.exe`)
![](/assets/heroic/2.png)
 
5. Install the launcher
![](/assets/heroic/3.png)

6. Download the game
![](/assets/heroic/4.png)

7. After downloading **DONT START THE GAME YET** just close the launcher

8. Back to Heroic Launcher, Select Executable
![](/assets/heroic/1.png) click the `Folder` icon

9. Navigate to your `WinePrefix drive_c` folder. (e.g. `/home/deck/Games/Heroic/Prefixes/default/Wuthering Waves/pfx/drive_c/Wuthering Waves`) and choose `launcher.exe`
![](/assets/heroic/5.png)

10. Click `Finish`, now proceed to [**Patching the game**](#patching-the-game)
![](/assets/heroic/6.png)

## Patching the game
This is the most important part to be able to play the game. Follow the instructions carefully!

1. Download `d3d9.dll` from my another repository: https://github.com/t4bby/dll-plugin-loader/releases
![](/assets/patching/1.png)

2. Move the `d3d9.dll` to `Wuthering Waves/Wuthering Waves Game/Client/Binaries/Win64` from your `WinePrefix drive_c` directory (e.g `/home/deck/Games/Heroic/Prefixes/default/Wuthering Waves/pfx/drive_c/Wuthering Waves/Wuthering Waves Game/Client/Binaries/Win64`)
![](/assets/patching/2.png)

3. Create folder inside the `Win64` folder named `Plugins`
![](/assets/patching/3.png)

4. Download the `bypass.dll` on this repository it is located on `patch` folder or click [here](https://github.com/t4bby/wuthering-waves-linux/raw/main/patch/bypass.dll) to download the file

5. Move the `bypass.dll` into the `Plugins` folder you created
![](/assets/patching/4.png)

All done. **Launch the game**

## Wahh anti-cheat windows pops up
You can safely ignore it. The game will still work
![](/assets/patching/5.png)

### Credits
- [Z4ee](https://github.com/Z4ee) for the ACE anti-cheat bypass

### Buy me a coffee
https://ko-fi.com/t4bby
