---
Ability1: Swift Swim
Ability2: Water Veil
BookSprite: SRD-goldeen-BookSprite.png
BoxSprite: SRD-goldeen-BoxSprite.png
DexCategory: Goldfish Pokemon
DexDescription: Goldeen loves swimming wild and free in rivers and ponds. If one of
  these Pokemon is placed in an aquarium, it will shatter the glass with its horn
  and make its escape.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Seaking]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Lightning Rod
HomeSprite: SRD-goldeen-HomeSprite.png
Image: goldeen.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Water Sport|Water Sport]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Supersonic|Supersonic]]'
- - Beginner
  - '[[SRD-Horn Attack|Horn Attack]]'
- - Beginner
  - '[[SRD-Water Pulse|Water Pulse]]'
- - '---------------------------'
  - '---------------------------'
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
Number: 118
ShuffleToken: SRD-goldeen-ShuffleToken.png
Type1: Water
Type2: ''
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-goldeen-BookSprite.png|wsmall]]
> ![[SRD-goldeen-HomeSprite.png]]
> ![[SRD-goldeen-BoxSprite.png|htiny]]
> ![[SRD-goldeen-ShuffleToken.png|wsmall]]


*Goldfish Pokemon*
*Goldeen loves swimming wild and free in rivers and ponds. If one of these Pokemon is placed in an aquarium, it will shatter the glass with its horn and make its escape.*

**DexID**:: 0118
**Name**:: Goldeen
**Type**:: Water
**Abilities**:: [[SRD-Swift Swim|Swift Swim]] / [[SRD-Water Veil|Water Veil]] ([[SRD-Lightning Rod|Lightning Rod]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'0" / 0.6m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Seaking]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Goldeen.md"
flatten moves as T
where file.path = this.file.path
```
