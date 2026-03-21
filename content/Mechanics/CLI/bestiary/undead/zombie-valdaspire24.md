---
publish: true
aliases:
  - Zombie
created: 2026-03-09T12:15:33.819-04:00
modified: 2026-03-09T12:15:33.819-04:00
published: 2026-03-09T12:15:33.819-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/1-4
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/undead/thrall
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Zombie
*Source: Valda's Spire of Secrets (2024) p. 0*  
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaNecromancer/Creatures/Zombie.webp#right)

A zombie is the rotting remains of the once living, held together and driven by dark magic.

```ad-statblock
title: Zombie
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaNecromancer/Tokens/Zombie.webp#token)
*Medium undead (Thrall), Neutral Evil*

- **Armor Class** 8 
- **Hit Points** 15 (`2d8 + 6`) 
- **Speed** 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|13 (+1)| 6 (-2)|16 (+3)| 3 (-4)| 6 (-2)| 5 (-3)|

- **Proficiency Bonus** +2
- **Saving Throws** Wisdom +0
- **Skills** ⏤
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 8
- **Damage Immunities** poison
- **Condition Immunities** [exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion), [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common plus one other language but can't speak
- **Challenge** 1/4

## Traits

***Undead Fortitude.*** If damage reduces the zombie to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), it makes a Constitution saving throw (DC 5 plus the damage taken) unless the damage is Radiant or from a [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md). On a successful save, the zombie drops to 1 [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) instead.

## Actions

***Slam.*** *Melee Attack Roll:* `+3`, reach 5 ft. *Hit:* 5 (`1d8 + 1`) Bludgeoning damage.
```
^statblock