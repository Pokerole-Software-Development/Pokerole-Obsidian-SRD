---
Ability1: Gluttony
Ability2: ''
BookSprite: SRD-panpour-BookSprite.png
BoxSprite: SRD-panpour-BoxSprite.png
DexCategory: Spray Pokemon
DexDescription: It does not thrive in dry climates. It keeps itself damp by shooting
  the water stored in its head tuft. Its water is valued by gardeners and Grass Pokemon
  breeders as it makes plants grow beautiful.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Water Stone
  Kind: Stone
  Pokemon: '[[SRD-Simipour]]'
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Torrent
HomeSprite: SRD-panpour-HomeSprite.png
Image: panpour.png
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
  - '[[SRD-Water Gun|Water Gun]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Fury Swipes|Fury Swipes]]'
- - Amateur
  - '[[SRD-Water Sport|Water Sport]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Scald|Scald]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Fling|Fling]]'
- - Amateur
  - '[[SRD-Acrobatics|Acrobatics]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Brine|Brine]]'
- - Ace
  - '[[SRD-Recycle|Recycle]]'
- - Ace
  - '[[SRD-Natural Gift|Natural Gift]]'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Nasty Plot|Nasty Plot]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Disarming Voice|Disarming Voice]]'
Number: 515
ShuffleToken: SRD-panpour-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 13.5
  Pounds: 29.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-panpour-BookSprite.png|wsmall]]
> ![[SRD-panpour-HomeSprite.png]]
> ![[SRD-panpour-BoxSprite.png|htiny]]
> ![[SRD-panpour-ShuffleToken.png|wsmall]]


*Spray Pokemon*
*It does not thrive in dry climates. It keeps itself damp by shooting the water stored in its head tuft. Its water is valued by gardeners and Grass Pokemon breeders as it makes plants grow beautiful.*

**DexID**:: 0515
**Name**:: Panpour
**Type**:: Water
**Abilities**:: [[SRD-Gluttony|Gluttony]] ([[SRD-Torrent|Torrent]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 29.8lbs / 13.5kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item        |
|:----------|:-----------------|:-------|:------------|
| To        | [[SRD-Simipour]] | Stone  | Water Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Panpour.md"
flatten moves as T
where file.path = this.file.path
```
