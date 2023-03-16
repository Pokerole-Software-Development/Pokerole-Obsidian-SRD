---
Ability1: Dry Skin
Ability2: Sand Veil
BookSprite: SRD-helioptile-BookSprite.png
BoxSprite: SRD-helioptile-BoxSprite.png
DexCategory: Generator Pokemon
DexDescription: They make their home in deserts. Using the sun, they can generate
  their energy by basking their frills since food is scarce where they live. They
  run pretty fast as to not burn themselves with the hot sand.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Sun Stone
  Kind: Stone
  Pokemon: '[[SRD-Heliolisk]]'
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: Solar Power
HomeSprite: SRD-helioptile-HomeSprite.png
Image: helioptile.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Pound|Pound]]'
- - Starter
  - '[[SRD-Tail Whip|Tail Whip]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Beginner
  - '[[SRD-Charge|Charge]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Mud Slap|Mud Slap]]'
- - Amateur
  - '[[SRD-Quick Attack|Quick Attack]]'
- - Amateur
  - '[[SRD-Razor Wind|Razor Wind]]'
- - Amateur
  - '[[SRD-Parabolic Charge|Parabolic Charge]]'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Bulldoze|Bulldoze]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Volt Switch|Volt Switch]]'
- - Ace
  - '[[SRD-Electrify|Electrify]]'
- - Ace
  - '[[SRD-Thunderbolt|Thunderbolt]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Agility|Agility]]'
- - Pro
  - '[[SRD-Electroweb|Electroweb]]'
- - Pro
  - '[[SRD-Magnet Rise|Magnet Rise]]'
Number: 694
ShuffleToken: SRD-helioptile-ShuffleToken.png
Type1: Electric
Type2: Normal
Weight:
  Kilograms: 6.0
  Pounds: 13.2
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-helioptile-BookSprite.png|wsmall]]
> ![[SRD-helioptile-HomeSprite.png]]
> ![[SRD-helioptile-BoxSprite.png|htiny]]
> ![[SRD-helioptile-ShuffleToken.png|wsmall]]


*Generator Pokemon*
*They make their home in deserts. Using the sun, they can generate their energy by basking their frills since food is scarce where they live. They run pretty fast as to not burn themselves with the hot sand.*

**DexID**:: 0694
**Name**:: Helioptile
**Type**:: Electric / Normal
**Abilities**:: [[SRD-Dry Skin|Dry Skin]] / [[SRD-Sand Veil|Sand Veil]] ([[SRD-Solar Power|Solar Power]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 13.2lbs / 6.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon           | Kind   | Item      |
|:----------|:------------------|:-------|:----------|
| To        | [[SRD-Heliolisk]] | Stone  | Sun Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Helioptile.md"
flatten moves as T
where file.path = this.file.path
```
