---
publish: true
aliases:
  - Evoker Wizard
created: 2026-03-29T21:53:56.082-04:00
modified: 2026-03-29T21:53:56.082-04:00
published: 2026-03-29T21:53:56.082-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/9
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Evoker Wizard (MPMM)
ac: 12
hp: 121
modifier: 2
hit_dice: 22d8 + 22
cr: "9"
stats:
  - 9
  - 14
  - 12
  - 17
  - 12
  - 11
source:
  - MPMM
  - VGM
---

# Evoker Wizard

![](Mechanics/CLI/bestiary/humanoid/img/evoker-wizard.webp#right)
Evokers harness arcane energy to destroy. Many armies employ evokers to rain destruction down on enemy forces.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

## Statblock

```ad-statblock
title: Evoker Wizard
![](/Mechanics/CLI/bestiary/humanoid/token/evoker-wizard-mpmm.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 12 (15 with [mage armor](/Mechanics/CLI/spells/mage-armor-xphb.md))
- **Hit Points** 121 (22d8 + 22) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
| 9 (-1)|14 (+2)|12 (+1)|17 (+3)|12 (+1)|11 (+0)|

- **Proficiency Bonus** +4
- **Saving Throws** Intelligence +7, Wisdom +5
- **Skills** [Arcana](/Mechanics/CLI/skills.md#Arcana) +7, [History](/Mechanics/CLI/skills.md#History) +7
- **Senses** passive Perception 11
- **Languages** any four languages
- **Challenge** 9

## Actions

***Multiattack.*** The evoker makes three Arcane Burst attacks.

***Arcane Burst.*** *Melee  or Ranged Spell Attack:* `+7` to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 25 (`4d10 + 3`) force damage.

***Sculpted Explosion (Recharge 4-6).*** The evoker unleashes a magical explosion of a particular damage type: cold, fire, lightning, or thunder. The magic erupts in a 20-foot-radius sphere centered on a point within 150 feet of the evoker. Each creature in that area must make a DC 15 Dexterity saving throw. The evoker can select up to three creatures it can see in the area to ignore the spell, as the evoker sculpts the spell's energy around them. On a failed save, a creature takes 40 (`9d8`) damage of the chosen type and is knocked [prone](/Mechanics/CLI/conditions.md#Prone). On a successful save, a creature takes half as much damage and isn't knocked [prone](/Mechanics/CLI/conditions.md#Prone).

***Spellcasting.*** The evoker casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 15):

**At will:** [light](/Mechanics/CLI/spells/light-xphb.md), [mage hand](/Mechanics/CLI/spells/mage-hand-xphb.md), [message](/Mechanics/CLI/spells/message-xphb.md), [prestidigitation](/Mechanics/CLI/spells/prestidigitation-xphb.md)

**2/day each:** [ice storm](/Mechanics/CLI/spells/ice-storm-xphb.md), [lightning bolt](/Mechanics/CLI/spells/lightning-bolt-xphb.md), [mage armor](/Mechanics/CLI/spells/mage-armor-xphb.md)

**1/day each:** [wall of ice](/Mechanics/CLI/spells/wall-of-ice-xphb.md)
```

^statblock

## Environment

urban

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 262, Volo's Guide to Monsters p. 214_
