---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/yugoloth
aliases:
- "Merrenoloth"
---
# Merrenoloth
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 180*  
![](Mechanics/CLI/bestiary/fiend/img/merrenoloth.webp#right)

The grim captains of the ferries on the River Styx, merrenoloths can navigate safely through the worst storms and always stay on course. Wielding fiery oars, merrenoloths strike fear into anyone who forcefully boards their vessels.

```ad-statblock
title: Merrenoloth
![](Mechanics/CLI/bestiary/fiend/token/merrenoloth-mpmm.webp#token)
*Medium fiend (yugoloth), Typically  Neutral Evil*

- **Armor Class** 13 
- **Hit Points** 40 (`9d8`) 
- **Speed** 30 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 8 (-1)|17 (+3)|10 (+0)|17 (+3)|14 (+2)|11 (+0)|

- **Proficiency Bonus** +2
- **Saving Throws** Dexterity +5, Intelligence +5
- **Skills** [History](Mechanics/CLI/rules/skills.md#History) +5, [Nature](Mechanics/CLI/rules/skills.md#Nature) +5, [Perception](Mechanics/CLI/rules/skills.md#Perception) +4, [Survival](Mechanics/CLI/rules/skills.md#Survival) +4
- **Senses** [blindsight](Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., [darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 14
- **Damage Resistances** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** acid, poison
- **Condition Immunities** [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Infernal, telepathy 60 ft.
- **Challenge** 3

## Traits

***Magic Resistance.*** The merrenoloth has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The merrenoloth makes one Oar attack and uses Fear Gaze.

***Oar.*** *Melee Weapon Attack:* `+5` to hit, reach 5 ft., one target. *Hit:* 8 (`2d4 + 3`) fire damage.

***Fear Gaze.*** The merrenoloth targets one creature it can see within 60 feet of it. The target must succeed on a DC 13 Wisdom saving throw or become [frightened](Mechanics/CLI/rules/conditions.md#Frightened) of the merrenoloth for 1 minute. The [frightened](Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Spellcasting.*** The merrenoloth casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability (spell save DC 13):

**At will:** [charm person](Mechanics/CLI/spells/charm-person-xphb.md), [darkness](Mechanics/CLI/spells/darkness-xphb.md), [detect magic](Mechanics/CLI/spells/detect-magic-xphb.md), [dispel magic](Mechanics/CLI/spells/dispel-magic-xphb.md), [gust of wind](Mechanics/CLI/spells/gust-of-wind-xphb.md)

**3/day:** [control water](Mechanics/CLI/spells/control-water-xphb.md)

## Bonus Actions

***Teleport.*** The merrenoloth teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.

## Lair Actions

On initiative count 20 (losing initiative ties) while captaining a vessel, the merrenoloth can take one of the following lair actions; it can't take the same lair action two rounds in a row:

- **Gale.** The air within 60 feet of the vessel is filled with wind. Until initiative count 20 on the next round, that area is difficult terrain, and when a Medium or smaller creature flies into that area or starts its turn flying there, it must succeed on a DC 13 Strength saving throw or be knocked [prone](Mechanics/CLI/rules/conditions.md#Prone).  
- **Propel.** A strong wind propels the vessel, increasing its speed by 30 feet until initiative count 20 on the next round.  
- **Repair.** The vessel regains 22 (`4d10`) hit points.  

## Regional Effects

A merrenoloth imbues its vessel with magic that creates one or more of the following effects:

- **Unerring.** The vessel always stays on course to the destination the merrenoloth names.  
- **Unsinkable.** The vessel doesn't sink even if its hull is breached.  

If the merrenoloth dies, these effects fade over the course of `1d6` hours.
```
^statblock

## Environment

coastal