---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-weavile-BookSprite.png
BoxSprite: SRD-weavile-BoxSprite.png
DexCategory: Sharp Claw Pokemon
DexDescription: They live in cold regions, forming groups of four that hunt prey with
  impressive coordination. They leave claw marks and patterns to indicate their territory.
  It is devious and loves to cause trouble.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Razor Claw
  Kind: Level
  Pokemon: '[[SRD-Sneasel]]'
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Pickpocket
HomeSprite: SRD-weavile-HomeSprite.png
Image: weavile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Taunt|Taunt]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Beginner
  - '[[SRD-Embargo|Embargo]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Revenge|Revenge]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Amateur
  - '[[SRD-Metal Claw|Metal Claw]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Night Slash|Night Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Snatch|Snatch]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icicle Crash|Icicle Crash]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Low Kick|Low Kick]]'
Number: 461
ShuffleToken: SRD-weavile-ShuffleToken.png
Type1: Dark
Type2: Ice
Weight:
  Kilograms: 34.0
  Pounds: 75.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-weavile-BookSprite.png|wsmall]]
> ![[SRD-weavile-HomeSprite.png]]
> ![[SRD-weavile-BoxSprite.png|htiny]]
> ![[SRD-weavile-ShuffleToken.png|wsmall]]


*Sharp Claw Pokemon*
*They live in cold regions, forming groups of four that hunt prey with impressive coordination. They leave claw marks and patterns to indicate their territory. It is devious and loves to cause trouble.*

**DexID**:: 0461
**Name**:: Weavile
**Type**:: Dark / Ice
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Pickpocket|Pickpocket]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'6" / 1.1m
**Weight**: 75.0lbs / 34.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item       |
|:----------|:----------------|:-------|:-----------|
| From      | [[SRD-Sneasel]] | Level  | Razor Claw |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Weavile.md"
flatten moves as T
where file.path = this.file.path
```
