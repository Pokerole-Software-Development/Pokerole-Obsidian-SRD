---
Ability1: Gluttony
Ability2: ''
BookSprite: SRD-simisage-BookSprite.png
BoxSprite: SRD-simisage-BoxSprite.png
DexCategory: Thorn Monkey Pokemon
DexDescription: "It becomes somewhat ill tempered after it evolves. The leaves on\
  \ it\u2019s head can be made into a bitter but effective medicine, however it will\
  \ attack anyone trying to take them with it\u2019s thorned tail."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Pansage]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Overgrow
HomeSprite: SRD-simisage-HomeSprite.png
Image: simisage.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Number: 512
ShuffleToken: SRD-simisage-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 30.5
  Pounds: 67.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-simisage-BookSprite.png|wsmall]]
> ![[SRD-simisage-HomeSprite.png]]
> ![[SRD-simisage-BoxSprite.png|htiny]]
> ![[SRD-simisage-ShuffleToken.png|wsmall]]


*Thorn Monkey Pokemon*
*It becomes somewhat ill tempered after it evolves. The leaves on it’s head can be made into a bitter but effective medicine, however it will attack anyone trying to take them with it’s thorned tail.*

**DexID**:: 0512
**Name**:: Simisage
**Type**:: Grass
**Abilities**:: [[SRD-Gluttony|Gluttony]] ([[SRD-Overgrow|Overgrow]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 67.2lbs / 30.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Pansage]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Simisage.md"
flatten moves as T
where file.path = this.file.path
```
