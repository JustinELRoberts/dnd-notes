---
publish: true
aliases:
  - Dreaming Dark Infiltrator
created: 2026-03-09T12:15:33.908-04:00
modified: 2026-03-09T12:15:33.908-04:00
published: 2026-03-09T12:15:33.908-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/7
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Dreaming Dark Infiltrator
*Source: Eberron: Forge of the Artificer p. 59*  
![](Mechanics/CLI/bestiary/humanoid/img/dreaming-dark-infiltrator.webp#right)

Dreaming Dark Infiltrators are spies sent to gather intelligence. They plant psychic seeds in their minds of their foes that enhance the infiltrators' combat prowess against those enemies.

```ad-statblock
title: Dreaming Dark Infiltrator
![](Mechanics/CLI/bestiary/humanoid/token/dreaming-dark-infiltrator-efa.webp#token)
*Small or Medium humanoid, Lawful Evil*

- **Armor Class** 15 
- **Hit Points** 104 (`16d8 + 32`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|17 (+3)|15 (+2)|18 (+4)|16 (+3)|17 (+3)|

- **Proficiency Bonus** +3
- **Saving Throws** Intelligence +7, Wisdom +6, Charisma +6
- **Skills** [Deception](Mechanics/CLI/rules/skills.md#Deception) +6, [Insight](Mechanics/CLI/rules/skills.md#Insight) +6, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +6
- **Senses** [Truesight](Mechanics/CLI/rules/senses.md#Truesight) 30 ft., passive Perception 13
- **Damage Resistances** psychic
- **Gear** [chain shirt](Mechanics/CLI/items/chain-shirt-xphb.md)
- **Languages** Common, Quori; telepathy 120 ft.
- **Challenge** 7

## Actions

***Multiattack.*** The infiltrator makes three Mind Blade attacks.

***Mind Blade.*** *Melee  or Ranged Attack Roll:* `+7`, reach 5 ft. or range 30 ft. *Hit:* 14 (`3d6 + 4`) Psychic damage.

***Spellcasting.*** The infiltrator casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 15):

**3/day:** [Detect Thoughts](Mechanics/CLI/spells/detect-thoughts-xphb.md)

**1/day:** [Synaptic Static](Mechanics/CLI/spells/synaptic-static-xphb.md)

## Bonus Actions

***Mind Curse.*** *Wisdom Saving Throw:* DC 15, one creature hit by the infiltrator's Mind Blade attack this turn. *Failure:* The target takes 14 (`4d6`) Psychic damage and is cursed. While cursed in this way, it has [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls against the infiltrator, and the infiltrator always knows its location while it and the infiltrator are on the same plane of existence. A cursed creature repeats the save whenever it finishes a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), ending the effect on itself on a success. *Success:* Half damage only.
```
^statblock