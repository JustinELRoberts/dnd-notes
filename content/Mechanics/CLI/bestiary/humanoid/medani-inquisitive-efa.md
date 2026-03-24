---
publish: true
aliases:
  - Medani Inquisitive
created: 2026-03-09T12:15:33.930-04:00
modified: 2026-03-09T12:15:33.930-04:00
published: 2026-03-09T12:15:33.930-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/3
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid/khoravar
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Medani Inquisitive

_Source: Eberron: Forge of the Artificer p. 82_\
![](Mechanics/CLI/bestiary/humanoid/img/medani-inquisitive.webp#right)

The most prized inquisitives of House Medani, a house of mostly Khoravar, employ their dragonmarks and their keen intellects to anticipate threats from any quarter. Some are part of a secretive order called the Basilisk's Gaze, dedicated to hunting down fugitive war criminals who committed atrocities during the Last War.

```ad-statblock
title: Medani Inquisitive
![](Mechanics/CLI/bestiary/humanoid/token/medani-inquisitive-efa.webp#token)
*Small or Medium humanoid (khoravar), Neutral*

- **Armor Class** 14 
- **Hit Points** 45 (`7d8 + 14`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|10 (+0)|14 (+2)|15 (+2)|16 (+3)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** Constitution +4, Wisdom +5
- **Skills** [Insight](Mechanics/CLI/rules/skills.md#Insight) +5, [Investigation](Mechanics/CLI/rules/skills.md#Investigation) +4
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 13
- **Gear** [breastplate](Mechanics/CLI/items/breastplate-xphb.md), [quarterstaff](Mechanics/CLI/items/quarterstaff-xphb.md)
- **Languages** Common, Elvish
- **Challenge** 3

## Actions

***Multiattack.*** The inquisitive makes three Crooked Staff attacks. It can replace one attack with a use of Inquisitive Eye.

***Crooked Staff.*** *Melee Attack Roll:* `+4`, reach 5 ft. *Hit:* 6 (`1d8 + 2`) Bludgeoning damage. If the target is a Medium or smaller creature, it has the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition. If the target already has the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition, the attack deals an extra 7 (`2d6`) Radiant damage.

***Inquisitive Eye.*** *Wisdom Saving Throw:* DC 13, one creature the inquisitive can see within 60 feet. *Failure:* 10 (`3d6`) Psychic damage, and the target is marked. The inquisitive has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on attack rolls against a target it has marked. While marked, the target can't become hidden from the inquisitive, and if it has the [Invisible](Mechanics/CLI/rules/conditions.md#Invisible) condition, it gains no benefit from that condition against the inquisitive. The mark disappears after 1 minute or when the inquisitive uses this action again. *Success:* Half damage only.

***Spellcasting.*** The inquisitive casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 13):

At Will : Guidance

**1/day each:** [Detect Thoughts](Mechanics/CLI/spells/detect-thoughts-xphb.md), [See Invisibility](Mechanics/CLI/spells/see-invisibility-xphb.md)

## Reactions

***Spontaneous Barrier (Recharge 4-6).*** Trigger: The inquisitive or an ally it can see is hit with an attack roll. _Response:_ The inquisitive adds 2 to its or the ally's AC against that attack, possibly causing it to miss.
```

^statblock
