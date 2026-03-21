---
publish: true
aliases:
  - Yarn Golem
created: 2026-03-09T12:15:33.886-04:00
modified: 2026-03-09T12:15:33.886-04:00
published: 2026-03-09T12:15:33.886-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/1-2
  - ttrpg-cli/monster/size/tiny
  - ttrpg-cli/monster/type/construct/familiar
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Yarn Golem
*Source: Valda's Spire of Secrets (2024) p. 0*  
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWitch/Creatures/Yarn%20Golem.webp#right)

The greatest of golems are formed of iron, stone, and clay, but the least of them are constructed of yarn. Balled and sewn into a vaguely humanoid shape, yarn golems are among the first animated objects that arcanists learn to create, practicing with them obsessively until they master the basics and move onto more rigid materials. Yarn golems are friendly and playful, but risk foolishly unraveling themselves if they catch on sharp objects.

```ad-statblock
title: Yarn Golem
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWitch/Tokens/YarnGolem.webp#token)
*Tiny construct (Familiar), Chaotic Neutral*

- **Armor Class** 13 
- **Hit Points** 21 (`6d4 + 6`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|16 (+3)|13 (+1)| 1 (-5)|10 (+0)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** passive Perception 10
- **Damage Resistances** piercing
- **Damage Immunities** poison, psychic
- **Condition Immunities** [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** understands Common plus one other language but can't speak
- **Challenge** 1/2

## Actions

***Poke.*** *Melee Attack Roll:* `+5`, reach 5 ft. *Hit:* 8 (`2d4 + 3`) Piercing damage.

***Tangle (Recharge 6).*** *Dexterity Saving Throw:* DC 12, one creature that the golem can see within 5 feet. *Failure:* If the target is Medium or smaller, it has the [Grappled](Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 12). While [Grappled](Mechanics/CLI/rules/conditions.md#Grappled), the target has the [Restrained](Mechanics/CLI/rules/conditions.md#Restrained) condition.
```
^statblock