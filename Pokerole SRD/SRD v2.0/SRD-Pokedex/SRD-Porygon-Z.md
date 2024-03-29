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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Conversion|Conversion]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Conversion 2|Conversion 2]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Psybeam|Psybeam]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nasty Plot|Nasty Plot]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick Room|Trick Room]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Agility|Agility]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Recover|Recover]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magnet Rise|Magnet Rise]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Signal Beam|Signal Beam]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Embargo|Embargo]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Discharge|Discharge]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lock-On|Lock-On]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tri Attack|Tri Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magic Coat|Magic Coat]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Zap Cannon|Zap Cannon]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hyper Beam|Hyper Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Trick|Trick]]'
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
