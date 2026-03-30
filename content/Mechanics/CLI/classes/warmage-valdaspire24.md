---
publish: true
aliases:
  - Warmage
created: 2026-03-29T21:53:55.975-04:00
modified: 2026-03-29T21:53:55.976-04:00
published: 2026-03-29T21:53:55.976-04:00
tags:
  - ttrpg-cli/class/warmage
  - ttrpg-cli/compendium/src/5e/valdaspire24
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Warmage

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='6'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Cantrips</th><th class="value">Cantrip Bonus Dice</th><th class="value">Tricks</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Spellcasting (Level 1)' class='internal-link'>Spellcasting</a>, <a href='#Arcane Initiation (Level 1)' class='internal-link'>Arcane Initiation</a>, <a href='#Warmage Edge (Level 1)' class='internal-link'>Warmage Edge</a></td><td class="value">4</td><td class="value">⏤</td><td class="value">⏤</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Reliable Cantrip (Level 2)' class='internal-link'>Reliable Cantrip</a>, <a href='#Warmage Tricks (Level 2)' class='internal-link'>Warmage Tricks</a></td><td class="value">4</td><td class="value">⏤</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Warmage Subclass (Level 3)' class='internal-link'>Warmage Subclass</a></td><td class="value">5</td><td class="value">⏤</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">5</td><td class="value">⏤</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Arcane Surge (Level 5)' class='internal-link'>Arcane Surge</a></td><td class="value">6</td><td class="value">1</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Tactical Insight (Level 6)' class='internal-link'>Tactical Insight</a></td><td class="value">6</td><td class="value">1</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 7)' class='internal-link'>Subclass Feature</a></td><td class="value">6</td><td class="value">1</td><td class="value">5</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">6</td><td class="value">1</td><td class="value">5</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td><td class="value">7</td><td class="value">1</td><td class="value">6</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">7</td><td class="value">1</td><td class="value">6</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"><a href='#Arcane Surge Improvement (Level 11)' class='internal-link'>Arcane Surge Improvement</a></td><td class="value">7</td><td class="value">2</td><td class="value">7</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">7</td><td class="value">2</td><td class="value">7</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td><td class="value">8</td><td class="value">2</td><td class="value">8</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Strategic Deflection (Level 14)' class='internal-link'>Strategic Deflection</a></td><td class="value">8</td><td class="value">2</td><td class="value">8</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Subclass Feature (Level 15)' class='internal-link'>Subclass Feature</a></td><td class="value">8</td><td class="value">2</td><td class="value">9</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">8</td><td class="value">2</td><td class="value">9</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td><td class="value">9</td><td class="value">3</td><td class="value">10</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Subclass Feature (Level 18)' class='internal-link'>Subclass Feature</a></td><td class="value">9</td><td class="value">3</td><td class="value">10</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">9</td><td class="value">3</td><td class="value">10</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Master Warmage (Level 20)' class='internal-link'>Master Warmage</a></td><td class="value">10</td><td class="value">4</td><td class="value">10</td></tr>
> </tbody></table>

^class-progression

## Hit Points

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWarmage/Class/Warmage.webp#right)

- **Hit Dice**: 1d8 per Warmage level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 5 OR 1d8 + CON  (minimum of 1)

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaWarmage/Class/Warmage-Cover.webp#center)

## Starting a Warmage

- **Saving Throw Proficiencies**: Constitution, Intelligence
- **Skill Proficiencies**: _Choose 2:_ [Acrobatics](/Mechanics/CLI/skills.md#Acrobatics), [Animal Handling](/Mechanics/CLI/skills.md#Animal%20Handling), [Arcana](/Mechanics/CLI/skills.md#Arcana), [Athletics](/Mechanics/CLI/skills.md#Athletics), [History](/Mechanics/CLI/skills.md#History), [Investigation](/Mechanics/CLI/skills.md#Investigation), [Medicine](/Mechanics/CLI/skills.md#Medicine), [Perception](/Mechanics/CLI/skills.md#Perception), or [Survival](/Mechanics/CLI/skills.md#Survival)
- **Weapon Proficiencies**: Simple weapons
- **Armor Training**: [Light armor](/Mechanics/CLI/item-types.md#Light%20Armor)

**Starting Equipment:** _Choose A or B:_ (A) [Leather Armor](/Mechanics/CLI/items/leather-armor-xphb.md), [Dagger](/Mechanics/CLI/items/dagger-xphb.md), [Arcane Focus (Staff)](/Mechanics/CLI/items/staff-xphb.md), [Gaming Set](/Mechanics/CLI/items/gaming-set-xphb.md) of your choice, [Explorer's Pack](/Mechanics/CLI/items/explorers-pack-xphb.md), and 22 GP; or (B) 50 GP

## Multiclassing Warmage

- Gain the Hit Point Die trait from the Core Warmage Traits table.
- Gain the Warmage's level 1 features, which are listed in the Warmage Features table.

## Warmage

Waving a black-and-red checkered banner, a dragonborn king charges into the fore. At his sides are Warmages of all houses, a chessboard of elite arcanists, poised to turn the tide of battle.

The undisputed masters of cantrips, Warmages turn the most fundamental types of magic into a deadly and precise art.

### Cantrip Masters

While other spellcasters aspire to grander and more complex spells, Warmages refine and master the most fundamental magic: cantrips. Warmages wield their magic in the same way that a warrior uses a sword, bow, or axe—as weapons to be perfected, not as an unknowable force to be feared. In contrast to sorcerers and wizards, their magic is a trainable skill, one that can be mastered by almost anyone with discipline and aptitude. Therefore, Warmages stand among the most fearsome of spellcasters, with only the most rudimentary of spells.

### Strategic Geniuses

Warmages have a long and storied history as masterful strategists and tacticians, both in grand battles and personal skirmishes. If a Warmage is outgunned or outmanned, they'll try to outthink their foes, which works more often than not. Warmages demonstrate an efficient kind of pragmatism, owing perhaps to their ability to solve many problems with just a few magical tools.

### Aligned Free Agents

While some Warmages are fully self-taught, the majority join a house: a loose confederation of Warmages who practice together and share secrets of the trade. Houses teach invaluable battlefield strategy, but each individual house also touts their own brands of tactics and styles of magical tricks. The House of Knights, for example, emphasizes armor and martial prowess, whereas the House of Kings emphasizes battlefield strategy.

By way of metaphor, houses that value honor and teamwork above all else brand themselves after games of strategy, whereas those who epitomize self-reliance name themselves for games of chance. This division in the Warmage houses is representative of a schism that dates back to the earliest Warmage masters. Legend has it that the first two masters separated when one decided to found a college. The other, out of spite, built a casino outside its grounds.

## Class Features

### Spellcasting (Level 1)

You have learned the simple, yet potent brand of spellcasting for which Warmages are known.

**Cantrips.** You know four Warmage cantrips of your choice. [Force Dart](/Mechanics/CLI/spells/force-dart-valdaspire24.md), [Prestidigitation](/Mechanics/CLI/spells/prestidigitation-xphb.md), [Quickstep](/Mechanics/CLI/spells/quickstep-valdaspire24.md), and [Shocking Grasp](/Mechanics/CLI/spells/shocking-grasp-xphb.md) are recommended. Whenever you gain a Warmage level, you can replace one of your cantrips from this feature with another Warmage cantrip of your choice. You can't replace a cantrip that is a prerequisite for a Warmage trick, unless you replace the trick at the same time.

You learn additional Warmage cantrips of your choice at higher levels, as shown in the Cantrips column of the Warmage Features table.

If another Warmage feature gives you cantrips, those cantrips don't count against your number of cantrips known, but otherwise count as Warmage cantrips for you.

**Spellcasting Ability.** Intelligence is your spellcasting ability for your Warmage spells.

**Spellcasting Focus.** You can use an [Arcane Focus](/Mechanics/CLI/items/arcane-focus-xphb.md) as a [Spellcasting Focus](/Mechanics/CLI/variant-rules/spellcasting-focus-xphb.md) for your Warmage spells.

### Arcane Initiation (Level 1)

Choose where you first learned the basics of magic.

Options (choose 1):

- [Adventurer](/Mechanics/CLI/optional-features/adventurer-valdaspire24.md)
- [Arcane Event](/Mechanics/CLI/optional-features/arcane-event-valdaspire24.md)
- [Circus Performer](/Mechanics/CLI/optional-features/circus-performer-valdaspire24.md)
- [Mercenary](/Mechanics/CLI/optional-features/mercenary-valdaspire24.md)
- [Self-Taught](/Mechanics/CLI/optional-features/self-taught-valdaspire24.md)
- [Survivalist](/Mechanics/CLI/optional-features/survivalist-valdaspire24.md)
- [Temple Initiate](/Mechanics/CLI/optional-features/temple-initiate-valdaspire24.md)
- [Tower Apprentice](/Mechanics/CLI/optional-features/tower-apprentice-valdaspire24.md)

> [!note] Making Your Own Initiation
>
> You can work with your GM to create an Arcane Initiation to suit your character's background. Choose two cantrips of your choice from any class's spell list; one cantrip should be suitable for combat, and the other for utility. Avoid choosing cantrips that are otherwise exclusive to another spellcaster. Also choose one skill.
> ^making-your-own-initiation

### Warmage Edge (Level 1)

Once per turn when you cast a Warmage cantrip, you can improve the spell, gaining the following benefits.

**Intelligence to Damage.** Add your Intelligence modifier to one damage roll of the spell if you don't already add it.

**Improved Cantrip Upgrade.** Starting at Warmage level 5, you improve one damage roll of the spell, adding extra dice to the damage roll as shown on the Cantrip Bonus Dice column of the Warmage Features table.

### Reliable Cantrip (Level 2)

When you cast a Warmage cantrip at a creature and you miss with the attack roll or the target succeeds on a saving throw against the cantrip, the target takes the cantrip's minimum amount of damage (if any) but suffers no additional effect from the cantrip. You can apply [Warmage Edge](/Mechanics/CLI/classes/warmage-valdaspire24.md#Warmage%20Edge%20\(Level%201\)) to this damage (which also deals minimum damage), but you can't use this damage to trigger [Warmage Tricks](/Mechanics/CLI/classes/warmage-valdaspire24.md#Warmage%20Tricks%20\(Level%202\)). For example, if you cast [Force Dart](/Mechanics/CLI/spells/force-dart-valdaspire24.md) and miss, you can apply [Warmage Edge](/Mechanics/CLI/classes/warmage-valdaspire24.md#Warmage%20Edge%20\(Level%201\)) to deal Force damage equal to 1 plus your Intelligence modifier.

### Warmage Tricks (Level 2)

You learn to use Warmage Tricks, special techniques that alter the way you fight, move, and cast your spells. You learn two tricks of your choice for which you meet the prerequisites. Warmage Tricks are described in the "Warmage Trick Options" section later on in the class's description.

**Prerequisites.** If a trick has a prerequisite, you must meet it to learn that trick. For example, if a trick requires you to be a level 5+ Warmage, you can select the trick once you reach Warmage level 5.

**Replacing and Gaining Tricks.** Whenever you gain a Warmage level, you can replace one of your tricks with another one for which you qualify. When you gain certain Warmage levels, you gain more tricks of your choice, as shown in the Tricks column of the Warmage Features table. You can't pick the same trick more than once unless its description says otherwise.

### Warmage Subclass (Level 3)

You gain a Warmage subclass of your choice. A subclass is a specialization that grants you features at certain Warmage levels. For the rest of your career, you gain each of your subclass's features that are of your Warmage level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Arcane Surge (Level 5)

Once on each of your turns, when you deal damage with a Warmage cantrip, you can double the number of damage dice dealt by the spell, as if you scored a [Critical Hit](/Mechanics/CLI/variant-rules/critical-hit-xphb.md). If you use this feature to improve a spell that has already scored a [Critical Hit](/Mechanics/CLI/variant-rules/critical-hit-xphb.md), the cantrip deals triple the number of damage dice in total.

You can use this feature twice. You regain one of its expended uses when you finish a [Short Rest](/Mechanics/CLI/variant-rules/short-rest-xphb.md), and you regain all expended uses when you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md). You gain an additional use when you reach Warmage level 11.

### Tactical Insight (Level 6)

You gain a bonus to saving throws against spells and other magical effects equal to your Intelligence modifier (minimum bonus of +1). You don't gain this bonus to Intelligence saving throws.

### Subclass Feature (Level 7)

You gain a feature from your Warmage Subclass.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 10)

You gain a feature from your Warmage Subclass.

### Arcane Surge Improvement (Level 11)

You gain an additional use of [Arcane Surge](/Mechanics/CLI/classes/warmage-valdaspire24.md#Arcane%20Surge%20\(Level%205\)).

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Strategic Deflection (Level 14)

When a creature casts a spell that forces you to make a saving throw to avoid damage, you can take a [Reaction](/Mechanics/CLI/variant-rules/reaction-xphb.md) to attempt to redirect some of the spell's energy to a new target. If you succeed on your saving throw against the spell, choose another creature you can see within the spell's range or up to 30 feet away from you, whichever is closer, to make a saving throw against the spell, using your spell save DC. The chosen creature can be the original spellcaster. On a failed save, the creature suffers the effects of the spell as if you had cast the spell and it had been the original target or been within the area of the spell.

Once you use this feature, you can't use it again until you finish a [Short](/Mechanics/CLI/variant-rules/short-rest-xphb.md) or [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md).

### Subclass Feature (Level 15)

You gain a feature from your Warmage Subclass.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 18)

You gain a feature from your Warmage Subclass.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Master Warmage (Level 20)

Whenever you roll [Initiative](/Mechanics/CLI/variant-rules/initiative-xphb.md) and have no uses of [Arcane Surge](/Mechanics/CLI/classes/warmage-valdaspire24.md#Arcane%20Surge%20\(Level%205\)) left, you regain one expended use of it.

## Optional Features

> [!example]- Optional Features: Trick
> ![Trick](/Mechanics/CLI/lists/list-optfeaturetype-t.md#Trick)
> ^list-optfeature-t

## Sources

_Valda's Spire of Secrets (2024)_
