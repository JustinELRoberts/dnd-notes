---
publish: true
aliases:
  - Kundarak Warden
created: 2026-03-09T12:15:33.966-04:00
modified: 2026-03-09T12:15:33.966-04:00
published: 2026-03-09T12:15:33.966-04:00
tags:
  - ttrpg-cli/compendium/src/5e/efa
  - ttrpg-cli/monster/cr/5
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid/dwarf
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Kundarak Warden

_Source: Eberron: Forge of the Artificer p. 81_\
![](Mechanics/CLI/bestiary/humanoid/img/kundarak-warden.webp#right)

Some dragonmarked heirs (mostly dwarves) of House Kundarak serve as personal guardians for the house's vaults and storehouses, and even its infamous prison, Dreadhold. Some also serve as agents of the mysterious Ghorad'din, a secretive group of assassins and spies little known beyond the members of the house. Kundarak wardens are adept at bypassing security measures as well as reinforcing them.

```ad-statblock
title: Kundarak Warden
![](Mechanics/CLI/bestiary/humanoid/token/kundarak-warden-efa.webp#token)
*Medium humanoid (dwarf), Neutral*

- **Armor Class** 14 
- **Hit Points** 82 (`11d8 + 33`) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|15 (+2)|12 (+1)|16 (+3)|17 (+3)|13 (+1)|10 (+0)|

- **Proficiency Bonus** +3
- **Saving Throws** Strength +5, Dexterity +4, Constitution +6, Intelligence +6, Wisdom +4
- **Skills** ⏤
- **Senses** [Darkvision](Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive Perception 11
- **Languages** Common, Dwarvish
- **Challenge** 5

## Traits

***Magic Resistance.*** The warden has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects.

## Actions

***Multiattack.*** The warden makes two Arcane Whip attacks. It can replace one attack with a use of Shackling Glyph if available.

***Arcane Whip.*** *Melee Attack Roll:* `+6`, reach 10 ft. *Hit:* 13 (`3d6 + 3`) Force damage, and if the target is a Medium or smaller creature, it has the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition. If the target already has the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition, the attack deals an extra 7 (`2d6`) Force damage.

***Shackling Glyph (Recharge 6).*** *Strength Saving Throw:* DC 14, one creature the warden can see within 60 feet. *Failure:* The creature has the [Grappled](Mechanics/CLI/rules/conditions.md#Grappled) condition (escape DC 14). While [Grappled](Mechanics/CLI/rules/conditions.md#Grappled), the creature has the [Restrained](Mechanics/CLI/rules/conditions.md#Restrained) condition.

***Spellcasting.*** The warden casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 14):

**At will:** [Alarm](Mechanics/CLI/spells/alarm-xphb.md), [Arcane Lock](Mechanics/CLI/spells/arcane-lock-xphb.md), [Mage Armor](Mechanics/CLI/spells/mage-armor-xphb.md) (included in AC)

**1/day:** [Dispel Magic](Mechanics/CLI/spells/dispel-magic-xphb.md)

## Reactions

***Protective Magic (3/Day).*** The warden casts [Counterspell](Mechanics/CLI/spells/counterspell-xphb.md) or [Shield](Mechanics/CLI/spells/shield-xphb.md) in response to the spell's trigger, using the same spellcasting ability as Spellcasting.

```

^statblock
