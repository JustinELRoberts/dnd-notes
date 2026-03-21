---
publish: true
aliases:
  - Jorasco Medic
created: 2026-03-09T12:15:33.880-04:00
modified: 2026-03-09T12:15:33.880-04:00
published: 2026-03-09T12:15:33.880-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/4
  - ttrpg-cli/monster/size/small
  - ttrpg-cli/monster/type/humanoid/halfling
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Jorasco Medic
*Source: Eberron: Forge of the Artificer p. 81*  
![](Mechanics/CLI/bestiary/humanoid/img/jorasco-medic.webp#right)

Dragonmarked heirs of House Jorasco served alongside every nation's armies in the Last War, providing medical care and magical healing to the injured. Though the warring nations treated Jorasco medics as sacrosanct, these medics also learned to channel their healing power into dazzling light to help them reach the wounded and escape from the thick of combat when necessary.

```ad-statblock
title: Jorasco Medic
![](Mechanics/CLI/bestiary/humanoid/token/jorasco-medic-efa.webp#token)
*Small humanoid (halfling), Neutral*

- **Armor Class** 16 
- **Hit Points** 58 (`9d6 + 27`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|12 (+1)|15 (+2)|16 (+3)|14 (+2)|17 (+3)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +5, Wisdom +5
- **Skills** [Insight](Mechanics/CLI/rules/skills.md#Insight) +5, [Medicine](Mechanics/CLI/rules/skills.md#Medicine) +5, [Perception](Mechanics/CLI/rules/skills.md#Perception) +5, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +4
- **Senses** passive Perception 15
- **Gear** [breastplate](Mechanics/CLI/items/breastplate-xphb.md)
- **Languages** Common, Halfling
- **Challenge** 4

## Traits

***Lucky.*** When the medic rolls a 1 on the `d20` of a [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md), it can reroll the die, and it must use the new roll.

## Actions

***Multiattack.*** The medic makes two Radiant Burst attacks.

***Radiant Burst.*** *Melee  or Ranged Attack Roll:* `+5`, reach 5 ft. or range 30 ft. *Hit:* 7 (`2d6`) Radiant damage, and the creature has the [Blinded](Mechanics/CLI/rules/conditions.md#Blinded) condition until the start of the medic's next turn.

## Bonus Actions

***Mark of Healing (2/Day).*** The medic casts [Cure Wounds](Mechanics/CLI/spells/cure-wounds-xphb.md) or [Lesser Restoration](Mechanics/CLI/spells/lesser-restoration-xphb.md), using Wisdom as the spellcasting ability.

```
^statblock