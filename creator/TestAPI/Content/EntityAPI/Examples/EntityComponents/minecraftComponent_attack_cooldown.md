---
author: v-josjones
ms.author: v-josjones
title: minecraft:attack_cooldown
ms.prod: gaming
---

# minecraft:attack_cooldown

`minecraft:attack_cooldown` adds a cooldown to an entity. The intention of this cooldown is to be used to prevent the entity from attempting to acquire new attack targets.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|attack_cooldown_complete_event|*not set* | Trigger|  Event to be run when the cooldown is complete. |
| attack_cooldown_time| [0.0, 1.0]| Range [a, b]| Amount of time in seconds for the cooldown. Can be specified as a number or a pair of numbers (min and max). |

## Example

```json
"minecraft:attack_cooldown":{
    "attack_cooldown_complete_event": "minecraft:cooldown",
    "attack_cooldown_time": [0.1, 1.0]
}
```

## Vanilla entities examples

### hoglin

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/hoglin.json" range="73-79":::

## Vanilla entities using `minecraft:attack_cooldown`

- [hoglin](../../../../Source/VanillaBehaviorPack_Snippets/entities/hoglin.md)
- [piglin](../../../../Source/VanillaBehaviorPack_Snippets/entities/piglin.md)