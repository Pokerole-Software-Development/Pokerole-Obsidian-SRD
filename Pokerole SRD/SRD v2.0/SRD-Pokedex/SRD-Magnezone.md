---
Ability1: Magnet Pull
Ability2: Sturdy
BookSprite: SRD-magnezone-BookSprite.png
BoxSprite: SRD-magnezone-BoxSprite.png
DexCategory: Magnet Area Pokemon
DexDescription: Magneton only evolves in very specific areas of the globe. It has
  the ability to repel itself from the ground using magnetism. If it is nervous it
  pulls all the pieces of metal around until it relaxes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Magneton]]'
  Speed: Slow
GenderType: N
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: Analytic
HomeSprite: SRD-magnezone-HomeSprite.png
Image: magnezone.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Magnetic Flux|Magnetic Flux]]'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Magnet Bomb|Magnet Bomb]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Electro Ball|Electro Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Barrier|Barrier]]'
- - Ace
  - '[[SRD-Mirror Coat|Mirror Coat]]'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Lock-On|Lock-On]]'
- - Ace
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 462
ShuffleToken: SRD-magnezone-ShuffleToken.png
Type1: Electric
Type2: Steel
Weight:
  Kilograms: 180.0
  Pounds: 396.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magnezone-BookSprite.png|wsmall]]
> ![[SRD-magnezone-HomeSprite.png]]
> ![[SRD-magnezone-BoxSprite.png|htiny]]
> ![[SRD-magnezone-ShuffleToken.png|wsmall]]


*Magnet Area Pokemon*
*Magneton only evolves in very specific areas of the globe. It has the ability to repel itself from the ground using magnetism. If it is nervous it pulls all the pieces of metal around until it relaxes.*

**DexID**:: 0462
**Name**:: Magnezone
**Type**:: Electric / Steel
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 396.8lbs / 180.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Magneton]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Magnezone.md"
flatten moves as T
where file.path = this.file.path
```
