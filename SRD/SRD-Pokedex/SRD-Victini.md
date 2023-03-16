---
Ability1: Victory Star
Ability2: ''
BookSprite: SRD-victini-BookSprite.png
BoxSprite: SRD-victini-BoxSprite.png
DexCategory: No Data
DexDescription: "On tournament days, Trainers eat a \u201CV\u201D shaped apple as\
  \ a sign of good luck. It is unknown if it has anything to do with this Pokemon."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-victini-HomeSprite.png
Image: victini.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Searing Shot|Searing Shot]]'
- - Master
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Master
  - '[[SRD-Confusion|Confusion]]'
- - Master
  - '[[SRD-Incinerate|Incinerate]]'
- - Master
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Headbutt|Headbutt]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Reversal|Reversal]]'
- - Master
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Inferno|Inferno]]'
- - Master
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - Master
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Master
  - '[[SRD-Stored Power|Stored Power]]'
- - Master
  - '[[SRD-Overheat|Overheat]]'
- - Master
  - '[[SRD-Trick|Trick]]'
- - Master
  - '[[SRD-Shock Wave|Shock Wave]]'
- - Master
  - '[[SRD-V-Create|V-Create]]'
Number: 494
ShuffleToken: SRD-victini-ShuffleToken.png
Type1: Psychic
Type2: Fire
Weight:
  Kilograms: 4.0
  Pounds: 8.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-victini-BookSprite.png|wsmall]]
> ![[SRD-victini-HomeSprite.png]]
> ![[SRD-victini-BoxSprite.png|htiny]]
> ![[SRD-victini-ShuffleToken.png|wsmall]]


*No Data*
*On tournament days, Trainers eat a “V” shaped apple as a sign of good luck. It is unknown if it has anything to do with this Pokemon.*

**DexID**:: 0494
**Name**:: Victini
**Type**:: Psychic / Fire
**Abilities**:: [[SRD-Victory Star|Victory Star]]
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
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Victini.md"
flatten moves as T
where file.path = this.file.path
```
