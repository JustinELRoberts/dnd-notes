---
publish: true
aliases:
  - Blackguard
created: 2026-03-29T21:53:55.929-04:00
modified: 2026-03-29T21:53:55.929-04:00
published: 2026-03-29T21:53:55.929-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/8
  - ttrpg-cli/monster/environment/underdark
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid/paladin
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Blackguard (MPMM)
ac: 18
hp: 119
modifier: 0
hit_dice: 14d8 + 56
cr: "8"
stats:
  - 18
  - 11
  - 18
  - 11
  - 14
  - 15
source:
  - MPMM
  - VGM
---

# Blackguard

![](Mechanics/CLI/bestiary/humanoid/img/blackguard.webp#right)
Blackguards are paladins who broke their sacred oaths and now indulge their own villainous ambitions. They consort with Fiends and Undead, and they reject many of the goodly things from their former lives.

Blackguards often adorn their armor and weapons with dread accoutrements or are marked by eerie phenomena. You may choose a blackguard's accoutrement or roll on the Blackguard Accoutrements table to determine it.

**Blackguard Accoutrements**

| dice: d8 | Accoutrement |
|----------|--------------|
| 1 | Armor etched with stylized depictions of gruesome battles |
| 2 | Helm wrought in the shape of a demonic boar |
| 3 | Helm wrought to resemble a death mask |
| 4 | Cloak decorated with bloody handprints |
| 5 | Curls of inky smoke seeping from armor at the joints |
| 6 | Dozens of flies buzzing about the blackguard |
| 7 | Severed hand hanging from a chain around the blackguard's neck |
| 8 | Glaive adorned with a length of cloth bearing the words "I choose violence" |
^blackguard-accoutrements

```ad-statblock
title: Blackguard
![](/Mechanics/CLI/bestiary/humanoid/token/blackguard-mpmm.webp#token)
*Medium humanoid (paladin), Typically  Neutral Evil*

- **Armor Class** 18 ([plate](/Mechanics/CLI/items/plate-armor.md))
- **Hit Points** 119 (14d8 + 56) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|18 (+4)|11 (+0)|18 (+4)|11 (+0)|14 (+2)|15 (+2)|

- **Proficiency Bonus** +3
- **Saving Throws** Wisdom +5, Charisma +5
- **Skills** [Athletics](/Mechanics/CLI/skills.md#Athletics) +7, [Deception](/Mechanics/CLI/skills.md#Deception) +5, [Intimidation](/Mechanics/CLI/skills.md#Intimidation) +5
- **Senses** passive Perception 12
- **Languages** any one language (usually Common)
- **Challenge** 8

## Actions

***Multiattack.*** The blackguard makes three attacks, using Glaive, Shortbow, or both.

***Glaive.*** *Melee Weapon Attack:* `+7` to hit, reach 10 ft., one target. *Hit:* 9 (`1d10 + 4`) slashing damage plus 9 (`2d8`) necrotic damage.

***Shortbow.*** *Ranged Weapon Attack:* `+3` to hit, range 80/320 ft., one target. *Hit:* 5 (`1d6 + 2`) piercing damage.

***Dreadful Aspect (Recharges after a Short or Long Rest).*** Each enemy within 30 feet of the blackguard must succeed on a DC 13 Wisdom saving throw or be [frightened](/Mechanics/CLI/conditions.md#Frightened) of the blackguard for 1 minute. If a [frightened](/Mechanics/CLI/conditions.md#Frightened) target ends its turn more than 30 feet away from the blackguard, the target can repeat the saving throw, ending the effect on itself on a success.

***Spellcasting.*** The blackguard casts one of the following spells, using Charisma as the spellcasting ability (spell save DC 13):

**2/day each:** [command](/Mechanics/CLI/spells/command-xphb.md), [dispel magic](/Mechanics/CLI/spells/dispel-magic-xphb.md), [find steed](/Mechanics/CLI/spells/find-steed-xphb.md)

## Bonus Actions

***Smite.*** Immediately after the blackguard hits a target with an attack roll, the blackguard can force that target to make a DC 13 Constitution saving throw. On a failed save, the target suffers one of the following effects of the blackguard's choice:

***Blind.*** The target is [blinded](/Mechanics/CLI/conditions.md#Blinded) for 1 minute. The [blinded](/Mechanics/CLI/conditions.md#Blinded) target can repeat the save at the end of each of its turns, ending the effect on itself on a success.

***Shove.*** The target is pushed up to 10 feet away and knocked [prone](/Mechanics/CLI/conditions.md#Prone).
```

^statblock

## Environment

underdark, urban

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 63, Volo's Guide to Monsters p. 211_
