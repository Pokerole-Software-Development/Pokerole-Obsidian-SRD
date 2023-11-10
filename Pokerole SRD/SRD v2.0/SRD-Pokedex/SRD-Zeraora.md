---
Ability1: Volt Absorb
Ability2: ''
BookSprite: SRD-zeraora-BookSprite.png
BoxSprite: SRD-zeraora-BoxSprite.png
DexCategory: No Data
DexDescription: An unfriendly creature was spotted in Alola, witnesses mentioned it
  electrified its claws and tore its foes apart with them. It disappeared into the
  wilderness and has not been reported again.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: ''
HomeSprite: SRD-zeraora-HomeSprite.png
Image: zeraora.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Scratch|Scratch]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Hone Claws|Hone Claws]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Master
  - '[[SRD-Volt Switch|Volt Switch]]'
- - Master
  - '[[SRD-Snarl|Snarl]]'
- - Master
  - '[[SRD-Fake Out|Fake Out]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Slash|Slash]]'
- - Master
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Master
  - '[[SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[SRD-Plasma Fists|Plasma Fists]]'
- - Master
  - '[[SRD-Close Combat|Close Combat]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Master
  - '[[SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[SRD-Dual Chop|Dual Chop]]'
Number: 807
ShuffleToken: SRD-zeraora-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 44.5
  Pounds: 98.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zeraora-BookSprite.png|wsmall]]
> ![[SRD-zeraora-HomeSprite.png]]
> ![[SRD-zeraora-BoxSprite.png|htiny]]
> ![[SRD-zeraora-ShuffleToken.png|wsmall]]


*No Data*
*An unfriendly creature was spotted in Alola, witnesses mentioned it electrified its claws and tore its foes apart with them. It disappeared into the wilderness and has not been reported again.*

**DexID**:: 0807
**Name**:: Zeraora
**Type**:: Electric
**Abilities**:: [[SRD-Volt Absorb|Volt Absorb]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 98.1lbs / 44.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zeraora.md"
flatten moves as T
where file.path = this.file.path
```
