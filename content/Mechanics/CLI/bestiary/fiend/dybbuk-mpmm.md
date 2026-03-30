---
publish: true
aliases:
  - Dybbuk
created: 2026-03-29T21:53:55.902-04:00
modified: 2026-03-29T21:53:55.902-04:00
published: 2026-03-29T21:53:55.902-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/4
  - ttrpg-cli/monster/environment/desert
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/fiend/demon
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Dybbuk (MPMM)
ac: 14
hp: 37
modifier: 4
hit_dice: 5d8 + 15
cr: "4"
stats:
  - 6
  - 19
  - 16
  - 16
  - 15
  - 14
source:
  - MPMM
---

# Dybbuk

![](Mechanics/CLI/bestiary/fiend/img/dybbuk.webp#right)
Dybbuks are demons that terrorize mortals on the Material Plane by possessing corpses and giving them a semblance of life, after which the demons use them to engage in a range of sordid activities.

In their natural form, dybbuks appear as translucent flying jellyfish, trailing long tentacles as they move through the air. They rarely travel in this fashion, however. Instead, a dybbuk possesses a suitable corpse as a vehicle, rousing the body from death. Dybbuks delight in terrorizing other creatures by making their host bodies behave in horrifying ways—throwing up gouts of blood, excreting piles of squirming maggots, and contorting their limbs in impossible ways as they scuttle across the ground.

```ad-statblock
title: Dybbuk
![](/Mechanics/CLI/bestiary/fiend/token/dybbuk-mpmm.webp#token)
*Medium fiend (demon), Typically  Chaotic Evil*

- **Armor Class** 14 
- **Hit Points** 37 (5d8 + 15) 
- **Speed** 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 6 (-2)|19 (+4)|16 (+3)|16 (+3)|15 (+2)|14 (+2)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Deception](/Mechanics/CLI/skills.md#Deception) +6, [Intimidation](/Mechanics/CLI/skills.md#Intimidation) +4, [Perception](/Mechanics/CLI/skills.md#Perception) +4
- **Senses** [darkvision](/Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception 14
- **Damage Resistances** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](/Mechanics/CLI/conditions.md#Charmed), [exhaustion](/Mechanics/CLI/conditions.md#Exhaustion), [frightened](/Mechanics/CLI/conditions.md#Frightened), [grappled](/Mechanics/CLI/conditions.md#Grappled), [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed), [petrified](/Mechanics/CLI/conditions.md#Petrified), [poisoned](/Mechanics/CLI/conditions.md#Poisoned), [prone](/Mechanics/CLI/conditions.md#Prone), [restrained](/Mechanics/CLI/conditions.md#Restrained)
- **Languages** Abyssal, Common, telepathy 120 ft.
- **Challenge** 4

## Traits

***Incorporeal Movement.*** The dybbuk can move through other creatures and objects as if they were difficult terrain. It takes 5 (`1d10`) force damage if it ends its turn inside an object.

***Magic Resistance.*** The dybbuk has advantage on saving throws against spells and other magical effects.

## Actions

***Tentacle.*** *Melee Weapon Attack:* `+6` to hit, reach 5 ft., one target. *Hit:* 13 (`2d8 + 4`) necrotic damage. If the target is a creature, its hit point maximum is also reduced by 3 (`1d6`). This reduction lasts until the target finishes a short or long rest. The target dies if its hit point maximum is reduced to 0.

***Possess Corpse (Recharge 6).*** The dybbuk disappears into an intact corpse within 5 feet of it that belonged to a Large or smaller Beast or Humanoid. The dybbuk gains 20 temporary hit points. While possessing the corpse, the dybbuk adopts the corpse's size and can't use Incorporeal Movement. Its game statistics otherwise remain the same. The possession lasts until the temporary hit points are lost or the dybbuk ends it as a bonus action. When the possession ends, the dybbuk appears in an unoccupied space within 5 feet of the corpse.

***Spellcasting.*** The dybbuk casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 12):

**At will:** [dimension door](/Mechanics/CLI/spells/dimension-door-xphb.md)

**3/day:** [phantasmal force](/Mechanics/CLI/spells/phantasmal-force-xphb.md)

## Bonus Actions

***Control Corpse.*** While Possess Corpse is active, the dybbuk makes the corpse do something unnatural, such as vomit blood, twist its head all the way around, or cause a quadruped to move as a biped. Any Beast or Humanoid that sees this behavior must succeed on a DC 12 Wisdom saving throw or become [frightened](/Mechanics/CLI/conditions.md#Frightened) of the dybbuk for 1 minute. The [frightened](/Mechanics/CLI/conditions.md#Frightened) creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that succeeds on a saving throw against this ability is immune to Control Corpse for 24 hours.
```

^statblock

## Environment

desert, urban

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 113_
