---
publish: true
aliases:
  - Tarkanan Marauder
created: 2026-03-09T12:15:33.980-04:00
modified: 2026-03-09T12:15:33.980-04:00
published: 2026-03-09T12:15:33.980-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/11
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Tarkanan Marauder
*Source: Eberron: Forge of the Artificer p. 73*  
![](Mechanics/CLI/bestiary/humanoid/img/tarkanan-marauder.webp#right)

This powerful assassin relies on teleportation to catch targets unaware and deal out rapid death.

```ad-statblock
title: Tarkanan Marauder
![](Mechanics/CLI/bestiary/humanoid/token/tarkanan-marauder-efa.webp#token)
*Small or Medium humanoid, Chaotic Evil*

- **Armor Class** 16 
- **Hit Points** 247 (`26d8 + 130`) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|17 (+3)|20 (+5)|16 (+3)|15 (+2)|13 (+1)|

- **Proficiency Bonus** +4
- **Saving Throws** Dexterity +7, Constitution +9, Wisdom +6
- **Skills** [Deception](Mechanics/CLI/rules/skills.md#Deception) +5, [Perception](Mechanics/CLI/rules/skills.md#Perception) +6, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +7
- **Senses** passive Perception 16
- **Gear** [breastplate](Mechanics/CLI/items/breastplate-xphb.md), [shortsword](Mechanics/CLI/items/shortsword-xphb.md)
- **Languages** Common, Thieves' cant
- **Challenge** 11

## Traits

***Evasion.*** If the marauder is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the marauder instead takes no damage if it succeeds on the save and only half as much damage if it fails. It can't use this trait if it has the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

## Actions

***Multiattack.*** The marauder makes three Aberrant Strike attacks.

***Aberrant Strike.*** *Melee Attack Roll:* `+7`, reach 5 ft. *Hit:* 13 (`3d6 + 3`) Piercing damage, plus 21 (`6d6`) Force damage if the marauder had [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on the attack roll.

***Spellcasting.*** The marauder casts one of the following spells, requiring no Material components and using Constitution as the spellcasting ability (spell save DC 17):

**At will:** [Message](Mechanics/CLI/spells/message-xphb.md)

**1/day:** [Disintegrate](Mechanics/CLI/spells/disintegrate-xphb.md)

## Bonus Actions

***Tear Through Space.*** The marauder teleports to a space it can see within 30 feet, appearing in a dazzling flash. *Constitution Saving Throw:* DC 17, each creature in a 5-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the marauder when it appears. *Failure:* The target has the [Blinded](Mechanics/CLI/rules/conditions.md#Blinded) condition until the end of the marauder's next turn.
```
^statblock