---
publish: true
aliases:
  - Archdruid
created: 2026-03-09T12:15:33.798-04:00
modified: 2026-03-09T12:15:33.798-04:00
published: 2026-03-09T12:15:33.798-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/12
  - ttrpg-cli/monster/environment/forest
  - ttrpg-cli/monster/environment/mountain
  - ttrpg-cli/monster/environment/swamp
  - ttrpg-cli/monster/environment/underwater
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid/druid
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Archdruid

_Source: Mordenkainen Presents: Monsters of the Multiverse p. 48, Volo's Guide to Monsters p. 210_\
![](Mechanics/CLI/bestiary/humanoid/img/archdruid.webp#right)

Archdruids watch over the natural wonders of their domains. They seldom interact with folk away from their druid groves and shrines, unless there is a great threat to the natural order or to a nearby community. An archdruid typically has one or more pupils who are [druids](Mechanics/CLI/bestiary/humanoid/druid.md), and the archdruid's lair is usually guarded by loyal Beasts and Fey creatures.

When an archdruid uses their Change Shape action, you may choose the creature they turn into, abiding by the action's restrictions. Or you may roll on the Archdruid Favored Shapes table to determine the form the archdruid adopts.

**Archdruid Favored Shapes**

| dice: d8 | Favored Shape |
|----------|---------------|
| 1 | [Air elemental](Mechanics/CLI/bestiary/elemental/air-elemental.md) |
| 2 | [Earth elemental](Mechanics/CLI/bestiary/elemental/earth-elemental.md) |
| 3 | [Fire elemental](Mechanics/CLI/bestiary/elemental/fire-elemental.md) |
| 4 | [Giant crocodile](Mechanics/CLI/bestiary/beast/giant-crocodile.md) |
| 5 | [Mammoth](Mechanics/CLI/bestiary/beast/mammoth.md) |
| 6 | [Flail snail](Mechanics/CLI/bestiary/elemental/flail-snail-mpmm.md) |
| 7 | [Triceratops](Mechanics/CLI/bestiary/beast/triceratops.md) |
| 8 | [Water elemental](Mechanics/CLI/bestiary/elemental/water-elemental.md) |
^archdruid-favored-shapes

```ad-statblock
title: Archdruid
![](Mechanics/CLI/bestiary/humanoid/token/archdruid-mpmm.webp#token)
*Medium humanoid (druid), Any alignment*

- **Armor Class** 14 ([hide armor](Mechanics/CLI/items/hide-armor-xphb.md))
- **Hit Points** 154 (`28d8 + 28`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|14 (+2)|14 (+2)|12 (+1)|12 (+1)|20 (+5)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +5, Wisdom +9
- **Skills** [Medicine](Mechanics/CLI/rules/skills.md#Medicine) +9, [Nature](Mechanics/CLI/rules/skills.md#Nature) +5, [Perception](Mechanics/CLI/rules/skills.md#Perception) +9
- **Senses** passive Perception 19
- **Languages** Druidic plus any two languages
- **Challenge** 12

## Actions

***Multiattack.*** The archdruid makes three Staff or Wildfire attacks. It can replace one attack with a use of Spellcasting.

***Staff.*** *Melee Weapon Attack:* `+6` to hit, reach 5 ft., one target. *Hit:* 5 (`1d6 + 2`) bludgeoning damage plus 21 (`6d6`) poison damage.

***Wildfire.*** *Ranged Spell Attack:* `+9` to hit, range 120 ft., one target. *Hit:* 26 (`6d6 + 5`) fire damage, and the target is [blinded](Mechanics/CLI/rules/conditions.md#Blinded) until the start of the druid's next turn.

***Spellcasting.*** The archdruid casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 17):

**At will:** [beast sense](Mechanics/CLI/spells/beast-sense-xphb.md), [entangle](Mechanics/CLI/spells/entangle-xphb.md), [speak with animals](Mechanics/CLI/spells/speak-with-animals-xphb.md)

**3/day each:** [animal messenger](Mechanics/CLI/spells/animal-messenger-xphb.md), [dominate beast](Mechanics/CLI/spells/dominate-beast-xphb.md), [faerie fire](Mechanics/CLI/spells/faerie-fire-xphb.md), [tree stride](Mechanics/CLI/spells/tree-stride-xphb.md)

**1/day each:** [commune with nature](Mechanics/CLI/spells/commune-with-nature-xphb.md) (as an action), [mass cure wounds](Mechanics/CLI/spells/mass-cure-wounds-xphb.md)

## Bonus Actions

***Change Shape (2/Day).*** The archdruid magically transforms into a Beast or an Elemental with a challenge rating of 6 or less and can remain in that form for up to 9 hours. The archdruid can choose whether its equipment falls to the ground, melds with its new form, or is worn by the new form. The archdruid reverts to its true form if it dies or falls [unconscious](Mechanics/CLI/rules/conditions.md#Unconscious). The archdruid can revert to its true form using a bonus action.

While in a new form, the archdruid's stat block is replaced by the stat block of that form, except the archdruid keeps its current hit points, its hit point maximum, this bonus action, its languages and ability to speak, and its Spellcasting action.

The new form's attacks count as magical for the purpose of overcoming resistances and immunity to nonmagical attacks.
```

^statblock

## Environment

forest, mountain, swamp, underwater
