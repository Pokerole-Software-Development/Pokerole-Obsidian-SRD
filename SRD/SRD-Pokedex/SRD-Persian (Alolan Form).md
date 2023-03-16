---
Ability1: Fur Coat
Ability2: Technician
BookSprite: SRD-persian-alolan-form-BookSprite.png
BoxSprite: SRD-persian-alolan-form-BoxSprite.png
DexCategory: Classy Cat Pokemon
DexDescription: "They were bred for their silky fur and round faces, not for their\
  \ temperament. This is an extremely proud Pokemon who will look down to anyone but\
  \ itself, despite this, it\u2019s very popular among Alola\u2019s elite."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Meowth (Alolan Form)]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Rattled
HomeSprite: SRD-persian-alolan-form-HomeSprite.png
Image: persian-alolan-form.png
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
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Dark Pulse|Dark Pulse]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - Ace
  - '[[SRD-Quash|Quash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Parting Shot|Parting Shot]]'
- - Pro
  - '[[SRD-Snarl|Snarl]]'
- - Pro
  - '[[SRD-Torment|Torment]]'
Number: 53
ShuffleToken: SRD-persian-alolan-form-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 33.0
  Pounds: 72.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-persian-alolan-form-BookSprite.png|wsmall]]
> ![[SRD-persian-alolan-form-HomeSprite.png]]
> ![[SRD-persian-alolan-form-BoxSprite.png|htiny]]
> ![[SRD-persian-alolan-form-ShuffleToken.png|wsmall]]


*Classy Cat Pokemon*
*They were bred for their silky fur and round faces, not for their temperament. This is an extremely proud Pokemon who will look down to anyone but itself, despite this, it’s very popular among Alola’s elite.*

**DexID**:: 0053A
**Name**:: Persian (Alolan Form)
**Type**:: Dark
**Abilities**:: [[SRD-Fur Coat|Fur Coat]] / [[SRD-Technician|Technician]] ([[SRD-Rattled|Rattled]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 72.8lbs / 33.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                      | Kind   | Speed   |
|:----------|:-----------------------------|:-------|:--------|
| From      | [[SRD-Meowth (Alolan Form)]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Persian (Alolan Form).md"
flatten moves as T
where file.path = this.file.path
```
