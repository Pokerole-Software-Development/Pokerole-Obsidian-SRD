---
Ability1: Chlorophyll
Ability2: Leaf Guard
BookSprite: SRD-tangrowth-BookSprite.png
BoxSprite: SRD-tangrowth-BoxSprite.png
DexCategory: Vine Pokemon
DexDescription: "While it remains still, it appears to be a large shrub. Unsuspecting\
  \ prey that wander near get ensnared by its vines. In the summer months, its vines\
  \ grow so large that you can\u2019t even see its eyes."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Tangela]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 6.6
  Meters: 2.0
HiddenAbility: Regenerator
HomeSprite: SRD-tangrowth-HomeSprite.png
Image: tangrowth.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Block|Block]]'
- - Starter
  - '[[SRD-Ingrain|Ingrain]]'
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Beginner
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Bind|Bind]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Tickle|Tickle]]'
- - Ace
  - '[[SRD-Wring Out|Wring Out]]'
- - Ace
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Ace
  - '[[SRD-Power Whip|Power Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nature Power|Nature Power]]'
- - Pro
  - '[[SRD-Confusion|Confusion]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
Number: 465
ShuffleToken: SRD-tangrowth-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 128.6
  Pounds: 283.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tangrowth-BookSprite.png|wsmall]]
> ![[SRD-tangrowth-HomeSprite.png]]
> ![[SRD-tangrowth-BoxSprite.png|htiny]]
> ![[SRD-tangrowth-ShuffleToken.png|wsmall]]


*Vine Pokemon*
*While it remains still, it appears to be a large shrub. Unsuspecting prey that wander near get ensnared by its vines. In the summer months, its vines grow so large that you can’t even see its eyes.*

**DexID**:: 0465
**Name**:: Tangrowth
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::7)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 6'6" / 2.0m
**Weight**: 283.5lbs / 128.6kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Tangela]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Tangrowth.md"
flatten moves as T
where file.path = this.file.path
```
