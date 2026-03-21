---
publish: true
aliases:
  - Berserker
created: 2026-03-09T12:15:34.038-04:00
modified: 2026-03-09T12:15:34.038-04:00
published: 2026-03-09T12:15:34.038-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid/cohort
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Berserker
*Source: Valda's Spire of Secrets (2024)*  


Ruthless and fierce, the berserker tears across the battlefield in a wild frenzy, devastating their enemies with boundless rage.

```ad-statblock
title: Berserker
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Tokens/Berserker.webp#token)
*Small or Medium humanoid (Cohort), Neutral*

- **Armor Class** (11 plus your Charisma modifier)
- **Hit Points** 7 plus seven times your Captain level (the berserker has a number of Hit Dice [d8s] equal to your Captain level)  (7 plus seven times your Captain level (the berserker has a number of Hit Dice [d8s] equal to your Captain level))
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|12 (+1)|14 (+2)| 9 (-1)|10 (+0)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** 3+PB, 2+PB
- **Skills** [Athletics](Mechanics/CLI/rules/skills.md#Athletics) +5, [Survival](Mechanics/CLI/rules/skills.md#Survival) +2
- **Senses** passive Perception 10
- **Gear** [greataxe](Mechanics/CLI/items/greataxe-xphb.md), four [handaxes](Mechanics/CLI/items/handaxe-xphb.md)
- **Languages** Common plus one other language
- **Challenge** 

## Traits

***Proficiencies.*** Simple and Martial weapons; Shields

***Bloodied Frenzy.*** While [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), the berserker has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls and saving throws.

***Level 5.*** Martial Excellence. The berserker has a +1 bonus to its attack and damage rolls. This bonus increases to +2 at Captain level 9, and +3 at Captain level 13.

***Level 13.*** Bloodied Resolve. While [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), the berserker has [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to Bludgeoning, Piercing, and Slashing damage.

## Actions

***Greataxe.*** *Melee Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), reach 5 ft. *Hit:* `1d12` plus your Charisma modifier Slashing damage.

***Handaxe.*** *Melee  or Ranged Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), reach 5 ft or range 20/60 ft. *Hit:* `1d6` plus your Charisma modifier Slashing damage.

## Bonus Actions

***Level 5.*** Adrenaline Burst. The berserker gains [Temporary Hit Points](Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) equal to half your Captain level.

***Level 9.*** Furious Strike. The berserker deals `1d10` extra damage on a hit with a weapon. The damage is the same type dealt by the weapon.

## Reactions

***Level 17.*** Retaliation. Trigger: A creature within 5 feet of the berserker deals damage to it. _Response:_ The berserker makes one melee attack.
```
^statblock