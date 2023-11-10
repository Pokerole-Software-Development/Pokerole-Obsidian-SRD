---
Ability1: Sturdy
Ability2: Magnet Pull
BookSprite: SRD-probopass-BookSprite.png
BoxSprite: SRD-probopass-BoxSprite.png
DexCategory: Compass Pokemon
DexDescription: It exudes strong magnetism from all over. It controls three small
  units called Mini-Noses that float around and act as arms. It usually stays motionless
  unless attacked or provoked.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Nosepass]]'
  Special: A trip to New Mauville
GenderType: ''
Height:
  Feet: 4.6
  Meters: 1.4
HiddenAbility: Sand Force
HomeSprite: SRD-probopass-HomeSprite.png
Image: probopass.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Block|Block]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Beginner
  - '[[SRD-Magnet Bomb|Magnet Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tri Attack|Tri Attack]]'
- - Amateur
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Gravity|Gravity]]'
- - Amateur
  - '[[SRD-Wide Guard|Wide Guard]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Rock Blast|Rock Blast]]'
- - Amateur
  - '[[SRD-Rest|Rest]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Power Gem|Power Gem]]'
- - Amateur
  - '[[SRD-Sandstorm|Sandstorm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Earth Power|Earth Power]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Lock-On|Lock-On]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Endure|Endure]]'
- - Pro
  - '[[SRD-Iron Head|Iron Head]]'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
Number: 476
ShuffleToken: SRD-probopass-ShuffleToken.png
Type1: Rock
Type2: Steel
Weight:
  Kilograms: 340.0
  Pounds: 749.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-probopass-BookSprite.png|wsmall]]
> ![[SRD-probopass-HomeSprite.png]]
> ![[SRD-probopass-BoxSprite.png|htiny]]
> ![[SRD-probopass-ShuffleToken.png|wsmall]]


*Compass Pokemon*
*It exudes strong magnetism from all over. It controls three small units called Mini-Noses that float around and act as arms. It usually stays motionless unless attacked or provoked.*

**DexID**:: 0476
**Name**:: Probopass
**Type**:: Rock / Steel
**Abilities**:: [[SRD-Sturdy|Sturdy]] / [[SRD-Magnet Pull|Magnet Pull]] ([[SRD-Sand Force|Sand Force]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::4)/(MaxVitality::8)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::4)/(MaxInsight::8)     |

**Height**: 4'6" / 1.4m
**Weight**: 749.6lbs / 340.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind    | Special                |
|:----------|:-----------------|:--------|:-----------------------|
| From      | [[SRD-Nosepass]] | Special | A trip to New Mauville |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Probopass.md"
flatten moves as T
where file.path = this.file.path
```
