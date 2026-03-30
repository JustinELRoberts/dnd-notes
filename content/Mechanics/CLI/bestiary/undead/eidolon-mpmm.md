---
publish: true
aliases:
  - Eidolon
created: 2026-03-29T21:53:56.070-04:00
modified: 2026-03-29T21:53:56.070-04:00
published: 2026-03-29T21:53:56.070-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/12
  - ttrpg-cli/monster/environment/coastal
  - ttrpg-cli/monster/environment/desert
  - ttrpg-cli/monster/environment/forest
  - ttrpg-cli/monster/environment/grassland
  - ttrpg-cli/monster/environment/mountain
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/undead
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Eidolon (MPMM)
ac: 9
hp: 63
modifier: -1
hit_dice: 18d8 - 18
cr: "12"
stats:
  - 7
  - 8
  - 9
  - 14
  - 19
  - 16
source:
  - MPMM
---

# Eidolon

![](Mechanics/CLI/bestiary/construct/img/sacred-statue.webp#right)
To protect sites they deem holy, gods often rely on eidolons, ghostly spirits bound to safeguard a sacred place. Forged from the souls of those with unwavering devotion, eidolons stalk temples and vaults to ensure that no enemy defiles, damages, or plunders these sites. If an enemy sets foot inside a warded location, the [eidolon](/Mechanics/CLI/bestiary/undead/eidolon-mpmm.md) plunges into a [statue](/Mechanics/CLI/bestiary/construct/sacred-statue-mpmm.md) specially prepared to house its soul; it then animates this effigy and uses the statue to drive out the intruders.

```ad-statblock
title: Eidolon
![](/Mechanics/CLI/bestiary/undead/token/eidolon-mpmm.webp#token)
*Medium undead, Any alignment*

- **Armor Class** 9 
- **Hit Points** 63 (18d8 - 18) 
- **Speed** 0 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 7 (-2)| 8 (-1)| 9 (-1)|14 (+2)|19 (+4)|16 (+3)|

- **Proficiency Bonus** +4
- **Saving Throws** Wisdom +8
- **Skills** [Perception](/Mechanics/CLI/skills.md#Perception) +8
- **Senses** [darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception 18
- **Damage Resistances** acid; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** cold, necrotic, poison
- **Condition Immunities** [charmed](/Mechanics/CLI/conditions.md#Charmed), [exhaustion](/Mechanics/CLI/conditions.md#Exhaustion), [frightened](/Mechanics/CLI/conditions.md#Frightened), [grappled](/Mechanics/CLI/conditions.md#Grappled), [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed), [petrified](/Mechanics/CLI/conditions.md#Petrified), [poisoned](/Mechanics/CLI/conditions.md#Poisoned), [prone](/Mechanics/CLI/conditions.md#Prone), [restrained](/Mechanics/CLI/conditions.md#Restrained)
- **Languages** the languages it knew in life
- **Challenge** 12

## Traits

***Incorporeal Movement.*** The eidolon can move through other creatures and objects as if they were difficult terrain. It takes 5 (`1d10`) force damage if it ends its turn inside an object other than a [sacred statue](/Mechanics/CLI/bestiary/construct/sacred-statue-mpmm.md).

***Sacred Animation (Recharge 5-6).*** When the eidolon moves into a space occupied by a [sacred statue](/Mechanics/CLI/bestiary/construct/sacred-statue-mpmm.md), the eidolon can disappear, causing the statue to become a creature under the eidolon's control. The eidolon uses the [sacred statue's stat block](/Mechanics/CLI/bestiary/construct/sacred-statue-mpmm.md) in place of its own.

***Turn Resistance.*** The eidolon has advantage on saving throws against any effect that turns Undead.

***Unusual Nature.*** The eidolon doesn't require air, food, drink, or sleep.

## Actions

***Divine Dread.*** Each creature within 60 feet of the eidolon that can see it must succeed on a DC 15 Wisdom saving throw or be [frightened](/Mechanics/CLI/conditions.md#Frightened) of it for 1 minute. While [frightened](/Mechanics/CLI/conditions.md#Frightened) in this way, the creature must take the [Dash](/Mechanics/CLI/actions.md#Dash) action and move away from the eidolon by the safest available route at the start of each of its turns, unless there is nowhere for it to move, in which case the creature also becomes [stunned](/Mechanics/CLI/conditions.md#Stunned) until it can move again. A [frightened](/Mechanics/CLI/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to any eidolon's Divine Dread for the next 24 hours.
```

^statblock

## Environment

coastal, desert, forest, grassland, mountain, urban

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 114_
