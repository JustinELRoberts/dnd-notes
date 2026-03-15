---
publish: true
aliases:
  - Captain
created: 2026-03-09T12:15:34.138-04:00
modified: 2026-03-09T12:15:34.138-04:00
published: 2026-03-09T12:15:34.138-04:00
tags:
  - ttrpg-cli/class/captain
  - ttrpg-cli/compendium/src/5e/valdaspire24
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Captain
*Source: Valda's Spire of Secrets (2024)*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='4'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Battle Dice</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Battle Tactics (Level 1)' class='internal-link'>Battle Tactics</a>, <a href='#Weapon Mastery (Level 1)' class='internal-link'>Weapon Mastery</a></td><td class="value">`2d6`</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Cohort (Level 2)' class='internal-link'>Cohort</a>, <a href='#Fighting Style (Level 2)' class='internal-link'>Fighting Style</a></td><td class="value">`2d6`</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Captain Subclass (Level 3)' class='internal-link'>Captain Subclass</a></td><td class="value">`2d6`</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">`2d6`</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Blitz (Level 5)' class='internal-link'>Blitz</a></td><td class="value">`3d6`</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 6)' class='internal-link'>Subclass Feature</a></td><td class="value">`3d6`</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Valiant Surge (Level 7)' class='internal-link'>Valiant Surge</a></td><td class="value">`3d6`</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">`3d6`</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"><a href='#Cohort (Level 9)' class='internal-link'>Cohort</a></td><td class="value">`3d8`</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">`3d8`</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"><a href='#Coordinated Strike (Level 11)' class='internal-link'>Coordinated Strike</a></td><td class="value">`3d8`</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">`3d8`</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"><a href='#Cohort (Level 13)' class='internal-link'>Cohort</a></td><td class="value">`4d8`</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Subclass Feature (Level 14)' class='internal-link'>Subclass Feature</a></td><td class="value">`4d8`</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Lead by Example (Level 15)' class='internal-link'>Lead by Example</a></td><td class="value">`4d8`</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">`4d8`</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Cohort (Level 17)' class='internal-link'>Cohort</a></td><td class="value">`5d8`</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Teamwork Maneuvers (Level 18)' class='internal-link'>Teamwork Maneuvers</a></td><td class="value">`5d8`</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">`5d8`</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Legendary Commander (Level 20)' class='internal-link'>Legendary Commander</a></td><td class="value">`5d8`</td></tr>
> </tbody></table>

^class-progression

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Class/Captain.webp#right)

## Hit Points

- **Hit Dice**: 1d8 per Captain level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 5 OR 1d8 + CON  (minimum of 1)

## Starting Captain

- **Saving Throw Proficiencies**: Charisma, Constitution
- **Skill Proficiencies**: *Choose 2:* [Animal Handling](Mechanics/CLI/rules/skills.md#Animal%20Handling), [Athletics](Mechanics/CLI/rules/skills.md#Athletics), [Deception](Mechanics/CLI/rules/skills.md#Deception), [History](Mechanics/CLI/rules/skills.md#History), [Insight](Mechanics/CLI/rules/skills.md#Insight), [Intimidation](Mechanics/CLI/rules/skills.md#Intimidation), [Perception](Mechanics/CLI/rules/skills.md#Perception), or [Persuasion](Mechanics/CLI/rules/skills.md#Persuasion)
- **Weapon Proficiencies**: Simple weapons and Martial weapons
- **Armor Training**: [Light armor](Mechanics/CLI/rules/item-types.md#Light%20Armor), [Medium armor](Mechanics/CLI/rules/item-types.md#Medium%20Armor), [Heavy armor](Mechanics/CLI/rules/item-types.md#Heavy%20Armor), and [Shields](Mechanics/CLI/items/shield-xphb.md)

**Starting Equipment:** *Choose A, B, or C:* (A) [Chain Shirt](Mechanics/CLI/items/chain-shirt-xphb.md), [Shield](Mechanics/CLI/items/shield-xphb.md), [Longsword](Mechanics/CLI/items/longsword-xphb.md), 6 [Javelins](Mechanics/CLI/items/javelin-xphb.md), [Explorer's Pack](Mechanics/CLI/items/explorers-pack-xphb.md), and 54 GP; (B) [Studded Leather Armor](Mechanics/CLI/items/studded-leather-armor-xphb.md), 2 [Shortswords](Mechanics/CLI/items/shortsword-xphb.md), [Longbow](Mechanics/CLI/items/longbow-xphb.md), 20 [Arrows](Mechanics/CLI/items/arrow-xphb.md), [Quiver](Mechanics/CLI/items/quiver-xphb.md), [Explorer's Pack](Mechanics/CLI/items/explorers-pack-xphb.md), and 11 GP; or (C) 140 GP

## Multiclassing Captain

- **Weapon Proficiencies**: Martial weapons
- **Armor Training**: [Light armor](Mechanics/CLI/rules/item-types.md#Light%20Armor), [Medium armor](Mechanics/CLI/rules/item-types.md#Medium%20Armor), [Shields](Mechanics/CLI/items/shield-xphb.md)

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Class/Captain-Cover.webp#center)

## Captain

Decisive leaders and brilliant strategists, Captains inspire their allies to greatness. They stand alongside their Cohorts—their devoted lieutenants—whom they entrust with their lives. Captains out-strategize their enemies, ensuring that, while they rarely deal the killing blow, they're always on the winning side.

### Fearless Leaders

A Captain thinks a little bigger than their compatriots, planning one step further and fitting their allies like puzzle pieces to the challenges ahead. To their eyes, there are few defeats; only setbacks, diversions, and detours. Success is always on the path ahead.

Moreover, Captains lead by example. They stand shoulder-to-shoulder with knights, creep through the night alongside rogues, and study arcane texts with mages, even when they barely understand what they're reading.

### Cohort and Commander

A Captain is only as good as their second in command, their Cohort, who stands by them at every step and safeguards their plan's success. Far more than an ally, a Captain's Cohort is a confidant, an advisor, and a trusted friend. Cohorts see their Captain as a wellspring of information, and will follow them to the ends of the earth.

## Class Features

### Battle Tactics (Level 1)

You learn maneuvers that are fueled by special dice called Battle Dice.

**Battle Dice.** You have two Battle Dice, which are d6s. A Battle Die is expended when you use it. You regain all expended Battle Dice when you roll [Initiative](Mechanics/CLI/rules/variant-rules/initiative-xphb.md) or finish a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). Your Battle Die changes and more Battle Dice become available as shown on the Battle Dice column of the Captain Features table.

**Maneuvers.** You can expend Battle Dice to perform maneuvers. Your maneuver options are detailed later in the class description.

**Saving Throws.** If a maneuver requires a saving throw, the DC equals 8 plus your Strength or Dexterity modifier and [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md).

**Maneuver Options.** Options:

- [Bolster](Mechanics/CLI/optional-features/bolster-valdaspire24.md)  
- [Born Leader](Mechanics/CLI/optional-features/born-leader-valdaspire24.md)  
- [Morale Boost](Mechanics/CLI/optional-features/morale-boost-valdaspire24.md)  
- [Rally](Mechanics/CLI/optional-features/rally-valdaspire24.md)  
- [Staggering Strike](Mechanics/CLI/optional-features/staggering-strike-valdaspire24.md)  

### Weapon Mastery (Level 1)

Your training with weapons allows you to use the [mastery properties](Mechanics/CLI/rules/variant-rules/weapon-mastery-properties-xphb.md) of two kinds of weapons of your choice with which you have proficiency, such as [Lances](Mechanics/CLI/items/lance-xphb.md) and [Longswords](Mechanics/CLI/items/longsword-xphb.md).

Whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you can change the kinds of weapons you chose.

### Cohort (Level 2)

You gain a loyal Cohort who carries your banner and follows your lead.

**Initiating a Cohort.** Choose your Cohort's stat block from those listed later in the class description. Following an 8-hour initiation period, which can be done during a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), that creature becomes your Cohort until you initiate a new Cohort to replace it. You can have only one Cohort at a time.

**Cohort in Combat.** Your Cohort is [Friendly](Mechanics/CLI/rules/variant-rules/friendly-attitude-xphb.md) to you and your allies and obeys your commands. In combat, your Cohort takes its turn immediately before or after your turn each round (your choice). Your Cohort uses your Charisma for its attack and damage rolls.

**Cohort Save DC.** If your Cohort forces a creature to make a saving throw, the DC is 8 plus your Charisma modifier and your [Proficiency](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md) bonus.

**Features.** Your Cohort improves and gains new features when you reach certain Captain levels, as shown on the Captain Features table.

**Proficiencies.** Your Cohort has proficiency in skills and saving throws listed in its statistics. Your Cohort uses your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md) instead of its own. Because Cohort statistics already include a +2 [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), you need only adjust skill and saving throw proficiencies starting at level 5.

> [!note] Cohort Species
> 
> When you initiate a new Humanoid Cohort, you can also give it one of the following traits to reflect its species.
> 
> **Dragonborn Draconic Ancestry.** The Cohort has [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to one of the following types of damage associated with its dragon progenitor (Captain's choice): Acid, Cold, Fire, Lightning, or Poison.
> 
> **Dwarf Resistances and Immunities.** The Cohort has [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to Poison damage and [Immunity](Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to the [Poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) condition.
> 
> **Elf Fey Ancestry.** The Cohort has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws it makes to avoid or end the [Charmed](Mechanics/CLI/rules/conditions.md#Charmed) condition.
> 
> **Gnome Saving Throws.** The Cohort has proficiency in one of the following saving throws: Intelligence, Wisdom, or Charisma.
> 
> **Goliath Powerful Build.** The Cohort has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on any ability check it makes to end the [Grappled](Mechanics/CLI/rules/conditions.md#Grappled) condition. It also counts as one size larger when determining its carrying capacity.
> 
> **Halfling Brave.** The Cohort has [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws it makes to avoid or end the [Frightened](Mechanics/CLI/rules/conditions.md#Frightened) condition.
> 
> **Human Skillful.** The Cohort has proficiency with one skill of your choice.
> 
> **Orc Relentless (1/Day).** When the Cohort is reduced to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), it is reduced to 1 [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) instead.
> 
> **Tiefling Fiendish Ancestry.** The Cohort has [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to one of the following types of damage associated with its fiendish progenitor (Captain's choice): Fire, Necrotic, or Poison.
^cohort-species

> [!note] Cohort Spells
> 
> Throughout your adventure, you may wish to customize the spells listed in a Cohort's stat block. You can exchange one of the spells listed in the Spellcasting feature with another of the same level. Your GM decides if a spell is appropriate for a Cohort. Generally, the Priest's spells are from the Cleric spell list, the Mage's spells are from the Wizard spell list, and the Shaman's spells are from the Druid spell list.
^cohort-spells

### Fighting Style (Level 2)

You gain a Fighting Style feat of your choice.

Whenever you gain a Captain level, you can replace the feat you chose with a different Fighting Style feat.

### Captain Subclass (Level 3)

You gain a Captain subclass of your choice. A subclass is a specialization that grants you features at certain Captain levels. For the rest of your career, you gain each of your subclass's features that are of your Captain level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Blitz (Level 5)

Once on each of your turns, you can direct your Cohort or an ally within 60 feet of yourself that can see or hear you. The chosen creature can take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) to move up to its [Speed](Mechanics/CLI/rules/variant-rules/speed-xphb.md) or make one attack with a weapon or [Unarmed Strike](Mechanics/CLI/rules/variant-rules/unarmed-strike-xphb.md).

### Subclass Feature (Level 6)

You gain a feature from your Captain Subclass.

### Valiant Surge (Level 7)

Whenever you or your Cohort score a [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md) or reduce an enemy to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), you regain an expended Battle Die.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Cohort (Level 9)

Your Cohort improves and gains a new feature.

### Subclass Feature (Level 10)

You gain a feature from your Captain Subclass.

### Coordinated Strike (Level 11)

Once per turn when you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action and hit with a weapon, you can deal an extra `2d8` damage to the target if your Cohort has dealt damage to that target since the end of your last turn. The extra damage is the same type dealt by the weapon.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Cohort (Level 13)

Your Cohort improves and gains a new feature.

### Subclass Feature (Level 14)

You gain a feature from your Captain Subclass.

### Lead by Example (Level 15)

Whenever you or your Cohort score a [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md), each ally you choose within 30 feet of you gains [Heroic Inspiration](Mechanics/CLI/rules/variant-rules/heroic-inspiration-xphb.md).

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Cohort (Level 17)

Your Cohort improves and gains a new feature.

### Teamwork Maneuvers (Level 18)

When you use a maneuver that targets an ally, you can target a second ally within range without expending an additional Battle Die.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Legendary Commander (Level 20)

Immediately after another creature's turn, you can choose yourself or an ally within 60 feet of yourself that can see or hear you to take a Legendary Action. This action is one of the following: [Attack](Mechanics/CLI/rules/actions.md#Attack) (one attack only), [Dash](Mechanics/CLI/rules/actions.md#Dash), [Disengage](Mechanics/CLI/rules/actions.md#Disengage), [Dodge](Mechanics/CLI/rules/actions.md#Dodge), [Hide](Mechanics/CLI/rules/actions.md#Hide), [Magic](Mechanics/CLI/rules/actions.md#Magic) (cast one cantrip only), or [Utilize](Mechanics/CLI/rules/actions.md#Utilize). A creature can only take one Legendary Action each round. When a creature takes the [Dash](Mechanics/CLI/rules/actions.md#Dash) or [Disengage](Mechanics/CLI/rules/actions.md#Disengage) action in this way, the benefits of that action last until the end of the creature's next turn.

You can use this feature to take three Legendary Actions and regain all expended uses when you finish a [Short](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md) or [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).