---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-zapdos-BookSprite.png
BoxSprite: SRD-zapdos-BoxSprite.png
DexCategory: No Data
DexDescription: The myth tells of a bird who lived inside the thunderstorms of the
  region. It covered itself in lightning while flying in the dark clouds. A news report
  said it was involved in the closure of an energy plant.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.2
  Meters: 1.6
HiddenAbility: Static
HomeSprite: SRD-zapdos-HomeSprite.png
Image: zapdos.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Peck|Peck]]'
- - Master
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Master
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Pluck|Pluck]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Charge|Charge]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Discharge|Discharge]]'
- - Master
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Master
  - '[[SRD-Light Screen|Light Screen]]'
- - Master
  - '[[SRD-Drill Peck|Drill Peck]]'
- - Master
  - '[[SRD-Thunder|Thunder]]'
- - Master
  - '[[SRD-Roost|Roost]]'
- - Master
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Twister|Twister]]'
- - Master
  - '[[SRD-Laser Focus|Laser Focus]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Number: 145
ShuffleToken: SRD-zapdos-ShuffleToken.png
Type1: Electric
Type2: Flying
Weight:
  Kilograms: 52.6
  Pounds: 116.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-zapdos-BookSprite.png|wsmall]]
> ![[SRD-zapdos-HomeSprite.png]]
> ![[SRD-zapdos-BoxSprite.png|htiny]]
> ![[SRD-zapdos-ShuffleToken.png|wsmall]]


*No Data*
*The myth tells of a bird who lived inside the thunderstorms of the region. It covered itself in lightning while flying in the dark clouds. A news report said it was involved in the closure of an energy plant.*

**DexID**:: 0145
**Name**:: Zapdos
**Type**:: Electric / Flying
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Static|Static]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::5)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 5'2" / 1.6m
**Weight**: 116.0lbs / 52.6kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Zapdos.md"
flatten moves as T
where file.path = this.file.path
```
