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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Disarming Voice|Disarming Voice]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Flower Shield|Flower Shield]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Lucky Chant|Lucky Chant]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Grass Knot|Grass Knot]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Heal Bell|Heal Bell]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Magic Coat|Magic Coat]]'
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
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Florges.md"
flatten moves as T
where file.path = this.file.path
```
