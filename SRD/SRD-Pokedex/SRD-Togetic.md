---
Ability1: Hustle
Ability2: Serene Grace
BookSprite: SRD-togetic-BookSprite.png
BoxSprite: SRD-togetic-BoxSprite.png
DexCategory: Happiness Pokemon
DexDescription: Although there have been very few sightings of this Pokemon in the
  wild, it is known to appear before kind hearted people and grant them happiness.
  It is very energetic and friendly.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Stat
  Pokemon: '[[SRD-Togepi]]'
  Stat: Happiness
  Value: 5
- Evolves: To
  Item: Shiny Stone
  Kind: Stone
  Pokemon: '[[SRD-Togekiss]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Super Luck
HomeSprite: SRD-togetic-HomeSprite.png
Image: togetic.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Charm|Charm]]'
- - Beginner
  - '[[SRD-Sweet Kiss|Sweet Kiss]]'
- - Beginner
  - '[[SRD-Metronome|Metronome]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Magical Leaf|Magical Leaf]]'
- - Amateur
  - '[[SRD-Yawn|Yawn]]'
- - Amateur
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - Amateur
  - '[[SRD-Encore|Encore]]'
- - Amateur
  - '[[SRD-Follow Me|Follow Me]]'
- - Amateur
  - '[[SRD-Bestow|Bestow]]'
- - Amateur
  - '[[SRD-Safeguard|Safeguard]]'
- - Amateur
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Amateur
  - '[[SRD-Baton Pass|Baton Pass]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - Ace
  - '[[SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[SRD-After You|After You]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Extrasensory|Extrasensory]]'
Number: 176
ShuffleToken: SRD-togetic-ShuffleToken.png
Type1: Fairy
Type2: Flying
Weight:
  Kilograms: 3.2
  Pounds: 7.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-togetic-BookSprite.png|wsmall]]
> ![[SRD-togetic-HomeSprite.png]]
> ![[SRD-togetic-BoxSprite.png|htiny]]
> ![[SRD-togetic-ShuffleToken.png|wsmall]]


*Happiness Pokemon*
*Although there have been very few sightings of this Pokemon in the wild, it is known to appear before kind hearted people and grant them happiness. It is very energetic and friendly.*

**DexID**:: 0176
**Name**:: Togetic
**Type**:: Fairy / Flying
**Abilities**:: [[SRD-Hustle|Hustle]] / [[SRD-Serene Grace|Serene Grace]] ([[SRD-Super Luck|Super Luck]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'0" / 0.6m
**Weight**: 7.1lbs / 3.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Stat      | Value   | Item        |
|:----------|:-----------------|:-------|:----------|:--------|:------------|
| From      | [[SRD-Togepi]]   | Stat   | Happiness | 5.0     |             |
| To        | [[SRD-Togekiss]] | Stone  |           |         | Shiny Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Togetic.md"
flatten moves as T
where file.path = this.file.path
```
