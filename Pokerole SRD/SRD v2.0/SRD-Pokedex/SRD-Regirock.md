---
Ability1: Clear Body
Ability2: ''
BookSprite: SRD-regirock-BookSprite.png
BoxSprite: SRD-regirock-BoxSprite.png
DexCategory: No Data
DexDescription: It is said to be an immortal being the size of the peak of a mountain.
  Could he be a remnant from the most ancient times of this world?
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 5.6
  Meters: 1.7
HiddenAbility: Sturdy
HomeSprite: SRD-regirock-HomeSprite.png
Image: regirock.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Stomp|Stomp]]'
- - Master
  - '[[SRD-Rock Throw|Rock Throw]]'
- - Master
  - '[[SRD-Charge Beam|Charge Beam]]'
- - Master
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Master
  - '[[SRD-Hammer Arm|Hammer Arm]]'
- - Master
  - '[[SRD-Lock-On|Lock-On]]'
- - Master
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Master
  - '[[SRD-Superpower|Superpower]]'
- - Master
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - Master
  - '[[SRD-Explosion|Explosion]]'
- - Master
  - '[[SRD-Mimic|Mimic]]'
- - Master
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[SRD-Rock Smash|Rock Smash]]'
- - Master
  - '[[SRD-Rock Polish|Rock Polish]]'
Number: 377
ShuffleToken: SRD-regirock-ShuffleToken.png
Type1: Rock
Type2: ''
Weight:
  Kilograms: 230.0
  Pounds: 507.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-regirock-BookSprite.png|wsmall]]
> ![[SRD-regirock-HomeSprite.png]]
> ![[SRD-regirock-BoxSprite.png|htiny]]
> ![[SRD-regirock-ShuffleToken.png|wsmall]]


*No Data*
*It is said to be an immortal being the size of the peak of a mountain. Could he be a remnant from the most ancient times of this world?*

**DexID**:: 0377
**Name**:: Regirock
**Type**:: Rock
**Abilities**:: [[SRD-Clear Body|Clear Body]] ([[SRD-Sturdy|Sturdy]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 4)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::10)/(MaxVitality::10)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 5'6" / 1.7m
**Weight**: 507.1lbs / 230.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Regirock.md"
flatten moves as T
where file.path = this.file.path
```
