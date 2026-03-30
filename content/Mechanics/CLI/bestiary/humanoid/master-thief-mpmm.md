---
publish: true
aliases:
  - Master Thief
created: 2026-03-29T21:53:56.009-04:00
modified: 2026-03-29T21:53:56.009-04:00
published: 2026-03-29T21:53:56.009-04:00
tags:
  - ttrpg-cli/compendium/src/5e/mpmm
  - ttrpg-cli/monster/cr/5
  - ttrpg-cli/monster/environment/urban
  - ttrpg-cli/monster/size/medium
  - ttrpg-cli/monster/type/humanoid
cssclasses:
  - json5e-monster
obsidianUIMode: preview
statblock: true
statblock-link: "#^statblock"
name: Master Thief (MPMM)
ac: 16
hp: 84
modifier: 4
hit_dice: 13d8 + 26
cr: "5"
stats:
  - 11
  - 18
  - 14
  - 11
  - 11
  - 12
source:
  - MPMM
  - VGM
---

# Master Thief

![](Mechanics/CLI/bestiary/humanoid/img/master-thief.webp#right)
Master thieves are known for perpetrating daring heists. They tend to develop a romanticized reputation. A master thief might "retire" from hands-on work to run a thieves' guild, spearhead some covert enterprise, or enjoy a quiet life of luxury.

When a master thief completes a challenging heist, they often leave behind a calling card to taunt their victims. You may roll on the Master Thief Calling Cards table to determine what a master thief leaves behind.

**Master Thief Calling Cards**

| dice: d10 | Calling Card |
|-----------|--------------|
| 1 | Tiny, folded paper cat |
| 2 | Red bird feather |
| 3 | Rose petal |
| 4 | Figurine made from twigs and twine |
| 5 | Small note with the words "It's been fun!" written on it in an ornate script |
| 6 | Glass bead that looks like an eye |
| 7 | Pistachio shells |
| 8 | Two playing cards balanced against each other, resembling a tent |
| 9 | Worthless coin with a bite mark in it |
| 10 | Chalk or charcoal sketch of a domino mask |
^master-thief-calling-cards

```ad-statblock
title: Master Thief
![](/Mechanics/CLI/bestiary/humanoid/token/master-thief-mpmm.webp#token)
*Medium humanoid, Any alignment*

- **Armor Class** 16 ([studded leather](/Mechanics/CLI/items/studded-leather-armor.md))
- **Hit Points** 84 (13d8 + 26) 
- **Speed** 30 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|11 (+0)|18 (+4)|14 (+2)|11 (+0)|11 (+0)|12 (+1)|

- **Proficiency Bonus** +3
- **Saving Throws** Dexterity +7, Intelligence +3
- **Skills** [Acrobatics](/Mechanics/CLI/skills.md#Acrobatics) +7, [Athletics](/Mechanics/CLI/skills.md#Athletics) +3, [Perception](/Mechanics/CLI/skills.md#Perception) +3, [Sleight of Hand](/Mechanics/CLI/skills.md#Sleight%20of%20Hand) +7, [Stealth](/Mechanics/CLI/skills.md#Stealth) +7
- **Senses** passive Perception 13
- **Languages** any one language (usually Common) plus thieves' cant
- **Challenge** 5

## Traits

***Evasion.*** If the thief is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the thief instead takes no damage if it succeeds on the saving throw and only half damage if it fails, provided the thief isn't [incapacitated](/Mechanics/CLI/conditions.md#Incapacitated).

## Actions

***Multiattack.*** The thief makes three Shortsword or Shortbow attacks.

***Shortsword.*** *Melee Weapon Attack:* `+7` to hit, reach 5 ft., one target. *Hit:* 7 (`1d6 + 4`) piercing damage plus 3 (`1d6`) poison damage.

***Shortbow.*** *Ranged Weapon Attack:* `+7` to hit, range 80/320 ft., one target. *Hit:* 7 (`1d6 + 4`) piercing damage plus 3 (`1d6`) poison damage.

## Bonus Actions

***Cunning Action.*** The thief takes the [Dash](/Mechanics/CLI/actions.md#Dash), [Disengage](/Mechanics/CLI/actions.md#Disengage), or [Hide](/Mechanics/CLI/actions.md#Hide) action.

## Reactions

***Uncanny Dodge.*** The thief halves the damage that it takes from an attack that hits it. The thief must be able to see the attacker.
```

^statblock

## Environment

urban

## Sources

_Mordenkainen Presents: Monsters of the Multiverse p. 174, Volo's Guide to Monsters p. 216_
