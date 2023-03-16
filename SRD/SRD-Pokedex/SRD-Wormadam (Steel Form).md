---
Ability1: Speed Boost
Ability2: Compound Eyes
BookSprite: SRD-wormadam-steel-form-BookSprite.png
BoxSprite: SRD-wormadam-steel-form-BoxSprite.png
DexCategory: Bagworm Pokemon
DexDescription: When Burmy evolved, its Trash cloak became a part of its body. For
  this reason there are many variations in body and type. It is a calm Pokemon that
  loves foil wrapping. This Pokemon is female only.
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
HomeSprite: SRD-wormadam-steel-form-HomeSprite.png
Image: wormadam-steel-form.png
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
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Captivate|Captivate]]'
- - Amateur
  - '[[SRD-Bug Bite|Bug Bite]]'
- - Amateur
  - '[[SRD-Hidden Power|Hidden Power]]'
- - Amateur
  - '[[SRD-Mirror Shot|Mirror Shot]]'
- - Amateur
  - '[[SRD-Metal Sound|Metal Sound]]'
- - Amateur
  - '[[SRD-Psybeam|Psybeam]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Quiver Dance|Quiver Dance]]'
- - Ace
  - '[[SRD-Attract|Attract]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - Ace
  - '[[SRD-Iron Head|Iron Head]]'
- - Ace
  - '[[SRD-Bug Buzz|Bug Buzz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Pro
  - '[[SRD-Synthesis|Synthesis]]'
Number: 413
ShuffleToken: SRD-wormadam-steel-form-ShuffleToken.png
Type1: Bug
Type2: Steel
Weight:
  Kilograms: 6.5
  Pounds: 14.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wormadam-steel-form-BookSprite.png|wsmall]]
> ![[SRD-wormadam-steel-form-HomeSprite.png]]
> ![[SRD-wormadam-steel-form-BoxSprite.png|htiny]]
> ![[SRD-wormadam-steel-form-ShuffleToken.png|wsmall]]


*Bagworm Pokemon*
*When Burmy evolved, its Trash cloak became a part of its body. For this reason there are many variations in body and type. It is a calm Pokemon that loves foil wrapping. This Pokemon is female only.*

**DexID**:: 0413F1
**Name**:: Wormadam (Steel Form)
**Type**:: Bug / Steel
**Abilities**:: [[SRD-Speed Boost|Speed Boost]] / [[SRD-Compound Eyes|Compound Eyes]] ([[SRD-Overcoat|Overcoat]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::6)     |

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
FROM "SRD/SRD-Pokedex/SRD-Wormadam (Steel Form).md"
flatten moves as T
where file.path = this.file.path
```
