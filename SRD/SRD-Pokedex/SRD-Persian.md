---
Ability1: Limber
Ability2: Technician
BookSprite: SRD-persian-BookSprite.png
BoxSprite: SRD-persian-BoxSprite.png
DexCategory: Classy Cat Pokemon
DexDescription: They are proud and temperamental. They scratch their trainers with
  little to no provocation whatsoever. Their elegance and grace is very valued, although
  they can be vicious hunters.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Meowth]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Unnerve
HomeSprite: SRD-persian-HomeSprite.png
Image: persian.png
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
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Play Rough|Play Rough]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Swift|Swift]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Switcheroo|Switcheroo]]'
- - Ace
  - '[[SRD-Assurance|Assurance]]'
- - Ace
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Feint|Feint]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hypnosis|Hypnosis]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Assist|Assist]]'
Number: 53
ShuffleToken: SRD-persian-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 32.0
  Pounds: 70.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-persian-BookSprite.png|wsmall]]
> ![[SRD-persian-HomeSprite.png]]
> ![[SRD-persian-BoxSprite.png|htiny]]
> ![[SRD-persian-ShuffleToken.png|wsmall]]


*Classy Cat Pokemon*
*They are proud and temperamental. They scratch their trainers with little to no provocation whatsoever. Their elegance and grace is very valued, although they can be vicious hunters.*

**DexID**:: 0053
**Name**:: Persian
**Type**:: Normal
**Abilities**:: [[SRD-Limber|Limber]] / [[SRD-Technician|Technician]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 70.5lbs / 32.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Meowth]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Persian.md"
flatten moves as T
where file.path = this.file.path
```
