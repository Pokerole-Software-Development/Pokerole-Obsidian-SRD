---
Ability1: Swift Swim
Ability2: Water Veil
BookSprite: SRD-seaking-BookSprite.png
BoxSprite: SRD-seaking-BoxSprite.png
DexCategory: Goldfish Pokemon
DexDescription: In the autumn, Seaking males can be seen doing courtship dances to
  females. After getting a mate both will be seen swimming powerfully up rivers and
  creeks to make their nest.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Goldeen]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 4.3
  Meters: 1.3
HiddenAbility: Lightning Rod
HomeSprite: SRD-seaking-HomeSprite.png
Image: seaking.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Poison Jab|Poison Jab]]'
- - Amateur
  - '[[SRD-Water Pulse|Water Pulse]]'
- - Amateur
  - '[[SRD-Flail|Flail]]'
- - Amateur
  - '[[SRD-Aqua Ring|Aqua Ring]]'
- - Amateur
  - '[[SRD-Fury Attack|Fury Attack]]'
- - Amateur
  - '[[SRD-Waterfall|Waterfall]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Horn Drill|Horn Drill]]'
- - Ace
  - '[[SRD-Agility|Agility]]'
- - Ace
  - '[[SRD-Soak|Soak]]'
- - Ace
  - '[[SRD-Megahorn|Megahorn]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Bounce|Bounce]]'
- - Pro
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Pro
  - '[[SRD-Drill Run|Drill Run]]'
Number: 119
ShuffleToken: SRD-seaking-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 39.0
  Pounds: 86.0
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-seaking-BookSprite.png|wsmall]]
> ![[SRD-seaking-HomeSprite.png]]
> ![[SRD-seaking-BoxSprite.png|htiny]]
> ![[SRD-seaking-ShuffleToken.png|wsmall]]


*Goldfish Pokemon*
*In the autumn, Seaking males can be seen doing courtship dances to females. After getting a mate both will be seen swimming powerfully up rivers and creeks to make their nest.*

**DexID**:: 0119
**Name**:: Seaking
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Water Veil|Water Veil]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'3" / 1.3m
**Weight**: 86.0lbs / 39.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Goldeen]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Seaking.md"
flatten moves as T
where file.path = this.file.path
```
