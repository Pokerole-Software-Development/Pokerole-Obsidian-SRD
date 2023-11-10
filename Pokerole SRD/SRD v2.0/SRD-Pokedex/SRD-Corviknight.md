---
Ability1: Pressure
Ability2: Unnerve
BookSprite: SRD-corviknight-BookSprite.png
BoxSprite: SRD-corviknight-BoxSprite.png
DexCategory: Raven Pokemon
DexDescription: With their great intellect and flying skills, these Pokemon very successfully
  take the place as the kings of the Galarian sky. When they fly, they cast giant
  shadows that strike fear upon foes and friends alike.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Corvisquire]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 7.2
  Meters: 2.2
HiddenAbility: Mirror Armor
HomeSprite: SRD-corviknight-HomeSprite.png
Image: corviknight.png
Legendary: 'No'
Moves:
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Steel Wing|Steel Wing]]'
- - Amateur
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Power Trip|Power Trip]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Taunt|Taunt]]'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Swagger|Swagger]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Pro
  - '[[SRD-Steel Beam|Steel Beam]]'
Number: 823
ShuffleToken: SRD-corviknight-ShuffleToken.png
Type1: Flying
Type2: Steel
Weight:
  Kilograms: 75.0
  Pounds: 165.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-corviknight-BookSprite.png|wsmall]]
> ![[SRD-corviknight-HomeSprite.png]]
> ![[SRD-corviknight-BoxSprite.png|htiny]]
> ![[SRD-corviknight-ShuffleToken.png|wsmall]]


*Raven Pokemon*
*With their great intellect and flying skills, these Pokemon very successfully take the place as the kings of the Galarian sky. When they fly, they cast giant shadows that strike fear upon foes and friends alike.*

**DexID**:: 0823
**Name**:: Corviknight
**Type**:: Flying / Steel
**Abilities**:: [[SRD-Pressure|Pressure]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Mirror Armor|Mirror Armor]])
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 7'2" / 2.2m
**Weight**: 165.3lbs / 75.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| From      | [[SRD-Corvisquire]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Corviknight.md"
flatten moves as T
where file.path = this.file.path
```
