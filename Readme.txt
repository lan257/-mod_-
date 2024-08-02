+-----------------------+
| Map for Goblins v1.09 |
+-----------------------+

* What exactly does the mod?

Changes the game's map to include a variety of information. The map displays:
- All Graces to unlock. Their icons are replaced with the normal ones once unlocked.
- All Bosses and their drops, anything with a boss HP bar. Their icons disappear once the bosses are defeated.
- All unique item drops, anything with a one time guaranteed item drop. Their icons disappear once the item drops are acquired.
	- The only exceptions not displayed in the map are the drops from the two friendly Living Jars in Jarburg.
- Hostile NPCs and their drops, mostly the ones unrelated to questlines or with next to no requirements. Their icons disappear once their drops are acquired.
- All Imp Statues and the amount of required keys to unlock them. Their icons disappear once unlocked.
- Teardrop Scarabs, only the ones that drop items. Their icons disappear once their drops are acquired.
- All loot from chests and corpses/shinies. Their icons disappear once the items are acquired.
	- The only exceptions are the Small Golden Effigy and the Serpent-Hunter.
	- Maps have a green background to make them easier to spot among all the displayed items.
- All locations (caves, catacombs, ruins, etc).
	- St. Trina's Hideaway map icon is also visible. This is not a bug, it's just that I made it visible.
- All Nomadic Merchants.
Adds a menu to all graces to configure what is displayed on the map or not. By default, the map displays nothing, you must use this new menu to configure it.


Obviously, the map contains all sort of spoilers for the entire game, don't use this mod if you care about spoilers or if this is your first playthrough.

Only English language is supported by me. Other people have made translations for this mod, I'm not involved with those.

Starting NG+ will reset all map icons and text except the ones for unique loot and drops that can only be obtained once per character and only if you already got them in NG (talisman pouches, crystal tears, cookbooks, etc).

The map icons that have some requirement will either mention the requirement (like Yura's death for Eleanore's invasion) or will only appear when the requirement is fulfilled (like the painting rewards being only accessible once the painting is obtained first).

Things that can be missed will remain indicated on the map for the rest of the run if they are missed (like the loot around the capital, Seedbed Curses, drops from the Black Knife Assassins in Ordina's evergaol, etc).

Respawning and non-respawning material nodes are not indicated in the map. Material nodes don't use acquisition flags like the rest of items, it would be possible to add them but they would permanently remain in the map even after they were looted, so I opted to not add them. Instead I recommend using my other mod Respawning Material Nodes (https://www.nexusmods.com/eldenring/mods/2739) and treat them as any other respawning node.

The map does no changes to NPC map icons (other than Nomadic Merchants) and does not add quest related items for the most part. There are a few things in, but don't expect more than that.

Everything is coordinate precise, if you are at the right spot and can't see what you are looking for then that means it's either right above or below you, or it's moving around (patrolling enemies, troll carriages, etc).

Some icons still automatically unlock under certain conditions, like graces unlocked after a boss kill, painting rewards after looting the painting, and so on. These icons will stay on the map until you activate the grace/loot the item and are not affected by the map configuration menu.

Nomadic Merchants tied to a grace location make their grace be displayed on the map, even if you choose to not display graces.

And yes, this mod is compatible with existing save files. Everything already done with that character will be automatically cleared from the map since it uses vanilla flags to determine what is done or not.

* Installation:

1. Download and install Mod Engine 2 (https://github.com/soulsmods/ModEngine2).
2. Unzip and drop the regulation.bin file and the "menu", "msg" and "script" folders inside the "mod" folder of Mod Engine 2.
3. Run launchmod_eldenring.bat from Mod Engine 2 to play.

* Mod Compatibility
This mod is not compatible with mods that change any of the following:
- BonfireWarpParam and WorldMapPointParam in the regulation.bin file.
- The 02_120_worldmap.gfx menu file.
- The m00_00_00_00.talkesdbnd script\talk file.
- Any of the used vanilla images found in the 01_common.tpf file, the mod doesn't change them, but they are required in their vanilla state for the most part. Mods that change the appearance of existing images only to give something a different look should be fine, like UI/button/map marker visual changes.
- Names, locations, text (indicating any merchants) and all the related flags of Graces.
- Names, locations, drops and their amounts, and all the related flags of bosses, enemies and hostile NPCs listed in the map.
- Locations, required amount of keys and unlock flags of Imp Statues.
- Locations, drops and all the related flags of Teardrop Scarabs listed in the map.
- Names, locations, amounts and acquisition flags of all lootable item chests/corpses/shinies.
- Names and locations of map locations (caves, catacombs, ruins, etc).
I do NOT recommend merging this with other mods unless it's only something visual like model replacements or mods that only touch game files/data completely unrelated to anything required by this mod to properly work.

Credits:
﻿- SoulsMods﻿ (https://github.com/soulsmods) for Mod Engine 2 and DSMapStudio.