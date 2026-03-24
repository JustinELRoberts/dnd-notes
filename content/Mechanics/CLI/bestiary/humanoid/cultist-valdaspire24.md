---
publish: true
aliases:
  - Cultist
created: 2026-03-09T12:15:33.904-04:00
modified: 2026-03-09T12:15:33.904-04:00
published: 2026-03-09T12:15:33.904-04:00
tags:
  - ttrpg-cli/compendium/src/5e/valdaspire24
  - ttrpg-cli/monster/cr/
  - ttrpg-cli/monster/size/small-or-medium
  - ttrpg-cli/monster/type/humanoid/cohort
cssclasses:
  - json5e-monster
obsidianUIMode: preview
---

# Cultist

_Source: Valda's Spire of Secrets (2024)_\
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Creatures/Cultist.webp#right)

Dogmatic and often unhinged, cultists draw upon forbidden, eldritch allies for a taste of arcane might.

```ad-statblock
title: Cultist
![](https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/refs/heads/main/img/ValdaCaptain/Tokens/Cultist.webp#token)
*Small or Medium humanoid (Cohort), Neutral*

- **Armor Class** 14 
- **Hit Points** 6 plus six times your Captain level (the cultist has a number of Hit Dice [d8s] equal to your Captain level)  (6 plus six times your Captain level (the cultist has a number of Hit Dice [d8s] equal to your Captain level))
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|10 (+0)|14 (+2)|12 (+1)| 9 (-1)| 9 (-1)|16 (+3)|

- **Proficiency Bonus** +2
- **Saving Throws** 3+PB
- **Skills** [Arcana](Mechanics/CLI/rules/skills.md#Arcana) +1, [Deception](Mechanics/CLI/rules/skills.md#Deception) +5
- **Senses** passive Perception 9
- **Gear** [studded leather armor](Mechanics/CLI/items/studded-leather-armor-xphb.md), [wand](Mechanics/CLI/items/wand-xphb.md)
- **Languages** Common plus one other language
- **Challenge** 

## Traits

***Proficiencies.*** Simple weapons; Light armor

***Level 5.*** Arcane Excellence. The cultist has a +1 bonus to its spell attack rolls and spell save DC. This bonus increases to +2 at Captain level 9, and +3 at Captain level 13.

***Level 5.*** Greater Curse. The cultist can choose the Necrotic Damage effect of its Eldritch Curse in addition to another effect. At Captain level 9, the Necrotic Damage effect deals `2d8` plus your Charisma modifier Necrotic damage.

## Actions

***Eldritch Curse.*** *Wisdom Saving Throw:* DC equals your Cohort save DC, one creature within 60 feet. *Failure:* The cultist chooses one of the following effects.

***Bleeding.*** Until the start of the cultist's next turn, the target takes an extra `1d4` Necrotic damage whenever it takes damage.

***Evil Eye.*** The target has the [Frightened](Mechanics/CLI/rules/conditions.md#Frightened) condition until the start of the cultist's next turn.

***Hobbled.*** The target's [Speed](Mechanics/CLI/rules/variant-rules/speed-xphb.md) is reduced to 10 feet until the start of the cultist's next turn.

***Necrotic Damage.*** The target takes `1d8` plus your Charisma modifier Necrotic damage.

***Level 17.*** Vulnerability Curse (2/Day). *Constitution Saving Throw:* DC equals your Cohort save DC, one creature within 60 feet. *Failure:* The target has [Vulnerability](Mechanics/CLI/rules/variant-rules/vulnerability-xphb.md) to one damage type of the cultist's choice until the start of the cultist's next turn. This [Vulnerability](Mechanics/CLI/rules/variant-rules/vulnerability-xphb.md) ends early after the target takes the chosen type of damage.

## Reactions

***Level 13.*** Hellish Rebuke. The cultist casts [Hellish Rebuke](Mechanics/CLI/spells/hellish-rebuke-xphb.md) in response to the spell's trigger, using your Charisma as the spellcasting ability (spell save DC equals your Cohort save DC).
```

^statblock
