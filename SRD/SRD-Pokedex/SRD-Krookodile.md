---
Ability1: Intimidate
Ability2: Moxie
BookSprite: SRD-krookodile-BookSprite.png
BoxSprite: SRD-krookodile-BoxSprite.png
DexCategory: Intimidation Pokemon
DexDescription: "A very violent Pokemon. They try to clamp down on anything that moves\
  \ in front of their eyes and once grasped they never let the prey escape. It can\
  \ be very dangerous if it\u2019s not tamed correctly."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Krokorok]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Anger Point
HomeSprite: SRD-krookodile-HomeSprite.png
Image: krookodile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Rage|Rage]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Torment|Torment]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Power Trip|Power Trip]]'
- - Amateur
  - '[[SRD-Sand Tomb|Sand Tomb]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - Amateur
  - '[[SRD-Swagger|Swagger]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Foul Play|Foul Play]]'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Pro
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 553
ShuffleToken: SRD-krookodile-ShuffleToken.png
Type1: Ground
Type2: Dark
Weight:
  Kilograms: 96.3
  Pounds: 212.3
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-krookodile-BookSprite.png|wsmall]]
> ![[SRD-krookodile-HomeSprite.png]]
> ![[SRD-krookodile-BoxSprite.png|htiny]]
> ![[SRD-krookodile-ShuffleToken.png|wsmall]]


*Intimidation Pokemon*
*A very violent Pokemon. They try to clamp down on anything that moves in front of their eyes and once grasped they never let the prey escape. It can be very dangerous if it’s not tamed correctly.*

**DexID**:: 0553
**Name**:: Krookodile
**Type**:: Ground / Dark
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Moxie|Moxie]] ([[SRD-Anger Point|Anger Point]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 212.3lbs / 96.3kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Krokorok]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Krookodile.md"
flatten moves as T
where file.path = this.file.path
```
