---
Ability1: Pickup
Ability2: ''
BookSprite: SRD-donphan-BookSprite.png
BoxSprite: SRD-donphan-BoxSprite.png
DexCategory: Armor Pokemon
DexDescription: Strong enough to knock down a house. They like to attack by rolling
  as a ball at high speed, however once they start rolling, they have a hard time
  stopping. Some may keep their loving Phanpy nature.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Phanpy]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 3.6
  Meters: 1.1
HiddenAbility: Sand Veil
HomeSprite: SRD-donphan-HomeSprite.png
Image: donphan.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Defense Curl|Defense Curl]]'
- - Starter
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Beginner
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - Beginner
  - '[[SRD-Rapid Spin|Rapid Spin]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Rollout|Rollout]]'
- - Amateur
  - '[[SRD-Magnitude|Magnitude]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Assurance|Assurance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Scary Face|Scary Face]]'
- - Ace
  - '[[SRD-Earthquake|Earthquake]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Ice Shard|Ice Shard]]'
- - Pro
  - '[[SRD-Fissure|Fissure]]'
Number: 232
ShuffleToken: SRD-donphan-ShuffleToken.png
Type1: Ground
Type2: ''
Weight:
  Kilograms: 120.0
  Pounds: 264.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-donphan-BookSprite.png|wsmall]]
> ![[SRD-donphan-HomeSprite.png]]
> ![[SRD-donphan-BoxSprite.png|htiny]]
> ![[SRD-donphan-ShuffleToken.png|wsmall]]


*Armor Pokemon*
*Strong enough to knock down a house. They like to attack by rolling as a ball at high speed, however once they start rolling, they have a hard time stopping. Some may keep their loving Phanpy nature.*

**DexID**:: 0232
**Name**:: Donphan
**Type**:: Ground
**Abilities**:: [[SRD-Pickup|Pickup]] ([[SRD-Sand Veil|Sand Veil]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::3)/(MaxVitality::6)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'6" / 1.1m
**Weight**: 264.6lbs / 120.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon        | Kind   | Speed   |
|:----------|:---------------|:-------|:--------|
| From      | [[SRD-Phanpy]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Donphan.md"
flatten moves as T
where file.path = this.file.path
```
