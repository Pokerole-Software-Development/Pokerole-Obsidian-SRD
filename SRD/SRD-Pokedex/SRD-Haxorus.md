---
Ability1: Rivalry
Ability2: Mold Breaker
BookSprite: SRD-haxorus-BookSprite.png
BoxSprite: SRD-haxorus-BoxSprite.png
DexCategory: Axe Jaw Pokemon
DexDescription: Their sturdy tusks will stay sharp even if they are used to cut steel.
  These Pokemon are covered in hard armor. They incredibly aggressive, if their territory
  is trespassed, they chase and slash mercilessly.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Fraxure]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 5.9
  Meters: 1.8
HiddenAbility: Unnerve
HomeSprite: SRD-haxorus-HomeSprite.png
Image: haxorus.png
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
  - '[[SRD-Night Slash|Night Slash]]'
- - Pro
  - '[[SRD-Draco Meteor|Draco Meteor]]'
- - Pro
  - '[[SRD-Superpower|Superpower]]'
Number: 612
ShuffleToken: SRD-haxorus-ShuffleToken.png
Type1: Dragon
Type2: ''
Weight:
  Kilograms: 105.5
  Pounds: 232.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-haxorus-BookSprite.png|wsmall]]
> ![[SRD-haxorus-HomeSprite.png]]
> ![[SRD-haxorus-BoxSprite.png|htiny]]
> ![[SRD-haxorus-ShuffleToken.png|wsmall]]


*Axe Jaw Pokemon*
*Their sturdy tusks will stay sharp even if they are used to cut steel. These Pokemon are covered in hard armor. They incredibly aggressive, if their territory is trespassed, they chase and slash mercilessly.*

**DexID**:: 0612
**Name**:: Haxorus
**Type**:: Dragon
**Abilities**:: [[SRD-Rivalry|Rivalry]] / [[SRD-Mold Breaker|Mold Breaker]] ([[SRD-Unnerve|Unnerve]])
**Base HP**:: 5

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::4)/(MaxStrength::8)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 5'9" / 1.8m
**Weight**: 232.6lbs / 105.5kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| From      | [[SRD-Fraxure]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Haxorus.md"
flatten moves as T
where file.path = this.file.path
```
