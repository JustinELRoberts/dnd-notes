---
publish: true
aliases:
  - Incorporeal Undead
created: 2026-03-09T12:15:34.096-04:00
modified: 2026-03-09T12:15:34.096-04:00
published: 2026-03-09T12:15:34.096-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/undead/cohort
  - ttrpg-cli/monster/type/undead/skull-banner-subclass
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Incorporeal Undead
*Source: Valda's Spire of Secrets (2024)*  

```ad-statblock
title: Incorporeal Undead
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Tokens/Incorporeal%20Undead.webp#token)
*Medium undead (Cohort, Skull Banner Subclass), Lawful Evil*

- **Armor Class** 15 
- **Hit Points** 4 plus four times your Captain level (the undead has a number of Hit Dice [d8s] equal to your Captain level)  (4 plus four times your Captain level (the undead has a number of Hit Dice [d8s] equal to your Captain level))
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)| 8 (-1)|10 (+0)|10 (+0)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** 3+PB, 0+PB
- **Skills** ⏤
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 10
- **Damage Resistances** bludgeoning, piercing, slashing
- **Damage Immunities** necrotic, poison
- **Condition Immunities** [charmed](Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](Mechanics/CLI/rules/conditions.md#Frightened), [grappled](Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned), [prone](Mechanics/CLI/rules/conditions.md#Prone), [restrained](Mechanics/CLI/rules/conditions.md#Restrained)
- **Languages** Common plus one other language
- **Challenge** 

## Traits

***Incorporeal Movement.*** The undead can move through other creatures and objects as if they were [Difficult Terrain](Mechanics/CLI/rules/variant-rules/difficult-terrain-xphb.md). It takes 5 (`1d10`) Force damage if it ends its turn inside an object.

***Level 5.*** Undead Excellence. The undead has a +1 bonus to its attack and damage rolls. This bonus increases to +2 at Captain level 9, and +3 at Captain level 13.

***Level 13.*** [Resistance](Mechanics/CLI/spells/resistance-xphb.md). The undead has [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to all damage types except Radiant and Force.

## Actions

***Death Touch.*** *Melee Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), reach 5 ft. *Hit:* `1d8` plus your Charisma modifier Necrotic damage.

***Level 17.*** Life Drain (2/Day). *Constitution Saving Throw:* DC equals your Cohort save DC, one creature within 5 feet. *Failure:* `8d8` Necrotic damage and the undead regains [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to the Necrotic damage taken. *Success:* Half damage only.

## Bonus Actions

***Level 9.*** Necrotic Strike. The undead's Death Touch deals an extra `1d8` Necrotic damage.

***Level 5:.*** Invisibility. The undead casts [Invisibility](Mechanics/CLI/spells/invisibility-xphb.md) on itself, requiring no spell components and using Charisma as the spellcasting ability.

```
^statblock