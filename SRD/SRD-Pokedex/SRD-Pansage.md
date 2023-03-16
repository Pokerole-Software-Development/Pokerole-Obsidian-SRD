---
Ability1: Gluttony
Ability2: ''
BookSprite: SRD-pansage-BookSprite.png
BoxSprite: SRD-pansage-BoxSprite.png
DexCategory: Grass Monkey Pokemon
DexDescription: "Pansage is a friendly Pokemon. It is good at finding berries and\
  \ will share them with other Pokemon. The leaves on it\u2019s head have medicinal\
  \ properties, if it finds a sick Pokemon it will offer some to heal it."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Leaf Stone
  Kind: Stone
  Pokemon: '[[SRD-Simisage]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Overgrow
HomeSprite: SRD-pansage-HomeSprite.png
Image: pansage.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Play Nice|Play Nice]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Lick|Lick]]'
- - Beginner
  - '[[SRD-Vine Whip|Vine Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Seed Bomb|Seed Bomb]]'
- - Amateur
  - '[[SRD-Torment|Torment]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Grass Knot|Grass Knot]]'
- - Ace
  - '[[SRD-Recycle|Recycle]]'
- - Ace
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Grass Whistle|Grass Whistle]]'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Giga Drain|Giga Drain]]'
Number: 511
ShuffleToken: SRD-pansage-ShuffleToken.png
Type1: Grass
Type2: ''
Weight:
  Kilograms: 10.5
  Pounds: 23.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-pansage-BookSprite.png|wsmall]]
> ![[SRD-pansage-HomeSprite.png]]
> ![[SRD-pansage-BoxSprite.png|htiny]]
> ![[SRD-pansage-ShuffleToken.png|wsmall]]


*Grass Monkey Pokemon*
*Pansage is a friendly Pokemon. It is good at finding berries and will share them with other Pokemon. The leaves on it’s head have medicinal properties, if it finds a sick Pokemon it will offer some to heal it.*

**DexID**:: 0511
**Name**:: Pansage
**Type**:: Grass
**Abilities**:: [[SRD-Gluttony|Gluttony]] ([[SRD-Overgrow|Overgrow]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 23.1lbs / 10.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| To        | [[SRD-Simisage]] | Stone  | Leaf Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Pansage.md"
flatten moves as T
where file.path = this.file.path
```
