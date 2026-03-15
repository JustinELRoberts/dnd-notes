---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct
aliases:
- "Scarecrow"
---
# Scarecrow
*Source: Monster Manual p. 268*  
![](Mechanics/CLI/bestiary/construct/img/scarecrow.webp#right)

At harvest time, when death revisits the twilit world and summer's blossoms bow their withered heads, eerie scarecrows loom in silent vigil over empty fields. With immortal patience, these stoic sentinels hold their posts through wind, storm, and flood, bound to their master's command, eager to terrify prey with its sackcloth visage and rend victims with its razor-sharp claws.

## Spirit-Powered Constructs

A scarecrow is animated by the bound spirit of a slain evil creature, granting it purpose and mobility. It is this uncanny presence from beyond death that allows a scarecrow to inspire fear in those it gazes upon. Hags and witches often bind scarecrows with the spirits of demons, but any evil spirit will do. Although aspects of the spirit's personality might surface, a scarecrow's spirit doesn't recall the memories it had as a creature, and its will is focused solely on serving its creator. If its creator dies, the spirit inhabiting a scarecrow either continues to follow its last commands, seeks revenge for its creator's death, or destroys itself.

## Statblock

```ad-statblock
title: Scarecrow
![](Mechanics/CLI/bestiary/construct/token/scarecrow.webp#token)
*Medium construct, Chaotic Evil*

- **Armor Class** 11 
- **Hit Points** 36 (`8d8`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|13 (+1)|11 (+0)|10 (+0)|10 (+0)|13 (+1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive Perception 10
- **Damage Vulnerabilities** fire
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks
- **Damage Immunities** poison
- **Condition Immunities** [charmed](Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned), [unconscious](Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** understands the languages of its creator but can't speak
- **Challenge** 1

## Traits

***False Appearance.*** While the scarecrow remains motionless, it is indistinguishable from an ordinary, inanimate scarecrow.

## Actions

***Multiattack.*** The scarecrow makes two claw attacks.

***Claw.*** *Melee Weapon Attack:* `+3` to hit, reach 5 ft., one target. *Hit:* 6 (`2d4 + 1`) slashing damage. If the target is a creature, it must succeed on a DC 11 Wisdom saving throw or be [frightened](Mechanics/CLI/rules/conditions.md#Frightened) until the end of the scarecrow's next turn.

***Terrifying Glare.*** The scarecrow targets one creature it can see within 30 feet of it. If the target can see the scarecrow, the target must succeed on a DC 11 Wisdom saving throw or be magically [frightened](Mechanics/CLI/rules/conditions.md#Frightened) until the end of the scarecrow's next turn. The [frightened](Mechanics/CLI/rules/conditions.md#Frightened) target is [paralyzed](Mechanics/CLI/rules/conditions.md#Paralyzed).
```
^statblock

## Environment

grassland