---
Ability1: Levitate
Ability2: ''
BookSprite: SRD-cryogonal-BookSprite.png
BoxSprite: SRD-cryogonal-BoxSprite.png
DexCategory: Crystallizing Pokemon
DexDescription: They are born in snow clouds. Using chains made of ice crystals they
  capture prey. If their body temperature goes up, they turns into steam and vanish
  until it freezes and becomes ice again.
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: ''
HomeSprite: SRD-cryogonal-HomeSprite.png
Image: cryogonal.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Starter
  - '[[SRD-Mist|Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - Beginner
  - '[[SRD-Bind|Bind]]'
- - Beginner
  - '[[SRD-Sharpen|Sharpen]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Amateur
  - '[[SRD-Aurora Beam|Aurora Beam]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Ice Beam|Ice Beam]]'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
- - Amateur
  - '[[SRD-Reflect|Reflect]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-Freeze Dry|Freeze Dry]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Night Slash|Night Slash]]'
- - Ace
  - '[[SRD-Sheer Cold|Sheer Cold]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Knock Off|Knock Off]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 615
ShuffleToken: SRD-cryogonal-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 148.0
  Pounds: 326.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cryogonal-BookSprite.png|wsmall]]
> ![[SRD-cryogonal-HomeSprite.png]]
> ![[SRD-cryogonal-BoxSprite.png|htiny]]
> ![[SRD-cryogonal-ShuffleToken.png|wsmall]]


*Crystallizing Pokemon*
*They are born in snow clouds. Using chains made of ice crystals they capture prey. If their body temperature goes up, they turns into steam and vanish until it freezes and becomes ice again.*

**DexID**:: 0615
**Name**:: Cryogonal
**Type**:: Ice
**Abilities**:: [[SRD-Levitate|Levitate]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 3'6" / 1.1m
**Weight**: 326.3lbs / 148.0kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Cryogonal.md"
flatten moves as T
where file.path = this.file.path
```
