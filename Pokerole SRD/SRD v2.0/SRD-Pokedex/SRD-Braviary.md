---
Ability1: Keen Eye
Ability2: Sheer Force
BookSprite: SRD-braviary-BookSprite.png
BoxSprite: SRD-braviary-BoxSprite.png
DexCategory: Valiant Pokemon
DexDescription: Brave, strong, loyal, and selfless; this Pokemon embodies the virtues
  of what a Pokemon companion should be. They are very rare and valued not only for
  their bravery but for their beautiful feathers.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Rufflet]]'
  Speed: Slow
GenderType: M
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Defiant
HomeSprite: SRD-braviary-HomeSprite.png
Image: braviary.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Beginner
  - '[[SRD-Wing Attack|Wing Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Aerial Ace|Aerial Ace]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Defog|Defog]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Crush Claw|Crush Claw]]'
- - Amateur
  - '[[SRD-Sky Drop|Sky Drop]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Superpower|Superpower]]'
- - Ace
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Ace
  - '[[SRD-Brave Bird|Brave Bird]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Pro
  - '[[SRD-Hurricane|Hurricane]]'
Number: 628
ShuffleToken: SRD-braviary-ShuffleToken.png
Type1: Normal
Type2: Flying
Weight:
  Kilograms: 41.0
  Pounds: 90.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-braviary-BookSprite.png|wsmall]]
> ![[SRD-braviary-HomeSprite.png]]
> ![[SRD-braviary-BoxSprite.png|htiny]]
> ![[SRD-braviary-ShuffleToken.png|wsmall]]


*Valiant Pokemon*
*Brave, strong, loyal, and selfless; this Pokemon embodies the virtues of what a Pokemon companion should be. They are very rare and valued not only for their bravery but for their beautiful feathers.*

**DexID**:: 0628
**Name**:: Braviary
**Type**:: Normal / Flying
**Abilities**:: [[SRD-Keen Eye|Keen Eye]] / [[SRD-Sheer Force|Sheer Force]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 90.4lbs / 41.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Rufflet]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Braviary.md"
flatten moves as T
where file.path = this.file.path
```
