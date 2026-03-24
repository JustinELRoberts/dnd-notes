---
publish: true
aliases:
  - Tharashk Hunter
created: 2026-03-09T12:15:33.828-04:00
modified: 2026-03-09T12:15:33.828-04:00
published: 2026-03-09T12:15:33.828-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/6
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid/human
  - ttrpg-cli/monster/type/humanoid/orc
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Tharashk Hunter

_Source: Eberron: Forge of the Artificer p. 85_\
![](Mechanics/CLI/bestiary/humanoid/img/tharashk-hunter.webp#right)

House Tharashk's heirs include inquisitives, dragonshard prospectors, and bounty hunters. They are more at home in the trackless wilds than in crowded city streets, but they are quite capable of tracking and pursuing their prey in any environment.

Tharashk hunters, typically humans or orcs, often work alongside Druids of the Gatekeepers, and occasionally with Aberrant Cultists of the Dragon Below.

```ad-statblock
title: Tharashk Hunter
![](Mechanics/CLI/bestiary/humanoid/token/tharashk-hunter-efa.webp#token)
*Small or Medium humanoid (human, orc), Neutral*

- **Armor Class** 16 
- **Hit Points** 97 (`15d8 + 30`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|19 (+4)|15 (+2)|11 (+0)|16 (+3)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Constitution +5
- **Skills** [Perception](Mechanics/CLI/rules/skills.md#Perception) +6, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +7, [Survival](Mechanics/CLI/rules/skills.md#Survival) +6
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 16
- **Gear** [longbow](Mechanics/CLI/items/longbow-xphb.md), [shortsword](Mechanics/CLI/items/shortsword-xphb.md), [studded leather armor](Mechanics/CLI/items/studded-leather-armor-xphb.md)
- **Languages** Common, Orc plus one other language
- **Challenge** 6

## Actions

***Multiattack.*** The hunter makes three attacks, using Shortsword or Longbow in any combination.

***Shortsword.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 11 (`2d6 + 4`) Piercing damage, and the target has [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls and ability checks until the end of its next turn.

***Longbow.*** *Ranged Attack Roll:* `+7`, range 150/600 ft. *Hit:* 17 (`3d8 + 4`) Piercing damage, and the target's [Speed](Mechanics/CLI/rules/variant-rules/speed-xphb.md) is reduced by 10 feet until the end of its next turn.

## Bonus Actions

***Mark of Tharashk.*** The hunter magically marks one creature it can see within 150 feet. The mark lasts for 1 hour, until the target dies, or until the hunter uses this [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) again. While the target is marked in this way, the hunter has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls against the target, and the target gains no benefit from the [Invisible](Mechanics/CLI/rules/conditions.md#Invisible) condition against the hunter.

## Reactions

***Uncanny Dodge.*** Trigger: The hunter is hit by an attack roll. _Response:_ The hunter halves the damage (round down) it takes from that attack.
```

^statblock
