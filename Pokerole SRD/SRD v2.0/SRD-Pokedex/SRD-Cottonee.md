---
Ability1: Prankster
Ability2: Infiltrator
BookSprite: SRD-cottonee-BookSprite.png
BoxSprite: SRD-cottonee-BoxSprite.png
DexCategory: Cotton Puff Pokemon
DexDescription: "They go wherever the wind takes them. On rainy days they can\u2019\
  t float, so they take shelter beneath big trees. To defend from predators they shed\
  \ their cotton and leave it as a decoy while they escape."
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Whimsicott]]'
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Chlorophyll
HomeSprite: SRD-cottonee-HomeSprite.png
Image: cottonee.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Absorb|Absorb]]'
- - Starter
  - '[[SRD-Fairy Wind|Fairy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Growth|Growth]]'
- - Beginner
  - '[[SRD-Leech Seed|Leech Seed]]'
- - Beginner
  - '[[SRD-Stun Spore|Stun Spore]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mega Drain|Mega Drain]]'
- - Amateur
  - '[[SRD-Cotton Spore|Cotton Spore]]'
- - Amateur
  - '[[SRD-Razor Leaf|Razor Leaf]]'
- - Amateur
  - '[[SRD-Poison Powder|Poison Powder]]'
- - Amateur
  - '[[SRD-Helping Hand|Helping Hand]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - Amateur
  - '[[SRD-Energy Ball|Energy Ball]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Giga Drain|Giga Drain]]'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - Ace
  - '[[SRD-Sunny Day|Sunny Day]]'
- - Ace
  - '[[SRD-Endeavor|Endeavor]]'
- - Ace
  - '[[SRD-Solar Beam|Solar Beam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Beat Up|Beat Up]]'
- - Pro
  - '[[SRD-Fake Tears|Fake Tears]]'
- - Pro
  - '[[SRD-Encore|Encore]]'
Number: 546
ShuffleToken: SRD-cottonee-ShuffleToken.png
Type1: Grass
Type2: Fairy
Weight:
  Kilograms: 0.6
  Pounds: 1.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-cottonee-BookSprite.png|wsmall]]
> ![[SRD-cottonee-HomeSprite.png]]
> ![[SRD-cottonee-BoxSprite.png|htiny]]
> ![[SRD-cottonee-ShuffleToken.png|wsmall]]


*Cotton Puff Pokemon*
*They go wherever the wind takes them. On rainy days they can’t float, so they take shelter beneath big trees. To defend from predators they shed their cotton and leave it as a decoy while they escape.*

**DexID**:: 0546
**Name**:: Cottonee
**Type**:: Grass / Fairy
**Abilities**:: [[SRD-Prankster|Prankster]] / [[SRD-Infiltrator|Infiltrator]] ([[SRD-Chlorophyll|Chlorophyll]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 1'0" / 0.3m
**Weight**: 1.3lbs / 0.6kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon            | Kind   | Item      |
|:----------|:-------------------|:-------|:----------|
| To        | [[SRD-Whimsicott]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Cottonee.md"
flatten moves as T
where file.path = this.file.path
```
