---
publish: true
aliases:
  - Prismatic Spray
created: 2026-03-09T12:15:33.915-04:00
modified: 2026-03-09T12:15:33.915-04:00
published: 2026-03-09T12:15:33.915-04:00
tags:
  - ttrpg-cli/compendium/src/5e/xphb
  - ttrpg-cli/spell/class/bard
  - ttrpg-cli/spell/class/sorcerer
  - ttrpg-cli/spell/class/wizard
  - ttrpg-cli/spell/feat/boon-of-siberys/sorcerer-spell
  - ttrpg-cli/spell/level/7th-level
  - ttrpg-cli/spell/school/evocation
  - ttrpg-cli/spell/subclass/evoker
cssclasses:
  - json5e-spell
obsidianUIMode: preview
classes:
  - Bard
  - Sorcerer
  - Wizard
  - Wizard (Evoker)
---

# Prismatic Spray

_7th-level, Evocation_

- **Casting time:** 1 Action
- **Range:** Self (60-foot Cone)
- **Components:** V, S
- **Duration:** Instantaneous

Eight rays of light flash from you in a 60-foot [Cone](Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md). Each creature in the [Cone](Mechanics/CLI/rules/variant-rules/cone-area-of-effect-xphb.md) makes a Dexterity saving throw. For each target, roll `1d8` to determine which color ray affects it, consulting the Prismatic Rays table.

**Prismatic Rays**

| dice: 1d8 | Ray |
|-----------|-----|
| 1 | **Red.** _Failed Save:_ `12d6` Fire damage. _Successful Save:_ Half as much damage. |
| 2 | **Orange.** _Failed Save:_ `12d6` Acid damage. _Successful Save:_ Half as much damage. |
| 3 | **Yellow.** _Failed Save:_ `12d6` Lightning damage. _Successful Save:_ Half as much damage. |
| 4 | **Green.** _Failed Save:_ `12d6` Poison damage. _Successful Save:_ Half as much damage. |
| 5 | **Blue.** _Failed Save:_ `12d6` Cold damage. _Successful Save:_ Half as much damage. |
| 6 | **Indigo.** _Failed Save:_ The target has the [Restrained](Mechanics/CLI/rules/conditions.md#Restrained) condition and makes a Constitution saving throw at the end of each of its turns. If it successfully saves three times, the condition ends. If it fails three times, it has the [Petrified](Mechanics/CLI/rules/conditions.md#Petrified) condition until it is freed by an effect like the [Greater Restoration](Mechanics/CLI/spells/greater-restoration-xphb.md) spell. The successes and failures needn't be consecutive; keep track of both until the target collects three of a kind. |
| 7 | **Violet.** _Failed Save:_ The target has the [Blinded](Mechanics/CLI/rules/conditions.md#Blinded) condition and makes a Wisdom saving throw at the start of your next turn. On a successful save, the condition ends. On a failed save, the condition ends, and the creature teleports to another plane of existence (DM's choice). |
| 8 | **Special.** The target is struck by two rays. Roll twice, rerolling any 8. |
^prismatic-rays

**Classes**: [Bard](Mechanics/CLI/lists/list-spells-classes-bard.md); [Sorcerer](Mechanics/CLI/lists/list-spells-classes-sorcerer.md); [Wizard (Evoker)](Mechanics/CLI/lists/list-spells-classes-evoker-xphb.md "subclass=XPHB;class=XPHB"); [Wizard](Mechanics/CLI/lists/list-spells-classes-wizard.md)

_Source: Player's Handbook (2024) p. 307. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)_
