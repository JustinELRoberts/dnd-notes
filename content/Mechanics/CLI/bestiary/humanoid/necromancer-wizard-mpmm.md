---
publish: true
aliases:
  - Necromancer Wizard
created: 2026-03-09T12:15:34.125-04:00
modified: 2026-03-09T12:15:34.125-04:00
published: 2026-03-09T12:15:34.125-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/9
  - ttrpg-cli/monster/environment/desert
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Necromancer Wizard
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 264, Volo's Guide to Monsters p. 217*  
![](Mechanics/CLI/bestiary/humanoid/img/necromancer-wizard.webp#right)

Necromancers study the interaction of life, death, and undeath. Some necromancers dig up or purchase corpses to create Undead servitors. A few instead use their powers for good, hunting Undead.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

## Statblock

```ad-statblock
title: Necromancer Wizard
![](Mechanics/CLI/bestiary/humanoid/token/necromancer-wizard-mpmm.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](Mechanics/CLI/spells/mage-armor-xphb.md))
- **Hit Points** 110 (`20d8 + 20`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|12 (+1)|17 (+3)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +7, Wisdom +5
- **Skills** [Arcana](Mechanics/CLI/rules/skills.md#Arcana) +7, [History](Mechanics/CLI/rules/skills.md#History) +7
- **Senses** passive Perception 11
- **Damage Resistances** necrotic
- **Languages** any four languages
- **Challenge** 9

## Actions

***Multiattack.*** The necromancer makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee  or Ranged Spell Attack:* `+7` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 25 (`4d10 + 3`) necrotic damage.

***Spellcasting.*** The necromancer casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 15):

**At will:** [dancing lights](Mechanics/CLI/spells/dancing-lights-xphb.md), [mage hand](Mechanics/CLI/spells/mage-hand-xphb.md), [prestidigitation](Mechanics/CLI/spells/prestidigitation-xphb.md)

**2/day each:** [bestow curse](Mechanics/CLI/spells/bestow-curse-xphb.md), [dimension door](Mechanics/CLI/spells/dimension-door-xphb.md), [mage armor](Mechanics/CLI/spells/mage-armor-xphb.md), [web](Mechanics/CLI/spells/web-xphb.md)

**1/day each:** [circle of death](Mechanics/CLI/spells/circle-of-death-xphb.md)

## Bonus Actions

***Summon Undead (1/Day).*** The necromancer magically summons five [skeletons](Mechanics/CLI/bestiary/undead/skeleton-xmm.md) or [zombies](Mechanics/CLI/bestiary/undead/zombie-xmm.md). The summoned creatures appear in unoccupied spaces within 60 feet of the necromancer, whom they obey. They take their turns immediately after the necromancer. Each lasts for 1 hour, until it or the necromancer dies, or until the necromancer dismisses it as a bonus action.

## Reactions

***Grim Harvest (1/Turn).*** When the necromancer kills a creature with necrotic damage, the necromancer regains 9 (`2d8`) hit points. 
```
^statblock

## Environment

desert, urban