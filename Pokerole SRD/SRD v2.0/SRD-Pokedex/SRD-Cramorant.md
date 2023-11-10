---
Ability1: Gulp Missile
Ability2: ''
BookSprite: SRD-cramorant-BookSprite.png
BoxSprite: SRD-cramorant-BoxSprite.png
DexCategory: Gulp Pokemon
DexDescription: Cramorant hunt for fish Pokemon to eat near seashores and lakes. They
  often try to engulf prey that is too large and it ends up blocking their gullets.
  They are airheaded and often forget what they were doing.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: ''
HomeSprite: SRD-cramorant-HomeSprite.png
Image: cramorant.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Belch|Belch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Peck|Peck]]'
- - Beginner
  - '[[SRD-Stockpile|Stockpile]]'
- - Beginner
  - '[[SRD-Swallow|Swallow]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Spit Up|Spit Up]]'
- - Amateur
  - '[[SRD-Water Gun|Water Gun]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Pluck|Pluck]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Dive|Dive]]'
- - Ace
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Ace
  - '[[SRD-Amnesia|Amnesia]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Roost|Roost]]'
- - Pro
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Pro
  - '[[SRD-Feather Dance|Feather Dance]]'
Number: 845
ShuffleToken: SRD-cramorant-ShuffleToken.png
Type1: Flying
Type2: Water
Weight:
  Kilograms: 18.0
  Pounds: 39.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cramorant-BookSprite.png|wsmall]]
> ![[SRD-cramorant-HomeSprite.png]]
> ![[SRD-cramorant-BoxSprite.png|htiny]]
> ![[SRD-cramorant-ShuffleToken.png|wsmall]]


*Gulp Pokemon*
*Cramorant hunt for fish Pokemon to eat near seashores and lakes. They often try to engulf prey that is too large and it ends up blocking their gullets. They are airheaded and often forget what they were doing.*

**DexID**:: 0845
**Name**:: Cramorant
**Type**:: Flying / Water
**Abilities**:: [[SRD-Gulp Missile|Gulp Missile]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'6" / 0.8m
**Weight**: 39.7lbs / 18.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cramorant.md"
flatten moves as T
where file.path = this.file.path
```
