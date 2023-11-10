---
Ability1: Anticipation
Ability2: ''
BookSprite: SRD-wormadam-grass-form-BookSprite.png
BoxSprite: SRD-wormadam-grass-form-BoxSprite.png
DexCategory: Bagworm Pokemon
DexDescription: When Burmy evolved, its Grass cloak became a part of its body. For
  this reason there are many variations in body and type. It is a calm Pokemon that
  loves flowers. This Pokemon is female only.
EventAbilities: ''
Evolutions:
- Evolves: From
  Gender: Female
  Kind: Level
  Pokemon: '[[SRD-Burmy]]'
  Speed: Fast
GenderType: F
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Overcoat
HomeSprite: SRD-wormadam-grass-form-HomeSprite.png
Image: wormadam-grass-form.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Protect|Protect]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Confusion|Confusion]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Growth|Growth]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Attract|Attract]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Leaf Storm|Leaf Storm]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 413
ShuffleToken: SRD-wormadam-grass-form-ShuffleToken.png
Type1: Bug
Type2: Grass
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wormadam-grass-form-BookSprite.png|wsmall]]
> ![[SRD-wormadam-grass-form-HomeSprite.png]]
> ![[SRD-wormadam-grass-form-BoxSprite.png|htiny]]
> ![[SRD-wormadam-grass-form-ShuffleToken.png|wsmall]]


*Bagworm Pokemon*
*When Burmy evolved, its Grass cloak became a part of its body. For this reason there are many variations in body and type. It is a calm Pokemon that loves flowers. This Pokemon is female only.*

**DexID**:: 0413
**Name**:: Wormadam (Grass Form)
**Type**:: Bug / Grass
**Abilities**:: [[SRD-Anticipation|Anticipation]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 1'6" / 0.5m
**Weight**: 14.3lbs / 6.5kg
**Good Starter**:: No
**Recommended Rank**:: Beginner

| Evolves   | Pokemon       | Kind   | Speed   | Gender   |
|:----------|:--------------|:-------|:--------|:---------|
| From      | [[SRD-Burmy]] | Level  | Fast    | Female   |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wormadam (Grass Form).md"
flatten moves as T
where file.path = this.file.path
```
