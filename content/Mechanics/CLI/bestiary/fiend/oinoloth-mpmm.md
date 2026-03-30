---
publish: true
aliases:
  - Oinoloth
created: 2026-03-29T21:53:55.954-04:00
modified: 2026-03-29T21:53:55.954-04:00
published: 2026-03-29T21:53:55.954-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/12
  - ttrpg-cli/monster/environment/desert
  - ttrpg-cli/monster/environment/underdark
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/fiend/yugoloth
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Oinoloth (MPMM)
ac: 17
hp: 119
modifier: 3
hit_dice: 14d8 + 56
cr: "12"
stats:
  - 19
  - 17
  - 18
  - 17
  - 16
  - 19
source:
  - MPMM
---

# Oinoloth

![](Mechanics/CLI/bestiary/fiend/img/oinoloth.webp#right)
Grim specters of death, oinoloths bring pestilence wherever they go. When armies recognize their awful forms, their mere appearance causes soldiers to break ranks and flee, lest they succumb to one of the awful plagues that oinoloths let loose.

Oinoloths solve thorny problems by killing everyone involved. They are typically hired as a last resort when a siege has gone on too long or an army has proven too strong to overcome. Once summoned, oinoloths stalk the killing field, poisoning the ground and sickening creatures they encounter. Sometimes they might be hired to lift the very plagues they spread, but the price for such work is high, and the effort turns the creatures they save into debilitated wrecks.

```ad-statblock
title: Oinoloth
![](/Mechanics/CLI/bestiary/fiend/token/oinoloth-mpmm.webp#token)
*Medium fiend (yugoloth), Typically  Neutral Evil*

- **Armor Class** 17 (natural armor)
- **Hit Points** 119 (14d8 + 56) 
- **Speed** 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|19 (+4)|17 (+3)|18 (+4)|17 (+3)|16 (+3)|19 (+4)|

- **Proficiency Bonus** +4
- **Saving Throws** Constitution +8, Wisdom +7
- **Skills** [Deception](/Mechanics/CLI/skills.md#Deception) +8, [Intimidation](/Mechanics/CLI/skills.md#Intimidation) +8, [Perception](/Mechanics/CLI/skills.md#Perception) +7
- **Senses** [blindsight](/Mechanics/CLI/senses.md#Blindsight) 60 ft., [darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception 17
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](/Mechanics/CLI/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 12

## Traits

***Magic Resistance.*** The oinoloth has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The oinoloth makes two Claw attacks, and it uses Spellcasting or Teleport.

***Claw.*** *Melee Weapon Attack:* `+8` to hit, reach 5 ft., one target. *Hit:* 14 (`3d6 + 4`) slashing damage plus 22 (`4d10`) necrotic damage.

***Corrupted Healing (Recharge 6).*** The oinoloth touches one willing creature within 5 feet of it. The target regains all its hit points. In addition, the oinoloth can end one disease on the target or remove one of the following conditions from it: [blinded](/Mechanics/CLI/conditions.md#Blinded), [deafened](/Mechanics/CLI/conditions.md#Deafened), [paralyzed](/Mechanics/CLI/conditions.md#Paralyzed), or [poisoned](/Mechanics/CLI/conditions.md#Poisoned). The target then gains 1 level of [exhaustion](/Mechanics/CLI/conditions.md#Exhaustion), and its hit point maximum is reduced by 7 (`2d6`). This reduction can be removed only by a [wish](/Mechanics/CLI/spells/wish-xphb.md) spell or by casting [greater restoration](/Mechanics/CLI/spells/greater-restoration-xphb.md) on the target three times within the same hour. The target dies if its hit point maximum is reduced to 0.

***Teleport.*** The oinoloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.

***Spellcasting.*** The oinoloth casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 16):

**At will:** [darkness](/Mechanics/CLI/spells/darkness-xphb.md), [detect magic](/Mechanics/CLI/spells/detect-magic-xphb.md), [dispel magic](/Mechanics/CLI/spells/dispel-magic-xphb.md), [hold monster](/Mechanics/CLI/spells/hold-monster-xphb.md), [invisibility](/Mechanics/CLI/spells/invisibility-xphb.md) (self only)

**1/day each:** [feeblemind](/Mechanics/CLI/spells/befuddlement-xphb.md), [globe of invulnerability](/Mechanics/CLI/spells/globe-of-invulnerability-xphb.md)

## Bonus Actions

***Bringer of Plagues (Recharge 5-6).*** The oinoloth blights the area in a 30-foot-radius sphere centered on itself. The blight lasts for 24 hours. While the area is blighted, all normal plants there wither and die.

Furthermore, when a creature moves into the blighted area or starts its turn there, that creature must make a DC 16 Constitution saving throw. On a failed save, the creature takes 14 (`4d6`) poison damage and is [poisoned](/Mechanics/CLI/conditions.md#Poisoned). On a successful save, the creature is immune to the oinoloth's Bringer of Plagues for the next 24 hours.

The [poisoned](/Mechanics/CLI/conditions.md#Poisoned) creature can't regain hit points. After every 24 hours that elapse, the [poisoned](/Mechanics/CLI/conditions.md#Poisoned) creature can repeat the saving throw. On a failed save, the creature's hit point maximum is reduced by 5 (`1d10`). This reduction lasts until the poison ends, and the target dies if its hit point maximum is reduced to 0. The poison ends after the creature successfully saves against it three times.
```

^statblock

## Environment

desert, underdark

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 202_
