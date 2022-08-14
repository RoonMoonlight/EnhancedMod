# Changelog
## Cosmos 19.2 (Mangrove) [August 13, 2022]
> *"Enough with the 19.84 joke, let's move along."*

Ahem. Anyways welcome back to Cosmos 19.2 Update! We apologize for not having any updates.
Due to Roon's class enrollment issues, the release could not be able to proceed until this weekend.

However we are happy to release this update to public, and this release might be the final version that dues own versioning scheme.
Starting from major update planned on August 20th, updates will be git commit/git branch based and all EnhancedMod projects will be synchronized for each updates. From now on to check what was changed please refer to our [releases](https://github.com/MysticMoonlight/EnhancedMod/releases) page or [commits](https://github.com/MysticMoonlight/EnhancedMod/commits/main) section.

### Highlights
* Reverted 1.19.84 joke to 1.19.2 - *Seriously, this is enough.*
* Added back the Lithium, Resounding and Lightmatica mod as the mod now supports latest version of the game
* Updated to support 1.19.2 (Some mods might still say 1.19.1 but it should be supported... Unless the Fabric loader refuses to launch due to strict version limit)
* Removed mod which was not intended to be added into the modpack: Please remove ChatHeads if you have any similar mod installed (It was supposed to be removed due to crash issue but we forgot to remove it from modpack)
* Missing dependency issue was finally fixed. Roughly Enough Items required Architectury API to be installed and loaded, but we totally forgot to move that to the construction site; this is no longer the case.

### Replaced & Moved
* [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) (Incompatible -> Main)
* [Resounding](https://modrinth.com/mod/resounding) (Incompatible -> Main)

## Cosmos 19.84 (The 1984 Update) [Jun 30, 2022]
Welcome to ~~not obviously april fools joke~~ 'The 1984 Update' (A.K.A Doomed 9th Update: Part 2). This update exists for mitigation against the Chat Report feature.
As you may heard but Mojang finally added worst feature: The report system.

Many Minecraft fans did not liked this change, so we decided to add this feature to prevent anyone from abusing report feature, as well as chat improvements.

### Highlights
* Starting from this update, our client will strip signatures that since 1.19 are attached to every message sent in the chat. tl;dr - Your privacy of chat messages are now secured
* Telemetry is disabled by default, now Mojang won't be able to collect your information
* Version name is now 1.19.84 (Can be disabled on mod settings)

### Additions
* [Disable Insecure Chat Toast](https://www.curseforge.com/minecraft/mc-mods/disable-insecure-chat-toast)
* [Fabric Language Kotlin](https://www.curseforge.com/minecraft/mc-mods/fabric-language-kotlin)
* [No Chat Reports](https://www.curseforge.com/minecraft/mc-mods/no-chat-reports)
* [Zoomify](https://www.curseforge.com/minecraft/mc-mods/zoomify)

### Replaced & Moved
* [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) (Main -> Incompatible)
* Just Enough Items -> [Roughly Enough Items](https://modrinth.com/mod/roughly-enough-items) (Mod outdated)

### Removal
* [Custom FoV](https://www.curseforge.com/minecraft/mc-mods/custom-fov-fabric) (Mod Author inactive)
* [Logical Zoom](https://www.curseforge.com/minecraft/mc-mods/logical-zoom) (Author inactive)

### Note
* As of this minor update, ReplayMod will no longer be compatible and we are not gonna add them back into the game, because of their nature of mod distribution and slow updates.
* If the `enforce-secure-profile` setting is turned on server you wish to join, you won't be able to join their server. Try asking the server owner to disable this feature in chat (And of course explain why that settings should be disabled).

## Cosmos 19.1 (The Doomed 9th Update) [Jun 18, 2022]
[Welcome to doomed 9th update, which was controversial for many Minecraft users.](https://arstechnica.com/gaming/2022/06/microsoft-will-start-banning-players-from-all-private-minecraft-servers/) We don't understand why the Mojang is ruining their own game by adding report feature into the game.

Anyways, welcome to yet another update! Thankfully the author of MaLiLib announced that he will be releasing the 1.19 version based on old source codes, meaning that KronHUD can also receive an update without any hassles.
We are happy to announce that KronHUD and MaLiLib are now returned to Cosmos, meaning that now you can customize the HUD to your likings once again, without having to rely on bloat clients.

### Highlights
* MaLiLib and KronHUD has been returned from long break! Enjoy customizing the pvp experience for yourself.
* This modpack should now support 1.19.1 snapshot and stable release (If released). We hope that the M$ doesn't do any harm to Mojang...

## Cosmos 19.0 "Mangrove" (Jun 18, 2022)
Welcome back to yet another major update of Cosmos! This update introduces new sound and visual effects, Just Enough Items, and more.

### Highlights
* Just Enough Items mod has arrived to Cosmos! Recently Badlion Client team added the feature which acts like [Just Enough Items](https://twitter.com/BadlionClient/status/1518590660017676289).
* Chat now displays player's heads! When other player sends message in chat, now it also displays the player's head.
* **Major improvements to ambient sounds** - New environment effects, footstep sounds and more
* New Falling Leaves effect - Enjoy the beautiful forest atmosphere of the game
* New Pling Sound will play when Cosmos is successfully loaded
* Dropped compatibility with ReplayMod due to late update release, lack of compatibility with CurseForge/Modrinth
* Temporarily dropped Litematica due to code rewrite process
* Temporarily dropped support for MaLiLib, KronHUD, Litematica due to code rewrite process. [Related Announcement can be found here.](https://www.curseforge.com/minecraft/mc-mods/malilib)

### Mod changes
#### Additions
* [Chat Heads](https://www.curseforge.com/minecraft/mc-mods/chat-heads)
* [Falling Leaves](https://www.curseforge.com/minecraft/mc-mods/falling-leaves-fabric)
* [Just Enough Items](https://www.curseforge.com/minecraft/mc-mods/jei)
* [Pling](https://www.curseforge.com/minecraft/mc-mods/pling)
* [Resounding](https://modrinth.com/mod/resounding) (Not yet added because 1.19 support is in progress)

#### Removal
* [Clear Hitboxes](https://www.curseforge.com/minecraft/mc-mods/clear-hitboxes) (Proprietary mod, Lack of updates)
* [Cull Leaves](https://www.curseforge.com/minecraft/mc-mods/cull-leaves) (Incompatible with Falling Leaves)
* [ReplayMod](https://www.replaymod.com/) (Removed due to late update release, lack of compatibility with CurseForge/Modrinth)
* [Animatica](https://www.curseforge.com/minecraft/mc-mods/animatica) and [CIT Resewn](https://modrinth.com/mod/cit-resewn) (Removal of backward compatibility)

## Cosmos 18.2 "Sharp Katana" (March 11, 2022)
After the long sleep, Katana has been sharpened once again! Cosmos 18.2 "Sharp Katana" is now available to public! This update is based on Minecraft 1.18.2/Fabric.

### Highlights
* Added Rich Presense powered by CraftPresense (Can be fully customizable on Mod Menu)
* New Saturation/Exhaustion display feature! This allows you to see which food or potion is better when holding any foods or potions.
* Added new category 'Legacy-Compatibility Mods', with 2 new mods: Animatica, CIT Resewn
* Schematica! It has still lack of features, but it includes many Schematica features for builders.
* Now ping displays as numerical instead of using icons
* Removed WorldEditCUI due to author's inactivty

### Mod changes
#### Additions
* Animatica
* AppleSkin
* Better Ping Displays
* CIT Resewn
* Colormatic
* CraftPresense
* Litematica

#### Removal
* WorldEditCUI for Fabric

## Cosmos 18.1 "Sharp Katana" (February 18, 2022)
### Highlights
* Initial release, based on Minecraft Fabric 1.18.1
