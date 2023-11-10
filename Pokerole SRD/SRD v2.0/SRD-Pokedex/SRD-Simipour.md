---
Ability1: Gluttony
Ability2: ''
BookSprite: SRD-simipour-BookSprite.png
BoxSprite: SRD-simipour-BoxSprite.png
DexCategory: Geyser Pokemon
DexDescription: It prefers places with clean water. When its tuft runs low, it replenishes
  it by siphoning water up with its tail. It is said that if you see a Simipour Swimming
  in a pond, the water is safe to drink.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Panpour]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Torrent
HomeSprite: SRD-simipour-HomeSprite.png
Image: simipour.png
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
  - '[[SRD-Scald|Scald]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - Pro
  - '[[SRD-Gunk Shot|Gunk Shot]]'
Number: 516
ShuffleToken: SRD-simipour-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 29.0
  Pounds: 63.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-simipour-BookSprite.png|wsmall]]
> ![[SRD-simipour-HomeSprite.png]]
> ![[SRD-simipour-BoxSprite.png|htiny]]
> ![[SRD-simipour-ShuffleToken.png|wsmall]]


*Geyser Pokemon*
*It prefers places with clean water. When its tuft runs low, it replenishes it by siphoning water up with its tail. It is said that if you see a Simipour Swimming in a pond, the water is safe to drink.*

**DexID**:: 0516
**Name**:: Simipour
**Type**:: Water
**Abilities**:: [[SRD-Gluttony|Gluttony]] ([[SRD-Torrent|Torrent]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 63.9lbs / 29.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Panpour]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Simipour.md"
flatten moves as T
where file.path = this.file.path
```
