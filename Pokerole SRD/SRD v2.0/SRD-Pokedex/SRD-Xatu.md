---
Ability1: Synchronize
Ability2: Early Bird
BookSprite: SRD-xatu-BookSprite.png
BoxSprite: SRD-xatu-BoxSprite.png
DexCategory: Mystic Pokemon
DexDescription: Xatu is known to stand motionless while staring at the sun all day
  long. Some people revere it as a mystical Pokemon out of their belief that Xatus
  have the power to see into the future.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Natu]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 4.9
  Meters: 1.5
HiddenAbility: Magic Bounce
HomeSprite: SRD-xatu-HomeSprite.png
Image: xatu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Air Slash|Air Slash]]'
- - Amateur
  - '[[SRD-Tailwind|Tailwind]]'
- - Amateur
  - '[[SRD-Future Sight|Future Sight]]'
- - Amateur
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Stored Power|Stored Power]]'
- - Ace
  - '[[SRD-Wish|Wish]]'
- - Ace
  - '[[SRD-Power Swap|Power Swap]]'
- - Ace
  - '[[SRD-Guard Swap|Guard Swap]]'
- - Ace
  - '[[SRD-Psychic|Psychic]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Pain Split|Pain Split]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
- - Pro
  - '[[SRD-Heat Wave|Heat Wave]]'
Number: 178
ShuffleToken: SRD-xatu-ShuffleToken.png
Type1: Psychic
Type2: Flying
Weight:
  Kilograms: 15.0
  Pounds: 33.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-xatu-BookSprite.png|wsmall]]
> ![[SRD-xatu-HomeSprite.png]]
> ![[SRD-xatu-BoxSprite.png|htiny]]
> ![[SRD-xatu-ShuffleToken.png|wsmall]]


*Mystic Pokemon*
*Xatu is known to stand motionless while staring at the sun all day long. Some people revere it as a mystical Pokemon out of their belief that Xatus have the power to see into the future.*

**DexID**:: 0178
**Name**:: Xatu
**Type**:: Psychic / Flying
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Magic Bounce|Magic Bounce]])
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::5)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::3)/(MaxSpecial::6)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 4'9" / 1.5m
**Weight**: 33.1lbs / 15.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon      | Kind   | Speed   |
|:----------|:-------------|:-------|:--------|
| From      | [[SRD-Natu]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Xatu.md"
flatten moves as T
where file.path = this.file.path
```
