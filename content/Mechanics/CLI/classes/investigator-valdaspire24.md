---
obsidianUIMode: preview
cssclasses:
- json5e-class
tags:
- ttrpg-cli/class/investigator
- ttrpg-cli/compendium/src/5e/valdaspire24
aliases:
- "Investigator"
---
# Investigator
*Source: Valda's Spire of Secrets (2024)*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='7'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Ritual Level</th><th class="value">Rushed Incantation</th><th class="value">Finisher</th><th class="value">Trinkets</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Ritualist (Level 1)' class='internal-link'>Ritualist</a>, <a href='#Weapon Mastery (Level 1)' class='internal-link'>Weapon Mastery</a></td><td class="value">1</td><td class="value">-</td><td class="value">⏤</td><td class="value">⏤</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Expertise (Level 2)' class='internal-link'>Expertise</a>, <a href='#Finisher (Level 2)' class='internal-link'>Finisher</a>, <a href='#Rushed Incantation (Level 2)' class='internal-link'>Rushed Incantation</a></td><td class="value">1</td><td class="value">3</td><td class="value">`1d8`</td><td class="value">⏤</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Investigator Subclass (Level 3)' class='internal-link'>Investigator Subclass</a>, <a href='#Trinkets (Level 3)' class='internal-link'>Trinkets</a></td><td class="value">2</td><td class="value">4</td><td class="value">`1d8`</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">2</td><td class="value">4</td><td class="value">`1d8`</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Exploit Weakness (Level 5)' class='internal-link'>Exploit Weakness</a></td><td class="value">3</td><td class="value">5</td><td class="value">`1d8`</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 6)' class='internal-link'>Subclass Feature</a></td><td class="value">3</td><td class="value">5</td><td class="value">`1d8`</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Holy Trinkets (Level 7)' class='internal-link'>Holy Trinkets</a></td><td class="value">4</td><td class="value">6</td><td class="value">`1d8`</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">4</td><td class="value">6</td><td class="value">`1d8`</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"><a href='#Expertise (Level 9)' class='internal-link'>Expertise</a></td><td class="value">5</td><td class="value">7</td><td class="value">`1d8`</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">5</td><td class="value">7</td><td class="value">`1d8`</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"><a href='#Improved Finisher (Level 11)' class='internal-link'>Improved Finisher</a></td><td class="value">6</td><td class="value">7</td><td class="value">`2d8`</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">6</td><td class="value">8</td><td class="value">`2d8`</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"><a href='#Enigma Arcane (Level 13)' class='internal-link'>Enigma Arcane</a></td><td class="value">6</td><td class="value">8</td><td class="value">`2d8`</td><td class="value">5</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Subclass Feature (Level 14)' class='internal-link'>Subclass Feature</a></td><td class="value">6</td><td class="value">8</td><td class="value">`2d8`</td><td class="value">5</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Enigma Arcane (Level 15)' class='internal-link'>Enigma Arcane</a></td><td class="value">6</td><td class="value">9</td><td class="value">`2d8`</td><td class="value">5</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">6</td><td class="value">9</td><td class="value">`2d8`</td><td class="value">5</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Enigma Arcane (Level 17)' class='internal-link'>Enigma Arcane</a></td><td class="value">6</td><td class="value">9</td><td class="value">`3d8`</td><td class="value">6</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Supernatural Resolve (Level 18)' class='internal-link'>Supernatural Resolve</a></td><td class="value">6</td><td class="value">10</td><td class="value">`3d8`</td><td class="value">6</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">6</td><td class="value">10</td><td class="value">`3d8`</td><td class="value">6</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Spellbinder (Level 20)' class='internal-link'>Spellbinder</a></td><td class="value">6</td><td class="value">10</td><td class="value">`3d8`</td><td class="value">6</td></tr>
> </tbody></table>

^class-progression

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaInvestigator/Class/Investigator.webp#right)

## Hit Points

- **Hit Dice**: 1d8 per Investigator level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 5 OR 1d8 + CON  (minimum of 1)

## Starting Investigator

- **Saving Throw Proficiencies**: Dexterity, Intelligence
- **Skill Proficiencies**: *Choose 3:* [Arcana](Mechanics/CLI/rules/skills.md#Arcana), [Athletics](Mechanics/CLI/rules/skills.md#Athletics), [Deception](Mechanics/CLI/rules/skills.md#Deception), [History](Mechanics/CLI/rules/skills.md#History), [Insight](Mechanics/CLI/rules/skills.md#Insight), [Intimidation](Mechanics/CLI/rules/skills.md#Intimidation), [Investigation](Mechanics/CLI/rules/skills.md#Investigation), [Medicine](Mechanics/CLI/rules/skills.md#Medicine), [Nature](Mechanics/CLI/rules/skills.md#Nature), [Perception](Mechanics/CLI/rules/skills.md#Perception), [Persuasion](Mechanics/CLI/rules/skills.md#Persuasion), [Religion](Mechanics/CLI/rules/skills.md#Religion), [Sleight of Hand](Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand), or [Stealth](Mechanics/CLI/rules/skills.md#Stealth)
- **Weapon Proficiencies**: Simple weapons and Martial weapons
- **Armor Training**: [Light armor](Mechanics/CLI/rules/item-types.md#Light%20Armor)

**Starting Equipment:** *Choose A or B:* (A) [Leather Armor](Mechanics/CLI/items/leather-armor-xphb.md), 2 [Daggers](Mechanics/CLI/items/dagger-xphb.md), [Rapier](Mechanics/CLI/items/rapier-xphb.md), [Heavy Crossbow](Mechanics/CLI/items/heavy-crossbow-xphb.md), 20 [Crossbow Bolts](Mechanics/CLI/items/bolt-xphb.md), [Crossbow Bolt Case](Mechanics/CLI/items/crossbow-bolt-case-xphb.md), [Dungeoneer's Pack](Mechanics/CLI/items/dungeoneers-pack-xphb.md) and 17 GP; or (B) 120 GP

## Multiclassing Investigator

- Gain the following traits from the Core Investigator Traits table: Hit Point Die, proficiency in one skill of your choice from the Investigators skill list, proficiency with Martial Weapons, and training with Light Armor.  
- Gain the Investigator's level 1 features, which are listed in the Investigator Features table  

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaInvestigator/Class/Investigator-Class.webp#center)

## Investigator

Supernatural detectives and monster slayers, Investigators are always on the hunt for malevolent outsiders. Whenever evil seeps into the world—be it Fiends, Undead, or strange Aberrations from beyond the stars—Investigators will be the first to locate them and banish their foul corruption from the mortal plane.

### Paranormal Investigators

There are forces more ancient than time, foes more sinister than the foulest men, and beings more titanic than gods. Investigators risk their lives and psyches to protect the world from supernatural threats, unraveling the mysteries of one werewolf or demonic cult at a time. Their investigations are never ending, for victory only delays doomsday another night.

### Exorcists and Occultists

To give themselves an edge against supernatural threats, Investigators dabble in forbidden magic themselves. Prepared Investigators keep a well-stocked grimoire of rituals, incantations, and notes on the powers and weaknesses of monsters—everything needed to level the playing field. Even so, an Investigator's occupation is perilous. A grimoire might spell out a vampire's fear of sunlight and aversion to silver, but it does little to hinder their fangs.

## Class Features

### Ritualist (Level 1)

You have learned to cast [Rituals](Mechanics/CLI/rules/variant-rules/ritual-xphb.md) to overcome supernatural threats.

**Grimoire.** Your [Rituals](Mechanics/CLI/rules/variant-rules/ritual-xphb.md) are recorded in a grimoire, a Tiny object that weighs 3 pounds and contains 100 pages. You determine the grimoire's appearance and materials.

The grimoire starts with four level 1 Investigator spells of your choice. [Detect Magic](Mechanics/CLI/spells/detect-magic-xphb.md), [Heroism](Mechanics/CLI/spells/heroism-xphb.md), [Memorize](Mechanics/CLI/spells/memorize-valdaspire24.md), and [Transient Bulwark](Mechanics/CLI/spells/transient-bulwark-valdaspire24.md) are recommended.

Whenever you gain an Investigator level, you can add two Investigator spells of your choice to your grimoire. The [Ritual](Mechanics/CLI/rules/variant-rules/ritual-xphb.md) Level column on the Investigator Feature table shows the maximum level of a spell you can add to your grimoire.

**Ritual Casting.** You can cast any spell as a [Ritual](Mechanics/CLI/rules/variant-rules/ritual-xphb.md) if that spell has the [Ritual](Mechanics/CLI/rules/variant-rules/ritual-xphb.md) tag and the spell is in your grimoire. You must read from the book to cast a spell in this way. You can't cast spells that are in your grimoire except as [Rituals](Mechanics/CLI/rules/variant-rules/ritual-xphb.md), unless you've learned them by other means.

**Bonus Rituals.** You can treat specific spells as if they have the [Ritual](Mechanics/CLI/rules/variant-rules/ritual-xphb.md) tag, allowing you to add them to your grimoire and cast them as [Rituals](Mechanics/CLI/rules/variant-rules/ritual-xphb.md). These spells are marked in the Investigator Spells list.

**Spellcasting Ability.** Intelligence is your spellcasting ability for your Investigator spells.

> [!note] Expanding and Replacing a Grimoire
> 
> The spells you add to your grimoire represent research into occult and supernatural threats, but you might find other spells during your adventures that you can add to your grimoire.
> 
> **Copying a Spell into the Grimoire.** When you find a level 1+ Investigator spell, you can copy it into your grimoire if it's of an eligible level and if you have time to copy it. For each level of the spell, the transcription takes 2 hours and costs 50 GP.
> 
> **Copying the Grimoire.** You can copy a spell from your grimoire into another book. This is like copying a new spell into your grimoire but faster, since you already know how to cast the spell. You need spend only 1 hour and 10 GP for each level of the copied spell.
> 
> If you lose your grimoire, you can recall from memory a number of spells equal to your Investigator level and use the same procedure to transcribe the spells into a new grimoire. Filling out the remainder of the new book requires you to find new spells to do so. For this reason, many Investigators keep a backup grimoire.
^expanding-and-replacing-a-grimoire

### Weapon Mastery (Level 1)

Your training with weapons allows you to use the [mastery properties](Mechanics/CLI/rules/variant-rules/weapon-mastery-properties-xphb.md) of two kinds of weapons of your choice with which you have proficiency, such as [Rapiers](Mechanics/CLI/items/rapier-xphb.md) and [Heavy Crossbows](Mechanics/CLI/items/heavy-crossbow-xphb.md).

Whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you can change the kinds of weapons you chose.

### Expertise (Level 2)

You gain [Expertise](Mechanics/CLI/rules/variant-rules/expertise-xphb.md) in two of your skill proficiencies of your choice. [Arcana](Mechanics/CLI/rules/skills.md#Arcana) and [Investigation](Mechanics/CLI/rules/skills.md#Investigation) are recommended if you have proficiency in them.

At Investigator level 9, you gain [Expertise](Mechanics/CLI/rules/variant-rules/expertise-xphb.md) in two more of your skill proficiencies of your choice.

### Finisher (Level 2)

Once per turn when you deal damage with a weapon to a creature that is [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), you can deal an extra `1d8` damage to the target. The damage is the same type as the damage dealt by the weapon.

This damage increases as you gain Investigator levels, as shown in the Finisher column of the Investigator Features table.

### Rushed Incantation (Level 2)

You can hastily perform any spell in your grimoire that has a casting time of an action or [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), casting the spell as a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md). You can cast it without Material components unless the components have a cost of 100+ GP specified by the spell.

You can use this feature three times. You regain one of its expended uses when you finish a [Short Rest](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md), and you regain all expended uses when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). You gain additional uses when you reach certain Investigator levels, as shown in the Rushed Incantation column of the Investigator Features table.

### Investigator Subclass (Level 3)

You gain a Investigator subclass of your choice. A subclass is a specialization that grants you features at certain Investigator levels. For the rest of your career, you gain each of your subclass's features that are of your Investigator level or lower.

### Trinkets (Level 3)

Your subclass grants you a number of supernatural trinkets to aid you in defeating supernatural threats and unraveling mysteries. You can use this feature twice, activating one of your trinket options each time you use it. You regain one of its expended uses when you finish a [Short Rest](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md), and you regain all expended uses when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). You gain additional uses when you reach certain Investigator levels, as shown in the Trinkets column of the Investigator Features table.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Exploit Weakness (Level 5)

Once per turn when you deal damage to a creature with an attack using a weapon, you can target the creature where it is most vulnerable to gain the following benefits.

**Damage Vulnerability.** Choose one damage type dealt by the attack. The target has [Vulnerability](Mechanics/CLI/rules/variant-rules/vulnerability-xphb.md) to the chosen damage type for this attack. [Vulnerability](Mechanics/CLI/rules/variant-rules/vulnerability-xphb.md) from this feature doesn't double extra damage from spells (such as [Hunter's Mark](Mechanics/CLI/spells/hunters-mark-xphb.md)) or features from other classes (such as the Rogue's Sneak Attack). The [Vulnerability](Mechanics/CLI/rules/variant-rules/vulnerability-xphb.md) doesn't apply to this attack if the target has [Immunity](Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to the chosen damage type.

**Disrupt Resistance.** If the target has [Resistance](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) to one or more damage types, it loses these [Resistances](Mechanics/CLI/rules/variant-rules/resistance-xphb.md) until the start of your next turn, including against the damage of the triggering attack.

### Subclass Feature (Level 6)

You gain a feature from your Investigator Subclass.

### Holy Trinkets (Level 7)

You keep a wide array of [Holy Symbols](Mechanics/CLI/items/holy-symbol-xphb.md) and blessed items on your person, even if you aren't particularly pious. You can use the following trinkets (expending a use of your [Trinkets](Mechanics/CLI/classes/investigator-valdaspire24.md#Trinkets%20(Level%203)) to do so).

**Amulet of Warding.** As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you place a divine ward on a creature of your choice within 60 feet of you. Until the start of your next turn, the warded creature gains a bonus to AC and saving throws equal to your Intelligence modifier (minimum of +1).

**Restorative Ankh.** As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), a creature of your choice within 60 feet of you regains [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to your Investigator level plus your Intelligence modifier.

**Rune of Banishment.** As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), choose one creature you can see within 60 feet of you. The creature must succeed on a Charisma saving throw against your spell save DC or be banished to a harmless location in the Ethereal Plane. While banished, the target has the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition and its [Speed](Mechanics/CLI/rules/variant-rules/speed-xphb.md) is 0. At the start of your next turn, the creature reappears in the space it left or in the nearest unoccupied space if that space is occupied.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Expertise (Level 9)

At Investigator level 9, you gain [Expertise](Mechanics/CLI/rules/variant-rules/expertise-xphb.md) in two more of your skill proficiencies of your choice.

### Subclass Feature (Level 10)

You gain a feature from your Investigator Subclass.

### Improved Finisher (Level 11)

When you take the [Attack](Mechanics/CLI/rules/actions.md#Attack) action on your turn, you can use your Finisher on a creature that isn't [Bloodied](Mechanics/CLI/rules/conditions.md#Bloodied), dealing only an extra `1d8` damage to the target.

At Investigator level 17, this damage increases to `2d8`.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Enigma Arcane (Level 13)

You learn a secret that unlocks potent arcane magic. You gain the ability to cast a level 7 spell, and discover additional secrets when you reach certain Investigator levels.

**Level 7 Spell.** You can cast one of the following spells without a spell slot and regain the ability to do so when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md): [Mirage Arcane](Mechanics/CLI/spells/mirage-arcane-xphb.md), [Plane Shift](Mechanics/CLI/spells/plane-shift-xphb.md), [Reverse Gravity](Mechanics/CLI/spells/reverse-gravity-xphb.md), [Sequester](Mechanics/CLI/spells/sequester-xphb.md), or [Teleport](Mechanics/CLI/spells/teleport-xphb.md).

### Subclass Feature (Level 14)

You gain a feature from your Investigator Subclass.

### Enigma Arcane (Level 15)

**Level 8 Spell.** At Investigator level 15, you can also cast one of the following spells without a spell slot and regain the ability to do so when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md): [Antimagic Field](Mechanics/CLI/spells/antimagic-field-xphb.md), [Glibness](Mechanics/CLI/spells/glibness-xphb.md), [Maze](Mechanics/CLI/spells/maze-xphb.md), or [Mind Blank](Mechanics/CLI/spells/mind-blank-xphb.md).

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Enigma Arcane (Level 17)

**Level 9 Spell.** At Investigator level 17, you can also cast one of the following spells without a spell slot and regain the ability to do so when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md): [Astral Projection](Mechanics/CLI/spells/astral-projection-xphb.md), [Gate](Mechanics/CLI/spells/gate-xphb.md), or [Weird](Mechanics/CLI/spells/weird-xphb.md).

### Supernatural Resolve (Level 18)

You have [Advantage](Mechanics/CLI/rules/variant-rules/advantage-xphb.md) on saving throws against spells and other magical effects unless you have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Spellbinder (Level 20)

Choose 5 Investigator spells in your grimoire of levels 1-3 that have a casting time of an action or [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md). You can use [Rushed Incantation](Mechanics/CLI/classes/investigator-valdaspire24.md#Rushed%20Incantation%20(Level%202)) to cast the chosen spells without expending a use of the feature, and you don't need to read from your grimoire to cast them.

Whenever you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md), you can replace one of those spells with another spell in your grimoire.