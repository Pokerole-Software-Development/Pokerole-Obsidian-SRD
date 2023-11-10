---
Ability1: Flower Gift
Ability2: ''
BookSprite: SRD-cherrim-BookSprite.png
BoxSprite: SRD-cherrim-BoxSprite.png
DexCategory: Blossom Pokemon
DexDescription: Cherrims bloom during times of strong sunlight, their petals open
  fully and radiant. If the sun is not visible, it will remain as a closed bud, barely
  moving trying to preserve its energy.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Cherubi]]'
  Speed: Fast
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-cherrim-HomeSprite.png
Image: cherrim.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Morning Sun|Morning Sun]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Amateur
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Amateur
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - Ace
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Ace
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Pro
  - '[[SRD-Heal Pulse|Heal Pulse]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
Number: 421
ShuffleToken: SRD-cherrim-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 9.3
  Pounds: 20.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cherrim-BookSprite.png|wsmall]]
> ![[SRD-cherrim-HomeSprite.png]]
> ![[SRD-cherrim-BoxSprite.png|htiny]]
> ![[SRD-cherrim-ShuffleToken.png|wsmall]]


*Blossom Pokemon*
*Cherrims bloom during times of strong sunlight, their petals open fully and radiant. If the sun is not visible, it will remain as a closed bud, barely moving trying to preserve its energy.*

**DexID**:: 0421
**Name**:: Cherrim
**Type**:: Grass
**Abilities**:: [[SRD-Flower Gift|Flower Gift]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 20.5lbs / 9.3kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Cherubi]] | Level  | Fast    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cherrim.md"
flatten moves as T
where file.path = this.file.path
```
