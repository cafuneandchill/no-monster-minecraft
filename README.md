# no-monster-minecraft

A data pack for Minecrafters who like playing without monsters.

## Credits

Created by Jason C. McDonald (CodeMouse92)

Some recipes based on Craftman by TheDiamondPlayables

## Purpose

My mother enjoys playing Minecraft with me, but she's never liked dealing with hostile mobs, so we usually turn those off. The trouble is, without monsters, there are so many important items you can never get! What's more, Peaceful mode just makes things *too* easy.

This data pack fixes all that.

## Features

* This data pack provides alternative sources for all hostile mob drops. Some are craftable or smeltable, others come from non-hostile mob drops.

* Adds the "missing recipes": saddles, bells, chain mail, elytra, and so on.

* Removes hostile mobs on any difficulty level. (You can control which types of
hostile mobs spawn.)

## Recipes

NOTE: `>>` indicates I haven't yet added this, but plan to very soon.

### Crafting

* Banner Pattern Globe
* Bell
* Blaze Rod
* Chainmail Boots
* Chainmail Chestplate
* Chainmail Helmet
* Chainmail Leggings
* Cobweb
* Diamond Horse Armor
* Elytra
* Enchanted Golden Apple
* >> Ender Pearl
* >> Ghast Tear
* Golden Horse Armor
* Gunpowder
* Iron Horse Armor
* Leather
* Name Tag
* Nether Star
* Red Sand
* >> Rotten Flesh
* Saddle
* Slimeball
* >> Spider Eye
* String
* Totem of Undying
* Trident
* Wither Skeleton Skull

### Blast Furnace

* Blaze Powder
* Charcoal
* Phantom Membrane
* Prismarine Crystal

## Drops

NOTE: `>>` indicates I haven't yet added this, but plan to very soon.

### Mob Drops

* >> Bones
* >> Skull

### Fishing Drops

* Prismarine Shard
* Wet Sponge

## Mob Control

Potentially hostile mobs are controlled by the datapack. Certain groups of
mobs can be allowed by turning on particular gamerules. By default, none of these groups are allowed to spawn.

NOTE: Not yet implemented. Coming very soon!

### Illagers

These are the evil villager types.

* Evokers
* Illusioners
* Pillagers
* Ravagers
* Vexes
* Vindicators
* Witches

This group is controlled by gamerule `spawnIllagers`. Remember, you can also
disable raids only using Minecraft's built-in `disableRaids` gamerule.

### Arthropods

These are hostile overworld arthropods.

* Cave Spiders
* Silverfish
* Spiders

This group is controlled by gamerule `spawnArthropods`.

### Monsters

These are monster-like overworld hostile mobs.

* Creepers
* Drowned
* Husks
* Phantom
* Slimes
* Skeletons
* Strays
* Zombies
* Zombie Villagers

This group is controlled by gamerule `spawnMonsters`.

### Guardians

These are controlled separately, since guardian spawning is limited to ocean
monuments, and thus may still be wanted.

* Elder Guardians
* Guardians

This group is controlled by gamerule `spawnGuardians`.

### Nether Mobs

These are non-monster nether mobs; there are safe ways of interacting with
(most) of these.

* Hoglins (1.16+)
* Piglins (1.16+)
* Zombie Piglins? (1.16+)
* Zombie Pigmen (<=1.15)

This group is controlled by gamerule `spawnNetherMobs`.

### Nether Monsters

These are monster-like hostile mobs in the nether.

* Blaze
* Ghast
* Magma Cube
* Wither Skeleton

This group is controlled by gamerule `spawnNetherMonsters`.

### End Mobs

These are non-monster mobs in the End; these are safe ways of interacting with
these.

* Enderman

This group is controlled by gamerule `spawnEndMobs`.

### End Monsters

These are monster-like hostile mobs in the End. Shulkers themselves are *always*
allowed to spawn, but eliminating the shulker bullets removes their means
of hostility.

* Endermite
* Shulker bullets

This group is controlled by gamerule `spawnEndMonsters`.

## Bosses

Because all items necessary to spawn bosses are accessible without other
hostile mobs being enabled, these can be controlled separately as well.
By default, bosses are automatically killed upon spawning, but you
can control that with the gamerule `spawnBosses`.

* Ender Dragon
* Wither

### Non-Controlled Mobs

One of the reasons for the datapack is the assumption that *some* challenge is
desired. Just for reference, the following mobs are potentially dangerous to
the player, but are not affected by this datapack:

* Bees
* Dolphins
* Iron Golems
* Llamas
* Pandas
* Polar Bears
* Pufferfish
* Shulkers
* Trader Llamas
* Wolves

All passive mobs are also unaffected.
