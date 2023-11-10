---
Ability1: Multitype
Ability2: ''
BookSprite: SRD-arceus-BookSprite.png
BoxSprite: SRD-arceus-BoxSprite.png
DexCategory: Plot Device
DexDescription: Plot Device
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 10.5
  Meters: 3.2
HiddenAbility: ''
HomeSprite: SRD-arceus-HomeSprite.png
Image: arceus.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Master
  - '[[SRD-Cosmic Power|Cosmic Power]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Punishment|Punishment]]'
- - Master
  - '[[SRD-Gravity|Gravity]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Master
  - '[[SRD-Extreme Speed|Extreme Speed]]'
- - Master
  - '[[SRD-Refresh|Refresh]]'
- - Master
  - '[[SRD-Future Sight|Future Sight]]'
- - Master
  - '[[SRD-Recover|Recover]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Perish Song|Perish Song]]'
- - Master
  - '[[SRD-Judgment|Judgment]]'
- - Master
  - '[[SRD-Sunsteel Strike|Sunsteel Strike]]'
- - Master
  - '[[SRD-Infestation|Infestation]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Master
  - '[[SRD-Light Of Ruin|Light Of Ruin]]'
- - Master
  - '[[SRD-Inferno|Inferno]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Phantom Force|Phantom Force]]'
- - Master
  - '[[SRD-Frenzy Plant|Frenzy Plant]]'
- - Master
  - '[[SRD-Detect|Detect]]'
- - Master
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - Master
  - '[[SRD-Sludge Wave|Sludge Wave]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Origin Pulse|Origin Pulse]]'
Number: 493
ShuffleToken: SRD-arceus-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 320.0
  Pounds: 705.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-arceus-BookSprite.png|wsmall]]
> ![[SRD-arceus-HomeSprite.png]]
> ![[SRD-arceus-BoxSprite.png|htiny]]
> ![[SRD-arceus-ShuffleToken.png|wsmall]]


*Plot Device*
*Plot Device*

**DexID**:: 0493
**Name**:: Arceus
**Type**:: Normal
**Abilities**:: [[SRD-Multitype|Multitype]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::12)/(MaxStrength::12)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 12)/(MaxDexterity::12) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::12)/(MaxVitality::12)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::12)/(MaxSpecial::12)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::12)/(MaxInsight::12)     |

**Height**: 10'5" / 3.2m
**Weight**: 705.5lbs / 320.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Arceus.md"
flatten moves as T
where file.path = this.file.path
```
