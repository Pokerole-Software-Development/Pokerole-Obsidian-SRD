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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Scratch|Scratch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Spark|Spark]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hone Claws|Hone Claws]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fury Swipes|Fury Swipes]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Volt Switch|Volt Switch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snarl|Snarl]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Out|Fake Out]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Charge|Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Slash|Slash]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wild Charge|Wild Charge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Guard|Quick Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Plasma Fists|Plasma Fists]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Close Combat|Close Combat]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fire Punch|Fire Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Drain Punch|Drain Punch]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Dual Chop|Dual Chop]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zeraora.md"
flatten moves as T
where file.path = this.file.path
```
