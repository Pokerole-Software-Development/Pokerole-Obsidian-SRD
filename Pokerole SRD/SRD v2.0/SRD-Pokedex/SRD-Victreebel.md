---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-victreebel-BookSprite.png
BoxSprite: SRD-victreebel-BoxSprite.png
DexCategory: Flycatcher Pokemon
DexDescription: They live together in small groups at tropical areas. Victreebel uses
  a sweet honey-like smell to lure and attract prey. They also use their long vines
  to rustle bushes around. They are territorial and aggressive.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Weepinbell]]'
GenderType: ''
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Gluttony
HomeSprite: SRD-victreebel-HomeSprite.png
Image: victreebel.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swallow|Swallow]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spit Up|Spit Up]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stockpile|Stockpile]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Tornado|Leaf Tornado]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leaf Blade|Leaf Blade]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Belch|Belch]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Whip|Power Whip]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
Number: 71
ShuffleToken: SRD-victreebel-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 15.5
  Pounds: 34.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-victreebel-BookSprite.png|wsmall]]
> ![[SRD-victreebel-HomeSprite.png]]
> ![[SRD-victreebel-BoxSprite.png|htiny]]
> ![[SRD-victreebel-ShuffleToken.png|wsmall]]


*Flycatcher Pokemon*
*They live together in small groups at tropical areas. Victreebel uses a sweet honey-like smell to lure and attract prey. They also use their long vines to rustle bushes around. They are territorial and aggressive.*

**DexID**:: 0071
**Name**:: Victreebel
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Gluttony|Gluttony]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'6" / 1.7m
**Weight**: 34.2lbs / 15.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon            | Kind   | Item       |
|:----------|:-------------------|:-------|:-----------|
| From      | [[SRD-Weepinbell]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Victreebel.md"
flatten moves as T
where file.path = this.file.path
```
