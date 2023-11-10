---
Ability1: Chlorophyll
Ability2: Own Tempo
BookSprite: SRD-lilligant-BookSprite.png
BoxSprite: SRD-lilligant-BoxSprite.png
DexCategory: Flowering Pokemon
DexDescription: "Even veteran gardeners face a challenge in getting its beautiful\
  \ flower to bloom as it withers with ease. This Pokemon is popular among celebrities\
  \ due to it\u2019s grace, elegance and delicious aroma."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Petilil]]'
GenderType: F
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Leaf Guard
HomeSprite: SRD-lilligant-HomeSprite.png
Image: lilligant.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Teeter Dance|Teeter Dance]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Pro
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Pro
  - '[[SRD-Ingrain|Ingrain]]'
Number: 549
ShuffleToken: SRD-lilligant-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 16.3
  Pounds: 35.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-lilligant-BookSprite.png|wsmall]]
> ![[SRD-lilligant-HomeSprite.png]]
> ![[SRD-lilligant-BoxSprite.png|htiny]]
> ![[SRD-lilligant-ShuffleToken.png|wsmall]]


*Flowering Pokemon*
*Even veteran gardeners face a challenge in getting its beautiful flower to bloom as it withers with ease. This Pokemon is popular among celebrities due to it’s grace, elegance and delicious aroma.*

**DexID**:: 0549
**Name**:: Lilligant
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Own Tempo|Own Tempo]] ([[SRD-Leaf Guard|Leaf Guard]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 35.9lbs / 16.3kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item      |
|:----------|:----------------|:-------|:----------|
| From      | [[SRD-Petilil]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Lilligant.md"
flatten moves as T
where file.path = this.file.path
```
