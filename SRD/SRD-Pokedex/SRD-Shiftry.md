---
Ability1: Chlorophyll
Ability2: Early Bird
BookSprite: SRD-shiftry-BookSprite.png
BoxSprite: SRD-shiftry-BoxSprite.png
DexCategory: Wicked Pokemon
DexDescription: "Feared as protectors of the forest. They are said to live atop towering\
  \ trees dating back thousands of years, creating terrible wind storms. It is said\
  \ they can read people\u2019s minds to prey on their fears."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Nuzleaf]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Pickpocket
HomeSprite: SRD-shiftry-HomeSprite.png
Image: shiftry.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Feint Attack|Feint Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Hurricane|Hurricane]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Pro
  - '[[SRD-Self Destruct|Self Destruct]]'
- - Pro
  - '[[SRD-Sucker Punch|Sucker Punch]]'
Number: 275
ShuffleToken: SRD-shiftry-ShuffleToken.png
Type1: Grass
Type2: Dark
Weight:
  Kilograms: 59.6
  Pounds: 131.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shiftry-BookSprite.png|wsmall]]
> ![[SRD-shiftry-HomeSprite.png]]
> ![[SRD-shiftry-BoxSprite.png|htiny]]
> ![[SRD-shiftry-ShuffleToken.png|wsmall]]


*Wicked Pokemon*
*Feared as protectors of the forest. They are said to live atop towering trees dating back thousands of years, creating terrible wind storms. It is said they can read people’s minds to prey on their fears.*

**DexID**:: 0275
**Name**:: Shiftry
**Type**:: Grass / Dark
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'3" / 1.3m
**Weight**: 131.4lbs / 59.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Nuzleaf]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Shiftry.md"
flatten moves as T
where file.path = this.file.path
```
