---
publish: true
aliases:
  - Drake-Blooded
created: 2026-03-09T12:15:34.041-04:00
modified: 2026-03-09T12:15:34.041-04:00
published: 2026-03-09T12:15:34.041-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/subclass/warden/drake-blooded
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Drake-Blooded

_[Warden](./warden-valdaspire24.md): Subclass Feature_\
_Source: Valda's Spire of Secrets (2024)_

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='4'></th><th colspan='4'>Spell Slots per Spell Level</th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Prepared Spells</th><th class="spellSlot">1st</th><th class="spellSlot">2nd</th><th class="spellSlot">3rd</th><th class="spellSlot">4th</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"></td><td class="value">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"></td><td class="value">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Drake-Blooded (Level 3)' class='internal-link'>Drake-Blooded</a></td><td class="value">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td><td class="value">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"></td><td class="value">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Arcane Strike (Level 6)' class='internal-link'>Arcane Strike</a></td><td class="value">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"></td><td class="value">5</td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td><td class="value">6</td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td><td class="value">6</td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Draconic Vengeance (Level 10)' class='internal-link'>Draconic Vengeance</a></td><td class="value">7</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td><td class="value">8</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td><td class="value">8</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td><td class="value">9</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"></td><td class="value">10</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"></td><td class="value">10</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td><td class="value">11</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Aspect of the Greatwyrm (Level 17)' class='internal-link'>Aspect of the Greatwyrm</a></td><td class="value">11</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"></td><td class="value">11</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td><td class="value">12</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"></td><td class="value">13</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td></tr>
> </tbody></table>

^class-progression

_Channel Draconic Magic with Your Blood_

Your call was the booming roar of dragons. As such, you have struck a pact with an ancient wyrm to protect its hoard from enemies that might despoil it. In turn, the surged through your veins like fire and granted you a measure of draconic power. Fire alights at your fingertips and your eyes bear reptilian slits. As a Drake-Blooded wyrm granted you a few drops of its blood to drink, which Warden, you are a champion among half-dragons and a titan among kobolds.

## Subclass Features

### Spellcasting (Level 3)

You have learned to cast spells. The information below details how you use those rules as a Drake-Blooded Warden.

**Cantrips.** You know two cantrips of your choice from the Sorcerer spell list (see that class's section for its list). [Sorcerous Burst](Mechanics/CLI/spells/sorcerous-burst-xphb.md) and [True Strike](Mechanics/CLI/spells/true-strike-xphb.md) are recommended. Whenever you gain a Warden level, you can replace one of these cantrips with another cantrip of your choice from the Sorcerer spell list.

When you reach Warden level 10, you learn another Sorcerer cantrip of your choice.

**Spell Slots.** The Drake-Blooded Spellcasting table shows how many spell slots you have to cast your level 1+ spells. You regain all expended slots when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

**Prepared Spells of Level 1+.** You prepare the list of level 1+ spells that are available for you to cast with this feature. To start, choose three level 1 spells from the Sorcerer spell list. [Burning Hands](Mechanics/CLI/spells/burning-hands-xphb.md), [Detect Magic](Mechanics/CLI/spells/detect-magic-xphb.md), and [Shield](Mechanics/CLI/spells/shield-xphb.md) are recommended.

The number of spells on your list increases as you gain Warden levels, as shown in the Prepared Spells column of the Drake-Blooded Spellcasting table.

Whenever that number increases, choose additional spells from the Sorcerer spell list until the number of spells on your list matches the number on the table. The chosen spells must be of a level for which you have spell slots. For example, if you're a level 7 Warden, your list of prepared spells can include five Sorcerer spells of levels 1 and 2 in any combination.

**Changing your Prepared Spells.** Whenever you gain a Warden level, you can replace one spell on your list with another Sorcerer spell for which you have spell slots.

**Spellcasting Ability.** Charisma is your spellcasting ability for your Sorcerer spells.

**Spellcasting Focus.** You can use an Arcane Focus as a [Spellcasting Focus](Mechanics/CLI/rules/variant-rules/spellcasting-focus-xphb.md) for your Sorcerer spells.

### Mortal Metamagic (Level 3)

You use the following Metamagic options to temporarily modify spells you cast. To use an option, you must expend the number of [Hit Point Dice](Mechanics/CLI/rules/variant-rules/hit-point-dice-xphb.md) that it costs. You can use only one Metamagic option on a spell when you cast it unless otherwise noted in one of those options.

**Empowered Spell (Costs 1 Hit Point Die).** When you roll damage for a spell, you can spend 1 [Hit Point Die](Mechanics/CLI/rules/variant-rules/hit-point-dice-xphb.md) to reroll a number of the damage dice up to your Charisma modifier (minimum of one), and you must use the new rolls.

You can use Empowered Spell even if you've already used a different Metamagic option during the casting of the spell.

**Quickened Spell (Costs 2 Hit Point Dice).** When you cast a spell that has a casting time of an action, you can expend 2 [Hit Point Dice](Mechanics/CLI/rules/variant-rules/hit-point-dice-xphb.md) to change the casting time to a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) for this casting. You can't modify a spell in this way if you've already cast a level 1+ spell on the current turn, nor can you cast a level 1+ spell on this turn after modifying a spell in this way.

### Arcane Strike (Level 6)

When you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action on your turn, you can replace one of the attacks with a casting of one of your Sorcerer cantrips that has a casting time of an action.

### Draconic Vengeance (Level 10)

When you take damage from a creature that is within 10 feet of you, you can take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) and expend a [Hit Point Die](Mechanics/CLI/rules/variant-rules/hit-point-dice-xphb.md) to unleash draconic energy in a 10-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from you. Each creature you choose in the [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) makes a Dexterity saving throw against your spell save DC. On a failed save, a creature takes damage equal to two rolls of your [Hit Point Die](Mechanics/CLI/rules/variant-rules/hit-point-dice-xphb.md) plus your Constitution modifier, or half as much damage on a successful one. The damage is your choice of Acid, Cold, Fire, Lightning, or Poison.

### Aspect of the Greatwyrm (Level 17)

You can wreathe yourself in a dragon's elemental might. As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can gain the benefits below for 1 minute or until you choose to end them (no action required). Once you use this feature, you can't use it again until you finish a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

**Breath Weapon.** When you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action on your turn, you can replace one of your attacks with an exhalation of magical energy in a 30-foot [Cone](Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Each creature in that area must make a Dexterity saving throw against your spell save DC, taking `6d6` damage on a failed save or half as much damage on a successful one. The damage is your choice of Acid, Cold, FIre, Lightning, or Poison.

**Elemental Fury.** When you deal damage with a Melee weapon or an [Unarmed Strike](Mechanics/CLI/rules/variant-rules/unarmed-strike-xphb.md), the target takes an extra `1d6` damage. The damage is your choice of Acid, Cold, FIre, Lightning, or Poison.

**Fly Speed.** You gain a [Fly Speed](Mechanics/CLI/rules/variant-rules/fly-speed-xphb.md) of 60 feet.
