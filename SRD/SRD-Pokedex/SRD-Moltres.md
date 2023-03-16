---
Ability1: Pressure
Ability2: ''
BookSprite: SRD-moltres-BookSprite.png
BoxSprite: SRD-moltres-BoxSprite.png
DexCategory: No Data
DexDescription: "The legend speaks of a bird who came flying from the south. Its fiery\
  \ body melted the snow and brought the spring along. A children\u2018s book depicts\
  \ a similar Pokemon living inside of a volcano."
EventAbilities: ''
Evolutions: []
GenderType: N
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Flame Body
HomeSprite: SRD-moltres-HomeSprite.png
Image: moltres.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Wing Attack|Wing Attack]]'
- - Master
  - '[[SRD-Ember|Ember]]'
- - Master
  - '[[SRD-Fire Spin|Fire Spin]]'
- - Master
  - '[[SRD-Agility|Agility]]'
- - Master
  - '[[SRD-Endure|Endure]]'
- - Master
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Master
  - '[[SRD-Flamethrower|Flamethrower]]'
- - Master
  - '[[SRD-Safeguard|Safeguard]]'
- - Master
  - '[[SRD-Air Slash|Air Slash]]'
- - Master
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Master
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Master
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Master
  - '[[SRD-Sky Attack|Sky Attack]]'
- - Master
  - '[[SRD-Roost|Roost]]'
- - Master
  - '[[SRD-Hurricane|Hurricane]]'
- - Master
  - '[[SRD-Burn Up|Burn Up]]'
- - Master
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Master
  - '[[SRD-Flame Charge|Flame Charge]]'
- - Master
  - '[[SRD-Curse|Curse]]'
- - Master
  - '[[SRD-Fire Blast|Fire Blast]]'
- - Master
  - '[[SRD-Swift|Swift]]'
- - Master
  - '[[SRD-Fly|Fly]]'
Number: 146
ShuffleToken: SRD-moltres-ShuffleToken.png
Type1: Fire
Type2: Flying
Weight:
  Kilograms: 60.0
  Pounds: 132.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-moltres-BookSprite.png|wsmall]]
> ![[SRD-moltres-HomeSprite.png]]
> ![[SRD-moltres-BoxSprite.png|htiny]]
> ![[SRD-moltres-ShuffleToken.png|wsmall]]


*No Data*
*The legend speaks of a bird who came flying from the south. Its fiery body melted the snow and brought the spring along. A children‘s book depicts a similar Pokemon living inside of a volcano.*

**DexID**:: 0146
**Name**:: Moltres
**Type**:: Fire / Flying
**Abilities**:: [[SRD-Pressure|Pressure]] ([[SRD-Flame Body|Flame Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 5)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::7)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::5)/(MaxInsight::5)     |

**Height**: 6'6" / 2.0m
**Weight**: 132.3lbs / 60.0kg
**Good Starter**:: No
**Recommended Rank**:: Master

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Moltres.md"
flatten moves as T
where file.path = this.file.path
```
