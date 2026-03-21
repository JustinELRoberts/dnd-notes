---
publish: true
aliases:
  - Vulkoori Venom Priest
created: 2026-03-09T12:15:34.028-04:00
modified: 2026-03-09T12:15:34.028-04:00
published: 2026-03-09T12:15:34.028-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/2
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid/elf
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Vulkoori Venom Priest
*Source: Eberron: Forge of the Artificer p. 98*  
![](Mechanics/CLI/bestiary/humanoid/img/vulkoori-venom-priest.webp#right)

Vulkoori venom priests delight in inflicting suffering through poison. Their weaponry and magic are carefully crafted to evoke the presence of the scorpion-god and strike terror into their enemies' hearts.

```ad-statblock
title: Vulkoori Venom Priest
![](Mechanics/CLI/bestiary/humanoid/token/vulkoori-venom-priest-efa.webp#token)
*Medium humanoid (elf), Neutral Evil*

- **Armor Class** 15 
- **Hit Points** 44 (`8d8 + 8`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|16 (+3)|12 (+1)|10 (+0)|16 (+3)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +3, Wisdom +5
- **Skills** [Perception](Mechanics/CLI/rules/skills.md#Perception) +5, [Religion](Mechanics/CLI/rules/skills.md#Religion) +2, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +5
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 15
- **Damage Resistances** poison
- **Gear** [holy symbol](Mechanics/CLI/items/holy-symbol-xphb.md), [quarterstaff](Mechanics/CLI/items/quarterstaff-xphb.md), [studded leather armor](Mechanics/CLI/items/studded-leather-armor-xphb.md)
- **Languages** Common, Elvish, Giant
- **Challenge** 2

## Traits

***Fey Ancestry.*** Magic can't put the priest to sleep.

## Actions

***Venom Staff.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 9 (`2d6 + 2`) Bludgeoning damage, and the target has the [Poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) condition until the end of the priest's next turn.

***Spellcasting.*** The priest casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 13, `+5` to hit with spell attacks):

**At will:** [Dancing Lights](Mechanics/CLI/spells/dancing-lights-xphb.md), [Ray of Sickness](Mechanics/CLI/spells/ray-of-sickness-xphb.md), [Thaumaturgy](Mechanics/CLI/spells/thaumaturgy-xphb.md)

**1/day each:** [Cure Wounds](Mechanics/CLI/spells/cure-wounds-xphb.md), [Hold Person](Mechanics/CLI/spells/hold-person-xphb.md), [Protection from Poison](Mechanics/CLI/spells/protection-from-poison-xphb.md)

## Bonus Actions

***Intensify Poison.*** Each creature with the [Poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) condition within a 30-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from the priest takes 3 (`1d6`) Poison damage.
```
^statblock