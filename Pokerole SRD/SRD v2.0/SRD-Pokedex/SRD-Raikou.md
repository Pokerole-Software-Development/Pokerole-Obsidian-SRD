---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-raikou-BookSprite.png
BoxSprite: SRD-raikou-BoxSprite.png
DexCategory: No Data
DexDescription: Johto Legends tell about a Pokemon born from lightning, with barks
  like crashing thunder, soaring the lands, sending resounding shock-waves as it walks.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.2
  Meters: 1.9
HiddenAbility: Inner Focus
HomeSprite: SRD-raikou-HomeSprite.png
Image: raikou.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Bite|Bite]]'
- - Master
  - '[[SRD-Leer|Leer]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Roar|Roar]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Spark|Spark]]'
- - Master
  - '[[SRD-Reflect|Reflect]]'
- - Master
  - '[[SRD-Crunch|Crunch]]'
- - Master
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Extrasensory|Extrasensory]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Calm Mind|Calm Mind]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Double Team|Double Team]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Volt Switch|Volt Switch]]'
- - Master
  - '[[SRD-Flash|Flash]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
Number: 243
ShuffleToken: SRD-raikou-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 178.0
  Pounds: 392.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-raikou-BookSprite.png|wsmall]]
> ![[SRD-raikou-HomeSprite.png]]
> ![[SRD-raikou-BoxSprite.png|htiny]]
> ![[SRD-raikou-ShuffleToken.png|wsmall]]


*No Data*
*Johto Legends tell about a Pokemon born from lightning, with barks like crashing thunder, soaring the lands, sending resounding shock-waves as it walks.*

**DexID**:: 0243
**Name**:: Raikou
**Type**:: Electric
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Inner Focus|Inner Focus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 7)/(MaxDexterity::7) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 6'2" / 1.9m
**Weight**: 392.4lbs / 178.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Raikou.md"
flatten moves as T
where file.path = this.file.path
```
