---
Ability1: Slow Start
Ability2: ''
BookSprite: SRD-regigigas-BookSprite.png
BoxSprite: SRD-regigigas-BoxSprite.png
DexCategory: No Data
DexDescription: A very old legend tells about the King of Giants, who could crush
  a mountain with its grip and mold living titans from the rubble.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 12.1
  Meters: 3.7
HiddenAbility: ''
HomeSprite: SRD-regigigas-HomeSprite.png
Image: regigigas.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - Master
  - '[[SRD-Crush Grip|Crush Grip]]'
- - Master
  - '[[SRD-Fire Punch|Fire Punch]]'
- - Master
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Master
  - '[[SRD-Thunder Punch|Thunder Punch]]'
- - Master
  - '[[SRD-Dizzy Punch|Dizzy Punch]]'
- - Master
  - '[[SRD-Knock Off|Knock Off]]'
- - Master
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Master
  - '[[SRD-Foresight|Foresight]]'
- - Master
  - '[[SRD-Revenge|Revenge]]'
- - Master
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[SRD-Payback|Payback]]'
- - Master
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Master
  - '[[SRD-Psych Up|Psych Up]]'
- - Master
  - '[[SRD-Giga Impact|Giga Impact]]'
- - Master
  - '[[SRD-Substitute|Substitute]]'
- - Master
  - '[[SRD-Strength|Strength]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Nature Power|Nature Power]]'
Number: 486
ShuffleToken: SRD-regigigas-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 420.0
  Pounds: 925.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-regigigas-BookSprite.png|wsmall]]
> ![[SRD-regigigas-HomeSprite.png]]
> ![[SRD-regigigas-BoxSprite.png|htiny]]
> ![[SRD-regigigas-ShuffleToken.png|wsmall]]


*No Data*
*A very old legend tells about the King of Giants, who could crush a mountain with its grip and mold living titans from the rubble.*

**DexID**:: 0486
**Name**:: Regigigas
**Type**:: Normal
**Abilities**:: [[SRD-Slow Start|Slow Start]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::8)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::5)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 12'1" / 3.7m
**Weight**: 925.9lbs / 420.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Regigigas.md"
flatten moves as T
where file.path = this.file.path
```
