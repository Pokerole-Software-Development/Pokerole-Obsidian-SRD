---
Ability1: Keen Eye
Ability2: Unnerve
BookSprite: SRD-corvisquire-BookSprite.png
BoxSprite: SRD-corvisquire-BoxSprite.png
DexCategory: Raven Pokemon
DexDescription: They are smart enough to use tools in battle, these Pokemon have been
  seen picking up rocks and flinging them or using ropes to wrap up foes. They choose
  their battles carefully and do not retreat.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rookidee]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Corviknight]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Big Pecks
HomeSprite: SRD-corvisquire-HomeSprite.png
Image: corvisquire.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Peck|Peck]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leer|Leer]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Power Trip|Power Trip]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hone Claws|Hone Claws]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pluck|Pluck]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Taunt|Taunt]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swagger|Swagger]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Brave Bird|Brave Bird]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Roost|Roost]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tailwind|Tailwind]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Smash|Rock Smash]]'
Number: 822
ShuffleToken: SRD-corvisquire-ShuffleToken.png
Type1: Flying
Type2: ''
Weight:
  Kilograms: 16.0
  Pounds: 35.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-corvisquire-BookSprite.png|wsmall]]
> ![[SRD-corvisquire-HomeSprite.png]]
> ![[SRD-corvisquire-BoxSprite.png|htiny]]
> ![[SRD-corvisquire-ShuffleToken.png|wsmall]]


*Raven Pokemon*
*They are smart enough to use tools in battle, these Pokemon have been seen picking up rocks and flinging them or using ropes to wrap up foes. They choose their battles carefully and do not retreat.*

**DexID**:: 0822
**Name**:: Corvisquire
**Type**:: Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Unnerve|Unnerve]] ([[SRD-Big Pecks|Big Pecks]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'6" / 0.8m
**Weight**: 35.3lbs / 16.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon             | Kind   | Speed   |
|:----------|:--------------------|:-------|:--------|
| From      | [[SRD-Rookidee]]    | Level  | Medium  |
| To        | [[SRD-Corviknight]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Corvisquire.md"
flatten moves as T
where file.path = this.file.path
```
