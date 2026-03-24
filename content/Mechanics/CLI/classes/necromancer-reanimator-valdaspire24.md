---
publish: true
aliases:
  - Reanimator
created: 2026-03-09T12:15:34.111-04:00
modified: 2026-03-09T12:15:34.111-04:00
published: 2026-03-09T12:15:34.111-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/subclass/necromancer/reanimator
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Reanimator

_[Necromancer](./necromancer-valdaspire24.md): Subclass Feature_\
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
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Reanimator (Level 3)' class='internal-link'>Reanimator</a></td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Lazarus Bolt (Level 6)' class='internal-link'>Lazarus Bolt</a></td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Quick Stitch (Level 10)' class='internal-link'>Quick Stitch</a></td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Patchwork Golem [Lichdom] (Level 20)' class='internal-link'>Patchwork Golem [Lichdom]</a></td></tr>
> </tbody></table>

^class-progression

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaAlchemist/Creatures/Alchemy%20Golem.webp#right)

_Stitch Together Terrible Minions_

Through bubbling test tubes and sparking electrodes, you have discovered the true heart of Necromancy: mad science. You've experimented in far-reaching disciplines of surgery, alchemy, and physics, using your animated minions as gruesome test subjects and walking surgical dummies. Most crucially, you have discovered that lightning can imbue almost anything with a semblance of life, from the smallest severed muscle to the most towering golems.

## Subclass Features

### Skilled Surgeon (Level 3)

You gain proficiency in the [Medicine](Mechanics/CLI/rules/skills.md#Medicine) skill, if you didn't already have it. Additionally, you gain a bonus to checks using this skill equal to your Intelligence modifier (minimum bonus of +1).

### Spell-Stitching (Level 3)

You can inscribe magical effects into your thralls with gruesome Spell-Stitches. You can expend [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20\(Level%201\)) points to apply Spell-Stitches to your thralls over the course of 1 hour, which can be done during a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). The number of Charnel Touch points required to apply each stitch is listed in parentheses. Each thrall can have a maximum of two stitches, which last until the thrall dies or you apply a new stitch to replace it.

**Armored Stitch (15 Charnel Touch Points).** The thrall's AC becomes 18 if it were lower.

**Fleet Stitch (5 Charnel Touch Points).** The thrall's [Speed](Mechanics/CLI/rules/variant-rules/speed-xphb.md) is doubled.

**Skilled Stitch (5 Charnel Touch Points).** The thrall has proficiency in all of your skills.

**Tough Stitch (10 Charnel Touch Points).** The thrall's [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum and current [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) increase by twice your Necromancer level.

**Vicious Stitch (10 Charnel Touch Points).** The thrall has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on the first attack roll it makes on each of its turns.

### Charnel Voltage (Level 3)

When you deal 5 or more damage with [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20\(Level%201\)), you can deal Lightning damage instead of Necrotic damage and cause the energy to arc to a second creature within 5 feet of the target. The second creature must succeed on a Dexterity saving throw against your spell save DC or take Lightning damage equal to half of the number of Charnel Touch points expended. A creature that takes Lightning damage from this feature can't make [Opportunity Attacks](Mechanics/CLI/rules/actions.md#Opportunity%20Attack) until the start of its next turn.

### Lazarus Bolt (Level 6)

As a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, you can drive a bolt into the torso of a creature within 5 feet of you that has died within the last minute and shock it back to life. That creature revives with 1 [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) and gains [Temporary Hit Points](Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) equal to twice your Necromancer level. This feature can't return to life a creature that lacks a heart, a creature that has died of old age, or a creature that is missing vital organs.

Once you use this feature, you can't use it again until you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). You can also restore your use of it by expending 20 [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20\(Level%201\)) points (no action required).

### Quick Stitch (Level 10)

As a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, you can apply a Spell-Stitch to one of your thralls, expending [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20\(Level%201\)) points as normal. This stitch lasts for 10 minutes and can exceed the thrall's maximum of two stitches.

### Patchwork Golem \[Lichdom] (Level 20)

You have reached the pinnacle of Necromancy and transformed yourself into a lich. Through abominable works of alchemy and surgery, you have constructed an artificial body to act as the vessel for your soul. You gain the following benefits in addition to those of your [Lichdom](Mechanics/CLI/classes/necromancer-valdaspire24.md#Lichdom%20\(Level%2020\)) feature.

**Golem Body.** Your spirit jar is your artificial golem body. It has a specific weakness, which you must discuss with your GM. Your rejuvenation is only stopped when your body is completely destroyed using its weakness. When you drop to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), you temporarily die and reanimate with half of your [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) after 1 hour.

**Gruesome Physicality.** Your Strength, Dexterity, and Constitution scores become 20 if they weren't already higher.

**Damage Resistance.** You gain [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to Bludgeoning, Piercing, and Slashing damage.

**Self-Stitches.** You can apply any number of Spell-Stiches to yourself as a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, expending [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20\(Level%201\)) points as normal. Spell-Stitches applied in this way last until you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).
