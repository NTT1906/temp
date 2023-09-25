# List of command enums:
| Type                                          | Description                | Is vanilla | Supported |
|-----------------------------------------------|----------------------------|------------|-----------|
| [`Boolean`](#boolean)                         | Boolean value              | true       | true      |
| [`GameMode`](#gamemode)                       | Minecraft Vanilla Gamemode | true       | true      |
| [`PocketMine GameMode`](#pocketmine-gamemode) | PocketMine-MP Gamemode     | false      | true      |
| [`Online Players`](#pocketmine-gamemode)      | PocketMine-MP Gamemode     | false      | true      |
| [`Entity Type`](#entity-type)                 | PocketMine-MP Gamemode     | true       | false     |
## Boolean
Name: `Boolean`<br>
Supported: Yes<br>
Ovommand: [DefaultEnums::BOOLEAN](https://github.com/GalaxyGamesMC/Ovommand/blob/main/src/galaxygames/ovommand/enum/DefaultEnums.php)<br>
Source: [Microsoft Creator](https://learn.microsoft.com/en-us/minecraft/creator/commands/enums/boolean)

| Name    | Aliases | Value |
|---------|---------|-------|
| `true`  |         | true  |
| `false` |         | false |
## GameMode
Name: `GameMode`<br>
Supported: Yes<br>
Ovommand: [DefaultEnums::VANILLA_GAMEMODE](https://github.com/GalaxyGamesMC/Ovommand/blob/main/src/galaxygames/ovommand/enum/DefaultEnums.php)

| Name        | Aliases | Value                                                                                                  |
|-------------|---------|--------------------------------------------------------------------------------------------------------|
| `adventure` | `a`     | [`Gamemode::ADVENTURE()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L37) |
| `creative`  | `c`     | [`Gamemode::CREATIVE()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L38)  |
| `spectator` |         | [`Gamemode::SPECTATOR()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L39) |
| `survival`  | `s`     | [`Gamemode::SURVIVAL()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L40)  |
## PocketMine GameMode
Name: `PMGameMode`<br>
Supported: Yes<br>
Ovommand: [DefaultEnums::GAMEMODE](https://github.com/GalaxyGamesMC/Ovommand/blob/main/src/galaxygames/ovommand/enum/DefaultEnums.php)

| Name        | Show aliases | Hidden aliases | Value                                                                                                  |
|-------------|--------------|----------------|--------------------------------------------------------------------------------------------------------|
| `adventure` | `a`          | `2`            | [`Gamemode::ADVENTURE()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L37) |
| `creative`  | `c`          | `1`            | [`Gamemode::CREATIVE()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L38)  |
| `spectator` | `v`          | `3`            | [`Gamemode::SPECTATOR()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L39) |
| `survival`  | `s`          | `0`            | [`Gamemode::SURVIVAL()`](https://github.com/pmmp/PocketMine-MP/blob/main/src/player/GameMode.php#L40)  |
## Online players
Name: `OnlinePlayers`<br>
Supported: Yes<br>
Ovommand: [DefaultEnums::ONLINE_PLAYER](https://github.com/GalaxyGamesMC/Ovommand/blob/main/src/galaxygames/ovommand/enum/DefaultEnums.php)

Show all online players
## Entity Type
Name: `EntityType`<br>
Supported: No<br>
Source: [Microsoft Creator](https://learn.microsoft.com/en-us/minecraft/creator/commands/enums/entitytype)

> **Important**
> ❗The list of entities may change rapidly due to game updates. The following table should not be used for application purposes, but rather as a temporary reference.

<details> <summary>Show table</summary>

| Name                               | Aliases                  | Value                  |
|------------------------------------|--------------------------|------------------------|
| `minecraft:slime`                  | `slime`                  | Slime                  |
| `minecraft:tnt`                    | `tnt`                    | TNT                    |
| `minecraft:camel`                  | `camel`                  | Camel                  |
| `minecraft:turtle`                 | `turtle`                 | Turtle                 |
| `minecraft:chicken`                | `chicken`                | Chicken                |
| `minecraft:bee`                    | `bee`                    | Bee                    |
| `minecraft:axolotl`                | `axolotl`                | Axolotl                |
| `minecraft:pig`                    | `pig`                    | Pig                    |
| `minecraft:hoglin`                 | `hoglin`                 | Hoglin                 |
| `minecraft:zoglin`                 | `zoglin`                 | Zoglin                 |
| `minecraft:sniffer`                | `sniffer`                | Sniffer                |
| `minecraft:cat`                    | `cat`                    | Cat                    |
| `minecraft:cow`                    | `cow`                    | Cow                    |
| `minecraft:sheep`                  | `sheep`                  | Sheep                  |
| `minecraft:wolf`                   | `wolf`                   | Wolf                   |
| `minecraft:villager`               | `villager`               | Villager               |
| `minecraft:wandering_trader`       | `wandering_trader`       | Wandering Trader       |
| `minecraft:mooshroom`              | `mooshroom`              | Mooshroom              |
| `minecraft:squid`                  | `squid`                  | Squid                  |
| `minecraft:glow_squid`             | `glow_squid`             | Glow Squid             |
| `minecraft:strider`                | `strider`                | Strider                |
| `minecraft:rabbit`                 | `rabbit`                 | Rabbit                 |
| `minecraft:bat`                    | `bat`                    | Bat                    |
| `minecraft:iron_golem`             | `iron_golem`             | Iron Golem             |
| `minecraft:snow_golem`             | `snow_golem`             | Snow Golem             |
| `minecraft:ocelot`                 | `ocelot`                 | Ocelot                 |
| `minecraft:horse`                  | `horse`                  | Horse                  |
| `minecraft:trader_llama`           | `trader_llama`           | Trader Llama           |
| `minecraft:llama`                  | `llama`                  | Llama                  |
| `minecraft:polar_bear`             | `polar_bear`             | Polar Bear             |
| `minecraft:parrot`                 | `parrot`                 | Parrot                 |
| `minecraft:dolphin`                | `dolphin`                | Dolphin                |
| `minecraft:panda`                  | `panda`                  | Panda                  |
| `minecraft:fox`                    | `fox`                    | Fox                    |
| `minecraft:frog`                   | `frog`                   | Frog                   |
| `minecraft:tadpole`                | `tadpole`                | Tadpole                |
| `minecraft:allay`                  | `allay`                  | Allay                  |
| `minecraft:husk`                   | `husk`                   | Husk                   |
| `minecraft:tropicalfish`           | `tropicalfish`           | Tropical Fish          |
| `minecraft:wither_skeleton`        | `wither_skeleton`        | Wither Skeleton        |
| `minecraft:cod`                    | `cod`                    | Cod                    |
| `minecraft:zombie_villager`        | `zombie_villager`        | Zombie Villager        |
| `minecraft:pufferfish`             | `pufferfish`             | Pufferfish             |
| `minecraft:witch`                  | `witch`                  | Witch                  |
| `minecraft:salmon`                 | `salmon`                 | Salmon                 |
| `minecraft:donkey`                 | `donkey`                 | Donkey                 |
| `minecraft:mule`                   | `mule`                   | Mule                   |
| `minecraft:skeleton_horse`         | `skeleton_horse`         | Skeleton Horse         |
| `minecraft:zombie_horse`           | `zombie_horse`           | Zombie Horse           |
| `minecraft:zombie`                 | `zombie`                 | Zombie                 |
| `minecraft:stray`                  | `stray`                  | Stray                  |
| `minecraft:drowned`                | `drowned`                | Drowned                |
| `minecraft:creeper`                | `creeper`                | Creeper                |
| `minecraft:skeleton`               | `skeleton`               | Skeleton               |
| `minecraft:spider`                 | `spider`                 | Spider                 |
| `minecraft:zombie_pigman`          | `zombie_pigman`          | Zombie Pigman          |
| `minecraft:enderman`               | `enderman`               | Enderman               |
| `minecraft:silverfish`             | `silverfish`             | Silverfish             |
| `minecraft:cave_spider`            | `cave_spider`            | Cave Spider            |
| `minecraft:ghast`                  | `ghast`                  | Ghast                  |
| `minecraft:magma_cube`             | `magma_cube`             | Magma Cube             |
| `minecraft:blaze`                  | `blaze`                  | Blaze                  |
| `minecraft:warden`                 | `warden`                 | Warden                 |
| `minecraft:guardian`               | `guardian`               | Guardian               |
| `minecraft:elder_guardian`         | `elder_guardian`         | Elder Guardian         |
| `minecraft:elder_guardian_ghost`   | `elder_guardian_ghost`   | Elder Guardian Ghost   |
| `minecraft:wither`                 | `wither`                 | Wither                 |
| `minecraft:ender_dragon`           | `ender_dragon`           | Ender Dragon           |
| `minecraft:shulker`                | `shulker`                | Shulker                |
| `minecraft:endermite`              | `endermite`              | Endermite              |
| `minecraft:vindicator`             | `vindicator`             | Vindicator             |
| `minecraft:evocation_illager`      | `evocation_illager`      | Evocation Illager      |
| `minecraft:vex`                    | `vex`                    | Vex                    |
| `minecraft:phantom`                | `phantom`                | Phantom                |
| `minecraft:pillager`               | `pillager`               | Pillager               |
| `minecraft:ravager`                | `ravager`                | Ravager                |
| `minecraft:piglin_brute`           | `piglin_brute`           | Piglin Brute           |
| `minecraft:piglin`                 | `piglin`                 | Piglin                 |
| `minecraft:goat`                   | `goat`                   | Goat                   |
| `minecraft:minecart`               | `minecart`               | Minecart               |
| `minecraft:hopper_minecart`        | `hopper_minecart`        | Hopper Minecart        |
| `minecraft:tnt_minecart`           | `tnt_minecart`           | TNT Minecart           |
| `minecraft:chest_minecart`         | `chest_minecart`         | Chest Minecart         |
| `minecraft:command_block_minecart` | `command_block_minecart` | Command Block Minecart |
| `minecraft:xp_bottle`              | `xp_bottle`              | XP Bottle              |
| `minecraft:xp_orb`                 | `xp_orb`                 | XP Orb                 |
| `minecraft:ender_crystal`          | `ender_crystal`          | Ender Crystal          |
| `minecraft:arrow`                  | `arrow`                  | Arrow                  |
| `minecraft:snowball`               | `snowball`               | Snowball               |
| `minecraft:egg`                    | `egg`                    | Egg                    |
| `minecraft:splash_potion`          | `splash_potion`          | Splash Potion          |
| `minecraft:leash_knot`             | `leash_knot`             | Leash Knot             |
| `minecraft:boat`                   | `boat`                   | Boat                   |
| `minecraft:chest_boat`             | `chest_boat`             | Chest Boat             |
| `minecraft:lightning_bolt`         | `lightning_bolt`         | Lightning Bolt         |
| `minecraft:evocation_fang`         | `evocation_fang`         | Evocation Fang         |
| `minecraft:armor_stand`            | `armor_stand`            | Armor Stand            |
| `minecraft:fireworks_rocket`       | `fireworks_rocket`       | Fireworks Rocket       |
| `minecraft:npc`                    | `npc`                    | NPC                    |

</details>
