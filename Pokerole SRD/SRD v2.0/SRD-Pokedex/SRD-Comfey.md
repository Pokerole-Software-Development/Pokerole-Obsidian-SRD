---
Ability1: Flower Veil
Ability2: Triage
BookSprite: SRD-comfey-BookSprite.png
BoxSprite: SRD-comfey-BoxSprite.png
DexCategory: Posy Picker Pokemon
DexDescription: This tiny Pokemon gathers flowers and connects them to itself forming
  a ring. The flowers never wither and their aroma becomes soothing and therapeutic.
  If it likes you it will create a flower ring just for you.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 0.3
  Meters: 0.1
HiddenAbility: Natural Cure
HomeSprite: SRD-comfey-HomeSprite.png
Image: comfey.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Starter
  - '[[SRD-Vine Whip|Vine Whip]]'
- - Starter
  - '[[SRD-Flower Shield|Flower Shield]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Beginner
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Wrap|Wrap]]'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Amateur
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Amateur
  - '[[SRD-Petal Blizzard|Petal Blizzard]]'
- - Amateur
  - '[[SRD-Synthesis|Synthesis]]'
- - Amateur
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Grass Knot|Grass Knot]]'
- - Ace
  - '[[SRD-Floral Healing|Floral Healing]]'
- - Ace
  - '[[SRD-Petal Dance|Petal Dance]]'
- - Ace
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Ace
  - '[[SRD-Grassy Terrain|Grassy Terrain]]'
- - Ace
  - '[[SRD-Play Rough|Play Rough]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Endure|Endure]]'
Number: 764
ShuffleToken: SRD-comfey-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-comfey-BookSprite.png|wsmall]]
> ![[SRD-comfey-HomeSprite.png]]
> ![[SRD-comfey-BoxSprite.png|htiny]]
> ![[SRD-comfey-ShuffleToken.png|wsmall]]


*Posy Picker Pokemon*
*This tiny Pokemon gathers flowers and connects them to itself forming a ring. The flowers never wither and their aroma becomes soothing and therapeutic. If it likes you it will create a flower ring just for you.*

**DexID**:: 0764
**Name**:: Comfey
**Type**:: Fairy
**Abilities**:: [[SRD-Flower Veil|Flower Veil]] / [[SRD-Triage|Triage]] ([[SRD-Natural Cure|Natural Cure]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 0'3" / 0.1m
**Weight**: 0.7lbs / 0.3kg
**Good Starter**:: No
**Recommended Rank**:: Starter

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Comfey.md"
flatten moves as T
where file.path = this.file.path
```
