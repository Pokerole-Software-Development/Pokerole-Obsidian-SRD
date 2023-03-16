---
Ability1: Chlorophyll
Ability2: Leaf Guard
BookSprite: SRD-tangela-BookSprite.png
BoxSprite: SRD-tangela-BoxSprite.png
DexCategory: Vine Pokemon
DexDescription: It blends with foliage on jungle and forest areas. Its vines snap
  off easily and painlessly if they are grabbed, allowing it to make a quick getaway.
  The lost vines are replaced by new growth the very next day.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Tangrowth]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Regenerator
HomeSprite: SRD-tangela-HomeSprite.png
Image: tangela.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Constrict|Constrict]]'
- - Starter
  - '[[SRD-Ingrain|Ingrain]]'
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
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Confusion|Confusion]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
Number: 114
ShuffleToken: SRD-tangela-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 35.0
  Pounds: 77.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-tangela-BookSprite.png|wsmall]]
> ![[SRD-tangela-HomeSprite.png]]
> ![[SRD-tangela-BoxSprite.png|htiny]]
> ![[SRD-tangela-ShuffleToken.png|wsmall]]


*Vine Pokemon*
*It blends with foliage on jungle and forest areas. Its vines snap off easily and painlessly if they are grabbed, allowing it to make a quick getaway. The lost vines are replaced by new growth the very next day.*

**DexID**:: 0114
**Name**:: Tangela
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Leaf Guard|Leaf Guard]] ([[SRD-Regenerator|Regenerator]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 3'3" / 1.0m
**Weight**: 77.2lbs / 35.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Tangrowth]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Tangela.md"
flatten moves as T
where file.path = this.file.path
```
