---
author: <Employee Name>
ms.author: <Employee Name>
title: <Name of Filter>
ms.prod: gaming
---

# Name of Filter

A quick summary of what the Filter does. Taken from the autogenerated docs, but can be fleshed out.

> [!NOTE]
> Please verify that the filter is still currently being used. Some filters have been phased out or have been updated. When looking for examples and you are unable to locate any, please let the creator/reader know and link to the updated filter

## Parameters

Use a table with four titles to match the autogenerated docs. If the name is a definition of an argument ,such as melee_fov, add a hyperlink to the definition.

Most filters have only one required parameter such as a Decimal, Integer or a Boolean

|Name |Default Value  |Type  |Description  |
|---------|---------|---------|---------|

If the table has a nested table, pull the table out as a definition, link to the table as a definition and place a snippet of the table below.

`Name of Filter` can also use `subject` and `operator` parameters but they are optional.

### subject

| Options| Description |
|:-----------:|:-----------:|
| block| The block involved with the interaction. |
| damager| The damaging actor involved with the interaction. |
| other| The other member of an interaction, not the caller. |
| parent| The caller's current parent. |
| player| The player involved with the interaction. |
| self| The entity or object calling the test |
| target| The caller's current target. |

### operator

| Options| Description |
|:-----------:|:-----------:|
| !=| Test for inequality. |
| <| Test for less-than the value. |
| <=| Test for less-than or equal to the value. |
| <>| Test for inequality. |
| =| Test for equality. |
| ==| Test for equality. |
| >| Test for greater-than the value. |
| >=| Test for greater-than or equal to the value. |
| equals| Test for equality. |
| not| Test for inequality. |


## Example

This is a custom example written by the developers/Technical writers of a fleshed out Filter using as many of the arguments available.

These can be pulled directly from the autogenerated docs.

### Full

```json
{ "test": "foo", "subject": "self", "operator": "equals", "value": true }
```

### Short (using Defaults)

```json
{ "test": "foo", "subject": "self", "operator": "equals", "value": true }
```

## Vanilla Mob examples

This section includes up to 2 snippets of the Filter being used in a vanilla mob.

### Mob 1

json snippet configured to the FilterPack_Snippets

## Vanilla Mobs using Name of Filter

A list to the vanilla Filter pack snippets that currently use the Filter. If more than 25 Filters are used, feel free to split the list into 2 or 3 columns.

- [area_effect_cloud](../../../../Source/VanillaBehaviorPack_Snippets/entities/area_effect_cloud.md)
- [armor_stand](../../../../Source/VanillaBehaviorPack_Snippets/entities/armor_stand.md)
- [arrow](../../../../Source/VanillaBehaviorPack_Snippets/entities/arrow.md)
- [bat](../../../../Source/VanillaBehaviorPack_Snippets/entities/bat.md)
- [bee](../../../../Source/VanillaBehaviorPack_Snippets/entities/bee.md)
- [blaze](../../../../Source/VanillaBehaviorPack_Snippets/entities/blaze.md)
- [boat](../../../../Source/VanillaBehaviorPack_Snippets/entities/boat.md)
- [cat](../../../../Source/VanillaBehaviorPack_Snippets/entities/cat.md)
- [cave spider](../../../../Source/VanillaBehaviorPack_Snippets/entities/cave_spider.md)
- [chest_minecart](../../../../Source/VanillaBehaviorPack_Snippets/entities/chest_minecart.md)
- [chicken](../../../../Source/VanillaBehaviorPack_Snippets/entities/chicken.md)
- [command_block_minecart](../../../../Source/VanillaBehaviorPack_Snippets/entities/command_block_minecart.md)
- [cow](../../../../Source/VanillaBehaviorPack_Snippets/entities/cow.md)
- [creeper](../../../../Source/VanillaBehaviorPack_Snippets/entities/creeper.md)
- [dolphin](../../../../Source/VanillaBehaviorPack_Snippets/entities/dolphin.md)
- [donkey](../../../../Source/VanillaBehaviorPack_Snippets/entities/donkey.md)
- [dragon_fireball](../../../../Source/VanillaBehaviorPack_Snippets/entities/dragon_fireball.md)
- [drowned](../../../../Source/VanillaBehaviorPack_Snippets/entities/drowned.md)
- [egg](../../../../Source/VanillaBehaviorPack_Snippets/entities/egg.md)
- [elder guardian](../../../../Source/VanillaBehaviorPack_Snippets/entities/elder_guardian.md)
- [ender_crystal](../../../../Source/VanillaBehaviorPack_Snippets/entities/ender_crystal.md)
- [ender_dragon](../../../../Source/VanillaBehaviorPack_Snippets/entities/ender_dragon.md)
- [ender pearl](../../../../Source/VanillaBehaviorPack_Snippets/entities/ender_pearl.md)
- [enderman](../../../../Source/VanillaBehaviorPack_Snippets/entities/enderman.md)
- [endermite](../../../../Source/VanillaBehaviorPack_Snippets/entities/endermite.md)
- [evocation illager](../../../../Source/VanillaBehaviorPack_Snippets/entities/evocation_illager.md)
- [eye_of_ender_signal](../../../../Source/VanillaBehaviorPack_Snippets/entities/eye_of_ender_signal.md)
- [fireball](../../../../Source/VanillaBehaviorPack_Snippets/entities/fireball.md)
- [fireworks_rocket](../../../../Source/VanillaBehaviorPack_Snippets/entities/fireworks_rocket.md)
- [fish](../../../../Source/VanillaBehaviorPack_Snippets/entities/fish.md)
- [fishing_hook](../../../../Source/VanillaBehaviorPack_Snippets/entities/fishing_hook.md)
- [fox](../../../../Source/VanillaBehaviorPack_Snippets/entities/fox.md)
- [ghast](../../../../Source/VanillaBehaviorPack_Snippets/entities/ghast.md)
- [guardian](../../../../Source/VanillaBehaviorPack_Snippets/entities/guardian.md)
- [hoglin](../../../../Source/VanillaBehaviorPack_Snippets/entities/hoglin.md)
- [hopper_minecart](../../../../Source/VanillaBehaviorPack_Snippets/entities/hopper_minecart.md)
- [horse](../../../../Source/VanillaBehaviorPack_Snippets/entities/horse.md)
- [husk](../../../../Source/VanillaFilterPack/entities/husk.md)
- [iron_golem](../../../../Source/VanillaFilterPack/entities/iron_golem.md)
- [lightning_bold](../../../../Source/VanillaBehaviorPack_Snippets/entities/lightning_bold.md)
- [llama_spit](../../../../Source/VanillaBehaviorPack_Snippets/entities/llama_spit.md)
- [llama](../../../../Source/VanillaBehaviorPack_Snippets/entities/llama.md)
- [magma cube](../../../../Source/VanillaBehaviorPack_Snippets/entities/magma_cube.md)
- [minecart](../../../../Source/VanillaBehaviorPack_Snippets/entities/minecart.md)
- [mooshroom](../../../../Source/VanillaBehaviorPack_Snippets/entities/mooshroom.md)
- [mule](../../../../Source/VanillaBehaviorPack_Snippets/entities/mule.md)
- [npc](../../../../Source/VanillaBehaviorPack_Snippets/entities/npc.md)
- [ocelot](../../../../Source/VanillaBehaviorPack_Snippets/entities/ocelot.md)
- [panda](../../../../Source/VanillaBehaviorPack_Snippets/entities/panda.md)
- [parrot](../../../../Source/VanillaBehaviorPack_Snippets/entities/parrot.md)
- [phantom](../../../../Source/VanillaBehaviorPack_Snippets/entities/phantom.md)
- [pig](../../../../Source/VanillaBehaviorPack_Snippets/entities/pig.md)
- [piglin brute](../../../../Source/VanillaBehaviorPack_Snippets/entities/piglin_brute.md)
- [piglin](../../../../Source/VanillaBehaviorPack_Snippets/entities/piglin.md)
- [pillager](../../../../Source/VanillaBehaviorPack_Snippets/entities/pillager.md)
- [player](../../../../Source/VanillaBehaviorPack_Snippets/entities/player.md)
- [polar bear](../../../../Source/VanillaBehaviorPack_Snippets/entities/polar_bear.md)
- [pufferfish](../../../../Source/VanillaBehaviorPack_Snippets/entities/pufferfish.md)
- [rabbit](../../../../Source/VanillaBehaviorPack_Snippets/entities/rabbit.md)
- [ravager](../../../../Source/VanillaBehaviorPack_Snippets/entities/ravager.md)
- [salmon](../../../../Source/VanillaBehaviorPack_Snippets/entities/salmon.md)
- [sheep](../../../../Source/VanillaBehaviorPack_Snippets/entities/sheep.md)
- [shulker_bullet](../../../../Source/VanillaBehaviorPack_Snippets/entities/shulker_bullet.md)
- [shulker](../../../../Source/VanillaBehaviorPack_Snippets/entities/shulker.md)
- [silverfish](../../../../Source/VanillaBehaviorPack_Snippets/entities/silverfish.md)
- [skeleton](../../../../Source/VanillaBehaviorPack_Snippets/entities/skeleton.md)
- [slime](../../../../Source/VanillaBehaviorPack_Snippets/entities/slime.md)
- [small_fireball](../../../../Source/VanillaBehaviorPack_Snippets/entities/small_fireball.md)
- [snow golem](../../../../Source/VanillaBehaviorPack_Snippets/entities/snow_golem.md)
- [snowball](../../../../Source/VanillaBehaviorPack_Snippets/entities/snowball.md)
- [spider](../../../../Source/VanillaBehaviorPack_Snippets/entities/spider.md)
- [splash_potion](../../../../Source/VanillaBehaviorPack_Snippets/entities/splash_potion.md)
- [squid](../../../../Source/VanillaBehaviorPack_Snippets/entities/squid.md)
- [stray](../../../../Source/VanillaBehaviorPack_Snippets/entities/stray.md)
- [strider](../../../../Source/VanillaBehaviorPack_Snippets/entities/strider.md)
- [thrown_trident](../../../../Source/VanillaBehaviorPack_Snippets/entities/thrown_trident.md)
- [tnt_minecart](../../../../Source/VanillaBehaviorPack_Snippets/entities/tnt_minecart.md)
- [tnt](../../../../Source/VanillaBehaviorPack_Snippets/entities/tnt.md)
- [tripod_camera](../../../../Source/VanillaBehaviorPack_Snippets/entities/tripod_camera.md)
- [tropicalfish](../../../../Source/VanillaBehaviorPack_Snippets/entities/tropicalfish.md)
- [turtle](../../../../Source/VanillaBehaviorPack_Snippets/entities/turtle.md)
- [vex](../../../../Source/VanillaBehaviorPack_Snippets/entities/vex.md)
- [villager_v2](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager_v2.md)
- [villager](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager.md)
- [vindicator](../../../../Source/VanillaBehaviorPack_Snippets/entities/vindicator.md)
- [wandering_trader](../../../../Source/VanillaBehaviorPack_Snippets/entities/wandering_trader.md)
- [witch](../../../../Source/VanillaBehaviorPack_Snippets/entities/witch.md)
- [wither skeleton](../../../../Source/VanillaBehaviorPack_Snippets/entities/wither_skeleton.md)
- [wither_skull_dangerous](../../../../Source/VanillaBehaviorPack_Snippets/entities/wither_skull_dangerous.md)
- [wither_skull](../../../../Source/VanillaBehaviorPack_Snippets/entities/wither_skull.md)
- [wither](../../../../Source/VanillaBehaviorPack_Snippets/entities/wither.md)
- [wolf](../../../../Source/VanillaBehaviorPack_Snippets/entities/wolf.md)
- [xp_bottle](../../../../Source/VanillaBehaviorPack_Snippets/entities/xp_bottle.md)
- [xp_orb](../../../../Source/VanillaBehaviorPack_Snippets/entities/xp_orb.md)
- [zoglin](../../../../Source/VanillaBehaviorPack_Snippets/entities/zoglin.md)
- [zombie_horse](../../../../Source/VanillaBehaviorPack_Snippets/entities/zombie_horse.md)
- [zombie pigman](../../../../Source/VanillaBehaviorPack_Snippets/entities/zombie_pigman.md)
- [zombie_villager_v2](../../../../Source/VanillaBehaviorPack_Snippets/entities/zombie_villager_v2.md)
- [zombie_villager](../../../../Source/VanillaBehaviorPack_Snippets/entities/zombie_villager.md)
- [zombie](../../../../Source/VanillaBehaviorPack_Snippets/entities/zombie.md)