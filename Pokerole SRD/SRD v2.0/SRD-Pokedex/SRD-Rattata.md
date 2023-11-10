---
Ability1: Run Away
Ability2: Guts
BookSprite: SRD-rattata-BookSprite.png
BoxSprite: SRD-rattata-BoxSprite.png
DexCategory: Mouse Pokemon
DexDescription: It can live anywhere it can find food, but they are often in cities
  and fields. They form large families in their burrows. Since they are often preyed
  on, Rattatas are always alert and quick to flee.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Raticate]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Hustle
HomeSprite: SRD-rattata-HomeSprite.png
Image: rattata.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Hyper Fang|Hyper Fang]]'
- - Amateur
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Super Fang|Super Fang]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Pro
  - '[[SRD-Screech|Screech]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
Number: 19
ShuffleToken: SRD-rattata-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 3.5
  Pounds: 7.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-rattata-BookSprite.png|wsmall]]
> ![[SRD-rattata-HomeSprite.png]]
> ![[SRD-rattata-BoxSprite.png|htiny]]
> ![[SRD-rattata-ShuffleToken.png|wsmall]]


*Mouse Pokemon*
*It can live anywhere it can find food, but they are often in cities and fields. They form large families in their burrows. Since they are often preyed on, Rattatas are always alert and quick to flee.*

**DexID**:: 0019
**Name**:: Rattata
**Type**:: Normal
**Abilities**:: [[SRD-Run Away|Run Away]] / [[SRD-Guts|Guts]] ([[SRD-Hustle|Hustle]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 7.7lbs / 3.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Raticate]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Rattata.md"
flatten moves as T
where file.path = this.file.path
```
