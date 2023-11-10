---
Ability1: Hustle
Ability2: Serene Grace
BookSprite: SRD-togekiss-BookSprite.png
BoxSprite: SRD-togekiss-BoxSprite.png
DexCategory: Jubilee Pokemon
DexDescription: Sightings of these Pokemon have become rare nowadays. They used to
  visit peaceful regions, bringing them gifts of kindness and great blessings. But
  they appear to have vanished in this times of conflict.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Togetic]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Super Luck
HomeSprite: SRD-togekiss-HomeSprite.png
Image: togekiss.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Amateur
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Water Pulse|Water Pulse]]'
Number: 468
ShuffleToken: SRD-togekiss-ShuffleToken.png
Type1: Fairy
Type2: Flying
Weight:
  Kilograms: 38.0
  Pounds: 83.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-togekiss-BookSprite.png|wsmall]]
> ![[SRD-togekiss-HomeSprite.png]]
> ![[SRD-togekiss-BoxSprite.png|htiny]]
> ![[SRD-togekiss-ShuffleToken.png|wsmall]]


*Jubilee Pokemon*
*Sightings of these Pokemon have become rare nowadays. They used to visit peaceful regions, bringing them gifts of kindness and great blessings. But they appear to have vanished in this times of conflict.*

**DexID**:: 0468
**Name**:: Togekiss
**Type**:: Fairy / Flying
**Abilities**:: [[SRD-Hustle|Hustle]] / [[SRD-Serene Grace|Serene Grace]] ([[SRD-Super Luck|Super Luck]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'9" / 1.5m
**Weight**: 83.8lbs / 38.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Togetic]] | Stone  | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Togekiss.md"
flatten moves as T
where file.path = this.file.path
```
