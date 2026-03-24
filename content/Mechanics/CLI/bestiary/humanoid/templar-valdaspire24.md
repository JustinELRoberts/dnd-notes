---
publish: true
aliases:
  - Templar
created: 2026-03-09T12:15:33.798-04:00
modified: 2026-03-09T12:15:33.798-04:00
published: 2026-03-09T12:15:33.798-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid/cohort
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Templar

_Source: Valda's Spire of Secrets (2024)_\
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Creatures/Templar.webp#right)

A daring knight, sworn to virtue and station, a templar knows no fear in their heart and no equal in battle.

```ad-statblock
title: Templar
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Tokens/Templar.webp#token)
*Small or Medium humanoid (Cohort), Neutral*

- **Armor Class** 16 
- **Hit Points** 6 plus six times your Captain level (the templar has a number of Hit Dice [d8s] equal to your Captain level)  (6 plus six times your Captain level (the templar has a number of Hit Dice [d8s] equal to your Captain level))
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)| 9 (-1)|13 (+1)|10 (+0)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** 0+PB, 1+PB
- **Skills** [Athletics](Mechanics/CLI/rules/skills.md#Athletics) +5, [Religion](Mechanics/CLI/rules/skills.md#Religion) +2
- **Senses** passive Perception 10
- **Gear** [chain mail](Mechanics/CLI/items/chain-mail-xphb.md), four [javelins](Mechanics/CLI/items/javelin-xphb.md), [greatsword](Mechanics/CLI/items/greatsword-xphb.md)
- **Languages** Common plus one other language
- **Challenge** 

## Traits

***Proficiencies.*** Simple and Martial weapons; Light, Medium, and Heavy armor, Shields

***Level 5.*** Martial Excellence. The templar has a +1 bonus to its attack and damage rolls. This bonus increases to +2 at Captain level 9, and +3 at Captain level 13.

***Level 9.*** Improved Smite. The Radiant damage of the templar's Smite increases by `1d8` (`3d8`) and again at Captain level 17 (`4d8`).

***Level 13.*** Zealous. The templar adds your Charisma modifier to its saving throws.

***Level 17.*** Blessed Blade. The templar has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls.

## Actions

***Greatsword.*** *Melee Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), reach 5 ft. *Hit:* `2d6` plus your Charisma modifier Slashing damage.

***Javelin.*** *Ranged Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), range 30/120 ft. *Hit:* `1d6` plus your Charisma modifier Piercing damage.

## Bonus Actions

***Smite (2/Day).*** The templar deals an extra `2d8` Radiant damage on a hit. The templar can use this [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) once more at Captain level 5 (3/Day), 9 (4/Day), 13 (5/Day), and 17 (6/Day).

## Reactions

***Level 5.*** Parry. Trigger: The templar is hit by a melee attack roll while holding a weapon. _Response:_ The templar adds your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md) to its AC against that attack, possibly causing it to miss.
```

^statblock
