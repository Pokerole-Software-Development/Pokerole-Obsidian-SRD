---
Ability1: Beast Boost
Ability2: ''
BookSprite: SRD-stakataka-BookSprite.png
BoxSprite: SRD-stakataka-BoxSprite.png
DexCategory: 'Aether Foundation Log #132'
DexDescription: We are finally on the other side. It has been so exciting. What we
  thought were the ruins of an abandoned civilization turned out to be small sentient
  creatures that stacked on each other to create a big UB.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 18.0
  Meters: 5.5
HiddenAbility: ''
HomeSprite: SRD-stakataka-HomeSprite.png
Image: stakataka.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Protect|Protect]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Slide|Rock Slide]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Stealth Rock|Stealth Rock]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bide|Bide]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Throw|Rock Throw]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Autotomize|Autotomize]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Defense|Iron Defense]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Iron Head|Iron Head]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rock Blast|Rock Blast]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wide Guard|Wide Guard]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magnet Rise|Magnet Rise]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zen Headbutt|Zen Headbutt]]'
- - Master
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick Room|Trick Room]]'
Number: 805
ShuffleToken: SRD-stakataka-ShuffleToken.png
Type1: Rock
Type2: Steel
Weight:
  Kilograms: 820.0
  Pounds: 1807.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-stakataka-BookSprite.png|wsmall]]
> ![[SRD-stakataka-HomeSprite.png]]
> ![[SRD-stakataka-BoxSprite.png|htiny]]
> ![[SRD-stakataka-ShuffleToken.png|wsmall]]


*Aether Foundation Log #132*
*We are finally on the other side. It has been so exciting. What we thought were the ruins of an abandoned civilization turned out to be small sentient creatures that stacked on each other to create a big UB.*

**DexID**:: 0805
**Name**:: Stakataka
**Type**:: Rock / Steel
**Abilities**:: [[SRD-Beast Boost|Beast Boost]]
**Base HP**:: 6

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::7)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::2) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::10)/(MaxVitality::10)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::4)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 18'0" / 5.5m
**Weight**: 1807.8lbs / 820.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Stakataka.md"
flatten moves as T
where file.path = this.file.path
```
