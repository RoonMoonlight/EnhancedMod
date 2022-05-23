# Changelog
## Team Fortress 2: Enhanced v9.0-2022.20a "Your Freedom" (May 23, 2022)
> *"As of this version, you will gain more freedom of your choice."* 

Welcome to yet another update of Team Fortress 2: Enhanced experimental release! This update brings many changes to the sound and hud effects.

In this update, **mastercomfig has been removed** due to restricting many settings and unnecessarily limiting the user's choice by forcing the settings. Due to this change, you need to follow additional step to reset the config revert back to default TF2 settings. Steps to reset the settings and configurations are explained below.

This is one of the update to resolve [Issue #8](https://github.com/MysticMoonlight/EnhancedMod/issues/8) - Thank you Sloofy once again for the reporting a issue!

Many people have suffered from bot crisis on Team Fortress 2 Casual mode, leading tf2 community to protest about updating the game. We, as Team Fortress 2 community, wants the answer to Valve why they are ignoring community's voice and not updating to prevent cheaters and bots on TF2.

Mystic Moonlight community now have a 6v6 community server; if you are tired of cheaters and bots from casual, you can now play on our server right [here](https://mysticmoonlight.carrd.co/) (Click on 'Community Server' then click 'Link' to connect).

Enjoy the new features with this update!

### Highlights
* SOUP is replaced with art only due to forcing the usage of Community Fixes hud
* Added TF2HUD+ Old Updated, allowing you to customize the HUD for your likings!
* Fonts has been improved for better looking
* Item images are now in HD
* **mastercomfig is now obsolete**
* Reverted domination sound with meet your match version
* Removed [Tweaked Stamp Background](https://gamebanana.com/mods/356346) as it is no longer necessary (Refer to [March 30, 2022 patch](https://wiki.teamfortress.com/wiki/March_30,_2022_Patch) for details)

### Breaking Changes
Warning: This will reset ALL settings. Make sure you back up your binds and other custom settings before you do this.

Due to removal of mastercomfig, unfortunately you will have to reset your config after update. Here's how to do that:

1. Go to following directory: `STEAM_FOLDER/userdata/USER_ID/440/remote/cfg` (For windows it is located on C:\Steam\userdata\[Your User ID]\440\remote)
2. Open the `config.cfg` with Notepad or any text editor, empty everything inside the cfg file and save it. DO NOT REMOVE THE CFG FILE.
3. Go back to your steam library, Right Click on Team Fortress 2 on your game list, then click on Properties.
4. Remove anything inside the Launch Option, replace it with the following launch option: `-novid -autoconfig -default +host_writeconfig config.cfg full +mat_savechanges +quit`
5. Close the window and launch TF2.
6. After the game closes, go back to Properties (Same with Step 3) and remove anything inside the launch options.
7. Close it and launch TF2. Now you are done!

As of this changes, you are now allowed to use your own launch options, such as `-novid` and more.

### Mod list changes
#### Additions
* [Absolutely HD Item Icons](https://gamebanana.com/mods/316151)
* [Dynamic KOTH/CP Soundtrack](https://gamebanana.com/sounds/53977)
* [Intruder alert for intel steal](https://gamebanana.com/sounds/42420)
* [Meet Your Match Match end (CASUAL MODE)](https://gamebanana.com/sounds/54246)
* [MYM Badge Domination/Nemesis/Revenge Sounds](https://gamebanana.com/sounds/44570)
* [Payload Struggle Terminus Warning](https://gamebanana.com/sounds/53979)
* [Source Text Refont [Better Looking Default Text]](https://gamebanana.com/mods/314848)
* [TF2HUD+ Old Updated](https://gamebanana.com/mods/26761)

#### Changes
* [Musical Events](https://gamebanana.com/sounds/53978) now forced to Barebones, NOT Definitive edition. If you have Definitive Edition installed, you should remove it and replace with Barebones otherwise there will be conflict with other additions.
* [Sloofy's Overhauled UI Portraits (SOUP)](https://github.com/Sloofy/soup/releases) link changed to GitHub and you need to install art only version from now on; if you have existing `soup-v181` folder, remove it and download art only version and put it on custom folder
* 
#### Removal
* [mastercomfig](https://mastercomfig.com)
* [Tweaked Stamp Background](https://gamebanana.com/mods/356346)

## Team Fortress 2: Enhanced v9.0-2022.18a "The Patriot's Legacy" (May 8, 2022)
Welcome to first experimental release of v9.0 series! This update includes improvements from existing Half-Life 1 sounds, which is backported from Half-Life 2.

This update is dedicated to Rick May, who was the Voice Actor of Soldier. Thank you Rick May.

### Highlights
* Existing sounds reused from Half-Life 1 now replaced with high-quality audios! (Backported from HL2)

### Mod list changes
#### Additions
* [Remastered HL1 sounds for HL2](https://gamebanana.com/sounds/60511)

## Team Fortress 2: Enhanced 8.0-2022.14a "Cross Land" (April 2, 2022)
This might probably the last development release due to upcoming exam happening soon. We will be back with great major update once the exams are all over! After test ends, 8.0 might release, so stay tuned!

### Highlight
* Removed all Toon effects due to consistency issue and usage of other materials from Bandai Namco, Sora, etc.
* New effects replacing all Toon effects for better consistency (Some of particles may not work, please report any issues if there is any bug related to particles)
* New gore effect inspired from Open Fortress!

### Mod list changes
#### Additions
* [Bloodiest Fortress 2](https://gamebanana.com/mods/367935)
* [Enhanced Explosions (V1.2)](https://gamebanana.com/mods/12442)
* [Improved Muzzleflashes](https://gamebanana.com/mods/12593)
* [Stylized Cow Mangler Effects Redux](https://gamebanana.com/mods/12388)
* [Stylized Projectile Effects Redux](https://gamebanana.com/mods/11719)
* [Stylized Righteous Bison Effects](https://gamebanana.com/mods/11720)
* [Stylized Rockettrails Redux](https://gamebanana.com/mods/12387)

#### Removal
* [Toon Explosion FX](https://gamebanana.com/mods/12446)
* [Toon Muzzle Flashes](https://gamebanana.com/mods/12592)
* [Toon Righteous Bison FX](https://gamebanana.com/mods/11852)
* [Toon Rocket Trails](https://gamebanana.com/mods/12410)

## Team Fortress 2: Enhanced 8.0-2022.13a "Rainbow Monoculus" (Mar 27, 2022)
Howdy! Due to Roon caught a COVID-19 and recovering from COVID-19, the experimental release of TF2: Enhanced had to be cancelled for several weeks. But no worries! We are now back.

This update includes some style changes to be more cartoon-ish style: On 2007 Beta version of Team Fortress 2, the muzzleflash effect was more cartoonish, however the particle has been replaced on retail version to be realistic one. This update reverts back to old style: which was intended to be more cartoonish styles.

### Highlight
* New Quickplay Styled Gamemode Portraits has been arrived for more cartoonish feelings
* Replaced all particle effect mods with Chaofanatic's Toon particle mods
* Merged Fixes/Improvement Mod and MvM Improvements type to Sounds or Visual mods category

### Mod list changes
#### Additions
* [Quickplay Styled Gamemode Portraits 2022 Edition](https://gamebanana.com/mods/366394)
* [Toon Explosion FX](https://gamebanana.com/mods/12446)
* [Toon Muzzle Flashes](https://gamebanana.com/mods/12592)
* [Toon Righteous Bison FX](https://gamebanana.com/mods/11852)
* [Toon Rocket Trails](https://gamebanana.com/mods/12410)

#### Removal
* [Altered Projectile Trails](https://gamebanana.com/mods/12420)
* [Expensive Explosions](https://gamebanana.com/mods/12454)
* [Simple Muzzleflashes V.3](https://gamebanana.com/mods/12584)

#### Replacement
* [Giblet Overhaul (Vanilla Blood)](https://gamebanana.com/mods/205664) -> [Giblet Overhaul (TF2C Blood)](https://gamebanana.com/mods/288308)

## Team Fortress 2: Enhanced 8.0-2022.09.a "Monochrome Witch" (Feb 27, 2022)
Due to recent real-life events, 2022.08.a had to be cancelled.

### Highlight
* New codename and some version display fixes
* Reverted back heavy voices
* Changed to Bloody Hit/Kill sound instead to keep hit/killsound consistency
* Fixed Vaccinator beam being misaligned
* Removed Effect+ Addon, instead moved some mods from Effect+
* Removed Visual Fix Pack due to conflict with several particle mods

### Mod list changes
#### Additions
* [Aligned Heal Beam Vaccinator Fixed](https://gamebanana.com/mods/12082)
* [DemonstrationTF Bloody Hit/Kill Sounds](https://drive.google.com/file/d/1TrAwgYa_wDi5Qab4c_PJe9p5GBbFp3Jd/view)
* [Expensive Explosions](https://gamebanana.com/mods/12454)
* [Simple Muzzleflashes V.3](https://gamebanana.com/mods/12584)

#### Removal
* **Effect+ Addon**
* [8-Bit Killsound](https://gamebanana.com/sounds/31498)
* [Heavy MVM Voice Lines Fix](https://gamebanana.com/sounds/59076)
* [Simple Retro Beep Hitsound](https://gamebanana.com/sounds/59256)
* [Ultimate TF2 Visual Fix Pack](https://github.com/agrastiOs/Ultimate-TF2-Visual-Fix-Pack)

#### Moved
* [Altered Fire FX](https://gamebanana.com/mods/289584) (Effect+ -> Main branch)
* [Altered Projectile Trails](https://gamebanana.com/mods/12420) (Effect+ -> Main branch)

## Team Fortress 2: Enhanced 8.0-2022.07.a (Feb 19, 2022)
Welcome to first experimental release of Team Fortress 2: Enhanced!

### Highlight
* New skybox textures while keeping original cartoon atmospheres
* Fixed Heavy MVM Voicelines being too dark than original Heavy voice in TF2
* Fixed and tweaked Stamp Background while loading the game
* New original hitsound and killsound replacing Guilty Gear Hit and Kill Sounds (These mods will stay optional)

### Mod list changes
#### Additions

* [Alternative Skyboxes](https://gamebanana.com/mods/358474)

* [Tweaked Stamp Background](https://gamebanana.com/mods/356346)

#### Removal
* [Classic Guilty Gear Slash Hitsounds](https://gamebanana.com/sounds/56790)
