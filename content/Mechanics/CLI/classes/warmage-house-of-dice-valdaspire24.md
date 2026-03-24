---
publish: true
aliases:
  - House of Dice
created: 2026-03-09T12:15:33.846-04:00
modified: 2026-03-09T12:15:33.846-04:00
published: 2026-03-09T12:15:33.846-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/subclass/warmage/dice
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# House of Dice

_[Warmage](./warmage-valdaspire24.md): Subclass Feature_\
_Source: Valda's Spire of Secrets (2024)_

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='3'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#House of Dice (Level 3)' class='internal-link'>House of Dice</a></td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Loaded Dice (Level 7)' class='internal-link'>Loaded Dice</a></td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Twisted Fate (Level 10)' class='internal-link'>Twisted Fate</a></td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Roll the Bones (Level 15)' class='internal-link'>Roll the Bones</a></td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Steal Luck (Level 18)' class='internal-link'>Steal Luck</a></td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"></td></tr>
> </tbody></table>

^class-progression

_Tempt Fate with Chaotic Die Rolls_

The House of Dice throws out the Warmage convention of meticulous, deliberate spellcasting in favor of wild, chaotic magic that presses the odds. Everything from their magical bursts to their enchanted sets of dice can fail horribly, so it's auspicious that they often keep their fingers on the scales of fate. These Warmages have mastered not only a repertoire of cantrips, but also techniques to manipulate fortune itself, allowing them to risk everything, and more than often come out on top.

## Subclass Features

### Bonus Proficiencies (Level 3)

Your light fingers and unscrupulous tactics help you win the day. You gain proficiency in the [Sleight of Hand](Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand) skill and with the [Gaming Set](Mechanics/CLI/items/gaming-set-xphb.md) ([Dice Set](Mechanics/CLI/items/dice-set-xphb.md)), if you don't already have it.

### Dice of Fate (Level 3)

You gain four Dice of Fate, which are d6s. Whenever you fail a [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) or make a damage roll, you can expend one Die of Fate and add it to the roll, potentially causing the [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) to succeed. Once you expend a Die of Fate, it goes to the GM, who can expend it to add it to a [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) or a damage roll made by an NPC or monster. When the GM expends a die, it passes back to you, and so on. When you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you regain all of your expended Dice of Fate, whether or not the GM has used them.

Beginning at level 7, you have an additional two Dice of Fate, and you can add two Dice of Fate at once to your damage rolls with Warmage cantrips.

### Chaos Roll (Level 3)

You can expend two of your [Dice of Fate](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Dice%20of%20Fate%20\(Level%203\)) as a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, rolling them on the Chaos Roll table to create a chaotic surge of energy.

**Chaos Roll**

| dice: 2d6 | Effect |
|-----------|--------|
| 2 | You cast [Fireball](Mechanics/CLI/spells/fireball-xphb.md) centered on yourself. |
| 3 | Your AC is reduced by 2 until the start of your next turn. |
| 4 | You have the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition. |
| 5 | Until the start of your next turn, each creature within a 60-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from you can only speak in a babbling nonsense language and can't cast spells with a Verbal component. |
| 6 | A 5-foot-radius [Sphere](Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) of butterflies, insects, or doves fills a location you choose within 60 feet of you. The [Sphere](Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md) is [Heavily Obscured](Mechanics/CLI/rules/variant-rules/heavily-obscured-xphb.md) until the start of your next turn. |
| 7 | You gain 7 [Temporary Hit Points](Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md), and you keep the [Dice of Fate](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Dice%20of%20Fate%20\(Level%203\)) instead of giving them to the GM. |
| 8 | You have the [Invisible](Mechanics/CLI/rules/conditions.md#Invisible) condition until the end of your next turn, as per the [Invisibility](Mechanics/CLI/spells/invisibility-xphb.md) spell. |
| 9 | An object within 60 feet of you chosen by the GM explodes, dealing no damage to you or your [Allies](Mechanics/CLI/rules/variant-rules/ally-xphb.md), and dealing `3d6` Fire damage to one creature caught in the blast. |
| 10 | You teleport up to 60 feet to an unoccupied space you can see. Each creature within 5 feet of the destination must succeed on a Dexterity saving throw against your spell save DC or take `2d6` Force damage. |
| 11 | Choose a creature you can see within 60 feet of you. That creature takes 4d6 Necrotic damage and you regain [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to the Necrotic damage taken. |
| 12 | You cast [Lightning Bolt](Mechanics/CLI/spells/lightning-bolt-xphb.md) and can add the [Dice of Fate](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Dice%20of%20Fate%20\(Level%203\)) to the damage roll. |
^chaos-roll

### Loaded Dice (Level 7)

You can subtly cheat your dice. Once on each of your turns when you roll a `d6`, you can flip the die upside down. Note that on a balanced `d6`, the top and bottom numbers add up to 7, so you can determine the bottom number by subtracting the top number from 7.

### Twisted Fate (Level 10)

When you make an attack roll or ability check with [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on your turn, you can attempt to invert fate as a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md). Expend a [Die of Fate](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Dice%20of%20Fate%20\(Level%203\)) and roll it. On a 5, you ignore [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on the roll. On a 6, you instead have [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on the roll.

### Roll the Bones (Level 15)

You can channel the chaotic energy of your dice in an instant. As a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) when you take damage from a creature you can see, you can expend two [Dice of Fate](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Dice%20of%20Fate%20\(Level%203\)) to make a [Chaos Roll](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Chaos%20Roll%20\(Level%203\)).

### Steal Luck (Level 18)

When you roll [Initiative](Mechanics/CLI/rules/variant-rules/initiative-xphb.md), roll a `d6`. You steal that many [Dice of Fate](Mechanics/CLI/classes/warmage-house-of-dice-valdaspire24.md#Dice%20of%20Fate%20\(Level%203\)) back from the GM.
