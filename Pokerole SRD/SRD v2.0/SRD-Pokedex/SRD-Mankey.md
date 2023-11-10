---
Ability1: Vital Spirit
Ability2: Anger Point
BookSprite: SRD-mankey-BookSprite.png
BoxSprite: SRD-mankey-BoxSprite.png
DexCategory: Pig Monkey Pokemon
DexDescription: It lives on the mountains or at the top of fruit trees. Light and
  agile on its feet and ferocious in temperament. When it gets angry, it goes into
  a frenzy and cannot be controlled.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Primeape]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Defiant
HomeSprite: SRD-mankey-HomeSprite.png
Image: mankey.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Covet|Covet]]'
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Low Kick|Low Kick]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Focus Energy|Focus Energy]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Swagger|Swagger]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Cross Chop|Cross Chop]]'
- - Ace
  - '[[SRD-Thrash|Thrash]]'
- - Ace
  - '[[SRD-Punishment|Punishment]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Final Gambit|Final Gambit]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Meditate|Meditate]]'
- - Pro
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Pro
  - '[[SRD-Beat Up|Beat Up]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stomping Tantrum|Stomping Tantrum]]'
Number: 56
ShuffleToken: SRD-mankey-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-mankey-BookSprite.png|wsmall]]
> ![[SRD-mankey-HomeSprite.png]]
> ![[SRD-mankey-BoxSprite.png|htiny]]
> ![[SRD-mankey-ShuffleToken.png|wsmall]]


*Pig Monkey Pokemon*
*It lives on the mountains or at the top of fruit trees. Light and agile on its feet and ferocious in temperament. When it gets angry, it goes into a frenzy and cannot be controlled.*

**DexID**:: 0056
**Name**:: Mankey
**Type**:: Fighting
**Abilities**:: [[SRD-Vital Spirit|Vital Spirit]] / [[SRD-Anger Point|Anger Point]] ([[SRD-Defiant|Defiant]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Primeape]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Mankey.md"
flatten moves as T
where file.path = this.file.path
```
