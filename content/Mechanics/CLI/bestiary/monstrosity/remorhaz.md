---
publish: true
aliases:
  - Remorhaz
created: 2026-03-29T21:53:55.981-04:00
modified: 2026-03-29T21:53:55.981-04:00
published: 2026-03-29T21:53:55.981-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mm
  - ttrpg-cli/monster/cr/11
  - ttrpg-cli/monster/environment/arctic
  - ttrpg-cli/monster/size/huge
  - ttrpg-cli/monster/type/monstrosity
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Remorhaz
ac: 17
hp: 195
modifier: 1
hit_dice: 17d12 + 85
cr: "11"
stats:
  - 24
  - 13
  - 21
  - 4
  - 10
  - 5
source:
  - MM
---

# Remorhaz

![](Mechanics/CLI/bestiary/monstrosity/img/remorhaz.webp#right)
From beneath the snow and ice bursts a remorhaz in a cloud of steam, its body pulsing with internal fire. Wing like fins flare from the back of the creature's head, and its wide mouth brims with jagged teeth.

## Arctic Predators

Remorhazes live in arctic climes, preying on elk, polar bears, and other creatures sharing their territory. They can't tolerate warm weather, having adapted to the cold by generating a furnace-like heat within their bodies. When hunting, a remorhaz burrows deep below the snow and ice and lies in wait for the faint vibrations created by a creature moving above it. While hidden under the ice and snow, it can lower its body temperature so that it doesn't melt its cover.

## Young Ones

Frost giant hunters scour the icy wastes for remorhaz nests and eggs. The giants prize young remorhazes, which can be trained from hatching to obey commands and guard the giants' icy citadels. Unlike fully grown specimens, young remorhazes gnaw on their victims instead of swallowing them whole.

## Statblock

```ad-statblock
title: Remorhaz
![](/Mechanics/CLI/bestiary/monstrosity/token/remorhaz.webp#token)
*Huge monstrosity, Unaligned*

- **Armor Class** 17 (natural armor)
- **Hit Points** 195 (17d12 + 85) 
- **Speed** 30 ft., burrow 20 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|24 (+7)|13 (+1)|21 (+5)| 4 (-3)|10 (+0)| 5 (-3)|

- **Proficiency Bonus** +4
- **Saving Throws** ⏤
- **Skills** ⏤
- **Senses** [darkvision](/Mechanics/CLI/senses.md#Darkvision) 60 ft., tremorsense 60 ft., passive Perception 10
- **Damage Immunities** cold, fire
- **Languages** —
- **Challenge** 11

## Traits

***Heated Body.*** A creature that touches the remorhaz or hits it with a melee attack while within 5 feet of it takes 10 (`3d6`) fire damage.

## Actions

***Bite.*** *Melee Weapon Attack:* `+11` to hit, reach 10 ft., one target. *Hit:* 40 (`6d10 + 7`) piercing damage plus 10 (`3d6`) fire damage. If the target is a creature, it is [grappled](/Mechanics/CLI/conditions.md#Grappled) (escape DC 17). Until this grapple ends, the target is [restrained](/Mechanics/CLI/conditions.md#Restrained), and the remorhaz can't bite another target.

***Swallow.*** The remorhaz makes one bite attack against a Medium or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](/Mechanics/CLI/conditions.md#Blinded) and [restrained](/Mechanics/CLI/conditions.md#Restrained), it has total cover against attacks and other effects outside the remorhaz, and it takes 21 (`6d6`) acid damage at the start of each of the remorhaz's turns.

If the remorhaz takes 30 damage or more on a single turn from a creature inside it, the remorhaz must succeed on a DC 15 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall [prone](/Mechanics/CLI/conditions.md#Prone) in a space within 10 feet of the remorhaz. If the remorhaz dies, a swallowed creature is no longer [restrained](/Mechanics/CLI/conditions.md#Restrained) by it and can escape from the corpse using 15 feet of movement, exiting [prone](/Mechanics/CLI/conditions.md#Prone).
```

^statblock

## Environment

arctic

## Sources

_Monster Manual p. 258. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>_
