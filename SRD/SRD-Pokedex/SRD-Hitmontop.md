---
Ability1: Intimidate
Ability2: Technician
BookSprite: SRD-hitmontop-BookSprite.png
BoxSprite: SRD-hitmontop-BoxSprite.png
DexCategory: Handstand Pokemon
DexDescription: They launch high speed kicks while spinning so fast that they get
  drilled into the ground. They move quicker by spinning than they do walking. They
  are very smart and like to perform dance-like kicks.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Tyrogue]]'
  Stat: Dexterity
  Value: -1
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Steadfast
HomeSprite: SRD-hitmontop-HomeSprite.png
Image: hitmontop.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Revenge|Revenge]]'
- - Starter
  - '[[SRD-Rolling Kick|Rolling Kick]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Quick Attack|Quick Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Triple Kick|Triple Kick]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Counter|Counter]]'
- - Amateur
  - '[[SRD-Feint|Feint]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Quick Guard|Quick Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Ace
  - '[[SRD-Detect|Detect]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mach Punch|Mach Punch]]'
- - Pro
  - '[[SRD-High Jump Kick|High Jump Kick]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Number: 237
ShuffleToken: SRD-hitmontop-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 48.0
  Pounds: 105.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hitmontop-BookSprite.png|wsmall]]
> ![[SRD-hitmontop-HomeSprite.png]]
> ![[SRD-hitmontop-BoxSprite.png|htiny]]
> ![[SRD-hitmontop-ShuffleToken.png|wsmall]]


*Handstand Pokemon*
*They launch high speed kicks while spinning so fast that they get drilled into the ground. They move quicker by spinning than they do walking. They are very smart and like to perform dance-like kicks.*

**DexID**:: 0237
**Name**:: Hitmontop
**Type**:: Fighting
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Technician|Technician]] ([[SRD-Steadfast|Steadfast]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 4'6" / 1.4m
**Weight**: 105.8lbs / 48.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Stat      |   Value |
|:----------|:----------------|:-------|:----------|--------:|
| From      | [[SRD-Tyrogue]] | Stat   | Dexterity |      -1 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Hitmontop.md"
flatten moves as T
where file.path = this.file.path
```
