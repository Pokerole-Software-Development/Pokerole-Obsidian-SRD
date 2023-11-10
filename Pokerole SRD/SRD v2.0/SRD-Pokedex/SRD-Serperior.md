---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-serperior-BookSprite.png
BoxSprite: SRD-serperior-BoxSprite.png
DexCategory: Regal Pokemon
DexDescription: It stops enemies dead in their tracks with just one intense glare.
  It is a noble and proud Pokemon. It is not aggressive but it can be very stubborn.
  It takes a really strong foe for it to take the fight seriously.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Servine]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 10.8
  Meters: 3.3
HiddenAbility: Contrary
HomeSprite: SRD-serperior-HomeSprite.png
Image: serperior.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Wrap|Wrap]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Leaf Tornado|Leaf Tornado]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Leaf Blade|Leaf Blade]]'
- - Amateur
  - '[[SRD-Coil|Coil]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Gastro Acid|Gastro Acid]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
Number: 497
ShuffleToken: SRD-serperior-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 63.0
  Pounds: 138.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-serperior-BookSprite.png|wsmall]]
> ![[SRD-serperior-HomeSprite.png]]
> ![[SRD-serperior-BoxSprite.png|htiny]]
> ![[SRD-serperior-ShuffleToken.png|wsmall]]


*Regal Pokemon*
*It stops enemies dead in their tracks with just one intense glare. It is a noble and proud Pokemon. It is not aggressive but it can be very stubborn. It takes a really strong foe for it to take the fight seriously.*

**DexID**:: 0497
**Name**:: Serperior
**Type**:: Grass
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Contrary|Contrary]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 10'8" / 3.3m
**Weight**: 138.9lbs / 63.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Servine]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Serperior.md"
flatten moves as T
where file.path = this.file.path
```
