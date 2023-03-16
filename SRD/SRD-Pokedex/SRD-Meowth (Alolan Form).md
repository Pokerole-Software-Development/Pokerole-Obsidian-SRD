---
Ability1: Pickup
Ability2: Technician
BookSprite: SRD-meowth-alolan-form-BookSprite.png
BoxSprite: SRD-meowth-alolan-form-BoxSprite.png
DexCategory: Scratch Cat Pokemon
DexDescription: "In old times, Meowth were taken to Alola as gifts for the tribe\u2019\
  s royals, this caused them to become incredibly greedy and pampered. Nowadays they\
  \ are feral, but their prideful nature remained."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Persian (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Rattled
HomeSprite: SRD-meowth-alolan-form-HomeSprite.png
Image: meowth-alolan-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Fake Out|Fake Out]]'
- - Beginner
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Pay Day|Pay Day]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Spite|Spite]]'
- - Pro
  - '[[SRD-Flatter|Flatter]]'
Number: 52
ShuffleToken: SRD-meowth-alolan-form-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 4.2
  Pounds: 9.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meowth-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-meowth-alolan-form-HomeSprite.png]]
> ![[SRD-meowth-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-meowth-alolan-form-ShuffleToken.png|wsmall]]


*Scratch Cat Pokemon*
*In old times, Meowth were taken to Alola as gifts for the tribe’s royals, this caused them to become incredibly greedy and pampered. Nowadays they are feral, but their prideful nature remained.*

**DexID**:: 0052A
**Name**:: Meowth (Alolan Form)
**Type**:: Dark
**Abilities**:: [[SRD-Pickup|Pickup]] / [[SRD-Technician|Technician]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 9.3lbs / 4.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon                       | Kind   | Speed   |
|:----------|:------------------------------|:-------|:--------|
| To        | [[SRD-Persian (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Meowth (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
