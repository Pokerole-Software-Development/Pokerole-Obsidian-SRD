---
Ability1: Limber
Ability2: Unburden
BookSprite: SRD-liepard-BookSprite.png
BoxSprite: SRD-liepard-BoxSprite.png
DexCategory: Cruel Pokemon
DexDescription: "It\u2019s difficult to see one in the wild. These Pokemon vanish\
  \ and appear attacking unexpectedly. Many Trainers are drawn to their beautiful\
  \ fur and elegant appeal. But they can be quite dangerous."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Purrloin]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Prankster
HomeSprite: SRD-liepard-HomeSprite.png
Image: liepard.png
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
  - '[[SRD-Taunt|Taunt]]'
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
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 510
ShuffleToken: SRD-liepard-ShuffleToken.png
Type1: Dark
Type2: ''
Weight:
  Kilograms: 37.5
  Pounds: 82.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-liepard-BookSprite.png|wsmall]]
> ![[SRD-liepard-HomeSprite.png]]
> ![[SRD-liepard-BoxSprite.png|htiny]]
> ![[SRD-liepard-ShuffleToken.png|wsmall]]


*Cruel Pokemon*
*It’s difficult to see one in the wild. These Pokemon vanish and appear attacking unexpectedly. Many Trainers are drawn to their beautiful fur and elegant appeal. But they can be quite dangerous.*

**DexID**:: 0510
**Name**:: Liepard
**Type**:: Dark
**Abilities**:: [[SRD-Limber|Limber]] / [[SRD-Unburden|Unburden]] ([[SRD-Prankster|Prankster]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 82.7lbs / 37.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Purrloin]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Liepard.md"
flatten moves as T
where file.path = this.file.path
```
