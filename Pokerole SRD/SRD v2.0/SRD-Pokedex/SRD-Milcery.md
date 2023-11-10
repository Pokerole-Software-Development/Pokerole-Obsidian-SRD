---
Ability1: Sweet Veil
Ability2: ''
BookSprite: SRD-milcery-BookSprite.png
BoxSprite: SRD-milcery-BoxSprite.png
DexCategory: Cream Pokemon
DexDescription: This Pokemon was born from sweet-smelling particles in the air, its
  body is made of cream, Finding one in your kitchen means Good Fortune. Give them
  berries and whip them with a whisk so they can evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Alcremie]]'
  Special: Berry & spin
GenderType: F
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Aroma Veil
HomeSprite: SRD-milcery-HomeSprite.png
Image: milcery.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Aromatic Mist|Aromatic Mist]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Beginner
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Draining Kiss|Draining Kiss]]'
- - Amateur
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Amateur
  - '[[SRD-Attract|Attract]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - Amateur
  - '[[SRD-Dazzling Gleam|Dazzling Gleam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Recover|Recover]]'
- - Ace
  - '[[SRD-Misty Terrain|Misty Terrain]]'
- - Ace
  - '[[SRD-Entrainment|Entrainment]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Charm|Charm]]'
- - Pro
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Pro
  - '[[SRD-Fling|Fling]]'
Number: 868
ShuffleToken: SRD-milcery-ShuffleToken.png
Type1: Fairy
Type2: ''
Weight:
  Kilograms: 0.3
  Pounds: 0.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-milcery-BookSprite.png|wsmall]]
> ![[SRD-milcery-HomeSprite.png]]
> ![[SRD-milcery-BoxSprite.png|htiny]]
> ![[SRD-milcery-ShuffleToken.png|wsmall]]


*Cream Pokemon*
*This Pokemon was born from sweet-smelling particles in the air, its body is made of cream, Finding one in your kitchen means Good Fortune. Give them berries and whip them with a whisk so they can evolve.*

**DexID**:: 0868
**Name**:: Milcery
**Type**:: Fairy
**Abilities**:: [[SRD-Sweet Veil|Sweet Veil]] ([[SRD-Aroma Veil|Aroma Veil]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 0.7lbs / 0.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind    | Special      |
|:----------|:-----------------|:--------|:-------------|
| To        | [[SRD-Alcremie]] | Special | Berry & spin |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Milcery.md"
flatten moves as T
where file.path = this.file.path
```
