---
publish: true
aliases:
  - Warden
created: 2026-03-09T12:15:34.112-04:00
modified: 2026-03-09T12:15:34.112-04:00
published: 2026-03-09T12:15:34.112-04:00
tags:
  - ttrpg-cli/class/warden
  - ttrpg-cli/compendium/src/5e/valdaspire24
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Warden

_Source: Valda's Spire of Secrets (2024)_

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='5'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Interrupt</th><th class="value">Weapon Mastery</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Fighting Style (Level 1)' class='internal-link'>Fighting Style</a>, <a href='#Sentinel's Stand (Level 1)' class='internal-link'>Sentinel's Stand</a>, <a href='#Weapon Mastery (Level 1)' class='internal-link'>Weapon Mastery</a></td><td class="value">-</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Guardian Tactics (Level 2)' class='internal-link'>Guardian Tactics</a>, <a href='#Unyielding Resolve (Level 2)' class='internal-link'>Unyielding Resolve</a></td><td class="value">-</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Warden Subclass (Level 3)' class='internal-link'>Warden Subclass</a></td><td class="value">-</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">-</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Extra Attack (Level 5)' class='internal-link'>Extra Attack</a>, <a href='#Interrupt (Level 5)' class='internal-link'>Interrupt</a></td><td class="value">3</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 6)' class='internal-link'>Subclass Feature</a></td><td class="value">3</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Mettle (Level 7)' class='internal-link'>Mettle</a></td><td class="value">3</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">3</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"><a href='#Survive (Level 9)' class='internal-link'>Survive</a></td><td class="value">4</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">4</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"><a href='#Sentinel's Strike (Level 11)' class='internal-link'>Sentinel's Strike</a></td><td class="value">4</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">4</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"><a href='#Font of Life (Level 13)' class='internal-link'>Font of Life</a></td><td class="value">5</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Extended Tactics (Level 14)' class='internal-link'>Extended Tactics</a></td><td class="value">5</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Improved Resolve (Level 15)' class='internal-link'>Improved Resolve</a></td><td class="value">5</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">5</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Subclass Feature (Level 17)' class='internal-link'>Subclass Feature</a></td><td class="value">6</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Sentinel's Soul (Level 18)' class='internal-link'>Sentinel's Soul</a></td><td class="value">6</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">6</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Legendary Resistance (Level 20)' class='internal-link'>Legendary Resistance</a></td><td class="value">6</td><td class="value">4</td></tr>
> </tbody></table>

^class-progression

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWarden/Class/Warden.webp#right)

## Hit Points

- **Hit Dice**: 1d10 per Warden level
- **Hit Points at First Level:** 10 + CON
- **Hit Points at Higher Levels:** add 6 OR 1d10 + CON  (minimum of 1)

## Starting Warden

- **Saving Throw Proficiencies**: Constitution, Strength
- **Skill Proficiencies**: _Choose 2:_ [Animal Handling](Mechanics/CLI/rules/skills.md#Animal%20Handling), [Athletics](Mechanics/CLI/rules/skills.md#Athletics), [Insight](Mechanics/CLI/rules/skills.md#Insight), [Intimidation](Mechanics/CLI/rules/skills.md#Intimidation), [Medicine](Mechanics/CLI/rules/skills.md#Medicine), [Perception](Mechanics/CLI/rules/skills.md#Perception), [Persuasion](Mechanics/CLI/rules/skills.md#Persuasion), or [Survival](Mechanics/CLI/rules/skills.md#Survival)
- **Weapon Proficiencies**: Simple weapons and Martial weapons
- **Armor Training**: [Light armor](Mechanics/CLI/rules/item-types.md#Light%20Armor), [Medium armor](Mechanics/CLI/rules/item-types.md#Medium%20Armor), [Heavy armor](Mechanics/CLI/rules/item-types.md#Heavy%20Armor), and [Shields](Mechanics/CLI/items/shield-xphb.md)

**Starting Equipment:** _Choose A or B:_ (A) [Chain Mail](Mechanics/CLI/items/chain-mail-xphb.md), [Shield](Mechanics/CLI/items/shield-xphb.md), [Warhammer](Mechanics/CLI/items/warhammer-xphb.md), 6 [Javelins](Mechanics/CLI/items/javelin-xphb.md), [Dungeoneer's Pack](Mechanics/CLI/items/dungeoneers-pack-xphb.md), and 15 GP; or (B) 130 GP

## Multiclassing Warden

- **Weapon Proficiencies**: Martial weapons
- **Armor Training**: [Light armor](Mechanics/CLI/rules/item-types.md#Light%20Armor), [Medium armor](Mechanics/CLI/rules/item-types.md#Medium%20Armor), [Shields](Mechanics/CLI/items/shield-xphb.md)

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWarden/Class/Warden-Cover.webp#center)

## Warden

Armed with a shield and stubborn resolve, Wardens stand in defense of their allies and the innocent wherever they travel.

### Guardian's Call

Every Warden hears a call to defend the helpless. Sometimes, they are directly called, such as when a village selects their mightiest member to defend them. Other times, they are compelled by more subtle means, such as witnessing uncontested injustice or feeling the weight of responsibility when tragedy occurs. The result is the same: Wardens who pick up their Shields and dedicate themselves to a charge.

### Strength of Champions

A Warden's source of strength is their bottomless tolerance for punishment. Once they have adopted a group of creatures as their charge, a Warden might also reflect those particular strengths: a Beastblood Guardian learns to hunt and roar with Beasts, and a Verdant Protector commands plants as a treant does.

## Class Features

### Fighting Style (Level 1)

You gain a Fighting Style feat of your choice. [Defense](Mechanics/CLI/feats/defense-xphb.md) is recommended.

Whenever you gain a Warden level, you can replace the feat you chose with a different Fighting Style feat.

### Sentinel's Stand (Level 1)

You gain one of the following benefits of your choice. Whenever you gain a Warden level, you can replace the chosen benefit with another one.

**Stalwart Spirit.** You gain proficiency in one saving throw of your choice.

**Steadfast Toughness.** Your [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum is increased by your Constitution modifier plus your Warden level. If you later replace this choice, your [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) maximum no longer receives this increase.

**Tower Shield.** While you are holding a [Shield](Mechanics/CLI/items/shield-xphb.md), you have a +3 bonus to your AC instead of +2. At Warden level 10, this bonus increases to +4.

### Weapon Mastery (Level 1)

Your training with weapons allows you to use the [mastery properties](Mechanics/CLI/rules/variant-rules/weapon-mastery-properties-xphb.md) of two kinds of Simple or Martial Melee weapons of your choice, such as [Halberds](Mechanics/CLI/items/halberd-xphb.md) and [Longswords](Mechanics/CLI/items/longsword-xphb.md). Whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you can practice weapon drills and change one of those weapon choices.

When you reach certain Warden levels, you gain the ability to use the [mastery properties](Mechanics/CLI/rules/variant-rules/weapon-mastery-properties-xphb.md) of more kinds of weapons, as shown in the Weapon Mastery column of the Warden Features table.

### Guardian Tactics (Level 2)

Your resolute fortitude allows you to hinder your foes and protect your allies using the following tactics.

**Block.** As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can choose one ally you can see. Until the start of your next turn, the ally's AC equals your AC if it is lower than that while the ally is within 5 feet of you. This effect ends early if you or the ally have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

**Challenge.** As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can goad an enemy that can see or hear you into attacking you. Until the start of your next turn,  the enemy has [Disadvantage](Mechanics/CLI/rules/variant-rules/disadvantage-xphb.md) on attack rolls against creatures other than you while it is within 5 feet of you. This effect ends early if you have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

**Grasp.** As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can block the retreat of foes within a 5-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) originating from you until the start of your next turn. A creature within the [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) can't willingly move further away from you unless it first takes the [Disengage](Mechanics/CLI/rules/actions.md#Disengage) action. The [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md) ends early if you have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

### Unyielding Resolve (Level 2)

While you are [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), you have [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to Bludgeoning, Piercing, and Slashing damage.

### Warden Subclass (Level 3)

You gain a Warden subclass of your choice. A subclass is a specialization that grants you features at certain Warden levels. For the rest of your career, you gain each of your subclass's features that are of your Warden level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Extra Attack (Level 5)

You can attack twice instead of once whenever you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action on your turn.

### Interrupt (Level 5)

When an enemy within 5 feet of you takes an action—such as Multiattack—that allows it to make multiple attacks or use additional abilities as a part of the same action, you can take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) to prevent one of its attacks or abilities. You take this [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) before any [D20 Test](Mechanics/CLI/rules/variant-rules/d20-test-xphb.md) is rolled for the action.

The enemy makes one fewer attack or uses one fewer ability than normal. You learn what attacks and abilities the enemy uses and choose which one to interrupt.

**Number of Uses.** You can use this [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) three times. You regain one expended use when you finish a [Short Rest](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md), and you regain all expended uses when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

**At Higher Levels.** When you reach certain Warden levels, you gain more uses of this [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md), as shown in the Interrupt column of the Warden Features table.

### Subclass Feature (Level 6)

You gain a feature from your Warden Subclass.

### Mettle (Level 7)

Your determination allows you to shrug off effects that would otherwise harm you. When you're subjected to an effect that allows you to make a Constitution saving throw to take only half damage, you instead take no damage if you succeed on the saving throw and only half damage if you fail. You can't use this feature if you have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Survive (Level 9)

When you are reduced to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) and not killed outright, you can drop to 1 [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) instead, and you regain a number of [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to twice your Warden level.

Once you use this feature, you can't use it again until you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

### Subclass Feature (Level 10)

You gain a feature from your Warden Subclass.

### Sentinel's Strike (Level 11)

You gain one of the following benefits of your choice. Whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you can replace the chosen benefit with another one.

**Interdict.** When you use Interrupt, you can make a melee attack against the enemy as a part of the same [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md). Additionally, you regain a use of Interrupt when you roll [Initiative](Mechanics/CLI/rules/variant-rules/initiative-xphb.md).

**Shield Slam.** Once per turn when you attack a creature within 5 feet of you as part of the [Attack](Mechanics/CLI/rules/actions.md#Attack) action and hit with a Melee weapon, you can immediately bash the target with your [Shield](Mechanics/CLI/items/shield-xphb.md) if it's equipped. The target takes Bludgeoning damage equal to `1d8` plus the Shield's AC bonus.

**Sweep.** When you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action on your turn using a Melee weapon, you can make an attack against each creature you choose within 5 feet of you, with a separate attack roll for each target, instead of attacking twice.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Font of Life (Level 13)

At the start of your turn, you can end one of the following conditions on yourself (no action required): [Blinded](Mechanics/CLI/rules/conditions.md#Blinded), [Charmed](Mechanics/CLI/rules/conditions.md#Charmed), [Deafened](Mechanics/CLI/rules/conditions.md#Deafened), [Frightened](Mechanics/CLI/rules/conditions.md#Frightened), [Paralyzed](Mechanics/CLI/rules/conditions.md#Paralyzed), [Poisoned](Mechanics/CLI/rules/conditions.md#Poisoned), [Stunned](Mechanics/CLI/rules/conditions.md#Stunned), or [Restrained](Mechanics/CLI/rules/conditions.md#Restrained).

You can use this feature twice. You regain one expended use when you finish a [Short Rest](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md), and you regain all expended uses when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

### Extended Tactics (Level 14)

The range of your Guardian Tactics increases to 10 feet: your Block affects an ally within 10 feet of yourself, your Challenge affects an enemy within 10 feet of yourself, and your Grasp is a 10-foot [Emanation](Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md).

### Improved Resolve (Level 15)

While you are [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), you have [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to every damage type except Force, Necrotic, Psychic, and Radiant.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 17)

You gain a feature from your Warden Subclass.

### Sentinel's Soul (Level 18)

You gain one of the following benefits of your choice. Whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you can replace the chosen benefit with another one.

**All-Seeing.** You have [Blindsight](Mechanics/CLI/rules/senses.md#Blindsight) with a range of 30 feet. If you already have [Blindsight](Mechanics/CLI/rules/senses.md#Blindsight), its range increases by 30 feet.

**Fortified.** No attack roll can have [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) against you unless you have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

**Unstoppable.** You can move through the space of any creature. Moving through its space doesn't cost you extra movement, but you can't stop in the same space. If the creature is your size or smaller, it has the [Prone](Mechanics/CLI/rules/conditions.md#Prone) condition when you enter its space.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Legendary Resistance (Level 20)

If you fail a saving throw, you can choose to succeed instead.

You can use this feature three times, and regain all expended uses when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).
