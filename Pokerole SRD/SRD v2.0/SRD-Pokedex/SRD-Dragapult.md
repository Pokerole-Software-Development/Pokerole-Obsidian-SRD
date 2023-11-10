---
Ability1: Clear Body
Ability2: Infiltrator
BookSprite: SRD-dragapult-BookSprite.png
BoxSprite: SRD-dragapult-BoxSprite.png
DexCategory: Stealth Pokemon
DexDescription: "When it isn\u2019t battling, it keeps Dreepy in the holes on its\
  \ horns. Once a fight starts, it launches the Dreepy like supersonic missiles. The\
  \ smaller Pokemon appear happy to be shot and will reload themselves."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Drakloak]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 9.8
  Meters: 3.0
HiddenAbility: Cursed Body
HomeSprite: SRD-dragapult-HomeSprite.png
Image: dragapult.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Infestation|Infestation]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Lock-On|Lock-On]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Double Hit|Double Hit]]'
- - Amateur
  - '[[SRD-U-Turn|U-Turn]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Dragon Darts|Dragon Darts]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Ace
  - '[[SRD-Take Down|Take Down]]'
- - Ace
  - '[[SRD-Dragon Rush|Dragon Rush]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Reflect|Reflect]]'
- - Pro
  - '[[SRD-Light Screen|Light Screen]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 887
ShuffleToken: SRD-dragapult-ShuffleToken.png
Type1: Dragon
Type2: Ghost
Weight:
  Kilograms: 50.0
  Pounds: 110.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-dragapult-BookSprite.png|wsmall]]
> ![[SRD-dragapult-HomeSprite.png]]
> ![[SRD-dragapult-BoxSprite.png|htiny]]
> ![[SRD-dragapult-ShuffleToken.png|wsmall]]


*Stealth Pokemon*
*When it isn’t battling, it keeps Dreepy in the holes on its horns. Once a fight starts, it launches the Dreepy like supersonic missiles. The smaller Pokemon appear happy to be shot and will reload themselves.*

**DexID**:: 0887
**Name**:: Dragapult
**Type**:: Dragon / Ghost
**Abilities**:: [[SRD-Clear Body|Clear Body]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 9'8" / 3.0m
**Weight**: 110.2lbs / 50.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Drakloak]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Dragapult.md"
flatten moves as T
where file.path = this.file.path
```
