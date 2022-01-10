# Team Fortress 2: Enhanced Lite
Team Fortress 2: Enhanced is the modpack focused on improving overall visuals and sound effects while keeping original TF2 atmosphere.

Due to license issue, the modpack will not be available, so you must download it on their mod page manually.

This version is lite version of Team Fortress 2: Enhanced, aiming for complete sv_pure 1/Valve server compatibility.

# Changelog
See [here](https://github.com/MysticMoonlight/EnhancedMod/blob/main/tf2e/CHANGELOG.md).

# How to Install
1. Extract the archive file you downloaded (It should be `.zip`, `.rar`, or `.7z`)
2. Put the folder or vpk file to `tf/custom` folder inside Local Files (To access local files, Go to Properties -> Local Files -> Browse...)
	* 2-1. **Attention to Linux/macOS Users!** If the folder contains uppercase and space, you must rename the folder to contain only lowercase/underscore/hyphen otherwise TF2 cannot detect the folder mod(s) upon launch!
3. Launch the game, enjoy the modpack!

## Additional Steps (Optional)
You need to do additional steps when installing SOUP and TF2 Community HUD Fixes together, in case if you wish to use both mod seperately.

If you are unsure what to do, you are safe to skip this step and just install default SOUP version (But expect lack of changes compared with original version of TF2 HUD Fixes)

Here's how to do that:

1. Download the latest [TF2 Community HUD Fixes](https://gamebanana.com/mods/26450) then extract the zip folder.
2. Locate to TF2 Community Fixes folder, then locate to `(HUD folder)/resource/ui` then open a file named `hudplayerclass.res` (We recommend using Notepad++ or VSCode)
3. Find the section named PlayerStatusClassImage, in there you can see the `"image"			"../hud/class_scoutred"`. Replace the following line with `"image"			"../materials/hud/class_scoutred"`
4. Remember to save then close the editor.
5. Download the art only version of SOUP [here](https://gamebanana.com/mods/download/26400), then extract the archive.
6. Locate to `art-only-soup-vXXX` folder(XXX is the version name), then move the `materials` and `scripts` to HUD Fixes file.
7. Move the hud folder you changed to custom folder. (You know where it is because we already explained it above)
8. Launch the game and now you are done! Enjoy the latest TF2 HUD Fixes with this patch.

# List of Mods
## UI Mods
* [Alternate Class Portraits (Full Version)](https://gamebanana.com/mods/26024)
* [HD TF2 Menu Logo](https://gamebanana.com/mods/27061)
* [Improved Create Server Menu](https://gamebanana.com/mods/332109)
* [Sloofy's Overhauled UI Portraits (SOUP)](https://gamebanana.com/mods/26400) (Please refer to additional steps if you wish to use SOUP with latest HUD Fixes)

## Visual Mods
* [Morning Lightwarp](https://gamebanana.com/mods/205354)

## Sound Mods
* [More Musical TF2 Events](https://gamebanana.com/sounds/53978) (Choose only one version - Barebones or Definitive)
* [Team Fortress 2 Soundtrack During Gameplay Mod](https://gamebanana.com/mods/36634)

## Fixes and Optimization Mods
* [Improved tr_target](https://gamebanana.com/mods/74748) ([Unofficial fix](https://github.com/RoonMoonlight/Improved-tr_target-UnofficialFix/releases/latest) available)
* [mastercomfig](https://mastercomfig.com)
* [Smissmas Casual Gametype Image Fix](https://gamebanana.com/mods/27036)

## Optional Mods
* [Color Coded Lethality of Sniper Rifle Charge Meter](https://gamebanana.com/mods/345919)
* [Classic Guilty Gear Slash Hitsounds](https://gamebanana.com/sounds/56790)
* [Smissmas Background in Color](https://gamebanana.com/mods/25229)

# Note
* This is intended for peoples who mainly play on Valve/sv_pure 1 servers. If you want full experience, please use the [original version](https://github.com/MysticMoonlight/EnhancedMod/blob/main/tf2e/LITE.md) instead.
* This obviously does not work on sv_pure 2 servers.
* Please use official download such as GameBanana, and do NOT use other illegal redistribution website.
