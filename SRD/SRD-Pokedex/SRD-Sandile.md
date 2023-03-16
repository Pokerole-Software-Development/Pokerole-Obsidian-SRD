---
Ability1: Intimidate
Ability2: Moxie
BookSprite: SRD-sandile-BookSprite.png
BoxSprite: SRD-sandile-BoxSprite.png
DexCategory: Desert Croc Pokemon
DexDescription: "They live hidden under the desert sands with only their eyes and\
  \ nostrils visible. They don\u2019t prey on anything bigger than themselves but\
  \ can be troublesome if they are being leaded by one of it\u2019s evolved forms."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Krokorok]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Anger Point
HomeSprite: SRD-sandile-HomeSprite.png
Image: sandile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Leer|Leer]]'
- - Starter
  - '[[SRD-Rage|Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Bite|Bite]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Torment|Torment]]'
- - '---------------------------'
  - '---------------------------'
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
  - '[[SRD-Thrash|Thrash]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Beat Up|Beat Up]]'
- - Pro
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
Number: 551
ShuffleToken: SRD-sandile-ShuffleToken.png
Type1: Ground
Type2: Dark
Weight:
  Kilograms: 15.2
  Pounds: 33.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-sandile-BookSprite.png|wsmall]]
> ![[SRD-sandile-HomeSprite.png]]
> ![[SRD-sandile-BoxSprite.png|htiny]]
> ![[SRD-sandile-ShuffleToken.png|wsmall]]


*Desert Croc Pokemon*
*They live hidden under the desert sands with only their eyes and nostrils visible. They don’t prey on anything bigger than themselves but can be troublesome if they are being leaded by one of it’s evolved forms.*

**DexID**:: 0551
**Name**:: Sandile
**Type**:: Ground / Dark
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Moxie|Moxie]] ([[SRD-Anger Point|Anger Point]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'3" / 0.7m
**Weight**: 33.5lbs / 15.2kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Krokorok]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Sandile.md"
flatten moves as T
where file.path = this.file.path
```
