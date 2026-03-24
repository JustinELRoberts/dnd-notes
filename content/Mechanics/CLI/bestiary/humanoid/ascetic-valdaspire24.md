---
publish: true
aliases:
  - Ascetic
created: 2026-03-09T12:15:33.823-04:00
modified: 2026-03-09T12:15:33.823-04:00
published: 2026-03-09T12:15:33.823-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid/cohort
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Ascetic

_Source: Valda's Spire of Secrets (2024)_

An ascetic is a disciplined, nimble combatant whose fists are as deadly as weapons.

```ad-statblock
title: Ascetic
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Tokens/Ascetic.webp#token)
*Small or Medium humanoid (Cohort), Neutral*

- **Armor Class** (13 plus your Charisma modifier)
- **Hit Points** 6 plus six times your Captain level (the ascetic has a number of Hit Dice [d8s] equal to your Captain level)  (6 plus six times your Captain level (the ascetic has a number of Hit Dice [d8s] equal to your Captain level))
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|16 (+3)|12 (+1)| 9 (-1)|14 (+2)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** 0+PB, 3+PB
- **Skills** +3+PB, +2+PB
- **Senses** passive Perception 12
- **Languages** Common plus one other language
- **Challenge** 

## Traits

***Proficiencies.*** Simple weapons

***Level 5.*** Martial Excellence. The ascetic has a +1 bonus to its attack and damage rolls. This bonus increases to +2 at Captain level 9, and +3 at Captain level 13.

## Actions

***Unarmed Strike.*** *Melee Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), reach 5 ft. *Hit:* `1d6` plus your Charisma modifier Bludgeoning damage.

***Level 9.*** Multiattack. The ascetic makes two [Unarmed Strikes](Mechanics/CLI/rules/variant-rules/unarmed-strike-xphb.md).

***Level 17.*** Stunning Strike (2/Day). *Constitution Saving Throw:* DC equals your Cohort save DC, one creature within 5 feet. *Failure:* The target has the [Stunned](Mechanics/CLI/rules/conditions.md#Stunned) condition until the end of its next turn. *Success:* The target's speed is halved and the next attack roll made against the target before then has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md).

## Bonus Actions

***Level 5.*** Flurry of Blows (2/Day). The ascetic makes one [Unarmed Strike](Mechanics/CLI/rules/variant-rules/unarmed-strike-xphb.md). The ascetic can take this [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) once more at Captain levels 9 (3/Day), 13 (4/Day), and 17 (5/Day).

***Focused Movement (2/Day).*** The ascetic takes the [Dash](Mechanics/CLI/rules/actions.md#Dash), [Disengage](Mechanics/CLI/rules/actions.md#Disengage), or [Dodge](Mechanics/CLI/rules/actions.md#Dodge) action.

## Reactions

***Level 13.*** Deflect Attack. Trigger: The ascetic is hit by an attack roll and takes Bludgeoning, Piercing, or Slashing damage from it. _Response:_ The ascetic reduces the damage taken by your Captain level.
```

^statblock
