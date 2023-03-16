---
Ability1: Leaf Guard
Ability2: Oblivious
BookSprite: SRD-steenee-BookSprite.png
BoxSprite: SRD-steenee-BoxSprite.png
DexCategory: Fruit Pokemon
DexDescription: "Its sweet aroma keeps attracting predators but it fends them away\
  \ with its hard and bitter head leaves. It likes to be taken seriously and can be\
  \ hard to deal with, if you make it mad you\u2019ll receive a kick."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bounsweet]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Tsareena]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Sweet Veil
HomeSprite: SRD-steenee-HomeSprite.png
Image: steenee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - Starter
  - '[[SRD-Splash|Splash]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Stomp|Stomp]]'
- - Amateur
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Acupressure|Acupressure]]'
- - Pro
  - '[[SRD-Feint|Feint]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
Number: 762
ShuffleToken: SRD-steenee-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 8.2
  Pounds: 18.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-steenee-BookSprite.png|wsmall]]
> ![[SRD-steenee-HomeSprite.png]]
> ![[SRD-steenee-BoxSprite.png|htiny]]
> ![[SRD-steenee-ShuffleToken.png|wsmall]]


*Fruit Pokemon*
*Its sweet aroma keeps attracting predators but it fends them away with its hard and bitter head leaves. It likes to be taken seriously and can be hard to deal with, if you make it mad you’ll receive a kick.*

**DexID**:: 0762
**Name**:: Steenee
**Type**:: Grass
**Abilities**:: [[SRD-Leaf Guard|Leaf Guard]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Sweet Veil|Sweet Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 18.1lbs / 8.2kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Bounsweet]] | Level  | Medium  |
| To        | [[SRD-Tsareena]]  | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Steenee.md"
flatten moves as T
where file.path = this.file.path
```
