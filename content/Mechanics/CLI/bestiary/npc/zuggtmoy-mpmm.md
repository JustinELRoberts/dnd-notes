---
publish: true
aliases:
  - Zuggtmoy
created: 2026-03-29T21:53:55.998-04:00
modified: 2026-03-29T21:53:55.998-04:00
published: 2026-03-29T21:53:55.998-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/23
  - ttrpg-cli/monster/size/large
  - ttrpg-cli/monster/type/fiend/demon
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Zuggtmoy (MPMM)
ac: 18
hp: 304
modifier: 2
hit_dice: 32d10 + 128
cr: "23"
stats:
  - 22
  - 15
  - 18
  - 20
  - 19
  - 24
source:
  - MPMM
---

# Zuggtmoy

![](Mechanics/CLI/bestiary/npc/img/zuggtmoy.webp#right)
The Demon Queen of Fungi, Lady of Rot and Decay, Zuggtmoy is an alien creature whose only desire is to infect the living with spores, transforming them into her mindless servants and, eventually, into decomposing hosts for the mushrooms, molds, and other fungi that she spawns.

Utterly inhuman, Zuggtmoy can mold her fungoid form into an approximation of a humanoid shape, including the skeletal-thin figure depicted in grimoires and ancient art, draped and veiled in mycelia and lichen. Indeed, much of her appearance and manner, and that of her servants, is a soulless mockery of mortal life and its many facets.

Zuggtmoy's cultists often follow her unwittingly. Most are fungi—infected to some degree, whether through inhaling her mind-controlling spores or being transformed to the point where flesh and fungus become one. Such cultists are fungal extensions of the Demon Queen's will.

Their devotion might begin with the seemingly harmless promises offered by exotic spores and mushrooms, but quickly consumes them, body and soul.

## Cultists of Zuggtmoy

> [!note]
> See the Cult of Zuggtmoy entry.

## Zuggtmoy's Lair

Zuggtmoy's principal lair is her palace on Shedaklah. It consists of two dozen mushrooms of pale yellow and rancid brown. These massive fungi are some of the largest in existence. They are surrounded by a field of acidic puffballs and poisonous vapors. The mushrooms themselves are all interconnected by bridges of shelf-fungi, and countless chambers have been hollowed out from within their rubbery, fibrous stalks.

## Statblock

```ad-statblock
title: Zuggtmoy
![](/Mechanics/CLI/bestiary/npc/token/zuggtmoy-mpmm.webp#token)
*Large fiend (demon), Chaotic Evil*

- **Armor Class** 18 (natural armor)
- **Hit Points** 304 (32d10 + 128) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|22 (+6)|15 (+2)|18 (+4)|20 (+5)|19 (+4)|24 (+7)|

- **Proficiency Bonus** +7
- **Saving Throws** Dexterity +9, Constitution +11, Wisdom +11
- **Skills** [Perception](/Mechanics/CLI/skills.md#Perception) +11
- **Senses** [truesight](/Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception 21
- **Damage Resistances** cold, fire, lightning
- **Damage Immunities** poison; bludgeoning, piercing, slashing that is nonmagical
- **Condition Immunities** [charmed](/Mechanics/CLI/conditions.md#Charmed), [exhaustion](/Mechanics/CLI/conditions.md#Exhaustion), [frightened](/Mechanics/CLI/conditions.md#Frightened), [poisoned](/Mechanics/CLI/conditions.md#Poisoned)
- **Languages** all, telepathy 120 ft.
- **Challenge** 23

## Traits

***Legendary Resistance (3/Day).*** If Zuggtmoy fails a saving throw, she can choose to succeed instead.

***Magic Resistance.*** Zuggtmoy has advantage on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** Zuggtmoy makes three Pseudopod attacks.

***Pseudopod.*** *Melee Weapon Attack:* `+13` to hit, reach 10 ft., one target. *Hit:* 15 (`2d8 + 6`) force damage plus 9 (`2d8`) poison damage.

***Spellcasting.*** Zuggtmoy casts one of the following spells, requiring no material components and using Charisma as the spellcasting ability (spell save DC 22):

**At will:** [detect magic](/Mechanics/CLI/spells/detect-magic-xphb.md), [locate animals or plants](/Mechanics/CLI/spells/locate-animals-or-plants-xphb.md)

**3/day each:** [dispel magic](/Mechanics/CLI/spells/dispel-magic-xphb.md), [entangle](/Mechanics/CLI/spells/entangle-xphb.md), [plant growth](/Mechanics/CLI/spells/plant-growth-xphb.md)

**1/day each:** [etherealness](/Mechanics/CLI/spells/etherealness-xphb.md), [teleport](/Mechanics/CLI/spells/teleport-xphb.md)

## Bonus Actions

***Infestation Spores (3/Day).*** Zuggtmoy releases spores that burst out in a cloud that fills a 20-foot-radius sphere centered on her, and it lingers for 1 minute. Any creature in the cloud when it appears, or that enters it later, must make a DC 19 Constitution saving throw. On a successful save, the creature can't be infected by these spores for 24 hours. On a failed save, the creature is infected with a disease called the spores of Zuggtmoy, which lasts until the creature is cured of the disease or dies. While infected in this way, the creature can't be reinfected, and it must repeat the saving throw at the end of every 24 hours, ending the infection on a success. On a failure, the infected creature's body is slowly taken over by fungal growth, and after three such failed saves, the creature dies and is reanimated as a [spore servant](/Mechanics/CLI/bestiary/plant/quaggoth-spore-servant.md) if it's a type of creature that can be.

***Mind Control Spores (Recharge 5-6).*** Zuggtmoy releases spores that burst out in a cloud that fills a 20-foot-radius sphere centered on her, and it lingers for 1 minute. Humanoids and Beasts in the cloud when it appears, or that enter it later, must make a DC 19 Wisdom saving throw. On a successful save, a creature can't be infected by these spores for 24 hours. On a failed save, the creature is infected with a disease called the influence of Zuggtmoy for 24 hours. While infected in this way, the creature is [charmed](/Mechanics/CLI/conditions.md#Charmed) by her and can't be reinfected by these spores.

## Reactions

***Protective Thrall.*** When Zuggtmoy is hit by an attack roll, one creature within 10 feet of her that is [charmed](/Mechanics/CLI/conditions.md#Charmed) by her is hit by the attack instead.

## Legendary Actions

Legendary Action Uses: 3. Immediately after another creature's turn, Zuggtmoy can expend a use to take one of the following actions. Zuggtmoy regains all expended uses at the start of each of their turns.

***Attack.*** Zuggtmoy makes one Pseudopod attack.

***Exert Will.*** One creature [charmed](/Mechanics/CLI/conditions.md#Charmed) by Zuggtmoy that she can see must use its reaction, if a available, to move up to its speed as she directs or to make one weapon attack against a target that she designates.

## Lair Actions

On Initiative count 20 (losing initiative ties), Zuggtmoy can take a lair action to cause one of the following effects; she can't use the same effect two rounds in a row:

- **Rally Plants.** Up to four plant creatures that are friendly to Zuggtmoy and that Zuggtmoy can see can use their reactions to move up to their speed and make one weapon attack.  
- **Summon Fungi.** Zuggtmoy causes four [gas spores](/Mechanics/CLI/bestiary/plant/gas-spore.md) or [violet fungi](/Mechanics/CLI/bestiary/plant/violet-fungus.md) to appear in unoccupied spaces that she chooses within the lair. They vanish after 1 hour.  
- **Unleash Spores.** Zuggtmoy uses either her Infestation Spores or her Mind Control Spores, centered on a mushroom or other fungus within her lair, instead of on herself.  

## Regional Effects

The region containing Zuggtmoy's lair is warped by his magic, creating one or more of the following effects:

- **Corrupted Nature.** Within 6 miles of the lair, all Wisdom ([Medicine](/Mechanics/CLI/skills.md#Medicine)) and Wisdom ([Survival](/Mechanics/CLI/skills.md#Survival)) checks have disadvantage.  
- **Fungal Infestation.** Molds and fungi grow on surfaces within 6 miles of the lair, even where they would normally find no purchase.  
- **Mutating Vegetation.** Vegetation within 1 mile of the lair becomes infested with parasitic fungi, slowly mutating as it is overwhelmed.  
- If Zuggtmoy dies, these effects fade over the course of `1d10` days.  
```

^statblock

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 281_
