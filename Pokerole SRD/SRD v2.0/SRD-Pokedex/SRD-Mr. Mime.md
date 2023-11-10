---
Ability1: Soundproof
Ability2: Filter
BookSprite: SRD-mr-mime-BookSprite.png
BoxSprite: SRD-mr-mime-BoxSprite.png
DexCategory: Barrier Pokemon
DexDescription: "You don\u2019t find this Pokemon, it finds you. It is really smart\
  \ and amuses itself by showing people its power to create barriers with pantomime.\
  \ It creates an invisible box and flees when you try to figure out the exit."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Move: Mimic
  Pokemon: '[[SRD-Mime Jr]]'
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Technician
HomeSprite: SRD-mr-mime-HomeSprite.png
Image: mr-mime.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Barrier|Barrier]]'
- - Starter
  - '[[SRD-Confusion|Confusion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Beginner
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Beginner
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Beginner
  - '[[SRD-Trick|Trick]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power Swap|Power Swap]]'
- - Amateur
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Amateur
  - '[[SRD-Copycat|Copycat]]'
- - Amateur
  - '[[SRD-Meditate|Meditate]]'
- - Amateur
  - '[[SRD-Double Slap|Double Slap]]'
- - Amateur
  - '[[SRD-Mimic|Mimic]]'
- - Amateur
  - '[[SRD-Psywave|Psywave]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - Amateur
  - '[[SRD-Substitute|Substitute]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recycle|Recycle]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Role Play|Role Play]]'
- - Ace
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Ace
  - '[[SRD-Safeguard|Safeguard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Pro
  - '[[SRD-Fake Out|Fake Out]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
Number: 122
ShuffleToken: SRD-mr-mime-ShuffleToken.png
Type1: Psychic
Type2: Fairy
Weight:
  Kilograms: 54.5
  Pounds: 120.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mr-mime-BookSprite.png|wsmall]]
> ![[SRD-mr-mime-HomeSprite.png]]
> ![[SRD-mr-mime-BoxSprite.png|htiny]]
> ![[SRD-mr-mime-ShuffleToken.png|wsmall]]


*Barrier Pokemon*
*You don’t find this Pokemon, it finds you. It is really smart and amuses itself by showing people its power to create barriers with pantomime. It creates an invisible box and flees when you try to figure out the exit.*

**DexID**:: 0122
**Name**:: Mr. Mime
**Type**:: Psychic / Fairy
**Abilities**:: [[SRD-Soundproof|Soundproof]] / [[SRD-Filter|Filter]] ([[SRD-Technician|Technician]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 4'3" / 1.3m
**Weight**: 120.2lbs / 54.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Move   |
|:----------|:----------------|:-------|:-------|
| From      | [[SRD-Mime Jr]] | Level  | Mimic  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mr. Mime.md"
flatten moves as T
where file.path = this.file.path
```
