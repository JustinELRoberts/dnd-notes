---
publish: true
aliases:
  - Feylost
created: 2026-03-09T12:15:33.977-04:00
modified: 2026-03-09T12:15:33.977-04:00
published: 2026-03-09T12:15:33.977-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24extras
  - ttrpg-cli/subclass/vagabond/feylost
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Feylost

_[Vagabond](./vagabond-valdaspire24extras.md): Subclass Feature_\
_Source: Valda's Spire of Secrets Extras (2024)_

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='3'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Feylost (Level 3)' class='internal-link'>Feylost</a></td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Misty Pathways (Level 6)' class='internal-link'>Misty Pathways</a></td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Irresistible Mood (Level 10)' class='internal-link'>Irresistible Mood</a></td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Mercurial (Level 14)' class='internal-link'>Mercurial</a></td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"></td></tr>
> </tbody></table>

^class-progression

_Master Your Magical Mood Swings_

The Feywild is a labyrinth of winding, magical paths, leading to delightful glades and nightmarish grottos alike. Mortals that wander there often become lost, vanishing for decades before returning without having aged a day. However, they return with infectious fey enchantments that sometimes overwhelm their minds and the minds of those nearby.

## Subclass Features

### Fey Moods (Level 3)

Your time in the Feywild has afflicted you with magical mood swings known as Fey Moods that overtake you in desperate situations. When you take damage that causes you to become [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), roll on the Fey Moods table. This mood lasts for 1 minute or until you are no longer [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied).

**Fey Moods**

| dice: d8 | Mood |
|----------|------|
| 1 | _**Arrogant.**_ Enemies within 5 feet of you have [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls against targets other than you. |
| 2 | _**Elated.**_ At the start of each of your turns, you gain [Temporary Hit Points](Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) equal to your Constitution modifier. |
| 3 | _**Fearful.**_ [Opportunity Attacks](Mechanics/CLI/rules/actions.md#Opportunity%20Attack) have [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) against you. |
| 4 | _**Forlorn.**_ When a creature you can see hits an ally within 5 feet of you with an attack roll, you can take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) to force the attack to hit you instead. |
| 5 | _**Manic.**_ When you roll a 1 on the `d20` for a [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md), the roll becomes a 20. |
| 6 | _**Paranoid.**_ You have [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on Dexterity ability checks and saving throws. |
| 7 | _**Serene.**_ You have [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on Intelligence, Wisdom, and Charisma saving throws. |
| 8 | _**Spiteful.**_ When a creature deals damage to you, the next time you hit that creature with an attack before the end of your next turn, the target takes an extra `1d8` Force damage. |
^fey-moods

### Frenzied Strike \[Maneuver] (Level 3)

When you hit a creature with an attack using a Melee weapon or an [Unarmed Strike](Mechanics/CLI/rules/variant-rules/unarmed-strike-xphb.md), you can expend one Battle Die as a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md) to infect the target's mind. The creature has the Frenzied condition until the end of its next turn.

A creature with the Frenzied condition loses the ability to distinguish between friend and foe, regarding all creatures it can see as enemies. While Frenzied, the creature chooses the targets for its attacks, spells, and abilities randomly from among the creatures it can see within range, and it must make an [Opportunity Attacks](Mechanics/CLI/rules/actions.md#Opportunity%20Attack) if any creature provokes one.

### Misty Pathways (Level 6)

You can cast [Misty Step](Mechanics/CLI/spells/misty-step-xphb.md) without a spell slot.

Once you use this feature, you can't use it again until you finish a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md) unless you expend one Battle Die (no action required) to restore your use of it.

### Irresistible Mood (Level 10)

When a creature deals damage to you that causes you to become [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), you can take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) to give the creature the [Charmed](Mechanics/CLI/rules/conditions.md#Charmed) or [Frightened](Mechanics/CLI/rules/conditions.md#Frightened) condition for 1 minute. The [Charmed](Mechanics/CLI/rules/conditions.md#Charmed) or [Frightened](Mechanics/CLI/rules/conditions.md#Frightened) target makes a Wisdom saving throw against your Maneuver save DC at the end of each of its turns, ending the condition on itself on a success.

### Mercurial (Level 14)

As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can expend one Battle Die to activate any Fey Mood option of your choice. This mood lasts for 1 minute. If you already have a Fey Mood active or you become [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied) while this mood is active, you can have both moods active at once.
