---
publish: true
aliases:
  - House of Roulette
created: 2026-03-09T12:15:33.789-04:00
modified: 2026-03-09T12:15:33.789-04:00
published: 2026-03-09T12:15:33.789-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24extras
  - ttrpg-cli/subclass/warmage/roulette
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# House of Roulette
*[Warmage](./warmage-valdaspire24.md): Subclass Feature*  
*Source: Valda's Spire of Secrets Extras (2024)*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='3'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#House of Roulette (Level 3)' class='internal-link'>House of Roulette</a></td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Lucky Number (Level 7)' class='internal-link'>Lucky Number</a></td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Spinning Shield (Level 10)' class='internal-link'>Spinning Shield</a></td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Cash Out (Level 15)' class='internal-link'>Cash Out</a></td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Everything on Black (Level 18)' class='internal-link'>Everything on Black</a></td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"></td></tr>
> </tbody></table>

^class-progression

*Spin the Wheel, Gambling on Your Lucky Numbers*

Like the Houses of Dice and Cards, Warmages of the House of Roulette are masters of the calculated gamble. Bearing a number of magical chips, they can push the odds when the need arises, pulling off longshot plays that other Warmages could only dream of.

## Subclass Features

### Spin the Wheel (Level 3)

You gain a roulette ball infused with arcane energy and a number of chips. As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can conjure a roulette wheel of magical force and roll the ball. Choose one of the bets from the Roulette Bets table below, announce your guess, and roll a `d100`. You gain the listed benefit if your guess is correct.

**Chips of Fate.** You have four Chips of Fate, and regain all expended chips when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). You gain two more Chips of Fate at level 7 (6 chips), 10 (8 chips), and 15 (10 chips).

Whenever you place a bet on the roulette wheel, you can expend 1-4 of your chips to place additional bets equal to the number of chips expended. No matter how many chips you expend, you can only place two types of bets, such as Singles and Tens, per `d100` roll. You can't place more than one Odd/Even or High/Low bets. You can gain two benefits at once if you win two bets on the same roll.

**Roulette Bets**

| Bet | Benefit |
|-----|---------|
| **Odd/Even.** Guess whether the roll is even or odd. | You gain a +2 bonus to your AC until the start of your next turn. |
| **High/Low.** Guess whether the roll is above or below 50. | You gain a +2 bonus on attack rolls you make until the start of your next turn. |
| **Lanes.** Guess which of the following spans the number falls within: 01-20, 21-40, 41-60 , 61-80, 81-00. | You can gain [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on a [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) you make before the end of your next turn. |
| **Tens.** Guess the 10s digit of the roll. | Once before the end of your next turn, you can add 10 to the damage roll of a Warmage cantrip you cast. |
| **Single.** Guess the exact number of the roll. | Until the start of your next turn, you have [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to all damage and treat any d20 roll you make as 20. |
^roulette-bets

### Lucky Number (Level 7)

Pick a Lucky Number from 1 to 100 If you roll that number on any `d100` roll of your Spin the Wheel feature, you gain the benefit of betting that number as a Single. You can change your Lucky Number whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

### Spinning Shield (Level 10)

When a creature you can see makes an attack roll against you, you can take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) to conjure your roulette wheel between yourself and the attacker. You and the attacker each roll a `d100`. If your roll is equal or higher than that of the attacker, the attack misses, and you can't use this ability again until you finish a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

### Cash Out (Level 15)

You can unleash the energy stored within a Chip of Fate to escape a tight spot. As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can expend a Chip of Fate to teleport up to 120 feet to an unoccupied space you can see.

### Everything on Black (Level 18)

Whenever you roll [Initiative](Mechanics/CLI/rules/variant-rules/initiative-xphb.md), you regain 4 expended Chips of Fate. Additionally, whenever you expend one or more Chips of Fate to bet on a Single and win, you regain all of your expended Chips of Fate.