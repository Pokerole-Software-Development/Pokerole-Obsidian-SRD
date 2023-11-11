---
Ability1: ''
Ability2: ''
BookImageName: ''
BookShinyImageName: ''
BookSprite: SRD-egg-BookSprite.png
BoxSprite: SRD-egg-BoxSprite.png
DexCategory: ''
DexDescription: ''
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 0.0
  Meters: 0
HiddenAbility: ''
HomeSprite: SRD-egg-HomeSprite.png
Image: egg.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rest|Rest]]'
Number: 0
ShuffleToken: SRD-egg-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 0
  Pounds: 0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-egg-BookSprite.png|wsmall]]
> ![[SRD-egg-HomeSprite.png]]
> ![[SRD-egg-BoxSprite.png|htiny]]
> ![[SRD-egg-ShuffleToken.png|wsmall]]


**
**

**DexID**:: 0000
**Name**:: Egg
**Type**:: Normal
**Abilities**:: [[SRD-|]]
**Base HP**:: 1

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::1)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::1) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::1)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::1)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::1)     |

**Height**: 0'0" / 0m
**Weight**: 0lbs / 0kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Egg.md"
flatten moves as T
where file.path = this.file.path
```
