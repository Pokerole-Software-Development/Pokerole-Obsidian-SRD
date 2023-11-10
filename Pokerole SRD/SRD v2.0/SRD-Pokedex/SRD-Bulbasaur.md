---
Ability1: Overgrow
Ability2: ''
BookSprite: SRD-bulbasaur-BookSprite.png
BoxSprite: SRD-bulbasaur-BoxSprite.png
DexCategory: Seed Pokemon
DexDescription: It carries a seed on its back since birth. As it grows older the seed
  also grows larger. It is known to be a well-behaved and loyal Pokemon, but pretty
  rare to find in the wild.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Ivysaur]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Chlorophyll
HomeSprite: SRD-bulbasaur-HomeSprite.png
Image: bulbasaur.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Sleep Powder|Sleep Powder]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Synthesis|Synthesis]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Pro
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Pro
  - '[[SRD-Amnesia|Amnesia]]'
- - Pro
  - '[[SRD-Grass Pledge|Grass Pledge]]'
Number: 1
ShuffleToken: SRD-bulbasaur-ShuffleToken.png
Type1: Grass
Type2: Poison
Weight:
  Kilograms: 6.9
  Pounds: 15.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-bulbasaur-BookSprite.png|wsmall]]
> ![[SRD-bulbasaur-HomeSprite.png]]
> ![[SRD-bulbasaur-BoxSprite.png|htiny]]
> ![[SRD-bulbasaur-ShuffleToken.png|wsmall]]


*Seed Pokemon*
*It carries a seed on its back since birth. As it grows older the seed also grows larger. It is known to be a well-behaved and loyal Pokemon, but pretty rare to find in the wild.*

**DexID**:: 0001
**Name**:: Bulbasaur
**Type**:: Grass / Poison
**Abilities**:: [[SRD-Overgrow|Overgrow]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 15.2lbs / 6.9kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Ivysaur]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Bulbasaur.md"
flatten moves as T
where file.path = this.file.path
```
