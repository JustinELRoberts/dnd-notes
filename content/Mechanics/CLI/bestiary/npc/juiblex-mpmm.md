---
publish: true
aliases:
  - Juiblex
created: 2026-03-09T12:15:33.816-04:00
modified: 2026-03-09T12:15:33.816-04:00
published: 2026-03-09T12:15:33.816-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/23
  - ttrpg-cli/monster/size/huge
  - ttrpg-cli/monster/type/fiend/demon
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Juiblex
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 160*  
![](Mechanics/CLI/bestiary/npc/img/juiblex.webp#right)

Called the Faceless Lord and the Oozing Hunger in ancient grimoires, Juiblex is demon lord of slime and ooze, a noxious creature that doesn't care about the plots and schemes of others of its kind. It exists only to consume, digesting and transforming living matter into more of itself.

A true horror, Juiblex is a mass of bubbling slime, swirling black and green, with glaring red eyes floating and shifting within it. It can rise up like a 20-foot hill, lashing out with dripping pseudopods to drag victims into its bulk. Those consumed by Juiblex are obliterated.

## Cultists of Juiblex

> [!note]
> See the Cult of Juiblex entry.

## Juiblex's Lair

Juiblex's principal lair is known as the Slime Pits, a realm that Juiblex shares with [Zuggtmoy](Mechanics/CLI/bestiary/npc/zuggtmoy-mpmm.md) (who also appears in this book). This layer of the Abyss, which is also known as Shedaklah, is a bubbling morass of fetid sludge. The landscape is covered in vast expanses of caustic slimes, and strange organic forms rise from the oceans of ooze at Juiblex's command.

Juiblex's challenge rating is 24 (62,000 XP) when encountered in its lair.

## Statblock

```ad-statblock
title: Juiblex
![](Mechanics/CLI/bestiary/npc/token/juiblex-mpmm.webp#token)
*Huge fiend (demon), Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 350 (`28d12 + 168`) 
- **Speed** 30 ft., climb 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|10 (+0)|23 (+6)|20 (+5)|20 (+5)|16 (+3)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +7, Constitution +13, Wisdom +12
- **Skills** [Perception](Mechanics/CLI/rules/skills.md#Perception) +12
- **Senses** [truesight](Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive Perception 22
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** acid; poison; bludgeoning, piercing, slashing that is nonmagical
- **Condition Immunities** [blinded](Mechanics/CLI/rules/conditions.md#Blinded), [charmed](Mechanics/CLI/rules/conditions.md#Charmed), [deafened](Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](Mechanics/CLI/rules/conditions.md#Frightened), [grappled](Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned), [prone](Mechanics/CLI/rules/conditions.md#Prone), [restrained](Mechanics/CLI/rules/conditions.md#Restrained), [stunned](Mechanics/CLI/rules/conditions.md#Stunned), [unconscious](Mechanics/CLI/rules/conditions.md#Unconscious)
- **Languages** all, telepathy 120 ft.
- **Challenge** 23

## Traits

***Foul.*** Any creature other than an Ooze that starts its turn within 10 feet of Juiblex must succeed on a DC 21 Constitution saving throw or be [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) until the start of the creature's next turn.

***Legendary Resistance (3/Day).*** If Juiblex fails a saving throw, it can choose to succeed instead.

***Magic Resistance.*** Juiblex has advantage on saving throws against spells and other magical effects.

***Regeneration.*** Juiblex regains 20 hit points at the start of its turn. If it takes fire or radiant damage, this trait doesn't function at the start of its next turn. Juiblex dies only if it starts its turn with 0 hit points and doesn't regenerate.

***Spider Climb.*** Juiblex can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

## Actions

***Multiattack.*** Juiblex makes three Acid Lash attacks.

***Acid Lash.*** *Melee  or Ranged Weapon Attack:* `+14` to hit, reach 10 ft. or range 60/120 ft., one target. *Hit:* 21 (`4d6 + 7`) acid damage. Any creature killed by this attack is drawn into Juiblex's body, where the corpse is dissolved after 1 minute.

***Eject Slime (Recharge 5-6).*** Juiblex spews out a corrosive slime, targeting one creature that it can see within 60 feet of it. The target must succeed on a DC 21 Dexterity saving throw or take 55 (`10d10`) acid damage. Unless the target avoids taking all of this damage, any metal armor worn by the target takes a permanent −1 penalty to the AC it offers, and any metal weapon the target is carrying or wearing takes a permanent −1 penalty to damage rolls. The penalty worsens each time a target is subjected to this effect. If the penalty on an object drops to −5, the object is destroyed. The penalty on an object can be removed by the [mending](Mechanics/CLI/spells/mending-xphb.md) spell.

***Spellcasting.*** Juiblex casts one of the following spells, requiring no material components and using Wisdom as the spellcasting ability (spell save DC 20):

**At will:** [detect magic](Mechanics/CLI/spells/detect-magic-xphb.md)

**3/day each:** [contagion](Mechanics/CLI/spells/contagion-xphb.md), [gaseous form](Mechanics/CLI/spells/gaseous-form-xphb.md)

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, Juiblex can expend a use to take one of the following actions. Juiblex regains all expended uses at the start of each of their turns.

***Attack.*** Juiblex makes one Acid Lash attack.

***Corrupting Touch (Costs 2 Actions).*** *Melee Weapon Attack:* `+14` to hit, reach 10 ft., one creature. *Hit:* 21 (`4d6 + 7`) poison damage, and the target is slimed. Until the slime is scraped off with an action, the target is [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned), and any creature, other than an Ooze, is [poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) while within 10 feet of the target.

## Lair Actions

On initiative count 20 (losing initiative ties), Juiblex can take one of the following lair actions; it can't take the same lair action two rounds in a row:

- **Green Slime.** A [green slime](Mechanics/CLI/traps-hazards/green-slime.md) (see the "Dungeon Master's Guide") appears on a spot on the ceiling that Juiblex chooses within the lair. The slime disintegrates after 1 hour.  
- **Slippery Slime.** Juiblex slimes a square area of ground it can see within the lair. The area can be up to 10 feet on a side. When the slime appears, each creature on it must succeed on a DC 21 Dexterity saving throw or fall [prone](Mechanics/CLI/rules/conditions.md#Prone) and slide 10 feet in a random direction determined by a `d8` roll. When a creature enters the area for the first time on a turn or ends its turn there, that creature must make the same save.  

    The slime lasts for 1 hour or until it is burned away with fire. If the slime is set on fire, it burns away after 1 round. Any creature that starts its turn in the burning slime takes 22 (`4d10`) fire damage.  
- **Sticky Slime.** Juiblex slimes a square area of ground it can see within the lair. The area can be up to 10 feet on a side. When the slime appears, each creature in that area must succeed on a DC 21 Strength saving throw or become [restrained](Mechanics/CLI/rules/conditions.md#Restrained). When a creature enters the area for the first time on a turn or ends its turn there, that creature must make the same save.  

    A [restrained](Mechanics/CLI/rules/conditions.md#Restrained) creature is stuck as long as it remains in the slimy area or until it breaks free. The [restrained](Mechanics/CLI/rules/conditions.md#Restrained) creature, or another creature that can reach it, can use its action to try to break free and must succeed on a DC 21 Strength check. The slime lasts for 1 hour or until it is burned away with fire. If the slime is set on fire, it burns away after 1 round. Any creature that starts its turn in the burning slime takes 22 (`4d10`) fire damage.  

## Regional Effects

The region containing Juiblex's lair is warped by its magic, creating one or more of the following effects:

- **Acidic Water.** Small bodies of water, such as ponds or wells, within 1 mile of the lair turn highly acidic, corroding any object that touches them.  
- **Corrupted Nature.** Within 6 miles of the lair, all Wisdom ([Medicine](Mechanics/CLI/rules/skills.md#Medicine)) and Wisdom ([Survival](Mechanics/CLI/rules/skills.md#Survival)) checks have disadvantage.  
- **Slime.** Surfaces within 6 miles of the lair are frequently covered by a thin film of slime, which is slick and sticks to anything that touches it.  

If Juiblex dies, these effects fade over the course of `1d10` days.
```
^statblock