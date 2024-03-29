---
Ability1: Chlorophyll
Ability2: ''
BookSprite: SRD-cherubi-BookSprite.png
BoxSprite: SRD-cherubi-BoxSprite.png
DexCategory: Cherry Pokemon
DexDescription: "It hides on bushes while absorbing the sunlight. Their small heads\
  \ store the energy needed for evolution, but this small head is frequently eaten\
  \ by other Pokemon and people so it\u2019s hard for them to evolve."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Cherrim]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.3
  Meters: 0.4
HiddenAbility: ''
HomeSprite: SRD-cherubi-HomeSprite.png
Image: cherubi.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Morning Sun|Morning Sun]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sunny Day|Sunny Day]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Worry Seed|Worry Seed]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Petal Blizzard|Petal Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Weather Ball|Weather Ball]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Nature Power|Nature Power]]'
Number: 420
ShuffleToken: SRD-cherubi-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 3.3
  Pounds: 7.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cherubi-BookSprite.png|wsmall]]
> ![[SRD-cherubi-HomeSprite.png]]
> ![[SRD-cherubi-BoxSprite.png|htiny]]
> ![[SRD-cherubi-ShuffleToken.png|wsmall]]


*Cherry Pokemon*
*It hides on bushes while absorbing the sunlight. Their small heads store the energy needed for evolution, but this small head is frequently eaten by other Pokemon and people so it’s hard for them to evolve.*

**DexID**:: 0420
**Name**:: Cherubi
**Type**:: Grass
**Abilities**:: [[SRD-Chlorophyll|Chlorophyll]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'3" / 0.4m
**Weight**: 7.3lbs / 3.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Cherrim]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cherubi.md"
flatten moves as T
where file.path = this.file.path
```
