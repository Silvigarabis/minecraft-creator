---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.receive_love
ms.prod: gaming
---

# minecraft:behavior.receive_love

`minecraft:behavior.receive_love` allows an entity to mate with another similar entity when approached to breed.

> [!NOTE]
> This behavior can only be used by `villager` entity types.

## Parameters

|Name |Default Value  |Type  |Description  |
|:---------:|:---------:|:---------:|:---------:|
|speed_multiplier| 1.0| Decimal| Movement speed multiplier of the mob when using this AI Goal |

## Example

```json
"minecraft:behavior.receive_love":{
    "priority": 2,
    "speed_multiplier": 1.0,
}
```

## Vanilla entities examples

### villager_v2

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/villager_v2.json" range="523-526":::

## Vanilla entities using `minecraft:behavior.receive_love`

- [villager_v2](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager_v2.md)
- [villager](../../../../Source/VanillaBehaviorPack_Snippets/entities/villager.md)