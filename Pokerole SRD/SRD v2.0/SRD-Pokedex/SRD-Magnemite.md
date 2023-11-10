---
Ability1: Magnet Pull
Ability2: Sturdy
BookSprite: SRD-magnemite-BookSprite.png
BoxSprite: SRD-magnemite-BoxSprite.png
DexCategory: Magnet Pokemon
DexDescription: It lurks near electric facilities and mountains as it is attracted
  by big magnetic fields. It is not aggressive and usually defends itself with a screech
  or a weak electric impulse to deter other from attacking.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Magneton]]'
  Speed: Medium
GenderType: N
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Analytic
HomeSprite: SRD-magnemite-HomeSprite.png
Image: magnemite.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Sonic Boom|Sonic Boom]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Light Screen|Light Screen]]'
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
- - Amateur
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Lock-On|Lock-On]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Signal Beam|Signal Beam]]'
Number: 81
ShuffleToken: SRD-magnemite-ShuffleToken.png
Type1: Electric
Type2: Steel
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-magnemite-BookSprite.png|wsmall]]
> ![[SRD-magnemite-HomeSprite.png]]
> ![[SRD-magnemite-BoxSprite.png|htiny]]
> ![[SRD-magnemite-ShuffleToken.png|wsmall]]


*Magnet Pokemon*
*It lurks near electric facilities and mountains as it is attracted by big magnetic fields. It is not aggressive and usually defends itself with a screech or a weak electric impulse to deter other from attacking.*

**DexID**:: 0081
**Name**:: Magnemite
**Type**:: Electric / Steel
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Magneton]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Magnemite.md"
flatten moves as T
where file.path = this.file.path
```
