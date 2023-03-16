---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-meganium-BookSprite.png
BoxSprite: SRD-meganium-BoxSprite.png
DexCategory: Herb Pokemon
DexDescription: Meganium's breath has the power to revive dead grass and plants. The
  aroma that comes from its petals contains a substance that calms aggressive feelings
  and helps others to restore health.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Bayleef]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Leaf Guard
HomeSprite: SRD-meganium-HomeSprite.png
Image: meganium.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Body Slam|Body Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
Number: 154
ShuffleToken: SRD-meganium-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 100.5
  Pounds: 221.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meganium-BookSprite.png|wsmall]]
> ![[SRD-meganium-HomeSprite.png]]
> ![[SRD-meganium-BoxSprite.png|htiny]]
> ![[SRD-meganium-ShuffleToken.png|wsmall]]


*Herb Pokemon*
*Meganium's breath has the power to revive dead grass and plants. The aroma that comes from its petals contains a substance that calms aggressive feelings and helps others to restore health.*

**DexID**:: 0154
**Name**:: Meganium
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Leaf Guard|Leaf Guard]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 5'9" / 1.8m
**Weight**: 221.6lbs / 100.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Bayleef]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Meganium.md"
flatten moves as T
where file.path = this.file.path
```
