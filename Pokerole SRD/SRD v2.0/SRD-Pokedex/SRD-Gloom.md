---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-gloom-BookSprite.png
BoxSprite: SRD-gloom-BoxSprite.png
DexCategory: Weed Pokemon
DexDescription: A horribly noxious honey drools from its mouth. One whiff of the honey
  can result in sickness. Some fans are said to enjoy its overwhelming stink, though.
  You can control this foul smell with lots of love and care.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Oddish]]'
  Speed: Medium
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Vileplume]]'
- Evolves: To
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Bellossom]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Stench
HomeSprite: SRD-gloom-HomeSprite.png
Image: gloom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growth|Growth]]'
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Beginner
  - '[[SRD-Acid|Acid]]'
- - Beginner
  - '[[SRD-Poison Powder|Poison Powder]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Stun Spore|Stun Spore]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Toxic|Toxic]]'
- - Amateur
  - '[[SRD-Moonlight|Moonlight]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
Number: 44
ShuffleToken: SRD-gloom-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 8.6
  Pounds: 19.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-gloom-BookSprite.png|wsmall]]
> ![[SRD-gloom-HomeSprite.png]]
> ![[SRD-gloom-BoxSprite.png|htiny]]
> ![[SRD-gloom-ShuffleToken.png|wsmall]]


*Weed Pokemon*
*A horribly noxious honey drools from its mouth. One whiff of the honey can result in sickness. Some fans are said to enjoy its overwhelming stink, though. You can control this foul smell with lots of love and care.*

**DexID**:: 0044
**Name**:: Gloom
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] ([[SRD-Stench|Stench]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 2'6" / 0.8m
**Weight**: 19.0lbs / 8.6kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   | Item       |
|:----------|:------------------|:-------|:--------|:-----------|
| From      | [[SRD-Oddish]]    | Level  | Medium  |            |
| To        | [[SRD-Vileplume]] | Stone  |         | Leaf Stone |
| To        | [[SRD-Bellossom]] | Stone  |         | Sun Stone  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Gloom.md"
flatten moves as T
where file.path = this.file.path
```
