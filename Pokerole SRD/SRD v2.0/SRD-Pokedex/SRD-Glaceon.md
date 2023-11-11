---
Ability1: Snow Cloak
Ability2: ''
BookSprite: SRD-glaceon-BookSprite.png
BoxSprite: SRD-glaceon-BoxSprite.png
DexCategory: Fresh Snow Pokemon
DexDescription: Eevees that are forced to live in freezing temperatures evolve into
  this Pokemon. It can control its body temperature to below zero, freezing its fur
  and making it extremely tough.
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Ice Stone
  Kind: Stone
  Pokemon: '[[SRD-Eevee]]'
GenderType: ''
Height:
  Feet: 2.6
  Meters: 0.8
HiddenAbility: Ice Body
HomeSprite: SRD-glaceon-HomeSprite.png
Image: glaceon.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tackle|Tackle]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Tail Whip|Tail Whip]]'
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Icy Wind|Icy Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bite|Bite]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Fang|Ice Fang]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Ice Shard|Ice Shard]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Barrier|Barrier]]'
- - Amateur
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Mirror Coat|Mirror Coat]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Hail|Hail]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Last Resort|Last Resort]]'
- - Ace
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Blizzard|Blizzard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Wish|Wish]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Captivate|Captivate]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Fake Tears|Fake Tears]]'
Number: 471
ShuffleToken: SRD-glaceon-ShuffleToken.png
Type1: Ice
Type2: ''
Weight:
  Kilograms: 25.9
  Pounds: 57.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-glaceon-BookSprite.png|wsmall]]
> ![[SRD-glaceon-HomeSprite.png]]
> ![[SRD-glaceon-BoxSprite.png|htiny]]
> ![[SRD-glaceon-ShuffleToken.png|wsmall]]


*Fresh Snow Pokemon*
*Eevees that are forced to live in freezing temperatures evolve into this Pokemon. It can control its body temperature to below zero, freezing its fur and making it extremely tough.*

**DexID**:: 0471
**Name**:: Glaceon
**Type**:: Ice
**Abilities**:: [[SRD-Snow Cloak|Snow Cloak]] ([[SRD-Ice Body|Ice Body]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::7)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::3)/(MaxInsight::6)     |

**Height**: 2'6" / 0.8m
**Weight**: 57.1lbs / 25.9kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon       | Kind   | Item      |
|:----------|:--------------|:-------|:----------|
| From      | [[SRD-Eevee]] | Stone  | Ice Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Glaceon.md"
flatten moves as T
where file.path = this.file.path
```
