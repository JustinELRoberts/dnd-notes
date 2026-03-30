---
publish: true
aliases:
  - Witch
created: 2026-03-29T21:53:56.058-04:00
modified: 2026-03-29T21:53:56.058-04:00
published: 2026-03-29T21:53:56.058-04:00
tags:
  - ttrpg-cli/class/witch
  - ttrpg-cli/compendium/src/5e/valdaspire24
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Witch

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='6'></th><th colspan='9'>Spell Slots per Spell Level</th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Hexes</th><th class="value">Cantrips</th><th class="value">Prepared Spells</th><th class="spellSlot">1st</th><th class="spellSlot">2nd</th><th class="spellSlot">3rd</th><th class="spellSlot">4th</th><th class="spellSlot">5th</th><th class="spellSlot">6th</th><th class="spellSlot">7th</th><th class="spellSlot">8th</th><th class="spellSlot">9th</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Spellcasting (Level 1)' class='internal-link'>Spellcasting</a>, <a href='#Witch's Curse (Level 1)' class='internal-link'>Witch's Curse</a>, <a href='#Hexes (Level 1)' class='internal-link'>Hexes</a></td><td class="value">2</td><td class="value">2</td><td class="value">2</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Cackle (Level 2)' class='internal-link'>Cackle</a>, <a href='#Familiar (Level 2)' class='internal-link'>Familiar</a></td><td class="value">3</td><td class="value">2</td><td class="value">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Witch Subclass (Level 3)' class='internal-link'>Witch Subclass</a></td><td class="value">3</td><td class="value">2</td><td class="value">6</td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">3</td><td class="value">3</td><td class="value">7</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Insidious Spell (Level 5)' class='internal-link'>Insidious Spell</a></td><td class="value">4</td><td class="value">3</td><td class="value">9</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 6)' class='internal-link'>Subclass Feature</a></td><td class="value">4</td><td class="value">3</td><td class="value">10</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Improved Familiar (Level 7)' class='internal-link'>Improved Familiar</a></td><td class="value">4</td><td class="value">3</td><td class="value">11</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">4</td><td class="value">3</td><td class="value">12</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"><a href='#Hastened Hex (Level 9)' class='internal-link'>Hastened Hex</a></td><td class="value">5</td><td class="value">3</td><td class="value">14</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">5</td><td class="value">4</td><td class="value">15</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"><a href='#Grand Hex (Level 11)' class='internal-link'>Grand Hex</a></td><td class="value">5</td><td class="value">4</td><td class="value">16</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">5</td><td class="value">4</td><td class="value">16</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"><a href='#Grand Hex (Level 13)' class='internal-link'>Grand Hex</a></td><td class="value">6</td><td class="value">4</td><td class="value">17</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Subclass Feature (Level 14)' class='internal-link'>Subclass Feature</a></td><td class="value">6</td><td class="value">4</td><td class="value">17</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Grand Hex (Level 15)' class='internal-link'>Grand Hex</a></td><td class="value">6</td><td class="value">4</td><td class="value">18</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">6</td><td class="value">4</td><td class="value">18</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Grand Hex (Level 17)' class='internal-link'>Grand Hex</a></td><td class="value">7</td><td class="value">4</td><td class="value">19</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Vengeful Curse (Level 18)' class='internal-link'>Vengeful Curse</a></td><td class="value">7</td><td class="value">4</td><td class="value">20</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">7</td><td class="value">4</td><td class="value">21</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Hexmaster (Level 20)' class='internal-link'>Hexmaster</a></td><td class="value">7</td><td class="value">4</td><td class="value">22</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> </tbody></table>

^class-progression

## Hit Points

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWitch/Class/Witch.webp#right)

- **Hit Dice**: 1d8 per Witch level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 5 OR 1d8 + CON  (minimum of 1)

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWitch/Class/Witch-Cover.webp#center)

## Starting a Witch

- **Saving Throw Proficiencies**: Charisma, Wisdom
- **Skill Proficiencies**: _Choose 2:_ [Arcana](/Mechanics/CLI/skills.md#Arcana), [Deception](/Mechanics/CLI/skills.md#Deception), [Insight](/Mechanics/CLI/skills.md#Insight), [Intimidation](/Mechanics/CLI/skills.md#Intimidation), [Nature](/Mechanics/CLI/skills.md#Nature), [Persuasion](/Mechanics/CLI/skills.md#Persuasion), [Religion](/Mechanics/CLI/skills.md#Religion), or [Survival](/Mechanics/CLI/skills.md#Survival)
- **Weapon Proficiencies**: Simple weapons
- **Armor Training**: [Light armor](/Mechanics/CLI/item-types.md#Light%20Armor)

**Starting Equipment:** _Choose A or B:_ (A) [Leather Armor](/Mechanics/CLI/items/leather-armor-xphb.md), [Sickle](/Mechanics/CLI/items/sickle-xphb.md), 2 [Daggers](/Mechanics/CLI/items/dagger-xphb.md), [Arcane Focus (orb)](/Mechanics/CLI/items/orb-xphb.md), [Explorer's Pack](/Mechanics/CLI/items/explorers-pack-xphb.md), and 5 GP; or (B) 50 GP

## Multiclassing Witch

- **Armor Training**: [Light armor](/Mechanics/CLI/item-types.md#Light%20Armor)

## Witch

Three old crones stoop over a boiling cauldron filled with all manner of bizarre filth, churning and bubbling with a noxious fume. In the smoke and vapor above the pot, the trio can make out shapes and figures of great import, and one cackles loudly at what she sees.

Witches are stricken by magic so dark it imprints a lasting shadow upon their essence. Through force of personality alone, they can spin this darkness outward, hexing creatures, casting manipulative spells, and even commanding a familiar with their thoughts.

### Cursed

While others are blessed with magic, Witches are cursed by it. Afflicted by some hateful arcana, whether accidentally or intentionally, Witches are twisted inside and out by its daily tortures. With grueling effort, they can warp this power into spells to wrack others with the same magic that plagues them.

### Pariahs and Outcasts

Almost without exception, Witches are feared and hated. They are victims of a number of misconceptions relating them to hags and other evil creatures of the night. As a result, known Witches are in great personal danger and can usually be found dwelling on the outskirts of civilization where townsfolk seldom tread. This does little to stop Witch hunting and burnings, but provides some measure of safety from them.

In reality, very few choose to become Witches, and many of them can hide adeptly in society, using their magic to fill a number of roles, from seer, to healer, to apothecary. Being accused as a Witch carries grave consequences, no matter the validity of the claim, so wise Witches relocate frequently, never residing in one place for too long.

## Class Features

### Spellcasting (Level 1)

You have learned to mold and reshape the magic that curses you into spells.

**Cantrips.** You know two cantrips of your choice from the Witch spell list. [Chill Touch](/Mechanics/CLI/spells/chill-touch-xphb.md) and [Minor Illusion](/Mechanics/CLI/spells/minor-illusion-xphb.md) are recommended. You can choose Hexes when you pick Witch cantrips.

Whenever you gain a Witch level, you can replace one of your cantrips with another cantrip of your choice from the Witch spell list.

When you reach Witch levels 4 and 10, you learn another cantrip of your choice from the Witch spell list, as shown in the Cantrips column of the Witch Features table.

**Spell Slots.** The Witch Features table shows how many spell slots you have to cast your level 1+ spells. You regain all expended slots when you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md).

**Prepared Spells of Level 1+.** You prepare the list of level 1+ spells that are available for you to cast with this feature. To start, choose two level 1 spells from the Witch spell list. [Hideous Laughter](/Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md) and [Thunderwave](/Mechanics/CLI/spells/thunderwave-xphb.md) are recommended.

The number of spells on your list increases as you gain Witch levels, as shown in the Prepared Spells column of the Witch Features table. Whenever that number increases, choose additional spells from the Witch spell list until the number of spells on your list matches the number on the table. The chosen spells must be of a level for which you have spell slots.

If another Witch feature gives you spells that you always have prepared, those spells don't count against the number of spells you can prepare with this feature, but those spells otherwise count as Witch spells for you.

**Changing Your Prepared Spells.** Whenever you gain a Witch level, you can replace one spell on your list with another Witch spell for which you have spell slots.

**Spellcasting Ability.** Charisma is your spellcasting ability for your Witch spells.

**Spellcasting Focus.** You can use an [Arcane Focus](/Mechanics/CLI/items/arcane-focus-xphb.md) as a [Spellcasting Focus](/Mechanics/CLI/variant-rules/spellcasting-focus-xphb.md) for your Witch spells.

### Witch's Curse (Level 1)

You are wracked by a terrible curse which infects your body and soul. Choose the form that this curse takes from the following options.

Options (choose 1):

- [Burned](/Mechanics/CLI/optional-features/burned-valdaspire24.md)
- [Drowned](/Mechanics/CLI/optional-features/drowned-valdaspire24.md)
- [Feral](/Mechanics/CLI/optional-features/feral-valdaspire24.md)
- [Hideous](/Mechanics/CLI/optional-features/hideous-valdaspire24.md)
- [Hollow](/Mechanics/CLI/optional-features/hollow-valdaspire24.md)
- [Infested](/Mechanics/CLI/optional-features/infested-valdaspire24.md)
- [Loveless](/Mechanics/CLI/optional-features/loveless-valdaspire24.md)
- [Possessed](/Mechanics/CLI/optional-features/possessed-valdaspire24.md)
- [Starving](/Mechanics/CLI/optional-features/starving-valdaspire24.md)
- [Visions](/Mechanics/CLI/optional-features/visions-valdaspire24.md)
- [Whispers](/Mechanics/CLI/optional-features/whispers-valdaspire24.md)

### Hexes (Level 1)

You learn a number of powerful cantrips, known as Hexes, derived from the same insidious magic that cursed you.

You know two Hexes of your choice from the Witch spell list, which don't count against your number of cantrips known. [Hex: Misfortune](/Mechanics/CLI/spells/hex-misfortune-valdaspire24.md) and [Hex: Ruin](/Mechanics/CLI/spells/hex-ruin-valdaspire24.md) are recommended. Whenever you gain a Witch level, you can replace one of your Hexes with another Hex of your choice from the Witch spell list. When you gain certain Witch levels, you gain more Hexes of your choice, as shown in the Hexes column of the Witch Features table.

### Cackle (Level 2)

You can take a [Bonus Action](/Mechanics/CLI/variant-rules/bonus-action-xphb.md) to Cackle. When you do so, you extend the duration of one of your Hexes by 1 round, provided the target of the Hex is within the spell's range.

Not all Witches laugh maniacally when they Cackle, but all Cackles require a Verbal component, as if casting a spell. These range from mundane curses and insults, to the murmuring of dead languages and speaking backwards.

### Familiar (Level 2)

You always have the [Find Familiar](/Mechanics/CLI/spells/find-familiar-xphb.md) spell prepared, and you can cast it in 10 minutes without a spell slot or components. The spell is improved in the following ways when you cast it.

**Expanded Options.** You can choose one of the normal forms for your familiar or one of the following special forms: [Death Snail](/Mechanics/CLI/bestiary/monstrosity/death-snail-valdaspire24.md), [Flying Book](/Mechanics/CLI/bestiary/construct/flying-book-valdaspire24.md), Homunculus, [Mock](/Mechanics/CLI/bestiary/monstrosity/mock-valdaspire24.md), [Moon Jelly](/Mechanics/CLI/bestiary/monstrosity/moon-jelly-valdaspire24.md), [Pet Rock](/Mechanics/CLI/bestiary/elemental/pet-rock-valdaspire24.md), [Pseudodragon](/Mechanics/CLI/bestiary/dragon/pseudodragon-xmm.md) (can't use its Sting), [Rag Doll](/Mechanics/CLI/bestiary/construct/rag-doll-valdaspire24.md), [Tin Soldier](/Mechanics/CLI/bestiary/construct/tin-soldier-valdaspire24.md), and [Winter Wolf Pup](/Mechanics/CLI/bestiary/monstrosity/winter-wolf-pup-valdaspire24.md).

**Witch Familiar.** The familiar's stat block is improved, as detailed in the Witch Familiar sidebar.

**Synchronized Turns.** Your familiar takes its turn immediately before or after your turn each round (your choice).

**Quick Attack.** Once per turn as an action or [Bonus Action](/Mechanics/CLI/variant-rules/bonus-action-xphb.md), you can command your familiar to take the [Attack](/Mechanics/CLI/actions.md#Attack) action (one attack only) on its turn.

**Spell Channeling.** When you cast a spell with a range other than Self on your turn, you can cast it as if you were in your familiar's space. The familiar must be within 100 feet of you, and it must take a [Reaction](/Mechanics/CLI/variant-rules/reaction-xphb.md) to deliver the spell when you cast the spell as normal.

> [!note] Witch Familiar
>
> As a Witch, the stat block of a familiar you summon is improved in the following ways.
>
> **Hit Points.** You add twice your Witch level to your familiar's [Hit Point](/Mechanics/CLI/variant-rules/hit-points-xphb.md) maximum.
>
> **Your Spell Attack Modifier.** Your familiar can use your spell attack modifier for its attack rolls.
>
> **Your Saving Throw.** If your familiar forces a creature to make a saving throw, it uses your spell save DC.
>
> **Your Proficiency Bonus.** Your familiar adds your [Proficiency Bonus](/Mechanics/CLI/variant-rules/proficiency-xphb.md) to its AC, saving throws, and damage rolls.
> ^witch-familiar

### Witch Subclass (Level 3)

You gain a Witch subclass of your choice. A subclass is a specialization that grants you features at certain Witch levels. For the rest of your career, you gain each of your subclass's features that are of your Witch level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Insidious Spell (Level 5)

When a creature fails its saving throw against one of your Hexes, it has [Disadvantage](/Mechanics/CLI/variant-rules/disadvantage-xphb.md) on saving throws it makes against your Witch spells before the end of your next turn. Similarly, if it fails its saving throw against one of your Witch spells, it has [Disadvantage](/Mechanics/CLI/variant-rules/disadvantage-xphb.md) on saving throws it makes against your Hexes until the end of your next turn.

### Subclass Feature (Level 6)

You gain a feature from your Witch Subclass.

### Improved Familiar (Level 7)

Your [Find Familiar](/Mechanics/CLI/spells/find-familiar-xphb.md) spell improves in the following ways.

**Force Damage.** Whenever your familiar deals damage with an attack, it can deal your choice of Force or its normal damage type.

**Expanded Options.** You can choose one of the following forms for your familiar: [Fright](/Mechanics/CLI/bestiary/undead/fright-valdaspire24.md), [Grep](/Mechanics/CLI/bestiary/monstrosity/grep-valdaspire24.md), [Imp](/Mechanics/CLI/bestiary/fiend/imp-xmm.md), [Quasit](/Mechanics/CLI/bestiary/fiend/quasit-xmm.md), [Sprite](/Mechanics/CLI/bestiary/fey/sprite-xmm.md), or [Yarn Golem](/Mechanics/CLI/bestiary/construct/yarn-golem-valdaspire24.md).

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Hastened Hex (Level 9)

Once per turn when you cast a Hex as a [Magic](/Mechanics/CLI/actions.md#Magic) action, you can cast a Witch cantrip that isn't a Hex and has a casting time of an action as a part of that casting.

### Subclass Feature (Level 10)

You gain a feature from your Witch Subclass.

### Grand Hex (Level 11)

You have perfected deeply malevolent forms of magic. You gain one Grand Hex^\[Optional features from [Grand Hex](/Mechanics/CLI/lists/list-optfeaturetype-gh.md); defined in valdawitch] of your choice. Whenever you gain a Witch level, you can replace one of your Grand Hexes with another one.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Grand Hex (Level 13)

You have perfected deeply malevolent forms of magic. You gain one Grand Hex^\[Optional features from [Grand Hex](/Mechanics/CLI/lists/list-optfeaturetype-gh.md); defined in valdawitch] of your choice. Whenever you gain a Witch level, you can replace one of your Grand Hexes with another one.

### Subclass Feature (Level 14)

You gain a feature from your Witch Subclass.

### Grand Hex (Level 15)

You have perfected deeply malevolent forms of magic. You gain one Grand Hex^\[Optional features from [Grand Hex](/Mechanics/CLI/lists/list-optfeaturetype-gh.md); defined in valdawitch] of your choice. Whenever you gain a Witch level, you can replace one of your Grand Hexes with another one.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Grand Hex (Level 17)

You have perfected deeply malevolent forms of magic. You gain one Grand Hex^\[Optional features from [Grand Hex](/Mechanics/CLI/lists/list-optfeaturetype-gh.md); defined in valdawitch] of your choice. Whenever you gain a Witch level, you can replace one of your Grand Hexes with another one.

### Vengeful Curse (Level 18)

When an enemy you can see within 60 feet of yourself deals damage that causes you or an [Ally](/Mechanics/CLI/variant-rules/ally-xphb.md) you can see within 60 feet of yourself to become [Bloodied](/Mechanics/CLI/conditions.md#Bloodied), you can take a [Reaction](/Mechanics/CLI/variant-rules/reaction-xphb.md) to curse the enemy. Until the end of your next turn, the cursed creature has [Disadvantage](/Mechanics/CLI/variant-rules/disadvantage-xphb.md) on [D20 Tests](/Mechanics/CLI/variant-rules/d20-test-xphb.md).

Once you use this feature, you can't use it again until you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md).

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Hexmaster (Level 20)

You have mastered your foul magic. When you cast a Hex that requires a saving throw, you can cause one target to automatically fail.

You can use this feature a number of times equal to your Charisma modifier (minimum of once), and you regain all expended uses when you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md). You can also restore one use of it by expending a spell slot (no action required).

## Sources

_Valda's Spire of Secrets (2024)_
