---
Ability1: Vital Spirit
Ability2: Anger Point
BookSprite: SRD-primeape-BookSprite.png
BoxSprite: SRD-primeape-BoxSprite.png
DexCategory: Pig Monkey Pokemon
DexDescription: It grows angry if you see its eyes and gets angrier if you run. If
  you fight it will go mad with rage. Not many trainers are capable of handling it,
  the angrier it gets the less intelligent it becomes.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Mankey]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Defiant
HomeSprite: SRD-primeape-HomeSprite.png
Image: primeape.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fling|Fling]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Pursuit|Pursuit]]'
- - Amateur
  - '[[SRD-Karate Chop|Karate Chop]]'
- - Amateur
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Meditate|Meditate]]'
- - Pro
  - '[[SRD-Overheat|Overheat]]'
Number: 57
ShuffleToken: SRD-primeape-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 32.0
  Pounds: 70.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-primeape-BookSprite.png|wsmall]]
> ![[SRD-primeape-HomeSprite.png]]
> ![[SRD-primeape-BoxSprite.png|htiny]]
> ![[SRD-primeape-ShuffleToken.png|wsmall]]


*Pig Monkey Pokemon*
*It grows angry if you see its eyes and gets angrier if you run. If you fight it will go mad with rage. Not many trainers are capable of handling it, the angrier it gets the less intelligent it becomes.*

**DexID**:: 0057
**Name**:: Primeape
**Type**:: Fighting
**Abilities**:: [[SRD-Vital Spirit|Vital Spirit]] / [[SRD-Anger Point|Anger Point]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 70.5lbs / 32.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Mankey]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Primeape.md"
flatten moves as T
where file.path = this.file.path
```
