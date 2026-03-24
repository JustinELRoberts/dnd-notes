---
publish: true
aliases:
  - Rimekeeper
created: 2026-03-09T12:15:33.943-04:00
modified: 2026-03-09T12:15:33.943-04:00
published: 2026-03-09T12:15:33.943-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24extras
  - ttrpg-cli/subclass/warden/rimekeeper
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Rimekeeper

_[Warden](./warden-valdaspire24.md): Subclass Feature_\
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
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Rimekeeper (Level 3)' class='internal-link'>Rimekeeper</a></td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Ice Blast (Level 6)' class='internal-link'>Ice Blast</a></td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Snowclad (Level 10)' class='internal-link'>Snowclad</a></td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Hoarfrost Herald (Level 17)' class='internal-link'>Hoarfrost Herald</a></td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"></td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"></td></tr>
> </tbody></table>

^class-progression

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWarden/Class/Rimekeeper.webp#right)

_Channel the Polar Winds_

Your call was the howling, icy winds of a remote arctic land. As a Rimekeeper, you defend the people of these frigid lands from colossal creatures that thrive in the frost and invaders that hail from warmer places. Wherever you travel, the north wind follows, summoned at your fingertips with hailstones and ice.

## Subclass Features

### North Wind (Level 3)

When you use Block or Challenge on a Large or smaller creature, you can create a howling wind to either pull the target 10 feet in a straight line toward you or push the target up to 10 feet straight away from you.

### Polar Acclimation (Level 3)

Your adaptation to arctic climates grants you the following benefits.

**Cold Resistance.** You have [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to Cold damage.

**Frozen Weapons.** When you deal damage with a weapon or an [Unarmed Strike](Mechanics/CLI/rules/variant-rules/unarmed-strike-xphb.md), it can deal your choice of Cold damage or its normal damage type.

**Frigid Weapons.** When you attack with a Melee weapon whose mastery property you can use, you can replace that property with the [Slow](Mechanics/CLI/rules/item-mastery.md#Slow) property for that attack.

### Ice Blast (Level 6)

As a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, you can unleash a burst of ice from your hands. You can use this ice to create one of the following magical effects of your choice within 5 feet of you. If an effect calls for a saving throw or ability check, the DC equals 8 plus your Constitution modifier and your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md).

**Black Ice.** You can create a slick area of ice covering the ground in a 5-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) centered on yourself. When the ice appears, each creature other than yourself standing in its area must succeed on a Dexterity saving throw or have the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition. A creature that enters the area for the first time on a turn or ends its turn there must also succeed on that save or fall [Prone](Mechanics/CLI/rules/conditions.md#Prone). This ice melts after 1 minute or if you create this effect again.

**Freeze Shut.** You freeze over a closed door, window, gate, container, or hatch, causing it to become stuck. A Strength ([Athletics](Mechanics/CLI/rules/skills.md#Athletics)) check can force the object open again. This ice melts after 10 minutes.

**Frostbite.** You bombard a creature you can see with frost. The target makes a Constitution saving throw, taking `2d12` Cold damage on a failed save or half as much damage on a successful one. This damage increases by `1d12` at Warden levels 11 (`3d12`) and 17 (`4d12`).

**Snowbank.** You deposit enough snow and ice in a 10-foot-wide bank to provide [Half Cover](Mechanics/CLI/rules/variant-rules/cover-xphb.md) for two Medium creatures. This bank melts after 10 minutes.

### Snowclad (Level 10)

You gain [Temporary Hit Points](Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) equal to your Constitution modifier at the start of each of your turns if you don't have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

### Hoarfrost Herald (Level 17)

You can embrace the bitter chill of hoarfrost. As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can gain the benefits below for 1 minute or until you choose to end them (no action required). Once you use this feature, you can't use it again until you finish a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

**Cold Immunity.** You have [Immunity](Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to Cold damage.

**Frostbite Strike.** When you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action, you can replace one of your attacks with a use of the Frostbite option of your Ice Blast.

**Iceclad.** You gain [Temporary Hit Points](Mechanics/CLI/rules/variant-rules/temporary-hit-points-xphb.md) equal to twice your Constitution modifier at the start of each of your turns if you don't have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.
