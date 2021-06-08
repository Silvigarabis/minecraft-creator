---
author: v-josjones
ms.author: v-josjones
title: minecraft:behavior.squid_dive
ms.prod: gaming
---

# minecraft:behavior.squid_dive

`minecraft:behavior.squid_dive` allows an entity to dive underwater.

> [!NOTE]
> This behavior can only be used by `squid` entity types.

## Example

```json
"minecraft:behavior.squid_dive":{
    "priority": 2,
}
```

## Vanilla entities examples

### squid

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/squid.json" range="87-89":::

## Vanilla entities using `minecraft:behavior.squid_dive`

- [squid](../../../../Source/VanillaBehaviorPack_Snippets/entities/squid.md)