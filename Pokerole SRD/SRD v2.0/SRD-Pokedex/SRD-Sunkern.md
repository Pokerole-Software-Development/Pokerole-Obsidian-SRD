---
Ability1: Chlorophyll
Ability2: Solar Power
BookSprite: SRD-sunkern-BookSprite.png
BoxSprite: SRD-sunkern-BoxSprite.png
DexCategory: Seed Pokemon
DexDescription: They suddenly appear after a cold winter. They survive by drinking
  only dewdrops from under the leaves of plants. It tries not to move a lot since
  lots of bird Pokemon prey on them.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Sunflora]]'
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Early Bird
HomeSprite: SRD-sunkern-HomeSprite.png
Image: sunkern.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Absorb|Absorb]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ingrain|Ingrain]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grass Whistle|Grass Whistle]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mega Drain|Mega Drain]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Worry Seed|Worry Seed]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Giga Drain|Giga Drain]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endeavor|Endeavor]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Natural Gift|Natural Gift]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Seed Bomb|Seed Bomb]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Swords Dance|Swords Dance]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Endure|Endure]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grassy Terrain|Grassy Terrain]]'
Number: 191
ShuffleToken: SRD-sunkern-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 1.8
  Pounds: 4.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sunkern-BookSprite.png|wsmall]]
> ![[SRD-sunkern-HomeSprite.png]]
> ![[SRD-sunkern-BoxSprite.png|htiny]]
> ![[SRD-sunkern-ShuffleToken.png|wsmall]]


*Seed Pokemon*
*They suddenly appear after a cold winter. They survive by drinking only dewdrops from under the leaves of plants. It tries not to move a lot since lots of bird Pokemon prey on them.*

**DexID**:: 0191
**Name**:: Sunkern
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]] / [[SRD-Solar Power|Solar Power]] ([[SRD-Early Bird|Early Bird]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 4.0lbs / 1.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Item      |
|:----------|:-----------------|:-------|:----------|
| To        | [[SRD-Sunflora]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Sunkern.md"
flatten moves as T
where file.path = this.file.path
```
