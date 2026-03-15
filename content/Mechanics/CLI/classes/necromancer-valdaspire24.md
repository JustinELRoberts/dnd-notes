---
obsidianUIMode: preview
cssclasses:
- json5e-class
tags:
- ttrpg-cli/class/necromancer
- ttrpg-cli/compendium/src/5e/valdaspire24
aliases:
- "Necromancer"
---
# Necromancer
*Source: Valda's Spire of Secrets (2024)*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='7'></th><th colspan='9'>Spell Slots per Spell Level</th></tr>
> <tr class="class-progression"><th class"level">Level</th><th class"pb">PB</th><th class"feature">Features</th><th class="value">Thralls</th><th class="value">CR Total</th><th class="value">Cantrips</th><th class="value">Prepared Spells</th><th class="spellSlot">1st</th><th class="spellSlot">2nd</th><th class="spellSlot">3rd</th><th class="spellSlot">4th</th><th class="spellSlot">5th</th><th class="spellSlot">6th</th><th class="spellSlot">7th</th><th class="spellSlot">8th</th><th class="spellSlot">9th</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class"level">1st</td><td class"pb">+2</td><td class"feature"><a href='#Spellcasting (Level 1)' class='internal-link'>Spellcasting</a>, <a href='#Charnel Touch (Level 1)' class='internal-link'>Charnel Touch</a></td><td class="value">-</td><td class="value">-</td><td class="value">3</td><td class="value">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">2nd</td><td class"pb">+2</td><td class"feature"><a href='#Thralls (Level 2)' class='internal-link'>Thralls</a>, <a href='#Dead Space (Level 2)' class='internal-link'>Dead Space</a></td><td class="value">1</td><td class="value">1/4</td><td class="value">3</td><td class="value">5</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">3rd</td><td class"pb">+2</td><td class"feature"><a href='#Necromancer Subclass (Level 3)' class='internal-link'>Necromancer Subclass</a>, <a href='#Dark Arcana (Level 3)' class='internal-link'>Dark Arcana</a></td><td class="value">2</td><td class="value">1/2</td><td class="value">3</td><td class="value">6</td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">4th</td><td class"pb">+2</td><td class"feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a></td><td class="value">2</td><td class="value">1/2</td><td class="value">4</td><td class="value">7</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">5th</td><td class"pb">+3</td><td class"feature"><a href='#Animate Dead (Level 5)' class='internal-link'>Animate Dead</a>, <a href='#Critical Spellcasting (Level 5)' class='internal-link'>Critical Spellcasting</a></td><td class="value">2</td><td class="value">1</td><td class="value">4</td><td class="value">9</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">6th</td><td class"pb">+3</td><td class"feature"><a href='#Subclass Feature (Level 6)' class='internal-link'>Subclass Feature</a></td><td class="value">2</td><td class="value">1</td><td class="value">4</td><td class="value">10</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">7th</td><td class"pb">+3</td><td class"feature"><a href='#Improved Thralls (Level 7)' class='internal-link'>Improved Thralls</a></td><td class="value">3</td><td class="value">1</td><td class="value">4</td><td class="value">11</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">8th</td><td class"pb">+3</td><td class"feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">3</td><td class="value">1</td><td class="value">4</td><td class="value">12</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">9th</td><td class"pb">+4</td><td class"feature"></td><td class="value">3</td><td class="value">2</td><td class="value">4</td><td class="value">14</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">10th</td><td class"pb">+4</td><td class"feature"><a href='#Subclass Feature (Level 10)' class='internal-link'>Subclass Feature</a></td><td class="value">3</td><td class="value">2</td><td class="value">5</td><td class="value">15</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">11th</td><td class"pb">+4</td><td class"feature"></td><td class="value">4</td><td class="value">2</td><td class="value">5</td><td class="value">16</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">12th</td><td class"pb">+4</td><td class"feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">4</td><td class="value">2</td><td class="value">5</td><td class="value">16</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">13th</td><td class"pb">+5</td><td class"feature"></td><td class="value">4</td><td class="value">3</td><td class="value">5</td><td class="value">17</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">14th</td><td class"pb">+5</td><td class"feature"><a href='#Improved Critical Spellcasting (Level 14)' class='internal-link'>Improved Critical Spellcasting</a></td><td class="value">4</td><td class="value">3</td><td class="value">5</td><td class="value">17</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">15th</td><td class"pb">+5</td><td class"feature"></td><td class="value">5</td><td class="value">3</td><td class="value">5</td><td class="value">18</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">16th</td><td class"pb">+5</td><td class"feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">5</td><td class="value">3</td><td class="value">5</td><td class="value">18</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class"level">17th</td><td class"pb">+6</td><td class"feature"></td><td class="value">5</td><td class="value">4</td><td class="value">5</td><td class="value">19</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">18th</td><td class"pb">+6</td><td class"feature"><a href='#Undying Servitude (Level 18)' class='internal-link'>Undying Servitude</a></td><td class="value">5</td><td class="value">4</td><td class="value">5</td><td class="value">20</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">19th</td><td class"pb">+6</td><td class"feature"><a href='#Epic Boon (Level 19)' class='internal-link'>Epic Boon</a></td><td class="value">6</td><td class="value">4</td><td class="value">5</td><td class="value">21</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class"level">20th</td><td class"pb">+6</td><td class"feature"><a href='#Lichdom (Level 20)' class='internal-link'>Lichdom</a>, <a href='#Subclass Feature (Level 20)' class='internal-link'>Subclass Feature</a></td><td class="value">6</td><td class="value">4</td><td class="value">5</td><td class="value">22</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> </tbody></table>

^class-progression

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaNecromancer/Class/Necromancer.webp#right)

## Hit Points

- **Hit Dice**: 1d6 per Necromancer level
- **Hit Points at First Level:** 6 + CON
- **Hit Points at Higher Levels:** add 4 OR 1d6 + CON  (minimum of 1)

## Starting Necromancer

- **Saving Throw Proficiencies**: Constitution, Intelligence
- **Skill Proficiencies**: *Choose 2:* [Arcana](Mechanics/CLI/rules/skills.md#Arcana), [Deception](Mechanics/CLI/rules/skills.md#Deception), [History](Mechanics/CLI/rules/skills.md#History), [Intimidation](Mechanics/CLI/rules/skills.md#Intimidation), [Investigation](Mechanics/CLI/rules/skills.md#Investigation), [Medicine](Mechanics/CLI/rules/skills.md#Medicine), [Persuasion](Mechanics/CLI/rules/skills.md#Persuasion), [Religion](Mechanics/CLI/rules/skills.md#Religion), or [Stealth](Mechanics/CLI/rules/skills.md#Stealth)
- **Weapon Proficiencies**: Simple weapons

**Starting Equipment:** *Choose A or B:* (A) 2 [Daggers](Mechanics/CLI/items/dagger-xphb.md), [Arcane Focus (Rod)](Mechanics/CLI/items/rod-xphb.md), [Robe](Mechanics/CLI/items/robe-xphb.md), [Sack](Mechanics/CLI/items/sack-xphb.md), [Shovel](Mechanics/CLI/items/shovel-xphb.md), [Scholar's Pack](Mechanics/CLI/items/scholars-pack-xphb.md) and 13 GP; or (B) 60 GP

## Multiclassing Necromancer

- Gain the Hit Point Die from the Core Necromancer Traits table.   
- Gain the Necromancer's level 1 features, which are listed in the Necromancer Features table. See the multiclassing rules to determine your available spell slots.  

![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaNecromancer/Class/Necromancer-Cover.webp#center)

## Necromancer

Necromancers hold sway over the the forces of life and death, twisting them to serve their ambitions and commanding small armies of lifeless, animated thralls.

### Dark Souls

Necromancers aren't gifted with the spark of magic. Rather, they turn to the most potent and dire source to fuel their powers: their souls. Each necromantic spell and enthralled Undead shaves away a miniscule part of their soul until only a spiritual husk remains, destined for no afterlife. This is a bargain they strike willingly—sometimes eagerly—in pursuit of an ambitious and terrible future.

### Grave Ambition

Necromancers must match their grand intellects with an equal lack of scruples—the willingness to turn to forbidden knowledge and unquestionably evil methods. They are almost always driven by a deeper, darker impulse, a goal that pushes them to the utter brink. This might be the distorted ideal of a "greater good" or a goal to fix morality itself; in every case, Necromancy is a grim implement for their life's work.

### Masters of Undeath

Trial and error teaches a Necromancer to puppet flesh, bone, and the spirits of the dead, binding them to their will. Unlike the Undead commanded by other spellcasters, a Necromancer's thralls are bound by the Necromancer's soul, leading to a small army of perfectly obedient minions that serve their master indefinitely.

## Class Features

### Spellcasting (Level 1)

Though it steadily burns away your very soul, you can cast necromantic spells.

**Cantrips.** You know three Necromancer cantrips of your choice. [Dancing Lights](Mechanics/CLI/spells/dancing-lights-xphb.md), [Mending](Mechanics/CLI/spells/mending-xphb.md), and [Ray of Frost](Mechanics/CLI/spells/ray-of-frost-xphb.md) are recommended. Whenever you gain a Necromancer level, you can replace one of your cantrips from this feature with another Necromancer cantrip of your choice.

When you reach Necromancer levels 4 and 10, you learn another Necromancer cantrip of your choice, as shown in the Cantrips column of the Necromancer Features table.

**Spell Slots.** The Necromancer Features table shows how many spell slots you have to cast your level 1+ spells. You regain all expended slots when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

**Prepared Spells of Level 1+.** You prepare the list of level 1+ spells that are available for you to cast with this feature. To start, choose four level 1 Necromancer spells. [Exhume](Mechanics/CLI/spells/exhume-valdaspire24.md), [Mage Armor](Mechanics/CLI/spells/mage-armor-xphb.md), [Ray of Sickness](Mechanics/CLI/spells/ray-of-sickness-xphb.md), and [Silent Image](Mechanics/CLI/spells/silent-image-xphb.md) are recommended.

The number of spells on your list increases as you gain Necromancer levels, as shown in the Prepared Spells column of the Necromancer Features table. Whenever that number increases, choose additional Necromancer spells until the number of spells on your list matches the number in the Necromancer Features table. The chosen spells must be of a level for which you have spell slots.

If another Necromancer feature gives you spells that you always have prepared, those spells don't count against the number of spells you can prepare with this feature, but those spells otherwise count as Necromancer spells for you.

**Changing Your Prepared Spells.** Whenever you gain a Necromancer level, you can replace one spell on your list with another Necromancer spell for which you have spell slots.

**Spellcasting Ability.** Intelligence is your spellcasting ability for your Necromancer spells.

**Spellcasting Focus.** You can use an Arcane Focus as a [Spellcasting Focus](Mechanics/CLI/rules/variant-rules/spellcasting-focus-xphb.md) for your Necromancer spells.

### Charnel Touch (Level 1)

You can draw upon an inner nexus of necromantic power. You have a pool of Charnel Touch points equal to 5 x your Necromancer level that replenishes when you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md).

As a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, you can channel this negative energy through your touch. Choose a number of Charnel Touch points to expend, up to a maximum of 5 x your [Proficiency Bonus](Mechanics/CLI/rules/variant-rules/proficiency-xphb.md), and make a melee spell attack against one creature within reach. On a hit, the target takes Necrotic damage equal to the number of points expended. This damage is doubled without expending additional points if the attack roll scores a [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md). If the spell attack misses, the Charnel Touch points aren't expended.

### Thralls (Level 2)

Unlike other spellcasters, you animate Undead creatures with a portion of your own life force, ensuring obedience.

**Animate Thralls.** You can animate Undead thralls by performing a ritual over the course of 10 minutes, which can be done during a [Short Rest](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md). The remains of one or more Medium or Small Humanoids within 30 feet of yourself rise as Undead creatures. These Undead become your thralls, and you maintain control over them indefinitely.

**Undead Thralls**

| Name | CR | AC | HP | Speed | Details and Traits |
|------|----|----|----|-------|--------------------|
| [Bloodlurk](Mechanics/CLI/bestiary/undead/bloodlurk-valdaspire24.md) | 2 | 10 | 75 | 20 ft., Climb 20 ft. | Amorphous, Spider Climb |
| [Bone Beast](Mechanics/CLI/bestiary/undead/bone-beast-valdaspire24.md) | 1 | 14 | 27 | 40 ft. | Pack Tactics |
| [Deadnaught](Mechanics/CLI/bestiary/undead/deadnaught-valdaspire24.md) | 1 | 16 | 45* | 30 ft. | Necromantic Bond, Regeneration, Proficiencies |
| [Gorger](Mechanics/CLI/bestiary/undead/gorger-valdaspire24.md) | 1 | 8 | 36 | 30 ft. | — |
| [Skeleton](Mechanics/CLI/bestiary/undead/skeleton-valdaspire24.md) | 1/4 | 14 | 13 | 30 ft. | — |
| [Spirit](Mechanics/CLI/bestiary/undead/spirit-valdaspire24.md) | 1/4 | 15 | 9 | 30 ft., Fly 30 ft. (hover) | Incorporeal Movement, Physical Resistances |
| [Zombie](Mechanics/CLI/bestiary/undead/zombie-valdaspire24.md) | 1/4 | 8 | 15 | 20 ft. | Undead Fortitude |
^undead-thralls

**Combat.** You can mentally control all your thralls without an action. If you have the [Incapacitated](Mechanics/CLI/rules/conditions.md#Incapacitated) condition, your thralls will move to protect your body from harm, but won't attack.

In combat, your thralls take their turns immediately before or after your turn each round (your choice). All thralls collectively share one [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) and [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), which a single thrall can use each round.

**Attacks and Save DCs.** Thralls use your spell attack modifier for their attacks. If one of your thralls forces a creature to make a saving throw, it uses your spell save DC.

**Healing your Thralls.** You can use your [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20(Level%201)) on Undead under your control without making an attack roll. Instead of dealing Necrotic damage, the Undead regains [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to the number of Charnel Touch points expended.

**Maximum Thralls.** You can animate and control one thrall that has a [Challenge Rating](Mechanics/CLI/rules/variant-rules/challenge-rating-xphb.md) of 1/4. As you gain Necromancer levels, you can animate more thralls. The combined CR of all your thralls can't exceed the number shown in the CR Total column of the Necromancer Features table, and the total number of thralls under your control can't exceed the number shown in the Thralls column of the Necromancer Features table.

At any time, you can take a [Magic](Mechanics/CLI/rules/actions.md#Magic) action to sever your connection to one or more thralls. Corporeal Undead crumple into a heap and incorporeal Undead flee to the Ethereal Plane.

**Other Undead.** When you cast [Animate Dead](Mechanics/CLI/spells/animate-dead-xphb.md), [Create Undead](Mechanics/CLI/spells/create-undead-xphb.md), or another spell that lets you create or control Undead, the Undead count as your thralls and can be commanded as such. If these thralls exceed your total [Challenge Rating](Mechanics/CLI/rules/variant-rules/challenge-rating-xphb.md) or number of thralls, you can immediately sever your connection to any of your existing thralls to stay within these limits. Your thralls can never command or create other Undead.

As always, you can't reanimate Undead that have been reduced to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). Your Animate Thralls ritual, the [Animate Dead](Mechanics/CLI/spells/animate-dead-xphb.md) spell, and similar magic only affects Humanoid corpses, whereas your thralls are Undead creatures.

> [!note] Necromancer Variant Rules
> 
> Use the following variant rules to tailor this class to your table and preferred playstyle.
> 
> **Necromancy Unleashed.** In order to ensure timely, balanced play, this class imposes limitations on the number of Undead a player can command, including with spells such as [Animate Dead](Mechanics/CLI/spells/animate-dead-xphb.md). Use this variant rule if you want to throw caution to the wind and embrace the undead horde experience.
> 
> Ignore the "Other Undead" section in the [Thralls](Mechanics/CLI/classes/necromancer-valdaspire24.md#Thralls%20(Level%202)) feature. Undead animated with spells are separate from your thralls for the purposes of your class features, and have no other class-based limitations.
> 
> **Alternate Necromancers.** Necromancers may fuel their spellcasting through ambition or zeal, rather than intellect. When you become a Necromancer, you can choose Wisdom or Charisma for the Primary Ability in the Core Necromancer Traits table. The chosen ability becomes your spellcasting ability, and replaces any Necromancer feature which uses Intelligence.
> 
> A Necromancer that uses Wisdom is called a "Resurrectionist" and one that uses Charisma is called a "Ghoul."
^necromancer-variant-rules

### Dead Space (Level 2)

You gain an extradimensional space that can hold up to 12 Medium or smaller corpses, piles of bones, or Undead creatures. The extradimensional space is linked to an item of your choice, such as a bag, a cloak, or a backpack. As a [Magic](Mechanics/CLI/rules/actions.md#Magic) action, you can use the linked item to place a corpse, pile of bones, or willing Undead creature in the extradimensional space, or to dump out contents of your choice from the extradimensional space. [Thralls](Mechanics/CLI/classes/necromancer-valdaspire24.md#Thralls%20(Level%202)) stored in your Dead Space count toward the total number of thralls under your control. The contents land in spaces of your choice within 5 feet of you, or as near to you as possible if those spaces are occupied.

You can link any item you can carry to the extradimensional space by performing a ritual over the course of 1 hour which can be done during a [Short Rest](Mechanics/CLI/rules/variant-rules/short-rest-xphb.md). The previous item linked to the space becomes disconnected when you link a new one.

### Necromancer Subclass (Level 3)

You gain a Necromancer subclass of your choice. A subclass is a specialization that grants you features at certain Necromancer levels. For the rest of your career, you gain each of your subclass's features that are of your Necromancer level or lower.

### Dark Arcana (Level 3)

As a [Bonus Action](Mechanics/CLI/rules/variant-rules/bonus-action-xphb.md), you can expend a spell slot to replenish your [Charnel Touch](Mechanics/CLI/classes/necromancer-valdaspire24.md#Charnel%20Touch%20(Level%201)) pool. The pool regains points equal to your Intelligence modifier plus `1d8` for each level of the spell slot expended, up to a maximum of your pool's total.

### Ability Score Improvement (Level 4)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Animate Dead (Level 5)

You always have the [Animate Dead](Mechanics/CLI/spells/animate-dead-xphb.md) spell prepared. When you cast this spell, its casting time is an action instead of 1 minute. You can also create a [Spirit](Mechanics/CLI/bestiary/undead/spirit-valdaspire24.md) using the spell.

Additionally, when you cast [Animate Dead](Mechanics/CLI/spells/animate-dead-xphb.md), you can reanimate the corpse of any type of Medium or Small creature that isn't Undead, instead of only Humanoids.. The resulting Undead always uses the statistics of a [Skeleton](Mechanics/CLI/bestiary/undead/skeleton-valdaspire24.md), [Spirit](Mechanics/CLI/bestiary/undead/spirit-valdaspire24.md), or [Zombie](Mechanics/CLI/bestiary/undead/zombie-valdaspire24.md).

### Critical Spellcasting (Level 5)

Your potent Necromancy grants you the following benefits.

**Critical Failures.** When a creature rolls a 1 on the `d20` for a saving throw against one of your spells, it suffers a Critical Failure. It fails the save regardless of its modifiers or the spell save DC. If the spell deals damage, you roll all of the spell's damage dice twice and add them together, then add any relevant modifiers. This additional damage applies only to the creature that rolled a 1.

**Improved Critical.** Your spell attacks can score a [Critical Hit](Mechanics/CLI/rules/variant-rules/critical-hit-xphb.md) on a roll of 19 or 20 on the `d20`.

### Subclass Feature (Level 6)

You gain a feature from your Necromancer Subclass.

### Improved Thralls (Level 7)

Your [Thralls](Mechanics/CLI/classes/necromancer-valdaspire24.md#Thralls%20(Level%202)) grow stronger under your control, granting the following benefits.

**Avoidance.** If one of your thralls is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

**Necrotic Damage.** Whenever one of your thralls deals Bludgeoning, Piercing, or Slashing damage, you can make it deal Necrotic damage instead.

**Turn Immunity.** Your thralls have [Immunity](Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to the [Charmed](Mechanics/CLI/rules/conditions.md#Charmed) and [Frightened](Mechanics/CLI/rules/conditions.md#Frightened) conditions, and are immune to effects that turn Undead.

### Ability Score Improvement (Level 8)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Subclass Feature (Level 10)

You gain a feature from your Necromancer Subclass.

### Ability Score Improvement (Level 12)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Improved Critical Spellcasting (Level 14)

Your [Critical Spellcasting](Mechanics/CLI/classes/necromancer-valdaspire24.md#Critical%20Spellcasting%20(Level%205)) improves in the following ways.

**Critical Failures.** A creature suffers a Critical Failure when it rolls a 1 or 2 on the `d20` for a saving throw against one of your spells.

**Improved Critical.** Your spell attacks can now score a critical hit on a roll of 18-20 on the `d20`.

### Ability Score Improvement (Level 16)

You gain the [Ability Score Improvement](Mechanics/CLI/feats/ability-score-improvement-xphb.md) feat or another feat of your choice for which you qualify.

### Undying Servitude (Level 18)

When one of your thralls is reduced to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), you take a [Reaction](Mechanics/CLI/rules/variant-rules/reaction-xphb.md) to cause it to drop to 1 [Hit Point](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) instead and regain [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md) equal to twice your Necromancer level.

Once you use this feature, you can't use it again until you finish a [Long Rest](Mechanics/CLI/rules/variant-rules/long-rest-xphb.md). You can also restore your use of it by expending a level 3+ spell slot (no action required).

### Epic Boon (Level 19)

You gain an Epic Boon feat or another feat of your choice for which you qualify.

### Lichdom (Level 20)

You unlock the pinnacle of necromantic prowess, through which you conquer death itself: The Rite of Lichdom.

**Becoming a Lich.** The Rite of Lichdom is a ritual that you can perform over the course of 30 days in an isolated location. Once completed, your soul is bound to a spirit jar and you become a lich, an Undead of incredible power. You gain the following benefits, as well as those granted by your Necromancer subclass.

**Creature Type.** You are Undead. You are immune to any effect that turns Undead.

**Spirit Jar.** A spirit jar is an object that houses a lich's soul, safeguarding its immortality. If you drop to 0 [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md), your body crumbles to dust and you reform after `1d4 + 1` days, reviving with all of your [Hit Points](Mechanics/CLI/rules/variant-rules/hit-points-xphb.md). Your new body coalesces in an unoccupied space within 5 feet of your spirit jar. The new body is identical in every way to the one that was destroyed but has none of the original's equipment.

**Truesight.** You have [Truesight](Mechanics/CLI/rules/senses.md#Truesight) with a range of 120 feet.

**Undead Immunities.** You have [Immunity](Mechanics/CLI/rules/variant-rules/immunity-xphb.md) to Necrotic and Poison damage and to the [Exhaustion](Mechanics/CLI/rules/conditions.md#Exhaustion) and [Poisoned](Mechanics/CLI/rules/conditions.md#Poisoned) conditions.

> [!note] Spirit Jar
> 
> A lich's spirit jar, or "phylactery," is as much a memento as it is their anchor to immortality, and as such, no two are alike. Spirit jars are often constructed from objects with sentimental value, such as family heirlooms or prized possessions, but can be fashioned from swords, pieces of armor, or even entire castles.
> 
> Furthermore, every spirit jar has a weakness, a critical flaw by which it can be destroyed, allowing its lich to be slain permanently. These weaknesses, too, are unique to each jar. One might require a ritual to be performed around it for 24 hours, while another might call for the jar to be dipped in the lava of an active volcano. Discuss with your GM the form your spirit jar takes and the weakness it possesses.
^spirit-jar

### Subclass Feature (Level 20)

You gain a feature from your Necromancer Subclass.