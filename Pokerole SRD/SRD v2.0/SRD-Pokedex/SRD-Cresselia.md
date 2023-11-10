---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-cresselia-BookSprite.png
BoxSprite: SRD-cresselia-BoxSprite.png
DexCategory: No Data
DexDescription: The embodiment of dreams comes to life during the crescent moon nights.
  You will be blessed with peaceful bedtimes If you keep one of its feathers. Or so
  they say.
EventAbilities: ''
Evolutions: []
GenderType: F
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-cresselia-HomeSprite.png
Image: cresselia.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Lunar Dance|Lunar Dance]]'
- - Master
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Master
  - '[[SRD-Psycho Cut|Psycho Cut]]'
- - Master
  - '[[SRD-Moonlight|Moonlight]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Mist|Mist]]'
- - Master
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Psychic|Psychic]]'
- - Master
  - '[[SRD-Moonblast|Moonblast]]'
- - Master
  - '[[SRD-Rest|Rest]]'
- - Master
  - '[[SRD-Captivate|Captivate]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Protect|Protect]]'
- - Master
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
Number: 488
ShuffleToken: SRD-cresselia-ShuffleToken.png
Type1: Psychic
Type2: ''
Weight:
  Kilograms: 85.6
  Pounds: 188.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cresselia-BookSprite.png|wsmall]]
> ![[SRD-cresselia-HomeSprite.png]]
> ![[SRD-cresselia-BoxSprite.png|htiny]]
> ![[SRD-cresselia-ShuffleToken.png|wsmall]]


*No Data*
*The embodiment of dreams comes to life during the crescent moon nights. You will be blessed with peaceful bedtimes If you keep one of its feathers. Or so they say.*

**DexID**:: 0488
**Name**:: Cresselia
**Type**:: Psychic
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::7)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::7)/(MaxInsight::7)     |

**Height**: 4'9" / 1.5m
**Weight**: 188.7lbs / 85.6kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cresselia.md"
flatten moves as T
where file.path = this.file.path
```
