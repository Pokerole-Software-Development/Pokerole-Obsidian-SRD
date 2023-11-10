---
Ability1: Adaptability
Ability2: Download
BookSprite: SRD-porygon-z-BookSprite.png
BoxSprite: SRD-porygon-z-BoxSprite.png
DexCategory: Virtual Pokemon
DexDescription: A software to explore another dimension was installed on Porygon.
  However, it began acting oddly due to glitches in the code. Since then, it has a
  fondness for videos of Meowth and Skitty on the internet
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Dubious Disc
  Kind: Trade
  Pokemon: '[[SRD-Porygon2]]'
GenderType: N
Height:
  Feet: 3.0
  Meters: 0.9
HiddenAbility: Analytic
HomeSprite: SRD-porygon-z-HomeSprite.png
Image: porygon-z.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Conversion|Conversion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Conversion 2|Conversion 2]]'
- - Beginner
  - '[[SRD-Psybeam|Psybeam]]'
- - Beginner
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Trick Room|Trick Room]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Recover|Recover]]'
- - Amateur
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
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
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Trick|Trick]]'
Number: 474
ShuffleToken: SRD-porygon-z-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 34.0
  Pounds: 75.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-porygon-z-BookSprite.png|wsmall]]
> ![[SRD-porygon-z-HomeSprite.png]]
> ![[SRD-porygon-z-BoxSprite.png|htiny]]
> ![[SRD-porygon-z-ShuffleToken.png|wsmall]]


*Virtual Pokemon*
*A software to explore another dimension was installed on Porygon. However, it began acting oddly due to glitches in the code. Since then, it has a fondness for videos of Meowth and Skitty on the internet*

**DexID**:: 0474
**Name**:: Porygon-Z
**Type**:: Normal
**Abilities**:: [[SRD-Adaptability|Adaptability]] / [[SRD-Download|Download]] ([[SRD-Analytic|Analytic]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'0" / 0.9m
**Weight**: 75.0lbs / 34.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Item         |
|:----------|:-----------------|:-------|:-------------|
| From      | [[SRD-Porygon2]] | Trade  | Dubious Disc |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Porygon-Z.md"
flatten moves as T
where file.path = this.file.path
```
