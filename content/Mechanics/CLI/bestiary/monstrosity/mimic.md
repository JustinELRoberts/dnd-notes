---
publish: true
aliases:
  - Mimic
created: 2026-03-29T21:53:55.916-04:00
modified: 2026-03-29T21:53:55.916-04:00
published: 2026-03-29T21:53:55.916-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mm
  - ttrpg-cli/monster/cr/2
  - ttrpg-cli/monster/environment/underdark
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/monstrosity/shapechanger
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Mimic
ac: 12
hp: 58
modifier: 1
hit_dice: 9d8 + 18
cr: "2"
stats:
  - 17
  - 12
  - 15
  - 5
  - 13
  - 8
source:
  - MM
---

# Mimic

![](Mechanics/CLI/bestiary/monstrosity/img/mimic.webp#right)
Mimics are shapeshifting predators able to take on the form of inanimate objects to lure creatures to their doom. In dungeons, these cunning creatures most often take the form of doors and chests, having learned that such forms attract a steady stream of prey.

## Imitative Predators

Mimics can alter their outward texture to resemble wood, stone, and other basic materials, and they have evolved to assume the appearance of objects that other creatures are likely to come into contact with. A mimic in its altered form is nearly unrecognizable until potential prey blunders into its reach, whereupon the monster sprouts pseudopods and attacks.

When it changes shape, a mimic excretes an adhesive that helps it seize prey and weapons that touch it. The adhesive is absorbed when the mimic assumes its amorphous form and on parts the mimic uses to move itself.

## Cunning Hunters

Mimics live and hunt alone, though they occasionally share their feeding grounds with other creatures. Although most mimics have only predatory intelligence, a rare few evolve greater cunning and the ability to carry on simple conversations in Common or Undercommon. Such mimics might allow safe passage through their domains or provide useful information in exchange for food.

> [!quote] A quote from X the Mystic's 3rd rule of dungeon survival
>
> Sometimes a chest is just a chest, but don't bet on it.

## Statblock

```ad-statblock
title: Mimic
![](/Mechanics/CLI/bestiary/monstrosity/token/mimic.webp#token)
*Medium monstrosity (shapechanger), Neutral*

- **Armor Class** 12 (natural armor)
- **Hit Points** 58 (9d8 + 18) 
- **Speed** 15 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|17 (+3)|12 (+1)|15 (+2)| 5 (-3)|13 (+1)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Stealth](/Mechanics/CLI/skills.md#Stealth) +5
- **Senses** [darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception 11
- **Damage Immunities** acid
- **Condition Immunities** [prone](/Mechanics/CLI/conditions.md#Prone)
- **Languages** —
- **Challenge** 2

## Traits

***Shapechanger.*** The mimic can use its action to polymorph into an object or back into its true, amorphous form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

***Adhesive (Object Form Only).*** The mimic adheres to anything that touches it. A Huge or smaller creature adhered to the mimic is also [grappled](/Mechanics/CLI/conditions.md#Grappled) by it (escape DC 13). Ability checks made to escape this grapple have disadvantage.

***False Appearance (Object Form Only).*** While the mimic remains motionless, it is indistinguishable from an ordinary object.

***Grappler.*** The mimic has advantage on attack rolls against any creature [grappled](/Mechanics/CLI/conditions.md#Grappled) by it.

## Actions

***Pseudopod.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 7 (`1d8 + 3`) bludgeoning damage. If the mimic is in object form, the target is subjected to its Adhesive trait.

***Bite.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 7 (`1d8 + 3`) piercing damage plus 4 (`1d8`) acid damage.
```

^statblock

## Environment

underdark, urban

## Sources

_Monster Manual p. 220. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>_
