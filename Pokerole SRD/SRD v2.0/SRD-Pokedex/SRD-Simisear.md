---
Ability1: Gluttony
Ability2: ''
BookSprite: SRD-simisear-BookSprite.png
BoxSprite: SRD-simisear-BoxSprite.png
DexCategory: Ember Pokemon
DexDescription: A flame burns on top of its head. It scatters embers from its head
  and tail to sear its opponents. It loves sweets and is not afraid to go near humans
  to try to get some candy by begging or by stealing.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Pansear]]'
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Blaze
HomeSprite: SRD-simisear-HomeSprite.png
Image: simisear.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lick|Lick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flame Burst|Flame Burst]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Gunk Shot|Gunk Shot]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Superpower|Superpower]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heat Wave|Heat Wave]]'
Number: 514
ShuffleToken: SRD-simisear-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-simisear-BookSprite.png|wsmall]]
> ![[SRD-simisear-HomeSprite.png]]
> ![[SRD-simisear-BoxSprite.png|htiny]]
> ![[SRD-simisear-ShuffleToken.png|wsmall]]


*Ember Pokemon*
*A flame burns on top of its head. It scatters embers from its head and tail to sear its opponents. It loves sweets and is not afraid to go near humans to try to get some candy by begging or by stealing.*

**DexID**:: 0514
**Name**:: Simisear
**Type**:: Fire
**Abilities**:: [[SRD-Gluttony|Gluttony]] ([[SRD-Blaze|Blaze]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Pansear]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Simisear.md"
flatten moves as T
where file.path = this.file.path
```
