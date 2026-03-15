---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpmm
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/gith
aliases:
- "Githzerai Anarch"
---
# Githzerai Anarch
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 142*  
![](Mechanics/CLI/bestiary/humanoid/img/githzerai-anarch.webp#right)

Anarchs are githzerai sages and mystics who lead communities and maintain the adamantine citadels that serve as strong points in Limbo and on other planes. They have formidable psionic capabilities and are able to manipulate the unformed substance of their adopted plane with a thought.

## An Anarch's Lair

In Limbo, githzerai anarchs create islands of tranquility in this turbulent plane. An anarch can use its psionic power to give form to formless substance, creating mountains, lakes, and structures to serve as a foundation for a githzerai community.

The anarch's challenge rating is 17 (18,000 XP) when it's encountered in its lair.

## Githzerai

Githzerai are otherworldly folk with psionic powers who share an ancestral link to githyanki (also in this book). The githzerai followers of the great leader Zaerith Menyar-Ag-Gith are an ascetic people who live apart from the rest of the cosmos, within the confines of fortresses floating through the chaos of Limbo. Instead of imposing their will on other peoples, they focus on controlling and manipulating their endlessly malleable home.

## Statblock

```ad-statblock
title: Githzerai Anarch
![](Mechanics/CLI/bestiary/humanoid/token/githzerai-anarch-mpmm.webp#token)
*Medium humanoid (gith), Any alignment*

- **Armor Class** 20 (psychic defense)
- **Hit Points** 144 (`17d8 + 68`) 
- **Speed** 30 ft., fly 40 ft. (hover)

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|16 (+3)|21 (+5)|18 (+4)|18 (+4)|20 (+5)|14 (+2)|

- **Proficiency Bonus** +5
- **Saving Throws** Strength +8, Dexterity +10, Intelligence +9, Wisdom +10
- **Skills** [Arcana](Mechanics/CLI/rules/skills.md#Arcana) +9, [Insight](Mechanics/CLI/rules/skills.md#Insight) +10, [Perception](Mechanics/CLI/rules/skills.md#Perception) +10
- **Senses** passive Perception 20
- **Languages** Gith
- **Challenge** 16

## Traits

***Legendary Resistance (3/Day).*** If the githzerai fails a saving throw, it can choose to succeed instead.

***Psychic Defense.*** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.

## Actions

***Multiattack.*** The githzerai makes three Unarmed Strike attacks.

***Unarmed Strike.*** *Melee Weapon Attack:* `+10` to hit, reach 5 ft., one target. *Hit:* 9 (`1d8 + 5`) bludgeoning damage plus 18 (`4d8`) psychic damage.

***Spellcasting (Psionics).*** The githzerai casts one of the following spells, requiring no spell components and using Wisdom as the spellcasting ability (spell save DC 18):

**At will:** [mage hand](Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is invisible)

**3/day each:** [see invisibility](Mechanics/CLI/spells/see-invisibility-xphb.md), [telekinesis](Mechanics/CLI/spells/telekinesis-xphb.md)

**1/day each:** [globe of invulnerability](Mechanics/CLI/spells/globe-of-invulnerability-xphb.md), [plane shift](Mechanics/CLI/spells/plane-shift-xphb.md), [wall of force](Mechanics/CLI/spells/wall-of-force-xphb.md)

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, the githzerai anarch can expend a use to take one of the following actions. The githzerai anarch regains all expended uses at the start of each of its turns.

***Strike.*** The githzerai makes one Unarmed Strike attack.

***Teleport.*** The githzerai teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 30 feet of it.

***Change Gravity (Costs 3 Actions).*** The githzerai casts the [reverse gravity](Mechanics/CLI/spells/reverse-gravity-xphb.md) spell, using Wisdom as the spellcasting ability. The spell has the normal effect, except that the githzerai can orient the area in any direction and creatures and objects fall toward the end of the area.

## Lair Actions

On initiative count 20 (losing initiative ties), the anarch can take one of the following lair actions; the anarch can't take the same lair action two rounds in a row:

- **Create Object.** The anarch casts the creation spell (as a 9th-level spell) using the unformed substance of Limbo instead of shadow material. If used in Limbo, the object remains until the anarch's [concentration](Mechanics/CLI/rules/conditions.md#Concentration) is broken, regardless of its composition. If the anarch moves more than 120 feet from the object, the anarch's [concentration](Mechanics/CLI/rules/conditions.md#Concentration) breaks.  
- **Move Object.** The anarch can magically move an object it can see within 150 feet of it by making a Wisdom check with advantage. The DC depends on the object's size: DC 5 for Tiny, DC 10 for Small, DC 15 for Medium, DC 20 for Large, and DC 25 for Huge or larger.  
- **Psionic Bolt.** The anarch casts the lightning bolt spell (at 5th level), but the anarch can change the damage type from lightning to cold, fire, psychic, radiant, or thunder. If the spell deals damage other than fire or lightning, it doesn't ignite flammable objects.  

## Regional Effects

The region containing an anarch's lair is warped by its presence, which creates one or more of the following effects:

- **Form Substance.** In Limbo, the anarch can spend 10 minutes stabilizing a 5-mile area centered on it, causing the unformed substance to take whatever inanimate form the anarch chooses. During that process, the anarch determines the shape and composition of the forms created.  
- **Stabilize Object.** The anarch stabilizes any object created in Limbo and brought to the Material Plane for as long as the anarch remains within 1 mile of it (no action required).  

If the anarch dies, these effects end after `1d6` rounds. All formed substance becomes a chaotic churn of energy and matter, unraveling into unformed substance that dissipates `1d6` rounds later.
```
^statblock