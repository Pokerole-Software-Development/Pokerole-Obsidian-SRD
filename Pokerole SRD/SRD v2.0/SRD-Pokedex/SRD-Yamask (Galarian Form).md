---
Ability1: Wandering Spirit
Ability2: ''
BookSprite: SRD-yamask-galarian-form-BookSprite.png
BoxSprite: SRD-yamask-galarian-form-BoxSprite.png
DexCategory: Spirit Pokemon
DexDescription: "It\u2019s said that this Pokemon was formed when an ancient clay\
  \ tablet was drawn to the dark energy of a spirit. The clay slab seems to be absorbing\
  \ Yamask's power that\u2019s why it is so pale."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Special
  Pokemon: '[[SRD-Runerigus]]'
  Special: Walk near a rune Painting
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-yamask-galarian-form-HomeSprite.png
Image: yamask-galarian-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Astonish|Astonish]]'
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Haze|Haze]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Disable|Disable]]'
- - Amateur
  - '[[SRD-Brutal Swing|Brutal Swing]]'
- - Amateur
  - '[[SRD-Crafty Shield|Crafty Shield]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Mean Look|Mean Look]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Power Split|Power Split]]'
- - Ace
  - '[[SRD-Guard Split|Guard Split]]'
- - Ace
  - '[[SRD-Destiny Bond|Destiny Bond]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Pro
  - '[[SRD-Psychic|Psychic]]'
- - Pro
  - '[[SRD-Memento|Memento]]'
Number: 562
ShuffleToken: SRD-yamask-galarian-form-ShuffleToken.png
Type1: Ground
Type2: Ghost
Weight:
  Kilograms: 1.5
  Pounds: 3.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-yamask-galarian-form-BookSprite.png|wsmall]]
> ![[SRD-yamask-galarian-form-HomeSprite.png]]
> ![[SRD-yamask-galarian-form-BoxSprite.png|htiny]]
> ![[SRD-yamask-galarian-form-ShuffleToken.png|wsmall]]


*Spirit Pokemon*
*It’s said that this Pokemon was formed when an ancient clay tablet was drawn to the dark energy of a spirit. The clay slab seems to be absorbing Yamask's power that’s why it is so pale.*

**DexID**:: 0562G
**Name**:: Yamask (Galarian Form)
**Type**:: Ground / Ghost
**Abilities**:: [[SRD-Wandering Spirit|Wandering Spirit]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'6" / 0.5m
**Weight**: 3.3lbs / 1.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind    | Special                   |
|:----------|:------------------|:--------|:--------------------------|
| To        | [[SRD-Runerigus]] | Special | Walk near a rune Painting |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Yamask (Galarian Form).md"
flatten moves as T
where file.path = this.file.path
```
