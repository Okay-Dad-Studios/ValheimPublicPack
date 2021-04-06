Adds various options to adjust combat difficulty and rewards.

For a detailed changelog, please check out the mods [NexusMods page](https://www.nexusmods.com/valheim/mods/495).

## Feature overview
- Highly configurable, everything can be disabled and adjusted to your liking
- Creatures can spawn with up to 5 stars (no maximum for custom difficulty)
- Creatures that usually cannot level up can spawn stars as well
- Bosses can spawn with as many stars as you want to
- Increased size for creatures and bosses based on level
- Multiple ways to adjust the difficulty of the game
- Respawnable camps and dungeons
- Loot multipliers, even for bosses and trophies
- Affixes for bosses
- Special effects for creatures
- Adjustable damage and health gain per player for multiplayer games
- Adjustable range for creature nameplates to be displayed on mouseover
- Support for the Mod Configuration Enforcer


## Creatures
Creature level can be adjusted in multiple ways:
You can set a difficulty that increases the level up chance of creatures or you can create your own difficulty.
As a second factor for difficulty, you can pick one of these options:
- Days passed in your world
- Distance from the initial spawning point
- Number of killed bosses in your world


Or you can disable the second factor, if you don't want to use it.Or you can just set a fixed level for all creatures or disable the level up for creatures completely.
Also, this mod enables leveling for creatures that usually cannot level up, like Serpents, Deathsquitos, Lox, Drakes, Wraiths, ...
You can even let camps and dungeons respawn!

## Creature star colors
Creatures can spawn with differently colored stars, if you want to. Each color tweaks the creature in a different way:
Magenta - Quick - Moves faster
40% increased movement speed
Red - Aggressive - Tries to hit you more often
Interval between two attack waves and circle time reduced by 50%, interval between circles increased by 150%
Green - Regenerating - Regenerates health over time
BaseHeal = Health at 0 stars * (1 + 0.25 * stars), Healing = BaseHeal * (10 * log(max(10, BaseHeal - 1000)) / (BaseHeal + 1000)) * 1.2 / second
Cyan - Curious - Comes checking for you from a farther distance
Hear and view range increased by 100%
White - Splitting - Splits in two lower level enemies with the same color upon death
Example: A 4 star Greydwarf will split into two 2 star Greydwarfs on death
Blue - Armored - Takes less damage, but moves slower
66% less damage taken, 50% reduced movement speed

## Creature elemental infusions
Creatures can spawn with different elemental infusions, if you want to. Each infusion adds elemental effects to the creature:
Fire-Infused - Resistant to fire damage and vulnerable to frost damage. Ignites you on hit.
Frost-Infused - Resistant to frost damage and vulnerable to fire damage. Freezes you on hit.
Lightning-Infused - Resistant to lightning damage and vulnerable to spirit damage. Deals lightning damage.
Spirit-Infused - Resistant to spirit damage and vulnerable to lightning damage. Heals itself on hits.
Poison-Infused - Immune to poison damage. Explodes in a poison cloud on death.
Chaos-Infused - One of the other infusions, randomly selected on each hit.

## Bosses
You can set a minimum and maximum level for bosses as well, if you want your bosses to spawn with up to five stars.
Theres is also the option to let your bosses spawn with different affixes, making them even more difficult to kill:
Reflective - Dealing direct damage to the boss will deal damage to you as well
Shielded - Takes 50% reduced damage from arrows
Mending - Regenerates health over time more quickly
Summoner - Summons strong creatures every 20% of maximum health lost
Elementalist - Deals 20% increased elemental damage
Enraged - Deals 30% increased physical damage
Twin - Spawns a second boss. The boss and its twin boss have 25% less health and damage and have shared health.

## Loot
For loot, you can set a chance for additional loot with each creature level and set a multiplier for all dropped items as well. You can even let enemies drop multiple trophies, if you like. You can also let bosses drop more loot or multiple trophies.

## Multiplayer
For multiplayer, everyone in your group should have this mod, preferably with the same settings. Otherwise, the client controlling the spawn will be responsible for the level of the enemies. Also, you need this mod to see the actual level of the creatures or all enemies above 2 stars will just show up without any stars.
Or don't tell your friends about this mod, spawn some 5 stars Lox and tell them to parry them, while you are shooting from a safe distance using your bow. Watch them die and then laugh uncontrollably like the psychopath you are.
The mod has an option to adjust the HP and DMG increase for creatures per player in multiplayer.

And be mindful with the settings. If you spawn an entire Fuling village with 5 stars Fulings, changing the settings or disabling the mod will not revert their level.

Need more stamina to fight tough enemies? Check out this sweet mod﻿ and make sure you are always properly rested!

## Using Mod Configuration Enforcer
If you want to use the MCE, to enforce a configuration for your multiplayer server, every client has to download the mod (or have at least version 1.3 installed). You can get it [here](https://www.nexusmods.com/valheim/mods/460). After that, you need to install the Creature Level and Loot Control and the MCE to the server as well. Just install BepInEx on the server, like
you would do it on any client and move the dll files to the BepInEx/plugins folder. Copy your configuration file from the BepInEx/config folder on your computer to the BepInEx/config folder on the server and restart the server. That's all. Your configuration will now be enforced on your server, if the client has both mods installed. Don't forget to restart the server, if you adjust the configuration on the server!


# I accidentally spawned a level 5000 creature / boss! What now?
If you have attached '-console' as a launch parameter for Valheim, you can open the console by hitting F5 in the game. The following commands can be used, to remove accidentally spawned creatures:
﻿	cllc killall
Removes all creatures in the area.
﻿	cllc killhighlevel
Removes all creatures with at least 6 stars from the area. You can pass a number there, to increase the level:
	﻿cllc killhighlevel 10
Removes all creatures that are at least level 10.


## Fun Features:
- Run away from giant Fuling Berserkers.
- Get killed instantly by Deathsquitos with 5 stars.
- Encounter 5 stars Serpents and curse the game, because the wind is against you and doesn't let you flee.
- Tame giant 5 stars Wolves and watch them devour your enemies!
- And so much more!
- (If you are only reading this list for some reason: Yes, you can use this mod to make the game A LOT easier.)


Need more stamina to fight tough enemies? Check out [this sweet mod](https://www.nexusmods.com/valheim/mods/431)﻿ and make sure you are always [properly rested](https://www.nexusmods.com/valheim/mods/427)!