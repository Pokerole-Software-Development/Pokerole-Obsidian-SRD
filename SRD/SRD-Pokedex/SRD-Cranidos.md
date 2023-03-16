---
Ability1: Mold Breaker
Ability2: ''
BookSprite: SRD-cranidos-BookSprite.png
BoxSprite: SRD-cranidos-BoxSprite.png
DexCategory: Head Butt Pokemon
DexDescription: "It was resurrected from an iron ball-like fossil. It downs prey with\
  \ headbutts and tramples trees and walls with ease. They were plentiful 100 million\
  \ years ago. You can\u2019t find one nowadays except as a fossil."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Rampardos]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Sheer Force
HomeSprite: SRD-cranidos-HomeSprite.png
Image: cranidos.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - Beginner
  - '[[SRD-Pursuit|Pursuit]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Chip Away|Chip Away]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Ace
  - '[[SRD-Screech|Screech]]'
- - Ace
  - '[[SRD-Head Smash|Head Smash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Hammer Arm|Hammer Arm]]'
Number: 408
ShuffleToken: SRD-cranidos-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 31.5
  Pounds: 69.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cranidos-BookSprite.png|wsmall]]
> ![[SRD-cranidos-HomeSprite.png]]
> ![[SRD-cranidos-BoxSprite.png|htiny]]
> ![[SRD-cranidos-ShuffleToken.png|wsmall]]


*Head Butt Pokemon*
*It was resurrected from an iron ball-like fossil. It downs prey with headbutts and tramples trees and walls with ease. They were plentiful 100 million years ago. You can’t find one nowadays except as a fossil.*

**DexID**:: 0408
**Name**:: Cranidos
**Type**:: Rock
**Abilities**:: [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'0" / 0.9m
**Weight**: 69.4lbs / 31.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Rampardos]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cranidos.md"
flatten moves as T
where file.path = this.file.path
```
