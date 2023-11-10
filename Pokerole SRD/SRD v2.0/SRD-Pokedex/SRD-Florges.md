---
Ability1: Flower Veil
Ability2: ''
BookSprite: SRD-florges-BookSprite.png
BoxSprite: SRD-florges-BoxSprite.png
DexCategory: Garden Pokemon
DexDescription: In times long past, castle rulers would invite Florges to create flower
  gardens to embellish their domains. Florges claim beautiful meadows as their territories
  but they are kind and merciful with visitors.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Floette]]'
GenderType: F
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Symbiosis
HomeSprite: SRD-florges-HomeSprite.png
Image: florges.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Disarming Voice|Disarming Voice]]'
- - Starter
  - '[[SRD-Flower Shield|Flower Shield]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wish|Wish]]'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Amateur
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Moonblast|Moonblast]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Grass Knot|Grass Knot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Magic Coat|Magic Coat]]'
Number: 671
ShuffleToken: SRD-florges-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 10.0
  Pounds: 22.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-florges-BookSprite.png|wsmall]]
> ![[SRD-florges-HomeSprite.png]]
> ![[SRD-florges-BoxSprite.png|htiny]]
> ![[SRD-florges-ShuffleToken.png|wsmall]]


*Garden Pokemon*
*In times long past, castle rulers would invite Florges to create flower gardens to embellish their domains. Florges claim beautiful meadows as their territories but they are kind and merciful with visitors.*

**DexID**:: 0671
**Name**:: Florges
**Type**:: Fairy
**Abilities**:: [[SRD-Flower Veil|Flower Veil]] ([[SRD-Symbiosis|Symbiosis]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::7)     |

**Height**: 3'6" / 1.1m
**Weight**: 22.0lbs / 10.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Item        |
|:----------|:----------------|:-------|:------------|
| From      | [[SRD-Floette]] | Stone  | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Florges.md"
flatten moves as T
where file.path = this.file.path
```
