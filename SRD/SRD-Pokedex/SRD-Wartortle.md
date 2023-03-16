---
Ability1: Torrent
Ability2: ''
BookSprite: SRD-wartortle-BookSprite.png
BoxSprite: SRD-wartortle-BoxSprite.png
DexCategory: Turtle Pokemon
DexDescription: "Its large tail is covered with rich, thick fur that deepens in color\
  \ with age. The scratches on its shell are evidence of this Pokemon\u2019s tough\
  \ attitude in battle. It is a good hunter underwater."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Squirtle]]'
  Speed: Medium
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Blastoise]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Rain Dish
HomeSprite: SRD-wartortle-HomeSprite.png
Image: wartortle.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Water Gun|Water Gun]]'
- - Beginner
  - '[[SRD-Withdraw|Withdraw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bubble|Bubble]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - Amateur
  - '[[SRD-Protect|Protect]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Skull Bash|Skull Bash]]'
- - Ace
  - '[[SRD-Iron Defense|Iron Defense]]'
- - Ace
  - '[[SRD-Rain Dance|Rain Dance]]'
- - Ace
  - '[[SRD-Hydro Pump|Hydro Pump]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Water Pledge|Water Pledge]]'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
Number: 8
ShuffleToken: SRD-wartortle-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 22.5
  Pounds: 49.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wartortle-BookSprite.png|wsmall]]
> ![[SRD-wartortle-HomeSprite.png]]
> ![[SRD-wartortle-BoxSprite.png|htiny]]
> ![[SRD-wartortle-ShuffleToken.png|wsmall]]


*Turtle Pokemon*
*Its large tail is covered with rich, thick fur that deepens in color with age. The scratches on its shell are evidence of this Pokemon’s tough attitude in battle. It is a good hunter underwater.*

**DexID**:: 0008
**Name**:: Wartortle
**Type**:: Water
**Abilities**:: [[SRD-Torrent|Torrent]] ([[SRD-Rain Dish|Rain Dish]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'3" / 1.0m
**Weight**: 49.6lbs / 22.5kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| From      | [[SRD-Squirtle]]  | Level  | Medium  |
| To        | [[SRD-Blastoise]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Wartortle.md"
flatten moves as T
where file.path = this.file.path
```
