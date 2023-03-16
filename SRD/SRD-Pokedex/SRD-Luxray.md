---
Ability1: Rivalry
Ability2: Intimidate
BookSprite: SRD-luxray-BookSprite.png
BoxSprite: SRD-luxray-BoxSprite.png
DexCategory: Gleam Eyes Pokemon
DexDescription: It is said that it can see through walls. This Pokemon can easily
  find hiding prey and locate its young. Male Luxrays can be found roaming alone,
  patrolling their territory; the females hunt in groups.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Luxio]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Guts
HomeSprite: SRD-luxray-HomeSprite.png
Image: luxray.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 405
ShuffleToken: SRD-luxray-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 42.0
  Pounds: 92.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-luxray-BookSprite.png|wsmall]]
> ![[SRD-luxray-HomeSprite.png]]
> ![[SRD-luxray-BoxSprite.png|htiny]]
> ![[SRD-luxray-ShuffleToken.png|wsmall]]


*Gleam Eyes Pokemon*
*It is said that it can see through walls. This Pokemon can easily find hiding prey and locate its young. Male Luxrays can be found roaming alone, patrolling their territory; the females hunt in groups.*

**DexID**:: 0405
**Name**:: Luxray
**Type**:: Electric
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Intimidate|Intimidate]] ([[SRD-Guts|Guts]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'6" / 1.4m
**Weight**: 92.6lbs / 42.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon       | Kind   | Speed   |
|:----------|:--------------|:-------|:--------|
| From      | [[SRD-Luxio]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Luxray.md"
flatten moves as T
where file.path = this.file.path
```
