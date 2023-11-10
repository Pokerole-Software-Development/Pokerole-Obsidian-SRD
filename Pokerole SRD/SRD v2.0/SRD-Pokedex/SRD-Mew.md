---
Ability1: Synchronize
Ability2: ''
BookSprite: SRD-mew-BookSprite.png
BoxSprite: SRD-mew-BoxSprite.png
DexCategory: No Data
DexDescription: Recent investigations declare that this Pokemon could be the common
  ancestor of all actual Pokemon, but it has been extinct for centuries. Some people
  claim to have seen one to get their 15 minutes of fame.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-mew-HomeSprite.png
Image: mew.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Pound|Pound]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Transform|Transform]]'
- - Master
  - '[[SRD-Mega Punch|Mega Punch]]'
- - Master
  - '[[SRD-Metronome|Metronome]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Barrier|Barrier]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Amnesia|Amnesia]]'
- - Master
  - '[[SRD-Me First|Me First]]'
- - Master
  - '[[SRD-Baton Pass|Baton Pass]]'
- - Master
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Master
  - '[[SRD-Aura Sphere|Aura Sphere]]'
- - Master
  - '[[SRD-Any Move|Any Move]]'
Number: 151
ShuffleToken: SRD-mew-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mew-BookSprite.png|wsmall]]
> ![[SRD-mew-HomeSprite.png]]
> ![[SRD-mew-BoxSprite.png|htiny]]
> ![[SRD-mew-ShuffleToken.png|wsmall]]


*No Data*
*Recent investigations declare that this Pokemon could be the common ancestor of all actual Pokemon, but it has been extinct for centuries. Some people claim to have seen one to get their 15 minutes of fame.*

**DexID**:: 0151
**Name**:: Mew
**Type**:: Psychic
**Abilities**:: [[SRD-Synchronize|Synchronize]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 1'3" / 0.4m
**Weight**: 8.8lbs / 4.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mew.md"
flatten moves as T
where file.path = this.file.path
```
