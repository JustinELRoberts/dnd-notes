---
publish: true
aliases:
  - Alchemist
created: 2026-03-29T21:53:55.575-04:00
modified: 2026-03-29T21:53:55.575-04:00
published: 2026-03-29T21:53:55.575-04:00
tags:
  - ttrpg-cli/class/alchemist
  - ttrpg-cli/compendium/src/5e/valdaspire24
cssclasses:
  - json5e-class
obsidianUIMode: preview
---

# Alchemist

> [!tldr] Class and Feature Progression
>
> <table class="class-progression">
> <thead>
> <tr><th colspan='6'></th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Reagents</th><th class="value"><a href="/Mechanics/CLI/lists/list-optfeaturetype-bf.md">Bomb Formulae</a></th><th class="value">Discoveries</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Bombs (Level 1)' class='internal-link'>Bombs</a>, <a href='#Reagents (Level 1)' class='internal-link'>Reagents</a>, <a href='#Potion Brewing (Level 1)' class='internal-link'>Potion Brewing</a></td><td class="value">2</td><td class="value">—</td><td class="value">—</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Bomb Formulae (Level 2)' class='internal-link'>Bomb Formulae</a>, <a href='#Reagent Synthesis (Level 2)' class='internal-link'>Reagent Synthesis</a></td><td class="value">4</td><td class="value">3</td><td class="value">—</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Alchemist Subclass (Level 3)' class='internal-link'>Alchemist Subclass</a></td><td class="value">6</td><td class="value">3</td><td class="value">—</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">8</td><td class="value">4</td><td class="value">—</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Discoveries (Level 5)' class='internal-link'>Discoveries</a>, <a href='#Potion Brewing (Level 5)' class='internal-link'>Potion Brewing</a></td><td class="value">10</td><td class="value">4</td><td class="value">1</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 6)' class='internal-link'>Subclass Feature</a></td><td class="value">12</td><td class="value">4</td><td class="value">1</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Evasion (Level 7)' class='internal-link'>Evasion</a></td><td class="value">14</td><td class="value">4</td><td class="value">1</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">16</td><td class="value">5</td><td class="value">1</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"><a href='#Potion Brewing (Level 9)' class='internal-link'>Potion Brewing</a></td><td class="value">18</td><td class="value">5</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">20</td><td class="value">5</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"><a href='#Blast Coating (Level 11)' class='internal-link'>Blast Coating</a></td><td class="value">22</td><td class="value">5</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">24</td><td class="value">6</td><td class="value">2</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"><a href='#Potion Brewing (Level 13)' class='internal-link'>Potion Brewing</a></td><td class="value">26</td><td class="value">6</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Subclass Feature (Level 14)' class='internal-link'>Subclass Feature</a></td><td class="value">28</td><td class="value">6</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"><a href='#Potion Mixologist (Level 15)' class='internal-link'>Potion Mixologist</a></td><td class="value">30</td><td class="value">6</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">32</td><td class="value">7</td><td class="value">3</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"><a href='#Potion Brewing (Level 17)' class='internal-link'>Potion Brewing</a></td><td class="value">34</td><td class="value">7</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Experimentalist (Level 18)' class='internal-link'>Experimentalist</a></td><td class="value">36</td><td class="value">7</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">38</td><td class="value">8</td><td class="value">4</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Philosopher's Stone (Level 20)' class='internal-link'>Philosopher's Stone</a>, <a href='#Nuclear Bomb (Level 20)' class='internal-link'>Nuclear Bomb</a></td><td class="value">40</td><td class="value">8</td><td class="value">4</td></tr>
> </tbody></table>

^class-progression

## Hit Points

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaAlchemist/Class/Alchemist.webp#right)

- **Hit Dice**: 1d8 per Alchemist level
- **Hit Points at First Level:** 8 + CON
- **Hit Points at Higher Levels:** add 5 OR 1d8 + CON  (minimum of 1)

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaAlchemist/Class/Alchemist-Cover.webp#center)

## Starting a Alchemist

- **Saving Throw Proficiencies**: Dexterity, Intelligence
- **Skill Proficiencies**: _Choose 3:_ [Arcana](/Mechanics/CLI/skills.md#Arcana), [History](/Mechanics/CLI/skills.md#History), [Insight](/Mechanics/CLI/skills.md#Insight), [Medicine](/Mechanics/CLI/skills.md#Medicine), [Nature](/Mechanics/CLI/skills.md#Nature), [Perception](/Mechanics/CLI/skills.md#Perception), [Sleight of Hand](/Mechanics/CLI/skills.md#Sleight%20of%20Hand), or [Survival](/Mechanics/CLI/skills.md#Survival)
- **Weapon Proficiencies**: Simple weapons and [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md)
- **Tool Proficiencies**: [Alchemist's Supplies](/Mechanics/CLI/items/alchemists-supplies-xphb.md)
- **Armor Training**: [Light armor](/Mechanics/CLI/item-types.md#Light%20Armor)

**Starting Equipment:** _Choose A or B_ (A) 2 [Daggers](/Mechanics/CLI/items/dagger-xphb.md), [Leather Armor](/Mechanics/CLI/items/leather-armor-xphb.md), [Alchemist's Supplies](/Mechanics/CLI/items/alchemists-supplies-xphb.md), [Alchemist's Fire](/Mechanics/CLI/items/alchemists-fire-xphb.md), [Scholar's Pack](/Mechanics/CLI/items/scholars-pack-xphb.md), and 6 GP; or (B) 160 GP

## Multiclassing Alchemist

- **Tool Proficiencies**: [Alchemist's Supplies](/Mechanics/CLI/items/alchemists-supplies-xphb.md)
- **Armor Training**: [Light armor](/Mechanics/CLI/item-types.md#Light%20Armor)

## Alchemist

Whether their methods are explosive, transformative, or restorative, Alchemists transmute the world around them to their liking.

### Explosive Reactions

One of the first things an Alchemist learns is which chemicals react explosively with one other. Ostensibly, this is to prevent deadly accidents, but adventuring Alchemists regularly apply this knowledge to create [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md).

An alchemical bomb is a one-pound, apple-sized, spherical glass or clay flask filled with a reactive chemical. A smaller vial of thin glass containing a reagent is suspended in the liquid, and the whole thing is sealed with a cork or wax seal. When the inner vial breaks, usually on impact, the chemicals react with a violent explosion. With experimentation, an Alchemist can even infuse these explosions with elemental fire, lightning, or frost.

### Serums and Tinctures

Experienced Alchemists learn to brew potions, alchemical concoctions that replicate magical effects. These range from the medicinal, such as Potions of Healing, to the transformative, such as Potions of Gaseous Form. Undisputed masters of potion-brewing, an adventuring Alchemist should have a surplus of potions to distribute among their allies.

### Elemental Sciences

The source of alchemy's power is the Elemental Planes. Therefore, it is no surprise that Alchemists strive to tap deeper into that power, researching and discovering new elemental compounds. The pinnacle of alchemy is the Philosopher's Stone, which is rumored to grant its bearer supreme command of the elements. Few Alchemists have succeeded in creating a Philosopher's Stone, and fewer still remain alive to divulge its secrets.

## Class Features

### Bombs (Level 1)

You can create volatile alchemical [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) using the statistics shown in the Bomb sidebar.

**Bomb Mastery.** You have proficiency with [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) and you can use the Bomb's mastery property.

**Priming Bombs.** When you take the [Attack](/Mechanics/CLI/actions.md#Attack) action on your turn, you can prime a [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md) to increase its potency. Make one attack using a [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md) or use the Bomb's Explode property; you can't make any other attacks using this [Attack](/Mechanics/CLI/actions.md#Attack) action. Add your Intelligence modifier to the damage roll.

When you prime your [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md) and deal damage with it, its damage increases by `1d10` when you reach Alchemist levels 5 (`2d10`), 11 (`3d10`), and 17 (`4d10`).

**Alchemist Save DC.** Some of your Alchemist features require your target to make a saving throw. The save DC equals 8 plus your Intelligence modifier and [Proficiency Bonus](/Mechanics/CLI/variant-rules/proficiency-xphb.md). You can use this saving throw for your [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) instead of the DC specified in the Explode property.

> [!note] How Many Bombs Do I Have?
>
> As an Alchemist, you can use [Alchemist's Supplies](/Mechanics/CLI/items/alchemists-supplies-xphb.md) to effectively make as many [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) as you need for the adventuring day at no cost. If you prefer to track your inventory of [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) manually, you can create a number of [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) equal to 10 + twice your Alchemist level when you finish a [Short](/Mechanics/CLI/variant-rules/short-rest-xphb.md) or [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md). After 24 hours, an unused [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md) becomes inert.
> ^how-many-bombs-do-i-have

### Reagents (Level 1)

You have a collection of powerful reagents that you use to brew potions and empower your [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md). You have 2 Reagents. You regain one expended Reagent when you finish a [Short Rest](/Mechanics/CLI/variant-rules/short-rest-xphb.md), and you regain all expended Reagents when you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md). You gain additional Reagents when you reach certain Alchemist levels, as shown in the Reagents column of the Alchemist Features table.

**Empowered Bomb.** When you deal damage with a [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md), you can expend a number of [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) up to your [Proficiency Bonus](/Mechanics/CLI/variant-rules/proficiency-xphb.md) and add `1d10` to the [Bomb's](/Mechanics/CLI/items/bomb-valdaspire24.md) damage roll for each expended [Reagent](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)).

Additionally, if you use the [Bomb's](/Mechanics/CLI/items/bomb-valdaspire24.md) Explode property, you can increase the radius of the explosion by 5 feet. You can do so once for each expended [Reagent](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)). For example, if you expend 2 [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)), you can choose for the [Sphere](/Mechanics/CLI/variant-rules/sphere-area-of-effect-xphb.md) to be a 5, 10 or 15-foot radius.

### Potion Brewing (Level 1)

You can spend 10 minutes and expend any number of [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) to brew potions, which can be done during a [Short Rest](/Mechanics/CLI/variant-rules/short-rest-xphb.md). You can have a total number of potions at one time up to your Intelligence modifier (minimum of 1). These potions retain potency until you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md), after which they become inert.

When you brew potions, you can also distill potions you have already brewed, destroying them and recovering the [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) expended to brew them, up to a maximum of the number of [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) listed on the Alchemist Features table. You can expend these [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) immediately to brew new potions.

Your potions don't have unpredictable effects if a creature drinks one of your potions while still under the effects of another.

The number of [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) and the Alchemist level required to brew a potion are given on the Potions table.

**Potions**

| Potion | Reagents |
|--------|----------|
| Alchemist Level 1 |  |
| Potion of Climbing | 1 |
| Potion of Diminution | 1 |
| Potion of Growth | 2 |
| [Potion of Healing](/Mechanics/CLI/items/potion-of-healing-xdmg.md) | 1 |
| Potion of Resistance | 1 |
| Potion of Water Breathing | 1 |
| Alchemist Level 5 |  |
| Potion of Greater Healing | 2 |
| Potion of Invisibility | 2 |
| Sovereign Glue | 1 |
| Universal Solvent | 1 |
| Alchemist Level 9 |  |
| Potion of Heroism | 3 |
| Potion of Hill Giant Strength | 3 |
| Potion of Superior Healing | 3 |
| Alchemist Level 13 |  |
| Potion of Flying | 5 |
| Potion of Frost Giant Strength | 4 |
| Potion of Stone Giant Strength | 4 |
| Potion of Invulnerability | 6 |
| Alchemist Level 17 |  |
| Potion of Fire Giant Strength | 7 |
| Potion of Speed | 9 |
^potions

### Bomb Formulae (Level 2)

Your research has uncovered new formulations for your [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) that you can apply just before throwing them. Choose three Bomb Formulae from the "[Bomb Formulae Options](/Mechanics/CLI/lists/list-optfeaturetype-bf.md)" section later in this class's description.

**Replacing and Gaining Formulae.** When you reach certain Alchemist levels, you learn additional formulae of your choice, as shown in the Bomb Formulae column of the Alchemist Features table. Additionally, whenever you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md), you can replace one of your Bomb Formulae with another formula of your choice.

If another Alchemist feature gives you a Bomb Formula, it doesn't count against your number of formulae.

**Applying Bomb Formulae.** Once per turn when you prime a [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md), you can apply a Bomb Formula to it, granting it special effects and potentially changing its damage dice.

### Reagent Synthesis (Level 2)

When you finish a [Short Rest](/Mechanics/CLI/variant-rules/short-rest-xphb.md), you can regain an additional number of expended [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) up to your Intelligence modifier (minimum of 1).

Once you use this feature, you can't do so again until you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md).

### Alchemist Subclass (Level 3)

You gain an Alchemist subclass of your choice. A subclass is a specialization that grants you features at certain Alchemist levels. For the rest of your career, you gain each of your subclass's features that are of your Alchemist level or lower.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Discoveries (Level 5)

In the course of your research, you have made a number of discoveries regarding the nature of alchemy. You gain one discovery of your choice from the "Discovery Options" section later in this class's description

Whenever you gain an Alchemist level, you can replace one of your discoveries with another one for which you qualify. When you gain certain Alchemist levels, you gain more discoveries of your choice, as shown in the Discoveries column of the Alchemist Features table. You can't pick the same discovery more than once.

### Potion Brewing (Level 5)

Your Potion Brewing feature gains new potions for you to brew.

### Subclass Feature (Level 6)

You gain a feature from your Alchemist Subclass.

### Evasion (Level 7)

When you're subjected to an effect that allows you to make a Dexterity saving throw to take only half damage, you instead take no damage if you succeed on the saving throw and only half damage if you fail.

You don't benefit from this feature if you have the [Incapacitated](/Mechanics/CLI/conditions.md#Incapacitated) condition.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Potion Brewing (Level 9)

Your Potion Brewing feature gains new potions for you to brew.

### Subclass Feature (Level 10)

You gain a feature from your Alchemist Subclass.

### Blast Coating (Level 11)

You automatically succeed on saving throws against your own [Bombs](/Mechanics/CLI/items/bomb-valdaspire24.md) and never take damage from them.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Potion Brewing (Level 13)

Your Potion Brewing feature gains new potions for you to brew.

### Subclass Feature (Level 14)

You gain a feature from your Alchemist Subclass.

### Potion Mixologist (Level 15)

You can mix two potions together and drink them as a [Bonus Action](/Mechanics/CLI/variant-rules/bonus-action-xphb.md), gaining the effects of both. You suffer no unexpected effects from mixing potions.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](/Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Potion Brewing (Level 17)

Your Potion Brewing feature gains new potions for you to brew.

### Experimentalist (Level 18)

When you finish a [Long Rest](/Mechanics/CLI/variant-rules/long-rest-xphb.md), you can replace any of your Bomb Formulae with other formulae of your choice, and you can replace one of your discoveries with another one for which you qualify.

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Philosopher's Stone (Level 20)

You gain the crowning achievement of alchemy: a Philosopher's Stone, a dynamo of alchemical energy in a fist-sized, glowing jewel.

**Constructing a New Philosopher's Stone.** If your Philosopher's Stone is destroyed, you can construct a new one using [Alchemist's Supplies](/Mechanics/CLI/items/alchemists-supplies-xphb.md), materials worth 1,000+ GP, and 7 days of work. You can only have one Philosopher's Stone at a time.

**Philosopher's Stone Benefits.** As long as you possess the stone, you gain the following benefits:

**Regenerating Reagents.** When you roll [Initiative](/Mechanics/CLI/variant-rules/initiative-xphb.md), you regain expended [Reagents](/Mechanics/CLI/classes/alchemist-valdaspire24.md#Reagents%20\(Level%201\)) until you have 6 if you have 5 or fewer.

**Quick Brewing.** You can brew potions as a [Utilize](/Mechanics/CLI/actions.md#Utilize) action, instead of over the course of 10 minutes.

**Longevity.** For every ten years that pass, your body ages only one year.

### Nuclear Bomb (Level 20)

You can utilize the most devastating Bomb Formula imaginable. By replacing your [Bomb's](/Mechanics/CLI/items/bomb-valdaspire24.md) explosive contents with your Philosopher's Stone, you can change it into a Nuclear Bomb. You must use the [Bomb's](/Mechanics/CLI/items/bomb-valdaspire24.md) Explosive property. This Bomb deals `10d10 + 100` Force damage instead of its normal Fire damage, and its explosion is a [Sphere](/Mechanics/CLI/variant-rules/sphere-area-of-effect-xphb.md) with a radius of 1 mile. A creature within 60 feet of the center of the [Sphere](/Mechanics/CLI/variant-rules/sphere-area-of-effect-xphb.md) gains no benefit from Evasion or similar features.

This [Bomb](/Mechanics/CLI/items/bomb-valdaspire24.md) completely destroys your Philosopher's Stone.

## Optional Features

> [!example]- Optional Features: Bomb Formula
> ![Bomb Formula](/Mechanics/CLI/lists/list-optfeaturetype-bf.md#Bomb%20Formula)
> ^list-optfeature-bf

> [!example]- Optional Features: Discovery Option
> ![Discovery Option](/Mechanics/CLI/lists/list-optfeaturetype-do.md#Discovery%20Option)
> ^list-optfeature-do

## Sources

_Valda's Spire of Secrets (2024)_
