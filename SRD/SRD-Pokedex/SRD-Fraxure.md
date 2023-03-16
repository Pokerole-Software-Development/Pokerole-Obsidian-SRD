---
Ability1: Rivalry
Ability2: Mold Breaker
BookSprite: SRD-fraxure-BookSprite.png
BoxSprite: SRD-fraxure-BoxSprite.png
DexCategory: Axe Jaw Pokemon
DexDescription: "Their tusks can shatter rocks. Territory battles between Fraxure\
  \ can be intensely violent. The tusks don\u2019t grow back anymore, if you find\
  \ a Fraxure with both tusks whole, it means it\u2019s one of the strongest."
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Axew]]'
  Speed: Slow
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Haxorus]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 3.3
  Meters: 1.0
HiddenAbility: Unnerve
HomeSprite: SRD-fraxure-HomeSprite.png
Image: fraxure.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Scratch|Scratch]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Assurance|Assurance]]'
- - Beginner
  - '[[SRD-Dragon Rage|Dragon Rage]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Dual Chop|Dual Chop]]'
- - Amateur
  - '[[SRD-Scary Face|Scary Face]]'
- - Amateur
  - '[[SRD-Slash|Slash]]'
- - Amateur
  - '[[SRD-False Swipe|False Swipe]]'
- - Amateur
  - '[[SRD-Dragon Claw|Dragon Claw]]'
- - Amateur
  - '[[SRD-Dragon Dance|Dragon Dance]]'
- - Amateur
  - '[[SRD-Taunt|Taunt]]'
- - Amateur
  - '[[SRD-Dragon Pulse|Dragon Pulse]]'
- - Amateur
  - '[[SRD-Swords Dance|Swords Dance]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Guillotine|Guillotine]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Giga Impact|Giga Impact]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Pro
  - '[[SRD-Counter|Counter]]'
- - Pro
  - '[[SRD-Night Slash|Night Slash]]'
Number: 611
ShuffleToken: SRD-fraxure-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 36.0
  Pounds: 79.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-fraxure-BookSprite.png|wsmall]]
> ![[SRD-fraxure-HomeSprite.png]]
> ![[SRD-fraxure-BoxSprite.png|htiny]]
> ![[SRD-fraxure-ShuffleToken.png|wsmall]]


*Axe Jaw Pokemon*
*Their tusks can shatter rocks. Territory battles between Fraxure can be intensely violent. The tusks don’t grow back anymore, if you find a Fraxure with both tusks whole, it means it’s one of the strongest.*

**DexID**:: 0611
**Name**:: Fraxure
**Type**:: Dragon
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::6)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 3'3" / 1.0m
**Weight**: 79.4lbs / 36.0kg
**Good Starter**:: No
**Recommended Rank**:: Ace

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Axew]]    | Level  | Slow    |
| To        | [[SRD-Haxorus]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Fraxure.md"
flatten moves as T
where file.path = this.file.path
```
