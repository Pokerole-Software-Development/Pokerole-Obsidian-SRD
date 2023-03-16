---
Ability1: Synchronize
Ability2: Early Bird
BookSprite: SRD-natu-BookSprite.png
BoxSprite: SRD-natu-BoxSprite.png
DexCategory: Little Bird Pokemon
DexDescription: It lives close to the deserts. Its wings are not fully developed so
  it hops to trees and cactus to peck something to eat. If you find one it will hold
  your stare, if you get closer it might disappear in an instant.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Xatu]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: Magic Bounce
HomeSprite: SRD-natu-HomeSprite.png
Image: natu.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Peck|Peck]]'
- - Starter
  - '[[SRD-Leer|Leer]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Teleport|Teleport]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Lucky Chant|Lucky Chant]]'
- - Amateur
  - '[[SRD-Miracle Eye|Miracle Eye]]'
- - Amateur
  - '[[SRD-Me First|Me First]]'
- - Amateur
  - '[[SRD-Confuse Ray|Confuse Ray]]'
- - Amateur
  - '[[SRD-Ominous Wind|Ominous Wind]]'
- - Amateur
  - '[[SRD-Psycho Shift|Psycho Shift]]'
- - Amateur
  - '[[SRD-Stored Power|Stored Power]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Future Sight|Future Sight]]'
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
  - '[[SRD-Haze|Haze]]'
Number: 177
ShuffleToken: SRD-natu-ShuffleToken.png
Type1: Psychic
Type2: Flying
Weight:
  Kilograms: 2.0
  Pounds: 4.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-natu-BookSprite.png|wsmall]]
> ![[SRD-natu-HomeSprite.png]]
> ![[SRD-natu-BoxSprite.png|htiny]]
> ![[SRD-natu-ShuffleToken.png|wsmall]]


*Little Bird Pokemon*
*It lives close to the deserts. Its wings are not fully developed so it hops to trees and cactus to peck something to eat. If you find one it will hold your stare, if you get closer it might disappear in an instant.*

**DexID**:: 0177
**Name**:: Natu
**Type**:: Psychic / Flying
**Abilities**:: [[SRD-Synchronize|Synchronize]] / [[SRD-Early Bird|Early Bird]] ([[SRD-Magic Bounce|Magic Bounce]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 0'7" / 0.2m
**Weight**: 4.4lbs / 2.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon      | Kind   | Speed   |
|:----------|:-------------|:-------|:--------|
| To        | [[SRD-Xatu]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Natu.md"
flatten moves as T
where file.path = this.file.path
```
