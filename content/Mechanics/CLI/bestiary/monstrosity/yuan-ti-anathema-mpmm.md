---
publish: true
aliases:
  - Yuan-ti Anathema
created: 2026-03-09T12:15:33.846-04:00
modified: 2026-03-09T12:15:33.846-04:00
published: 2026-03-09T12:15:33.846-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/12
  - ttrpg-cli/monster/environment/desert
  - ttrpg-cli/monster/environment/forest
  - ttrpg-cli/monster/environment/underdark
  - ttrpg-cli/monster/size/huge
  - ttrpg-cli/monster/type/monstrosity
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Yuan-ti Anathema

_Source: Mordenkainen Presents: Monsters of the Multiverse p. 272, Volo's Guide to Monsters p. 202_\
![](Mechanics/CLI/bestiary/monstrosity/img/yuan-ti-anathema.webp#right)

As part of their quest for godhood, a yuan-ti abomination might perform a ritual that, if successful, transforms them into an even greater form: a yuan-ti anathema. This ritual demands the sacrifice of hundreds of snakes and requires the abomination to bathe in the blood of their enemies. The transformation is quick but painful.

Anathemas consider themselves demigods on the path to greater divinity. They demand obeisance from weaker creatures and use every resource at their disposal to war against neighbors, seeking the captives, sacrifices, glory, and riches the anathemas believe they need to achieve true divinity.

Anathemas don't age, allowing them to pursue their goals until the end of days. Truly powerful ones might rule multiple yuan-ti cities and bring entire regions under their control.

```ad-statblock
title: Yuan-ti Anathema
![](Mechanics/CLI/bestiary/monstrosity/token/yuan-ti-anathema-mpmm.webp#token)
*Huge monstrosity, Typically  Neutral Evil*

- **Armor Class** 16 (natural armor)
- **Hit Points** 189 (`18d12 + 72`) 
- **Speed** 40 ft., climb 40 ft., swim 40 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|23 (+6)|13 (+1)|19 (+4)|19 (+4)|17 (+3)|20 (+5)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** [Perception](Mechanics/CLI/rules/skills.md#Perception) +11, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +5
- **Senses** [blindsight](Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., [darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 21
- **Damage Resistances** acid, fire, lightning
- **Damage Immunities** poison
- **Condition Immunities** [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** Abyssal, Common, Draconic
- **Challenge** 12

## Traits

***Magic Resistance.*** The anathema has advantage on saving throws against spells and other magical effects.

***Ophidiophobia Aura.*** Any creature of the anathema's choice, other than a snake or a yuan-ti, that starts its turn within 30 feet of the anathema must succeed on a DC 17 Wisdom saving throw or become [frightened](Mechanics/CLI/rules/conditions.md#Frightened) of snakes and yuan-ti. A [frightened](Mechanics/CLI/rules/conditions.md#Frightened) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a target's saving throw is successful or the effect ends for it, the target is immune to this anathema's aura for the next 24 hours.

***Six Heads.*** The anathema has advantage on saves against being [blinded](Mechanics/CLI/rules/conditions.md#Blinded), [charmed](Mechanics/CLI/rules/conditions.md#Charmed), [deafened](Mechanics/CLI/rules/conditions.md#Deafened), [frightened](Mechanics/CLI/rules/conditions.md#Frightened), [stunned](Mechanics/CLI/rules/conditions.md#Stunned), or knocked [unconscious](Mechanics/CLI/rules/conditions.md#Unconscious).

## Actions

***Multiattack (Anathema Form Only).*** The anathema makes two Claw attacks and one Flurry of Bites attack.

***Claw (Anathema Form Only).*** *Melee Weapon Attack:* `+10` to hit, reach 10 ft., one target. *Hit:* 13 (`2d6 + 6`) slashing damage.

***Flurry of Bites (Anathema Form Only).*** *Melee Weapon Attack:* `+10` to hit, reach 10 ft., one creature. *Hit:* 27 (`6d6 + 6`) piercing damage plus 14 (`4d6`) poison damage.

***Constrict (Snake Form Only).*** *Melee Weapon Attack:* `+10` to hit, reach 15 ft., one Large or smaller creature. *Hit:* 16 (`3d6 + 6`) bludgeoning damage plus 7 (`2d6`) acid damage, and the target is [grappled](Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16). Until this grapple ends, the target is [restrained](Mechanics/CLI/rules/conditions.md#Restrained), and it takes 16 (`3d6 + 6`) bludgeoning damage plus 7 (`2d6`) acid damage at the start of each of its turns. The anathema can constrict only one creature at a time.

***Spellcasting (Anathema Form Only).*** The anathema casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 17):

**At will:** [animal friendship](Mechanics/CLI/spells/animal-friendship-xphb.md) (snakes only)

**3/day each:** [darkness](Mechanics/CLI/spells/darkness-xphb.md), [entangle](Mechanics/CLI/spells/entangle-xphb.md), [fear](Mechanics/CLI/spells/fear-xphb.md), [polymorph](Mechanics/CLI/spells/polymorph-xphb.md), [suggestion](Mechanics/CLI/spells/suggestion-xphb.md)

## Bonus Actions

***Change Shape.*** The anathema transforms into a Huge constrictor snake or back into its true form. Its statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```

^statblock

## Environment

desert, forest, underdark
