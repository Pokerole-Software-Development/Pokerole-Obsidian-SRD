---
Ability1: Trace
Ability2: Download
BookSprite: SRD-porygon2-BookSprite.png
BoxSprite: SRD-porygon2-BoxSprite.png
DexCategory: Virtual Pokemon
DexDescription: This man-made Pokemon is an upgraded version of Porygon. Used for
  space exploration and planetary development, boasting the power of science. Its
  AI software allows it to learn on its own.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: 'Upgrade '
  Kind: Trade
  Pokemon: '[[SRD-Porygon]]'
- Evolves: To
  Item: Dubious Disc
  Kind: Trade
  Pokemon: '[[SRD-Porygon-Z]]'
GenderType: N
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Analytic
HomeSprite: SRD-porygon2-HomeSprite.png
Image: porygon2.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Conversion|Conversion]]'
- - Starter
  - '[[SRD-Conversion 2|Conversion 2]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Recycle|Recycle]]'
- - Amateur
  - '[[SRD-Discharge|Discharge]]'
- - Amateur
  - '[[SRD-Lock-On|Lock-On]]'
- - Amateur
  - '[[SRD-Tri Attack|Tri Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Magic Coat|Magic Coat]]'
- - Ace
  - '[[SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Gravity|Gravity]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Shock Wave|Shock Wave]]'
Number: 233
ShuffleToken: SRD-porygon2-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 32.5
  Pounds: 71.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-porygon2-BookSprite.png|wsmall]]
> ![[SRD-porygon2-HomeSprite.png]]
> ![[SRD-porygon2-BoxSprite.png|htiny]]
> ![[SRD-porygon2-ShuffleToken.png|wsmall]]


*Virtual Pokemon*
*This man-made Pokemon is an upgraded version of Porygon. Used for space exploration and planetary development, boasting the power of science. Its AI software allows it to learn on its own.*

**DexID**:: 0233
**Name**:: Porygon2
**Type**:: Normal
**Abilities**:: [[SRD-Trace|Trace]] / [[SRD-Download|Download]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'0" / 0.6m
**Weight**: 71.7lbs / 32.5kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon           | Kind   | Item         |
|:----------|:------------------|:-------|:-------------|
| From      | [[SRD-Porygon]]   | Trade  | Upgrade      |
| To        | [[SRD-Porygon-Z]] | Trade  | Dubious Disc |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Porygon2.md"
flatten moves as T
where file.path = this.file.path
```
