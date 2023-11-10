---
Ability1: Rivalry
Ability2: Mold Breaker
BookSprite: SRD-axew-BookSprite.png
BoxSprite: SRD-axew-BoxSprite.png
DexCategory: Tusk Pokemon
DexDescription: "They mark their territory by leaving gashes in trees with their tusks.\
  \ If a tusk breaks, a new one grows back quickly. They fight each other to see who\u2019\
  s got the sharpest tusks. Only the strongest ever evolve."
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Fraxure]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Unnerve
HomeSprite: SRD-axew-HomeSprite.png
Image: axew.png
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
Number: 610
ShuffleToken: SRD-axew-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 18.0
  Pounds: 39.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-axew-BookSprite.png|wsmall]]
> ![[SRD-axew-HomeSprite.png]]
> ![[SRD-axew-BoxSprite.png|htiny]]
> ![[SRD-axew-ShuffleToken.png|wsmall]]


*Tusk Pokemon*
*They mark their territory by leaving gashes in trees with their tusks. If a tusk breaks, a new one grows back quickly. They fight each other to see who’s got the sharpest tusks. Only the strongest ever evolve.*

**DexID**:: 0610
**Name**:: Axew
**Type**:: Dragon
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 39.7lbs / 18.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Amateur

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Fraxure]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Axew.md"
flatten moves as T
where file.path = this.file.path
```
