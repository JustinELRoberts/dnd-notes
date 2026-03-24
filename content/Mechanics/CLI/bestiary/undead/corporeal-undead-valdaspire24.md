---
publish: true
aliases:
  - Corporeal Undead
created: 2026-03-09T12:15:34.106-04:00
modified: 2026-03-09T12:15:34.106-04:00
published: 2026-03-09T12:15:34.106-04:00
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

# Corporeal Undead

_Source: Valda's Spire of Secrets (2024)_\
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Creatures/Corporeal%20Undead.webp#center)

```ad-statblock
title: Corporeal Undead
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Tokens/Corporeal%20Undead.webp#token)
*Medium undead (Cohort, Skull Banner Subclass), Lawful Evil*

- **Armor Class** 10 
- **Hit Points** 6 plus six times your Captain level (the undead has a number of Hit Dice [d8s] equal to your Captain level)  (6 plus six times your Captain level (the undead has a number of Hit Dice [d8s] equal to your Captain level))
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|10 (+0)|13 (+1)| 9 (-1)|12 (+1)| 9 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** 3+PB, 1+PB
- **Skills** ⏤
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 11
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common plus one other language, but can't speak
- **Challenge** 

## Traits

***Proficiencies.*** Simple weapons; Light and Medium armor, Shields

***Reanimate (1/Day).*** If reduced to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) but not destroyed outright, the undead revives with half of its [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) after 1 minute.

***Level 5.*** Undead Excellence. The undead has a +1 bonus to its attack and damage rolls. This bonus increases to +2 at Captain level 9, and +3 at Captain level 13.

***Level 13.*** Regeneration. The undead regains 5 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) at the start of each of its turns if it is [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied) and has at least 1 [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md).

## Actions

***Slam.*** *Melee Attack Roll:* Bonus equals your Charisma modifier plus your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), reach 5 ft. *Hit:* `1d8` plus your Charisma modifier Bludgeoning damage. If the target is a Large or smaller creature, it has the [Grappled](Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC equals your Cohort save DC).

***Level 17.*** Paralytic Bite (2/Day). *Constitution Saving Throw:* DC equals your Cohort save DC, one creature within 5 feet. *Failure:* The target has the [Paralyzed](Mechanics/CLI/rules/conditions.md#Paralyzed) condition until the end of its next turn. *Success:* The target's [Speed](Mechanics/CLI/rules/variant-rules/speed-xphb.md) is halved until the start of the undead's next turn.

## Bonus Actions

***Level 9.*** Necrotic Strike. The undead's Slam deals an extra `1d8` Necrotic damage.

## Reactions

***Level 5.*** Undead Resilience. Trigger: The undead is hit by a [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md). _Response:_ The undead turns the [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md) into a normal hit.
```

^statblock
