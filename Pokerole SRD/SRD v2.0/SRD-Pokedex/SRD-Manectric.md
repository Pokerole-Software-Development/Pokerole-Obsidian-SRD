---
Ability1: Static
Ability2: Lightning Rod
BookSprite: SRD-manectric-BookSprite.png
BoxSprite: SRD-manectric-BoxSprite.png
DexCategory: Discharge Pokemon
DexDescription: Their manes are constantly releasing dangerous sparks that often end
  up in forest fires. When they get in battle, thunderclouds show up with them. They
  are extremely rare to see in the wild.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Electrike]]'
  Speed: Medium
- Evolves: To
  Item: Manectite
  Kind: Mega
  Pokemon: '[[SRD-Manectric (Mega Form)]]'
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Minus
HomeSprite: SRD-manectric-HomeSprite.png
Image: manectric.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Howl|Howl]]'
- - Beginner
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Electric Terrain|Electric Terrain]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Spark|Spark]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Amateur
  - '[[SRD-Roar|Roar]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Discharge|Discharge]]'
- - Ace
  - '[[SRD-Charge|Charge]]'
- - Ace
  - '[[SRD-Wild Charge|Wild Charge]]'
- - Ace
  - '[[SRD-Thunder|Thunder]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
- - Pro
  - '[[SRD-Crunch|Crunch]]'
Number: 310
ShuffleToken: SRD-manectric-ShuffleToken.png
Type1: Electric
Type2: ''
Weight:
  Kilograms: 40.2
  Pounds: 88.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-manectric-BookSprite.png|wsmall]]
> ![[SRD-manectric-HomeSprite.png]]
> ![[SRD-manectric-BoxSprite.png|htiny]]
> ![[SRD-manectric-ShuffleToken.png|wsmall]]


*Discharge Pokemon*
*Their manes are constantly releasing dangerous sparks that often end up in forest fires. When they get in battle, thunderclouds show up with them. They are extremely rare to see in the wild.*

**DexID**:: 0310
**Name**:: Manectric
**Type**:: Electric
**Abilities**:: [[SRD-Static|Static]] / [[SRD-Lightning Rod|Lightning Rod]] ([[SRD-Minus|Minus]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 4'9" / 1.5m
**Weight**: 88.6lbs / 40.2kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon                       | Kind   | Speed   | Item      |
|:----------|:------------------------------|:-------|:--------|:----------|
| From      | [[SRD-Electrike]]             | Level  | Medium  |           |
| To        | [[SRD-Manectric (Mega Form)]] | Mega   |         | Manectite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Manectric.md"
flatten moves as T
where file.path = this.file.path
```
