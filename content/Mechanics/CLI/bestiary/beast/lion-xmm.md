---
publish: true
aliases:
  - Lion
created: 2026-03-09T12:15:34.092-04:00
modified: 2026-03-09T12:15:34.092-04:00
published: 2026-03-09T12:15:34.092-04:00
tags:
  - ttrpg-cli/compendium/src/5e/xmm
  - ttrpg-cli/monster/cr/1
  - ttrpg-cli/monster/environment/desert
  - ttrpg-cli/monster/environment/grassland
  - ttrpg-cli/monster/environment/hill
  - ttrpg-cli/monster/environment/mountain
  - ttrpg-cli/monster/size/large
  - ttrpg-cli/monster/type/beast
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Lion
*Source: Monster Manual (2024) p. 364, Player's Handbook (2024) p. 352. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  
![](Mechanics/CLI/bestiary/beast/img/lion.webp#right)

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [Panther](Mechanics/CLI/bestiary/beast/panther-xmm.md) stat block can also represent a mountain lion, while the [Giant Goat](Mechanics/CLI/bestiary/beast/giant-goat-xmm.md) stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

> [!gallery]
![A druid calls on animals o...](Mechanics/CLI/bestiary/beast/img/animals-hills-and-mountains.webp "A druid calls on animals of the hills and mountains to aid her cause")
![Aquatic animals swim along...](Mechanics/CLI/bestiary/beast/img/animals-aquatic.webp "Aquatic animals swim alongside a druid exploring the sea")
![Inhabitants of the rain fo...](Mechanics/CLI/bestiary/beast/img/animals-rainforest.webp "Inhabitants of the rain forest answer a druid's summons")

```ad-statblock
title: Lion
![](Mechanics/CLI/bestiary/beast/token/lion-xmm.webp#token)
*Large beast, Unaligned*

- **Armor Class** 12 
- **Hit Points** 22 (`4d10`) 
- **Speed** 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|15 (+2)|11 (+0)| 3 (-4)|12 (+1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](Mechanics/CLI/rules/skills.md#Perception) +3, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +4
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 13
- **Languages** —
- **Challenge** 1

## Traits

***Pack Tactics.*** The lion has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on an attack roll against a creature if at least one of the lion's allies is within 5 feet of the creature and the ally doesn't have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

***Running Leap.*** With a 10-foot running start, the lion can [Long Jump](Mechanics/CLI/rules/variant-rules/long-jump-xphb.md) up to 25 feet.

## Actions

***Multiattack.*** The lion makes two Rend attacks. It can replace one attack with a use of Roar.

***Rend.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 7 (`1d8 + 3`) Slashing damage.

***Roar.*** *Wisdom Saving Throw:* DC 11, one creature within 15 feet. *Failure:* The target has the [Frightened](Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the lion's next turn.
```
^statblock

## Environment

desert, grassland, hill, mountain