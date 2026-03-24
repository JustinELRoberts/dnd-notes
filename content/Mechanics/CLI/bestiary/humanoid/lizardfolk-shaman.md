---
publish: true
aliases:
  - Lizardfolk Shaman
created: 2026-03-09T12:15:34.052-04:00
modified: 2026-03-09T12:15:34.052-04:00
published: 2026-03-09T12:15:34.052-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mm
  - ttrpg-cli/monster/cr/2
  - ttrpg-cli/monster/environment/forest
  - ttrpg-cli/monster/environment/swamp
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid/lizardfolk
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Lizardfolk Shaman

_Source: Monster Manual p. 205_\
![](Mechanics/CLI/bestiary/humanoid/img/lizardfolk.webp#right)

Lizardfolk are primitive reptilian humanoids that lurk in the swamps and jungles of the world. Their hut villages thrive in forbidding grottos, half-sunken ruins, and watery caverns.

## Territorial Xenophobes

Lizardfolk deal and trade with other races only rarely. Fiercely territorial, they use camouflaged scouts to guard the perimeter of their domain. When unwelcome visitors are detected, a tribe sends a hunting band to harass or drive the trespassers off, or tricks them into blundering into the lairs of crocodiles and other dangerous creatures.

Lizardfolk have no notion of traditional morality, and they find the concepts of good and evil utterly alien. Truly neutral creatures, they kill when it is expedient and do whatever it takes to survive.

Lizardfolk rarely stray beyond their claimed hunting grounds. Any creature that enters their territory is fair game to be stalked, killed, and devoured. They make no distinction between humanoids, beasts, and monsters. Similarly, lizardfolk don't like reaching too far beyond their borders, where they could easily become the hunted instead of the hunters.

Occasions might arise when lizardfolk will form alliances with their neighbors. These lizardfolk usually learn firsthand that humans, dwarves, halflings, and elves can sometimes prove helpful or trustworthy. Once lizardfolk forge ties with outsiders, they are steadfast and fierce allies.

## Great Feasts and Sacrifices

Lizardfolk are omnivorous, but they have a taste for humanoid flesh. Prisoners are often taken back to their camps to become the centerpieces of great feasts and rites involving dancing, storytelling, and ritual combat.

Victims are either cooked and eaten by the tribe, or are sacrificed to Semuanya, the lizardfolk god.

## Canny Crafters

Though they aren't skilled artisans, lizardfolk craft tools and ornamental jewelry out of the bones of their kills, and they use the hides and shells of dead monsters to create shields.

## Lizardfolk Leaders

Lizardfolk respect and fear magic with a religious awe. Lizardfolk shamans lead their tribes, overseeing rites and ceremonies performed to honor Semuanya. From time to time, however, a lizardfolk tribe produces a powerful figure touched not by Semuanya but by Sess'inek-a reptilian demon lord who seeks to corrupt and control the lizardfolk.

Lizardfolk born in Sess'inek's image are larger and more cunning than other lizardfolk, and are thoroughly evil. These lizard kings and queens dominate lizardfolk tribes, usurping a shaman's authority and inspiring uncharacteristic aggression among their subjects.

## Dragon Worshipers

Lizardfolk speak Draconic, which they are thought to have learned from dragons in ancient times. A tribe that wanders into the territory of a dragon will offer it tribute to win its favor. An evil dragon might exploit lizardfolk for its own vile ends, turning them into raiders and plunderers.

> [!quote] A quote from A merchant's account of his experience with the lizardfolk tribes of the Lizard Marsh
>
> In all my dealings with the lizardfolk, I was never able to tell what they were thinking. Their reptilian eyes belied no hint of their intentions. I gave them supplies. They gave me the willies.

## Statblock

```ad-statblock
title: Lizardfolk Shaman
![](Mechanics/CLI/bestiary/humanoid/token/lizardfolk-shaman.webp#token)
*Medium humanoid (lizardfolk), Neutral*

- **Armor Class** 13 (natural armor)
- **Hit Points** 27 (`5d8 + 5`) 
- **Speed** 30 ft., swim 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|10 (+0)|13 (+1)|10 (+0)|15 (+2)| 8 (-1)|

- **Proficiency Bonus** +2
- **Saving Throws** ⏤
- **Skills** [Perception](Mechanics/CLI/rules/skills.md#Perception) +4, [Stealth](Mechanics/CLI/rules/skills.md#Stealth) +4, [Survival](Mechanics/CLI/rules/skills.md#Survival) +6
- **Senses** passive Perception 14
- **Languages** Draconic
- **Challenge** 2

## Traits

***Spellcasting (Lizardfolk Form Only).*** The lizardfolk is a 5th-level spellcaster. Its spellcasting ability is Wisdom (spell save DC 12, `+4` to hit with spell attacks). The lizardfolk has the following druid spells prepared:

**Cantrips (at will):** [druidcraft](Mechanics/CLI/spells/druidcraft-xphb.md), [produce flame](Mechanics/CLI/spells/produce-flame-xphb.md), [thorn whip](Mechanics/CLI/spells/thorn-whip-xphb.md)

**1st level (4 slots):** [entangle](Mechanics/CLI/spells/entangle-xphb.md), [fog cloud](Mechanics/CLI/spells/fog-cloud-xphb.md)

**2nd level (3 slots):** [heat metal](Mechanics/CLI/spells/heat-metal-xphb.md), [spike growth](Mechanics/CLI/spells/spike-growth-xphb.md)

**3rd level (2 slots):** [conjure animals](Mechanics/CLI/spells/conjure-animals-xphb.md) (reptiles only), [plant growth](Mechanics/CLI/spells/plant-growth-xphb.md)

***Hold Breath.*** The lizardfolk can hold its breath for 15 minutes.

## Actions

***Multiattack (Lizardfolk Form Only).*** The lizardfolk makes two attacks: one with its bite and one with its claws.

***Bite.*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one target. *Hit:* 5 (`1d6 + 2`) piercing damage, or 7 (`1d10 + 2`) piercing damage in [crocodile](Mechanics/CLI/bestiary/beast/crocodile-xmm.md) form. If the lizardfolk is in crocodile form and the target is a Large or smaller creature, the target is [grappled](Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 12). Until this grapple ends, the target is [restrained](Mechanics/CLI/rules/conditions.md#Restrained), and the lizardfolk can't bite another target. If the lizardfolk reverts to its true form, the grapple ends.

***Claws (Lizardfolk Form Only).*** *Melee Weapon Attack:* `+4` to hit, reach 5 ft., one target. *Hit:* 4 (`1d4 + 2`) slashing damage.

***Change Shape (Recharges after a Short or Long Rest).*** The lizardfolk magically polymorphs into a [crocodile](Mechanics/CLI/bestiary/beast/crocodile-xmm.md), remaining in that form for up to 1 hour. It can revert to its true form as a bonus action. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.
```

^statblock

## Environment

forest, swamp
