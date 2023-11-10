---
Ability1: Leaf Guard
Ability2: Oblivious
BookSprite: SRD-bounsweet-BookSprite.png
BoxSprite: SRD-bounsweet-BoxSprite.png
DexCategory: Fruit Pokemon
DexDescription: "This happy-go-lucky Pokemon produces a delicious aroma that unfortunately\
  \ attracts predators to it, when it escapes, it looks as if it\u2019s happily skipping\
  \ around so it rarely gets help."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Steenee]]'
  Speed: Medium
GenderType: F
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Sweet Veil
HomeSprite: SRD-bounsweet-HomeSprite.png
Image: bounsweet.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Splash|Splash]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Play Rough|Play Rough]]'
- - Pro
  - '[[SRD-Acupressure|Acupressure]]'
Number: 761
ShuffleToken: SRD-bounsweet-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 3.2
  Pounds: 7.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bounsweet-BookSprite.png|wsmall]]
> ![[SRD-bounsweet-HomeSprite.png]]
> ![[SRD-bounsweet-BoxSprite.png|htiny]]
> ![[SRD-bounsweet-ShuffleToken.png|wsmall]]


*Fruit Pokemon*
*This happy-go-lucky Pokemon produces a delicious aroma that unfortunately attracts predators to it, when it escapes, it looks as if it’s happily skipping around so it rarely gets help.*

**DexID**:: 0761
**Name**:: Bounsweet
**Type**:: Grass
**Abilities**:: [[SRD-Leaf Guard|Leaf Guard]] / [[SRD-Oblivious|Oblivious]] ([[SRD-Sweet Veil|Sweet Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 7.1lbs / 3.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Steenee]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bounsweet.md"
flatten moves as T
where file.path = this.file.path
```
