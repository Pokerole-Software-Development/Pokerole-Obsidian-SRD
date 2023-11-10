---
Ability1: Limber
Ability2: Unburden
BookSprite: SRD-purrloin-BookSprite.png
BoxSprite: SRD-purrloin-BoxSprite.png
DexCategory: Devious Pokemon
DexDescription: "They have adapted to live in the streets of big cities. They steal\
  \ for fun but their victims can\u2019t help but forgive them. Their cute act is\
  \ a ruse. People who keep them as pets often regret it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Liepard]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: Prankster
HomeSprite: SRD-purrloin-HomeSprite.png
Image: purrloin.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Assist|Assist]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Trick|Trick]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Pay Day|Pay Day]]'
Number: 509
ShuffleToken: SRD-purrloin-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 10.1
  Pounds: 22.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-purrloin-BookSprite.png|wsmall]]
> ![[SRD-purrloin-HomeSprite.png]]
> ![[SRD-purrloin-BoxSprite.png|htiny]]
> ![[SRD-purrloin-ShuffleToken.png|wsmall]]


*Devious Pokemon*
*They have adapted to live in the streets of big cities. They steal for fun but their victims can’t help but forgive them. Their cute act is a ruse. People who keep them as pets often regret it.*

**DexID**:: 0509
**Name**:: Purrloin
**Type**:: Dark
**Abilities**:: [[SRD-Limber|Limber]] / [[SRD-Unburden|Unburden]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'3" / 0.4m
**Weight**: 22.3lbs / 10.1kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Liepard]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Purrloin.md"
flatten moves as T
where file.path = this.file.path
```
