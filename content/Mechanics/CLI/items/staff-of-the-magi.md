---
obsidianUIMode: preview
cssclasses:
- json5e-item
tags:
- ttrpg-cli/compendium/src/5e/dmg
- ttrpg-cli/item/attunement/required
- ttrpg-cli/item/rarity/legendary
- ttrpg-cli/item/tier/major
- ttrpg-cli/item/weapon/simple
aliases:
- "Staff of the Magi"
---
# Staff of the Magi
*Staff, weapon, major, legendary (requires attunement by a sorcerer, warlock, or wizard)*  
![](Mechanics/CLI/items/img/staff-of-the-magi.webp#right)

- **Damage**:
  - One-handed: 1d6 bludgeoning
  - Two-handed: 1d8 bludgeoning
- **Properties**: [Versatile](Mechanics/CLI/rules/item-properties.md#Versatile)
- **Weight**: 4.0 lbs.

This staff can be wielded as a magic quarterstaff that grants a +2 bonus to attack and damage rolls made with it. While you hold it, you gain a +2 bonus to spell attack rolls.

The staff has 50 charges for the following properties. It regains `4d6 + 2` expended charges daily at dawn. If you expend the last charge, roll a `d20`. On a 20, the staff regains `1d12 + 1` charges.

## Spell Absorption

While holding the staff, you have advantage on saving throws against spells. In addition, you can use your reaction when another creature casts a spell that targets only you. If you do, the staff absorbs the magic of the spell, canceling its effect and gaining a number of charges equal to the absorbed spell's level. However, if doing so brings the staff's total number of charges above 50, the staff explodes as if you activated its retributive strike (see below).

## Spells

While holding the staff, you can use an action to expend some of its charges to cast one of the following spells from it, using your spell save DC and spellcasting ability: [conjure elemental](Mechanics/CLI/spells/conjure-elemental-xphb.md) (7 charges), [dispel magic](Mechanics/CLI/spells/dispel-magic-xphb.md) (3 charges), [fireball](Mechanics/CLI/spells/fireball-xphb.md) (7th-level version, 7 charges), [flaming sphere](Mechanics/CLI/spells/flaming-sphere-xphb.md) (2 charges), [ice storm](Mechanics/CLI/spells/ice-storm-xphb.md) (4 charges), [invisibility](Mechanics/CLI/spells/invisibility-xphb.md) (2 charges), [knock](Mechanics/CLI/spells/knock-xphb.md) (2 charges), [lightning bolt](Mechanics/CLI/spells/lightning-bolt-xphb.md) (7th-level version, 7 charges), [passwall](Mechanics/CLI/spells/passwall-xphb.md) (5 charges), [plane shift](Mechanics/CLI/spells/plane-shift-xphb.md) (7 charges), [telekinesis](Mechanics/CLI/spells/telekinesis-xphb.md) (5 charges), [wall of fire](Mechanics/CLI/spells/wall-of-fire-xphb.md) (4 charges), or [web](Mechanics/CLI/spells/web-xphb.md) (2 charges).

You can also use an action to cast one of the following spells from the staff without using any charges: [arcane lock](Mechanics/CLI/spells/arcane-lock-xphb.md), [detect magic](Mechanics/CLI/spells/detect-magic-xphb.md), [enlarge/reduce](Mechanics/CLI/spells/enlarge-reduce-xphb.md), [light](Mechanics/CLI/spells/light-xphb.md), [mage hand](Mechanics/CLI/spells/mage-hand-xphb.md), or [protection from evil and good](Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md).

## Retributive Strike

You can use an action to break the staff over your knee or against a solid surface, performing a retributive strike. The staff is destroyed and releases its remaining magic in an explosion that expands to fill a 30-foot-radius sphere centered on it.

You have a 50 percent chance to instantly travel to a random plane of existence, avoiding the explosion. If you fail to avoid the effect, you take force damage equal to 16 × the number of charges in the staff. Every other creature in the area must make a DC 17 Dexterity saving throw. On a failed save, a creature takes an amount of damage based on how far away it is from the point of origin, as shown in the following table. On a successful save, a creature takes half as much damage.

| Distance from Origin | Damage |
|----------------------|--------|
| 10 ft. away or closer | 8 × the number of charges in the staff |
| 11 to 20 ft. away | 6 × the number of charges in the staff |
| 21 to 30 ft. away | 4 × the number of charges in the staff |
^distance-from-origin-damage

*Source: Dungeon Master's Guide p. 203. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*