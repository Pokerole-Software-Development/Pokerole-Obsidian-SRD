---
Ability1: Sweet Veil
Ability2: ''
BookSprite: SRD-alcremie-BookSprite.png
BoxSprite: SRD-alcremie-BoxSprite.png
DexCategory: Cream Pokemon
DexDescription: There is a vast number of recipes to evolve an Alcremie, changing
  their color and flavor, some are sweet, some are sour but they are all delicious.
  Cakes baked with its help can be sold for a lot of money.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Special
  Pokemon: '[[SRD-Milcery]]'
  Special: Berry & spin
GenderType: F
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Aroma Veil
HomeSprite: SRD-alcremie-HomeSprite.png
Image: alcremie.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Decorate|Decorate]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mystical Fire|Mystical Fire]]'
- - Pro
  - '[[SRD-Substitute|Substitute]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
Number: 869
ShuffleToken: SRD-alcremie-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 0.5
  Pounds: 1.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-alcremie-BookSprite.png|wsmall]]
> ![[SRD-alcremie-HomeSprite.png]]
> ![[SRD-alcremie-BoxSprite.png|htiny]]
> ![[SRD-alcremie-ShuffleToken.png|wsmall]]


*Cream Pokemon*
*There is a vast number of recipes to evolve an Alcremie, changing their color and flavor, some are sweet, some are sour but they are all delicious. Cakes baked with its help can be sold for a lot of money.*

**DexID**:: 0869
**Name**:: Alcremie
**Type**:: Fairy
**Abilities**:: [[SRD-Sweet Veil|Sweet Veil]] ([[SRD-Aroma Veil|Aroma Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 1'0" / 0.3m
**Weight**: 1.1lbs / 0.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind    | Special      |
|:----------|:----------------|:--------|:-------------|
| From      | [[SRD-Milcery]] | Special | Berry & spin |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Alcremie.md"
flatten moves as T
where file.path = this.file.path
```
