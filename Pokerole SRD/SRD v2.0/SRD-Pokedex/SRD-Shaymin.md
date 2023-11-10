---
Ability1: Natural Cure
Ability2: ''
BookSprite: SRD-shaymin-BookSprite.png
BoxSprite: SRD-shaymin-BoxSprite.png
DexCategory: No Data
DexDescription: "There are old traces of gigantic trees that once grew all over the\
  \ earth. They were called the \u201CTrees of Life\u201D and their flowers granted\
  \ the power of flight to the kindhearted, or so the legend says."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Gracidea flower
  Kind: Special
  Pokemon: '[[SRD-Shaymin (Sky Form)]]'
GenderType: N
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: ''
HomeSprite: SRD-shaymin-HomeSprite.png
Image: shaymin.png
Legendary: 'Yes'
Moves:
- - Master
  - '[[SRD-Growth|Growth]]'
- - Master
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Master
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Master
  - '[[SRD-Synthesis|Synthesis]]'
- - Master
  - '[[SRD-Sweet Scent|Sweet Scent]]'
- - Master
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Master
  - '[[SRD-Worry Seed|Worry Seed]]'
- - Master
  - '[[SRD-Aromatherapy|Aromatherapy]]'
- - Master
  - '[[SRD-Energy Ball|Energy Ball]]'
- - Master
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Master
  - '[[SRD-Healing Wish|Healing Wish]]'
- - Master
  - '[[SRD-Seed Flare|Seed Flare]]'
- - Master
  - '[[SRD-Earth Power|Earth Power]]'
- - Master
  - '[[SRD-Endeavor|Endeavor]]'
- - Master
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Master
  - '[[SRD-Zen Headbutt|Zen Headbutt]]'
Number: 492
ShuffleToken: SRD-shaymin-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 2.1
  Pounds: 4.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shaymin-BookSprite.png|wsmall]]
> ![[SRD-shaymin-HomeSprite.png]]
> ![[SRD-shaymin-BoxSprite.png|htiny]]
> ![[SRD-shaymin-ShuffleToken.png|wsmall]]


*No Data*
*There are old traces of gigantic trees that once grew all over the earth. They were called the “Trees of Life” and their flowers granted the power of flight to the kindhearted, or so the legend says.*

**DexID**:: 0492
**Name**:: Shaymin
**Type**:: Grass
**Abilities**:: [[SRD-Natural Cure|Natural Cure]]
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::6)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 6)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::6)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::6)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::6)/(MaxInsight::6)     |

**Height**: 0'7" / 0.2m
**Weight**: 4.6lbs / 2.1kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                    | Kind    | Item            |
|:----------|:---------------------------|:--------|:----------------|
| To        | [[SRD-Shaymin (Sky Form)]] | Special | Gracidea flower |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shaymin.md"
flatten moves as T
where file.path = this.file.path
```
