---
Ability1: Clear Body
Ability2: Infiltrator
BookSprite: SRD-drakloak-BookSprite.png
BoxSprite: SRD-drakloak-BoxSprite.png
DexCategory: Caretaker Pokemon
DexDescription: "It battles alongside Dreepy and dotes on them until they evolve.\
  \ Without a Dreepy to place on its head and care for, it gets so uneasy it\u2019\
  ll try to substitute it with any Pokemon it finds"
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Dreepy]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Dragapult]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Cursed Body
HomeSprite: SRD-drakloak-HomeSprite.png
Image: drakloak.png
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
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
Number: 886
ShuffleToken: SRD-drakloak-ShuffleToken.png
Type1: Dragon
Type2: Ghost
Weight:
  Kilograms: 11.0
  Pounds: 24.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-drakloak-BookSprite.png|wsmall]]
> ![[SRD-drakloak-HomeSprite.png]]
> ![[SRD-drakloak-BoxSprite.png|htiny]]
> ![[SRD-drakloak-ShuffleToken.png|wsmall]]


*Caretaker Pokemon*
*It battles alongside Dreepy and dotes on them until they evolve. Without a Dreepy to place on its head and care for, it gets so uneasy it’ll try to substitute it with any Pokemon it finds*

**DexID**:: 0886
**Name**:: Drakloak
**Type**:: Dragon / Ghost
**Abilities**:: [[SRD-Clear Body|Clear Body]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'6" / 1.4m
**Weight**: 24.3lbs / 11.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Dreepy]]    | Level  | Slow    |
| To        | [[SRD-Dragapult]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Drakloak.md"
flatten moves as T
where file.path = this.file.path
```
