---
Ability1: Flower Veil
Ability2: ''
BookSprite: SRD-floette-BookSprite.png
BoxSprite: SRD-floette-BoxSprite.png
DexCategory: Fairy Pokemon
DexDescription: It flutters around flower meadows and takes care of buds that are
  starting to wilt. People who fill their gardens with their preferred flower receive
  its visit every spring. They are loyal and caring Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Flabebe]]'
  Speed: Fast
- Evolves: To
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Florges]]'
GenderType: F
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Symbiosis
HomeSprite: SRD-floette-HomeSprite.png
Image: floette.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fairy Wind|Fairy Wind]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grassy Terrain|Grassy Terrain]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Petal Blizzard|Petal Blizzard]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Camouflage|Camouflage]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magic Coat|Magic Coat]]'
Number: 670
ShuffleToken: SRD-floette-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 0.9
  Pounds: 2.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-floette-BookSprite.png|wsmall]]
> ![[SRD-floette-HomeSprite.png]]
> ![[SRD-floette-BoxSprite.png|htiny]]
> ![[SRD-floette-ShuffleToken.png|wsmall]]


*Fairy Pokemon*
*It flutters around flower meadows and takes care of buds that are starting to wilt. People who fill their gardens with their preferred flower receive its visit every spring. They are loyal and caring Pokemon.*

**DexID**:: 0670
**Name**:: Floette
**Type**:: Fairy
**Abilities**:: [[SRD-Flower Veil|Flower Veil]] ([[SRD-Symbiosis|Symbiosis]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 0'7" / 0.2m
**Weight**: 2.0lbs / 0.9kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   | Item        |
|:----------|:----------------|:-------|:--------|:------------|
| From      | [[SRD-Flabebe]] | Level  | Fast    |             |
| To        | [[SRD-Florges]] | Stone  |         | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Floette.md"
flatten moves as T
where file.path = this.file.path
```
