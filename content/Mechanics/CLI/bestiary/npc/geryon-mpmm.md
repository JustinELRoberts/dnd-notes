---
publish: true
aliases:
  - Geryon
created: 2026-03-09T12:15:33.954-04:00
modified: 2026-03-09T12:15:33.954-04:00
published: 2026-03-09T12:15:33.954-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/22
  - ttrpg-cli/monster/size/huge
  - ttrpg-cli/monster/type/fiend/devil
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Geryon

_Source: Mordenkainen Presents: Monsters of the Multiverse p. 136_\
![](Mechanics/CLI/bestiary/npc/img/geryon.webp#right)

Geryon is locked in an endless struggle with Levistus for control of Stygia. The two have fought for centuries, each displacing the other innumerable times. Currently, Levistus claims lordship over Stygia, but he has been trapped in an enormous block of ice at the command of Asmodeus. In response, Geryon is marshaling his followers, hoping to use this opportunity to replace his hated rival.

Among the archdevils, Geryon is known for his martial prowess. He is a ferocious hunter and a relentless tracker. He often joins his troops in battle; he loves to feel flesh and steel sundered beneath his claws and to taste his foes' blood. Yet Geryon's ferocity has also limited his ability to collect souls and forge an effective hierarchy. Sages who study the Nine Hells believe the battle for control of Stygia is a test staged by Asmodeus in hopes of purging the worst impulses from both Geryon and Levistus—or discovering a competent replacement for both.

## Cultists of Geryon

> [!note]
> See the Cult of Geryon entry.

## Geryon's Lair

Geryon has recently reclaimed his ancient fortress, Coldsteel, a sprawling complex that rises from the icy center of Stygia. He roams the passages, spitting oaths of vengeance against Asmodeus and hatching schemes to reclaim his standing from Levistus. The challenge rating of Geryon is 23 (50,000 XP) when he's encountered in his lair.

## Statblock

```ad-statblock
title: Geryon
![](Mechanics/CLI/bestiary/npc/token/geryon-mpmm.webp#token)
*Huge fiend (devil), Lawful Evil*

- **Armor Class** 19 (natural armor)
- **Hit Points** 300 (`24d12 + 144`) 
- **Speed** 30 ft., fly 50 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|29 (+9)|17 (+3)|22 (+6)|19 (+4)|16 (+3)|23 (+6)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +10, Constitution +13, Wisdom +10, Charisma +13
- **Skills** [Deception](Mechanics/CLI/rules/skills.md#Deception) +13, [Intimidation](Mechanics/CLI/rules/skills.md#Intimidation) +13, [Perception](Mechanics/CLI/rules/skills.md#Perception) +10
- **Senses** [truesight](Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive Perception 20
- **Damage Resistances** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
- **Damage Immunities** cold, fire, poison
- **Condition Immunities** [charmed](Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 22

## Traits

***Legendary Resistance (3/Day).*** If Geryon fails a saving throw, he can choose to succeed instead.

***Magic Resistance.*** Geryon has advantage on saving throws against spells and other magical effects.

***Regeneration.*** Geryon regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Geryon dies only if he starts his turn with 0 hit points and doesn't regenerate.

## Actions

***Multiattack.*** Geryon makes one Claw attack and one Stinger attack.

***Claw.*** *Melee Weapon Attack:* `+16` to hit, reach 15 ft., one target. *Hit:* 23 (`4d6 + 9`) cold damage. If the target is Large or smaller, it is [grappled](Mechanics/CLI/rules/conditions.md#Grappled) (DC 24), and it is [restrained](Mechanics/CLI/rules/conditions.md#Restrained) until the grapple ends. Geryon can grapple one creature at a time. If the target is already [grappled](Mechanics/CLI/rules/conditions.md#Grappled) by Geryon, the target takes an extra 27 (`6d8`) cold damage.

***Stinger.*** *Melee Weapon Attack:* `+16` to hit, reach 20 ft., one creature. *Hit:* 14 (`2d4 + 9`) force damage, and the target must succeed on a DC 21 Constitution saving throw or take 13 (`2d12`) poison damage and become [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) until it finishes a short or long rest. The target's hit point maximum is reduced by an amount equal to half the poison damage taken. This reduction lasts until the [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) condition is removed. The target dies if its hit point maximum is reduced to 0.

***Teleport.*** Geryon teleports, along with any equipment he is wearing and carrying, up to 120 feet to an unoccupied space he can see.

***Spellcasting.*** Geryon casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 21):

**At will:** [alter self](Mechanics/CLI/spells/alter-self-xphb.md) (can become Medium when changing his appearance), [detect magic](Mechanics/CLI/spells/detect-magic-xphb.md), [ice storm](Mechanics/CLI/spells/ice-storm-xphb.md), [invisibility](Mechanics/CLI/spells/invisibility-xphb.md) (self only), [locate object](Mechanics/CLI/spells/locate-object-xphb.md), [suggestion](Mechanics/CLI/spells/suggestion-xphb.md), [wall of ice](Mechanics/CLI/spells/wall-of-ice-xphb.md)

**1/day:** [banishment](Mechanics/CLI/spells/banishment-xphb.md)

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, Geryon can expend a use to take one of the following actions. Geryon regains all expended uses at the start of each of their turns.

***Infernal Glare.*** Geryon targets one creature he can see within 60 feet of him. The target must succeed on a DC 23 Wisdom saving throw or become [frightened](Mechanics/CLI/rules/conditions.md#Frightened) of Geryon until the end of its next turn.

***Teleport.*** Geryon uses Teleport.

***Swift Sting (Costs 2 Actions).*** Geryon makes one Stinger attack.

## Lair Actions

On initiative count 20 (losing initiative ties), Geryon can take one of the following lair actions; he can't take the same lair action two rounds in a row:

- **Banish.** Geryon casts the banishment spell.  
- **Chill Blast.** Geryon causes a blast of cold to burst from the ground at a point he can see within 120 feet of him. The cold fills a cube, 10 feet on each side, centered on that point. Each creature in that area must succeed on a DC 21 Constitution saving throw or take 28 (`8d6`) cold damage.  
- **Hateful Restraints.** Geryon targets one creature he can see within 60 feet of him. The target must succeed on a DC 21 Wisdom saving throw or become [restrained](Mechanics/CLI/rules/conditions.md#Restrained) for 1 minute. The target can end the effect on itself if it deals any damage to one or more of its allies.  

## Regional Effects

The region containing Geryon's lair is warped by his magic, creating one or more of the following effects:

- **Chilling Wind.** Freezing strong winds howl around the area within 1 mile of the lair.  
- **Enervating Screams.** Howls and screams fill the air within 1 mile of the lair. Any creature that finishes a short or long rest in this area must succeed on a DC 21 Wisdom saving throw or derive no benefit from the rest.  
- **Hellish Doorways.** Sapient creatures within 1 mile of the lair frequently see shimmering portals leading to places they consider safe. Passing through a portal always deposits a traveler somewhere in Stygia.  

If Geryon dies, these effects fade over the course of `1d10` days.
```

^statblock
