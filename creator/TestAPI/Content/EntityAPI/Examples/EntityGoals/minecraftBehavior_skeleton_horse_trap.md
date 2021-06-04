---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.skeleton_horse_trap
ms.prod: gaming
---

# minecraft:behavior.skeleton_horse_trap

`minecraft:behavior.skeleton_horse_trap` Allows an entity to be Horse Traps and be triggered like them, spawning a lightning bolt and a bunch of horses when a player is nearby.

> [!NOTE]
> This behavior can only be used by `horse`, `mule`, `donkey` and `skeleton horses` entity types.

## Parameters

|Name |Default Value  |Type  |Description  |
|:---------:|:---------:|:---------:|:---------:|
|duration| 1.0| Decimal| Amount of time in seconds the trap exists. After this amount of time is elapsed, the trap is removed from the world if it hasn't been activated |
|within_radius| 0.0| Decimal| Distance in blocks that the player has to be within to trigger the horse trap |

## Example

```json
"minecraft:behavior.skeleton_horse_trap":{
    "priority": 2,
    "duration": 1.0,
    "within_radius": 12.0,
}
```

## Vanilla entities examples

### skeleton_horse

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/skeleton_horse.json" range="60-64":::

## Vanilla entities using `minecraft:behavior.skeleton_horse_trap`

- [skeleton_horse](../../../../Source/VanillaBehaviorPack_Snippets/entities/skeleton_horse.md)